# Auto-Quizzer
TLDR: A way to test knowledge retention from books

## Purpose
Auto-Quizzer accepts text or image input and outputs an automatically generated question to test your recall ability. 
*Recall* refers to how much information is retained - it's a good way to tell if you understand something.

There will also be an answer checker which gives a score based on how much key information was recalled.

## Question Generating
There are many different types of questions and they can be separated into two main fields: *closed* and *open* questions.

Closed questions have a fixed answer. Examples include:

1. Multiple Choice
2. Fill in the blank
3. Naming the concept based on definition

Open questions have many possible answers. Examples include:

1. Define, describe, explain, analyse, evaluate, compare, contrast, assess, ...
2. Recall  𝑛  key concepts and write down what you remember about them

## Answer Checking
Fixed answers can be easily verified by examining the original context.

Short answer responses may vary drastically in its phrasing so we turn to other means to examine answer accuracy. These include:
1. Keyword matching
2. Cosine similarity of semantic vector representations
