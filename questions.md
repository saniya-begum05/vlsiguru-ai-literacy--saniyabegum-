 Q1 — AI, ML, Deep Learning, Generative AI, and Agents
 Q2 — Is Everything That Looks Intelligent Actually AI?
 Q3 — What Happens When You Ask an LLM a Question?
 Q4 — Hallucination Experiment
 Q5 — AI Assistant vs Search vs Authoritative Reference
 Q6 — What Is an AI Agent?
 Q7 — Where Should Humans Still Make the Decision?
 Q8 — Find AI Around You
 Q9 — Prediction, Classification, and Generation
 Q10 — Personal AI Verification Protocol

Q1. AI → ML → Deep Learning → Generative AI → Agents
1. Definitions
Artificial Intelligence (AI): AI is a field of computer science that enables machines to perform tasks that normally require human intelligence, such as problem-solving, learning, and decision-making.
Machine Learning (ML): ML is a subset of AI in which computers learn patterns from data and use them to make predictions or decisions.
Deep Learning (DL): Deep learning is a subset of machine learning that uses neural networks with multiple layers to learn complex patterns.
Generative AI: Generative AI creates new content, such as text, images, audio, video, and code, based on patterns learned from data.
AI Agent: An AI agent is a system that uses an AI model and may use external tools to perform actions and achieve a particular goal.
2. Relationship diagram
Artificial Intelligence (AI)
          |
    Machine Learning (ML)
          |
      Deep Learning
          |
   Generative AI
   (often uses DL)
Note: This is a simplified diagram. Generative AI is not a separate level that contains all deep learning. An AI agent is also not necessarily a level in this hierarchy; it is a system that can use an AI model, tools, and workflows.
3. Examples
Concept
Example
AI
A system that solves a puzzle using predefined rules
ML
An email spam detector trained on previous emails
Deep Learning
A neural network that recognizes objects in images
Generative AI
ChatGPT generating an explanation
AI Agent
An assistant that searches documents and prepares a report
4. Relationship and differences
AI is the broad field of making machines perform intelligent tasks. ML is one approach to AI, and deep learning is one approach to ML. Generative AI focuses on creating new content, whereas an AI agent focuses on accomplishing a goal through actions. A generative AI model can be used inside an AI agent, but generating content and taking actions are different capabilities.
5. References
IBM: AI, Machine Learning, and Deep Learning⁠�
IBM: Artificial Intelligence⁠�
Verification note: The definitions are consistent with these references. The diagram is simplified to make the relationships easier to understand.
Q2. Is Everything That Looks Intelligent Actually AI?
1. Classification table
Scenario
Classification
Reason
A. A calculator produces 25 × 16 = 400.
Traditional software
It performs a predefined mathematical operation.
B. A rule-based program displays WARNING if temperature > 80°C.
Traditional software
It follows a condition explicitly written by a programmer.
C. An email system identifies spam using patterns learned from previous emails.
Machine-learning-based AI
It learns patterns from data to classify emails.
D. An AI assistant writes a summary of a document.
Generative AI
It generates new text based on the document.
E. A navigation application estimates arrival time using traffic and historical data.
Machine-learning-based AI
It can use learned patterns to predict travel time.
Note: Real applications may combine AI with traditional software, databases, and manually written rules.
2. What makes AI different from ordinary software?
Traditional software generally follows rules explicitly written by programmers. Machine-learning systems learn patterns from data and apply those patterns to new inputs. Generative AI uses learned patterns to produce new content.
However, AI systems also use ordinary software and algorithms. A system should not be called AI simply because it appears intelligent or performs automation.
3. Conclusion
Not every automated system uses AI. A calculator and a simple temperature-warning program can work entirely through predefined instructions. A trained spam detector uses machine learning, while a generative assistant creates new text. To determine whether a system uses AI, we should examine reliable evidence about how its features work.
Q3. What Happens When You Ask an LLM a Question?
1. Explanation
A Large Language Model (LLM) processes a user's prompt and generates a response using patterns learned during training.
The process works approximately as follows:
The user enters a prompt.
The prompt is converted into tokens.
The model processes the tokens and available context.
The model calculates probabilities for possible next tokens.
A token is selected.
The selected token is added to the sequence.
The process repeats until the response is complete.
2. Important terms
Term
Meaning
Prompt
The question or instruction given to the model
Token
A unit of text processed by the model, such as a word, part of a word, or punctuation
Context
Information available to the model while generating a response
Probability
A numerical measure of how likely a possible next token is according to the model
Next-token prediction
Predicting a possible next token based on the preceding sequence
Generated response
The final text produced by the model
3. Flow diagram
User Prompt
     |
     v
Tokenization
     |
     v
Model Processes Context
     |
     v
Calculate Next-Token Probabilities
     |
     v
Select Next Token
     |
     v
Add Token to Sequence
     |
     v
Repeat Until Complete
     |
     v
Generated Response
4. Why can an LLM produce fluent but incorrect answers?
An LLM generates text based on learned patterns. It can produce sentences that sound natural even when some claims are false, unsupported, or outdated. Fluency does not guarantee factual accuracy.
Therefore, important claims should be checked against reliable sources.
5. Reference
IBM: Large Language Models⁠�
Verification note: This is an intuitive explanation. Actual language models perform more complex computations than those shown in the diagram.
Q4. Hallucination Experiment: Can AI Sound Confident and Still Be Wrong?
1. Objective
The objective of this experiment is to compare two AI assistants and determine whether their answers are factually correct, incomplete, contradictory, or unsupported.
2. Question used for the experiment
Prompt: What is the chemical symbol for gold?
The independently verifiable answer is Au.
Reference: Royal Society of Chemistry — Gold⁠�
3. Experiment table
Open two AI assistants, submit the same prompt, and fill in the actual responses.
Item
AI Assistant 1
AI Assistant 2
Prompt
What is the chemical symbol for gold?
What is the chemical symbol for gold?
Actual response
Write the exact response here.
Write the exact response here.
Verified answer
Au
Au
Evidence
Royal Society of Chemistry
Royal Society of Chemistry
Result
Record whether the actual response is correct.
Record whether the actual response is correct.
4. Analysis
The chemical symbol for gold is Au. If both assistants return Au, both answers are correct for this question.
However, this result does not prove that either assistant always provides correct information. A single simple question may not reveal a hallucination.
If an assistant gives a different symbol, compare its answer with the reference and record the discrepancy. If both assistants answer correctly, explain that the experiment did not expose a failure.
5. Reflection
An AI assistant can sound confident even when its answer is wrong because fluent language is not proof of factual accuracy. This experiment teaches us to verify important claims against reliable evidence instead of trusting an answer only because it sounds convincing.
Verification note: Complete the table using the actual responses from the two assistants. Do not invent experimental results.
Q5. AI Assistant vs Search vs Authoritative Reference
1. Question selected
What is the difference between RAM and ROM?
This question can be investigated using an AI assistant, a web search, and technical documentation.
2. AI assistant answer
RAM stands for Random Access Memory. It is generally used as working memory while a computer is running and is volatile, meaning its contents are normally lost when power is removed.
ROM stands for Read-Only Memory. It is a form of non-volatile memory that retains stored information without power and is commonly associated with firmware or other persistent instructions.
3. Web search
Search the web for:
Difference between RAM and ROM
Review multiple results and note whether they agree about volatility, data retention, and common uses.
4. Authoritative reference
Use a relevant technical reference from a semiconductor manufacturer, such as Micron.
Micron Technology⁠�
Find suitable documentation about the memory technologies being compared. Record the specific page or document you actually consult.
5. Comparison table
Method
Accuracy
Explanation
Traceability
Ease of verification
AI assistant
May be correct but can make mistakes
Usually explains concepts in simple language
Depends on whether useful sources are provided
Important claims need independent checking
Web search
Depends on the sources found
Provides different explanations
Links allow users to inspect sources
Requires evaluating the quality of results
Authoritative reference
Generally strong for the subject covered
May use technical language
Provides identifiable technical documentation
Claims can be checked against the original document
6. Conclusion
An AI assistant is useful for understanding a topic quickly. Web search helps locate different explanations and references. An authoritative technical reference is especially important when accuracy matters.
I would use an AI assistant to understand a concept, search to discover relevant sources, and authoritative documentation to verify important technical claims before making an engineering decision.
Verification note: Open the reference and record the actual page you used. The table above describes the general strengths and limitations of each method; it is not a claim that a live comparison has already been performed.
Q6. What Is an AI Agent?
1. Five important ideas
LLM: A Large Language Model processes and generates language. It can answer questions, summarize documents, and generate text.
LLM application: A software application that uses an LLM to perform a task, such as a chatbot that explains technical concepts.
RAG system: Retrieval-Augmented Generation retrieves relevant information from documents or another information source and supplies it to a language model to help generate a grounded response.
Tool-using assistant: An AI application that can call external tools, such as a search engine, calculator, or database.
AI agent: A system that uses an AI model and other capabilities to work toward a goal through a sequence of steps. Depending on its design, it can choose tools, examine their results, and decide what to do next.
2. Architecture diagram
       User Request
             |
             v
        AI Agent
             |
       Understand Goal
             |
             v
        Choose Action
             |
             v
         Call Tool
             |
             v
      Tool Executes Task
             |
             v
        Tool Result
             |
             v
       Evaluate Result
             |
       Is it sufficient?
          /       \
        No         Yes
        |           |
        v           v
   Next Action   Final Response
3. How is an agent different from a simple chatbot?
A simple chatbot may generate a response directly from the information available to its model. An AI agent can be designed to plan several steps, use external tools, examine results, and continue working toward a goal.
Not every chatbot is an agent, and not every agent operates fully autonomously.
4. Example outside VLSI
Imagine asking an AI assistant to plan a one-day trip.
The user provides a destination and budget.
The agent searches for places to visit.
It checks opening hours.
It compares travel times.
It prepares an itinerary.
It presents the itinerary for the user to review.
The agent uses tools and multiple steps instead of merely generating a general travel suggestion.
5. Reference
IBM Research: LLM-Based AI Agents⁠�
Verification note: AI agent architectures differ. Some use repeated planning and tool calls, while others follow predefined workflows.
Q7. Where Should Humans Still Make the Decision?
AI can assist with tasks, but humans should retain appropriate responsibility for consequential decisions.
Five-row table
Situation
Possible problem if AI output is accepted without checking
Required verification
Who approves the result?
1. AI summarizes a technical document.
It may omit important limitations or change the meaning.
Compare the summary with the original document.
Engineer or document reviewer
2. AI recommends an electronic component.
The component may not meet the design requirements.
Check the official datasheet, specifications, and operating limits.
Responsible engineer
3. AI generates code.
The code may contain bugs or security problems.
Review the code and test normal and boundary cases.
Developer or engineering reviewer
4. AI provides medical information.
The answer may be inaccurate or overlook a serious symptom.
Consult qualified healthcare professionals and reliable medical sources.
Qualified healthcare professional and patient, as appropriate
5. AI recommends a financial decision.
It may overlook risks, fees, or personal circumstances.
Verify the information, assumptions, and risks.
Individual making the decision, with professional advice where appropriate
Conclusion
Humans should make or approve decisions when errors could cause serious harm, financial loss, safety problems, or legal consequences. AI should be treated as an assistant rather than an unquestionable authority.
The amount of verification required should depend on the risk and consequences of the decision.
Q8. Find AI Around You
The following table identifies five everyday systems and their commonly documented AI-related functions.
System
AI involvement
Primary task
Source
Conclusion
1. Google Translate
Neural machine translation supports translation features.
Translation
Google Translate⁠�
AI is used for translation.
2. Gmail
Machine-learning techniques help identify unwanted email.
Classification
Gmail⁠�
AI/ML supports spam filtering alongside other techniques.
3. Google Photos
AI-powered features support image search and organization.
Recognition and search
Google Photos⁠�
AI is used in supported image-related features.
4. Google Maps
Data-driven methods support features such as traffic and travel-time predictions.
Prediction and navigation
Google Maps⁠�
AI/ML may contribute to predictions alongside map data and conventional software.
5. ChatGPT
Generative AI models support conversational responses.
Generation and question answering
ChatGPT⁠�
Generative AI is central to its conversational functionality.
Conclusion
AI appears in many everyday applications, including translation, email filtering, image search, navigation, and conversational assistants. However, an application may combine AI with ordinary software, databases, and predefined rules.
We should use public evidence to support claims about AI involvement instead of assuming that every intelligent-looking feature uses AI.
Verification note: The links above are starting points. Before submitting, find an official explanation of the particular AI feature you are describing. If you cannot verify a system's internal implementation, state that limitation.
Q9. Prediction, Classification, and Generation
1. Classification table
Example
Primary task type
Explanation
A. Predicting house prices
Prediction
Estimates a numerical value, such as a house's expected price.
B. Detecting whether an image contains a cat
Classification
Assigns the image to a category, such as cat or no cat.
C. Writing an email from a short instruction
Generation
Creates new text from the instruction.
D. Predicting whether a customer will cancel a subscription
Classification
Typically predicts a category: cancel or not cancel.
E. Summarizing a research paper
Generation
Produces a shorter version of the original content.
F. Identifying whether a transaction is fraudulent
Classification
Assigns a category, such as fraudulent or legitimate.
G. Generating an image from a text description
Generation
Creates an image based on a text prompt.
H. Predicting the next word or token in a sentence
Prediction
Estimates probabilities for possible next tokens.
2. Why is next-token prediction fundamental to modern language models?
Many modern language models are trained to predict the next token based on the tokens that came before it. By learning patterns from large amounts of text, they develop capabilities that support writing, summarization, explanation, and question answering.
During generation, the model repeatedly selects a next token to build a sequence of text.
3. Important distinction
One AI system can perform multiple types of tasks.
For example, a language model uses next-token prediction internally while generating a summary. An application may also classify an input before generating a response.
The classification should reflect the primary behavior requested.
Caveat: Predicting whether a customer will cancel is often a classification task when the result is a category. Predicting the probability or time until cancellation may use a different formulation.
Q10. Design Your Personal AI Verification Protocol
Seven-step procedure
Step 1: Define the problem
Clearly identify the task the AI must solve. Specify the expected result, constraints, and how success will be measured.
Example: Check whether an AI explanation accurately describes the difference between RAM and ROM.
Step 2: Inspect assumptions
Identify assumptions in the AI response. Check whether the question is clear and whether important information is missing.
Example: Determine whether the explanation refers to typical computer memory or a specific memory technology.
Step 3: Identify the required evidence
Determine which sources are suitable for checking the answer. Prefer official documentation, technical datasheets, primary references, and reputable educational sources.
Example: Find technical documentation describing the memory technologies involved.
Step 4: Verify important claims
Break the answer into individual claims. Check each important claim against reliable sources. Look for unsupported statements, contradictions, and missing conditions.
Example: Verify the statements about volatility and data retention.
Step 5: Test the result
Use a suitable test, calculation, example, or independent method to check whether the answer is correct. For engineering work, consider boundary conditions and possible failures.
Example: Compare the explanation with a second reliable reference and investigate any disagreement.
Step 6: Decide whether to accept, reject, or revise
Accept the answer when important claims are sufficiently supported. Reject it if it is demonstrably wrong or unsafe. Revise it if it is partly correct but incomplete or unclear.
Example: Correct a misleading statement and add any necessary qualifications.
Step 7: Record the decision
Document the prompt, important claims, sources checked, tests performed, corrections, and final decision. For high-impact tasks, obtain approval from the appropriate qualified person.
Example: Save the final explanation and reference links so another person can reproduce the verification.
Example: Applying the protocol
Task: Ask an AI assistant to explain the difference between RAM and ROM.
Step
Action
1. Define the problem
Request an accurate comparison of RAM and ROM.
2. Inspect assumptions
Check whether the answer refers to typical computer memory.
3. Identify evidence
Find relevant technical documentation.
4. Verify claims
Check volatility, data retention, and common uses.
5. Test
Compare the explanation with another reliable reference.
6. Decide
Correct unsupported or misleading claims before using the answer.
7. Record
Save the final explanation and the sources used.
Final conclusion
AI can help us learn and work efficiently, but its answers should not automatically be trusted. A personal verification protocol improves reliability by requ
