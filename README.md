# Project Title
```
Author(s): Harshal Vijay Hivarkar 
Affiliation: Suryodaya College of Engineering & Technology
Date: March 2026
```

## Abstract
```
This project builds an AI Code Reviewer that acts like a mini GitHub Copilot. Users upload their code, and the system automatically checks for bugs, suggests performance optimizations, and improves code quality. The tool combines CodeBERT (an AI model trained on code) with simple NLP and static‑analysis rules. It reads the code, understands the logic, and gives clear, human‑friendly feedback. The main aim is to help students and beginners write better, cleaner, and safer code with less effort. The project shows how AI can support real‑world software engineering tasks in a simple, usable way.
```

## introduction
```
Nowadays, coding is very important in studies and jobs, but many students and new developers make mistakes in their programs. These mistakes can cause bugs, slow performance, or bad‑quality code. This project creates an AI Code Reviewer that helps users improve their code automatically. When a student uploads a file, the system acts like a smart assistant: it finds bugs, suggests faster or cleaner code, and points out style problems. The idea is inspired by tools like GitHub Copilot but made simpler and focused on learning. By using modern AI and simple code‑analysis techniques, this project tries to make coding easier and more fun for beginners.
```
## Literature review
```
Many researchers have studied how AI can understand and improve code. Earlier works used traditional rule‑based tools that only check style or syntax errors. Recently, models like CodeBERT and similar deep‑learning methods can “read” code like text and understand its meaning. Some papers combine these models with static‑analysis tools to find bugs and performance issues. Other tools, such as GitHub Copilot, suggest whole lines or functions while coding. Several studies show that combining AI models with simple code‑analysis rules gives better results than using only one method. This project follows that idea but focuses on education and student‑level simplicity instead of professional‑scale systems.
```

## Methodology
``
The AI Code Reviewer follows a simple flow. First, the user uploads a code file (for example, Python or Java). The system then parses the code into tokens and comments so both the model and static rules can read it. Next, CodeBERT processes the code text to understand logic, patterns, and possible problems. At the same time, lightweight static‑analysis rules check for common mistakes like unused variables, wrong types, or weak security. The outputs from the AI model and the rules are combined into one clear review. Finally, the system shows the user a list of bugs, optimization ideas, and code‑quality suggestions in easy, student‑friendly language.
```


## implementation
```
The project is built in Python using standard libraries and a pre‑trained CodeBERT model. The user interface is a simple web page or command‑line tool where students can drag and drop or paste their code. The backend splits the code into parts, sends them to the model, and runs light static checks. CodeBERT returns possible issues, and the rules add extra warnings or style tips. The system then merges these messages and formats them in simple English, using short bullet points. For example, it might say, “You can replace this loop with a built‑in function to make it faster” or “This variable is not used; remove it.” The main goal is to keep the design small, fast, and easy to use.
```

## Results and Discussion
```
Show outputs, performance metrics, comparisons, or screenshots.
```

## Limitation
```
Talk about Limitation
```

## Future Scope
```
Mention possible improvements or next steps.
```
## Conculusion  
```
Summarize your findings and contributions.
```
## References
```
[1] Author, "Paper Title," Journal/Conference, Year.
[2] Author, "Another Paper," Year.
[3] text links
```
