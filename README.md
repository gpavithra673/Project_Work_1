## GRAMMAR CORRECTOR WITH INTEGRATED SPEECH RECOGNITION AND FEEDBACK
The project focused on improving communication skills, particularly for students. Proficiency in written and oral communication is essential for both career advancement and academic achievement. But many students find it difficult to acquire these abilities, particularly those who have little access to seminars, individualized learning experiences, and high-quality language materials. Using cutting-edge artificial intelligence (AI) technology, such as machine learning (ML) and natural language processing (NLP), this project offers a comprehensive solution.
The project's main objective is to remove communication barriers, which have an adverse effect on a maximum of 80 percent of students in learning contexts with limited resources. The suggested system offers real-time feedback on spoken and written communication using a blend of deep learning methods and rule-based models. Through the process of examining user input, the system may identify and fix grammatical mistakes, offer suggestions for better pronunciation, and hone speech patterns, all of which contribute to a personalized learning experience for pupils.

## About
A rule-based model is an approach in artificial intelligence and machine learning that relies on predefined rules to make decisions or perform tasks. These rules are created by domain experts and are designed to capture specific patterns or conditions in the data. In the context of grammar correction, a rule-based model uses linguistic rules to identify and correct grammatical errors. For instance, these rules might include subject-verb agreement, tense consistency, and correct usage of articles or prepositions.
<br>
To implement grammar correction using a rule-based model, we would first define a set of grammatical rules that govern sentence structure and word usage. These rules would then be applied to analyze sentences. When the model detects a violation of the rules—such as a missing article, incorrect verb form, or improper punctuation—it suggests corrections. Tools like natural language processing libraries (e.g., spaCy) can help identify parts of speech and grammatical dependencies, which are then matched against the predefined rules. This method is effective for handling common grammar mistakes but may be less adaptable to complex or creative language use, where rules may need to be flexible.
In a rule-based grammar correction model, these rules are defined by linguists or language experts and may cover a wide range of grammatical aspects, such as:
Subject-verb agreement: Ensuring that the subject and verb in a sentence agree in number (e.g., "She has a pen" is correct, whereas "She have a pen" is incorrect).
Tense consistency: Verifying that the tense used in a sentence or paragraph is consistent (e.g., "He went to the store and bought milk" is correct, while "He went to the store and buys milk" would be flagged for tense inconsistency).<br>
Article usage: Checking the correct use of articles (e.g., "I need a book" versus "I need an apple").
Preposition use: Ensuring that prepositions are used appropriately within a sentence (e.g., "She is on the phone" is correct, whereas "She is in the phone" is incorrect).
Punctuation rules: Identifying mistakes in punctuation, such as missing commas, misplaced apostrophes, or unnecessary punctuation.
Pronoun reference: Ensuring that pronouns refer clearly and correctly to their antecedents (e.g., "John gave his book to Mary" versus "John gave their book to Mary").
Word order and sentence structure: Enforcing correct word order in sentences, particularly in languages where sentence structure follows strict patterns (e.g., "The cat sat on the mat" versus "Sat the cat on the mat").
spaCy is an open-source, high-performance library for Natural Language Processing (NLP) in Python. It provides tools for efficiently processing large volumes of text, extracting meaningful information, and performing various NLP tasks, such as tokenization, part-of-speech tagging, named entity recognition, and dependency parsing. spaCy is designed to work with both rule-based and machine-learning approaches, making it flexible for different use cases.
Tokenization: At the core of spaCy is its tokenizer, which breaks down text into individual tokens (words, punctuation, etc.). The tokenizer is rule-based, leveraging language-specific patterns to identify meaningful units of text. For instance, it knows to treat contractions like "don't" as two tokens ("do" and "not"). It also handles special cases like abbreviations, numbers, and URLs, ensuring that the tokens produced are contextually correct.
Part-of-Speech Tagging (POS Tagging): Once tokenized, spaCy's part-of-speech tagger assigns a grammatical tag to each token, such as noun, verb, adjective, or adverb. The model for POS tagging is pre-trained using supervised machine learning techniques on large corpora of text. It uses the surrounding context of a word (the words before and after) to determine its function in the sentence, making it capable of handling ambiguous cases. For example, in the sentence "They can fish," the word "can" could be a modal verb (as in "able to") or a noun ("a container"), and spaCy's POS tagger identifies the correct usage based on context.
Dependency Parsing: spaCy also includes a dependency parser, which analyzes the syntactic structure of sentences. This helps in understanding the relationships between words, such as identifying subjects, objects, and modifiers. The dependency parser builds a directed graph where the words are nodes, and the relationships between them are edges. This can be especially useful for tasks like text summarization, information extraction, or question-answering systems.
Named Entity Recognition (NER): Another powerful feature of spaCy is Named Entity Recognition (NER), which identifies proper nouns and classifies them into predefined categories like people, organizations, locations, dates, and more. This is done using a statistical model trained on labeled datasets, which learns patterns to detect and classify entities. NER is useful in applications like news processing, customer feedback analysis, or any domain where it's necessary to extract specific information from text.


## Features
<!--List the features of the project as shown below-->
- Speech-to-Text Conversion: Transforms spoken input into text for analysis.
- Grammar Error Detection: Identifies grammatical errors in the sentence, such as incorrect verb usage, tense, punctuation, or sentence structure.
- Real-time Feedback: Provides immediate feedback by highlighting errors and suggesting corrected versions of the sentence.
- Scoring Mechanism: Generates a score based on the grammatical accuracy of the sentence, allowing users to monitor their progress.
- Speech Fluency Assessment: Evaluates the user’s spoken input based on fluency and pronunciation (without pronunciation checking).
- Rule-based Analysis: Utilizes a rule-based system to check grammatical correctness efficiently.
- Adaptive Learning: Tracks progress over time, offering personalized feedback and targeting common mistakes.
- User-Friendly Interface: Designed to be accessible to students from diverse backgrounds, encouraging continuous learning.
- Educational Tool: Aims to improve communication skills, particularly for students with limited resources.

## Requirements
HARDWARE ENVIRONMENT
    Processor: Intel Core i5 or higher
    Hard Disk: 500 GB (minimum)
    RAM: 8 GB (minimum)
    Keyboard: Standard 110 keys enhanced
    GPU: NVIDIA GPU (for deep learning model training)

SOFTWARE ENVIRONMENT
   Operating System: Windows 10, macOS, or Linux (Ubuntu 18.04+)
   Language: Python 3.7 or higher, JavaScript

TECHNOLOGIES USED
    IDE: Visual Studio Code, Jupyter Notebooks
   Framework: Flask (for backend), React.js (for frontend)
   Deep Learning Libraries: TensorFlow, PyTorch
   NLP Libraries: spaCy, NLTK
   Speech APIs: Google Speech-to-Text, Microsoft Azure Speech API

## System Architecture
![arc](https://github.com/user-attachments/assets/4f891e22-63ec-4dc9-9b37-bea5eaf88f8d)

## Output
#### Output1 - Name of the output
![{F256462A-D36B-4893-88A9-58A2E1688D4A}](https://github.com/user-attachments/assets/aa605c20-7de2-4aca-9df5-679a077f3c99)

## Results and Impact
The result of the grammar-checking model effectively highlights errors in the input text and provides feedback to the user. When an error is detected, the incorrect part of the sentence is marked, and the system suggests a corrected version. Each sentence is evaluated based on grammatical rules, and a score is generated to reflect the number and type of errors made. The score provides an objective measure of sentence correctness, helping users track their progress. Additionally, the model offers a separate score for the user's fluency and accuracy in speech, ensuring a holistic approach to language assessment. By highlighting specific errors and offering corrective feedback, the tool encourages continuous learning and improvement.

## References
[1] James E. Hoard, Richard H. Wojcik, Katherina Holzhauser, “ An Automated Grammar and Style Checker for Writers of Simplified English”, 01 Jan 1992 (Springer, Dordrecht).
[2] Jeff Hawthorne, Felicity Radcliffe, Leslie A. Whitaker, “Enhancing Semantic Validity in Large Language Model Tasks Through Automated Grammar Checking ”,15 July 2024.
[3] Wei Li,Houfeng Wang ,”Detection-Correction Structure via General Language Model for Grammatical Error Correction”, 28 May 2024 (Cornell University).
[4]	Flora Ramírez Bustamante ,Fernando Sánchez León ,”GramCheck: a grammar and style checker”,05 Aug 1996(Charles III University of Madrid,Autonomous University of Madrid)
[5]	Kostiantyn Omelianchuk ,Andrii Liubonko ,Oleksandr Skurzhanskyi ,Artem N. Chernodub,Oleksandr Korniienko,Igor Samokhin,”Pillars of Grammatical Error Correction: Comprehensive Inspection Of Contemporary Approaches In The Era of Large Language Models”,23 Apr 2024 (The Catholic University of America)
[6]	Sakshi, Satnam Singh ,Reeta Rautela, “Chatbot: A Bridge Between Technology and Learn”, 06 Oct 2022
[7]	Pabboz Anushka, M S Reddy, Y.Bala Saketh Reddy, D. Sangeetha Devi, “Chatbot using Machine Learning”, 10 July 2024

