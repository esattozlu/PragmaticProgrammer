# PragmaticProgrammer

## Chapter 1: A Pragmatic Philosophy

Pragmatic programmers think beyond the problem, placing it in its larger context and seeking out the bigger picture.

### Topic 1. It’s Your Life
It's your life. If you are not satisfied, change it. Change is in your hands.

### Topic 2. The Cat Ate My Source Code

- Team Trust
In a healthy environment based in trust, you can safely speak your mind, present your ideas, and rely on your team members who can in turn rely on you.

- Take Responsibility
When you make a mistake (as we all do) or an error in judgment, admit it honestly and try to offer options.
Don’t blame someone or something else, or make up an excuse.
Mistakes happen. The important thing is to handle it professionally.

### Topic 3. Software Entropy
If there is a "broken window" in the project, later developers do not hesitate to break windows. Therefore, for the sustainability of the project, it is necessary to proceed without leaving any broken windows and by repairing the defects.

### Topic 4. Stone Soup and Boiled Frogs
Before asking for an improvement, it is necessary to show the team that it can be done by starting the process. Then, wait for the team to complete the next steps with statements such as "it would be nice if we add this too" on top of our own development. People find it easier to join an ongoing success.

### Topic 5. Good-Enough Software 
"Good enough" doesn't mean the code is sloppy or bad. Sometimes products with minor faults but working are preferred rather than perfect. The important thing is to meet the demands and needs of the users.
### Topic 6. Your Knowledge Portfolio 
- Building Your Portfolio
    - Invest regularly
    - Diversify
    - Manage risk
    - Buy low, sell high
    - Review and rebalance

- Goals
    - Learn at least one new language every year
    - Read a technical book each month
    - Read nontechnical books, too
    - Take classes
    - Participate in local user groups and meetups
    - Experiment with different environments
    - Stay current

- Critical Thinking
    - Ask the “Five Whys”
    - Who does this benefit?
    - What’s the context?
    - When or Where would this work?
    - Why is this a problem?
### Topic 7. Communicate!

- Know what you want to say. 
- Know your audience. 
- Choose your moment. 
- Choose a style.
- Make it look good.
- Involve your audience.
- Be a listener.
- Get back to people.
- Keep code and documentation together.

## Chapter 2: A Pragmatic Approach
### Topic 8. The Essence of Good Design 
Considering that the code you write may change in the future, write decoupled, cohesive and changeable code.

### Topic 9. DRY—The Evils of Duplication 
DRY – Don’t Repeat Yourself
Repetition in coding is dangerous. If there are repetitive codes, when there is a change, it is necessary to apply the change wherever it is repeated. If it is forgotten that the code is repetitive, making changes only in one place will cause conflict in the code.
Design your code modularly for reuse.


### Topic 10. Orthogonality
BENEFITS OF ORTHOGONALITY 
- Gain Productivity 
It is easier to write relatively small, independent, orthogonal components than to write a single large block of code. Simple orthogonal components combine to increase productivity and efficiency.
- Reduce Risk 
Orthogonal approach reduces risks in software. If a module is broken, it is unlikely to affect the other module. The system is less fragile. Errors made do not spread to the entire system. It has high testability.
- TOOLKITS AND LIBRARIES 
When using third-party applications, be careful not to disturb the orthogonality of the application.
- TESTING 
An orthogonally designed and implemented system is easier to test. Because interactions between system components are limited, most of the system testing can be performed at the module level. Module-level (or unit) testing is much easier to specify and perform than integration testing.

### Topic 11. Reversibility
Ensure both interchangeability and reversibility using a flexible architecture.

### Topic 12. Tracer Bullets
While writing the code, it is necessary to use tracer bullets to keep track of where the code goes, what results it provides, and the future of the code.

### Topic 13. Prototypes and Post-it Notes
It is important to use prototypes to analyze, uncover and reduce risk.
 
### Topic 14. Domain Languages 
Choose a language suitable for the problem domain.

### Topic 15. Estimating
It is important to be able to predict the feasibility, duration, and challenges of a project. Thus, no surprise problems are encountered during the development process.
For accurate estimation;
- Understand What’s Being Asked 
- Build a Model of the System 
- Break the Model into Components 
- Give Each Parameter a Value 
- Calculate the Answers 
- Keep Track of Your Estimating Prowess 

## Chapter 3: The Basic Tools

### Topic 16. The Power of Plain Text 
HTML, JSON, YAML,HTTP, SMTP, IMAP, and so on are all plain text.
That’s for some good reasons:
- Insurance against obsolescence 
- Leverage existing tools
- Easier testing

### Topic 17. Shell Games
You can launch applications, debuggers, browsers, editors, and utilities from the shell. You can search for files, query the status of the system, and filter the output. And by programming the shell, you can create complex macro commands for activities you do frequently.

### Topic 18. Power Editing
- Achieve Editor Fluency
#### What does "Fluent" Mean?
When editing text, move and make selections by character, word, line, and paragraph.
When editing code, move by various syntactic units (matching delimiters, functions, modules, ...).
Reindent code following changes.
Comment and uncomment blocks of code with a single command.
Undo and redo changes.
Split the editor window into multiple panels, and navigate between them.
Navigate to a particular line number. Sort selected lines.
Search for both strings and regular expressions, and repeat previous searches.
Display compilation errors in the current project. Run the current project’s tests.

### Topic 19. Version Control
Version control systems keep track of every change you make to your source code and documentation. With a properly configured source code control system, you can always revert to a previous version of your software.
But a version control system does much more than roll back errors. 
A good VCS will allow you to answer questions such as:
- Who made the changes to this line of code?
- What is the difference between the current version and last week's version?
- How many lines of code have we changed in this version?
- Which files are changed most often?
Such information is invaluable for defect tracking, auditing, performance and quality purposes.

### Topic 20. Debugging
Fix the Problem, Not the Blame
It doesn't matter if the bug is your fault or someone else's. It's is your problem.

#### WHERE TO START
- Before you start looking at the error, make sure you're working on cleanly generated code without warnings.
- When trying to solve any problem, you need to collect all relevant data.

#### DEBUGGING STRATEGIES
- Reproducing Bugs
The best way to start fixing a bug is to make it reproducible. If you can't reproduce the error, you won't know if it has been fixed.

- Logging and/or Tracing
You need to trace the state of a program or a data structure over time.

- Rubber Ducking
A very simple but particularly useful technique for finding the cause of a problem is to simply explain it to someone else.


#### DEBUGGING CHECKLIST
- Is the problem being reported a direct result of the underlying bug, or merely a symptom?
- Is the bug really in the framework you’re using? Is it in the OS? Or is it in your code?
- If you explained this problem in detail to a coworker, what would you say?
- If the suspect code passes its unit tests, are the tests complete enough? What happens if you run the tests with this data?
- Do the conditions that caused this bug exist anywhere else in the system? Are there other bugs still in the larval stage, just waiting to hatch?

### Topic 21. Text Manipulation
Learn a Text Manipulation Language

### Topic 22. Engineering Daybooks
Use a daybooks to take notes in meetings, jot down what we're working on, note down variable values while debugging, leave reminders, save ideas.

## Chapter 4: Pragmatic Paranoia
### Topic 23. Design by Contract
### Topic 24. Dead Programs Tell No Lies
### Topic 25. Assertive Programming
### Topic 26. How to Balance Resources
### Topic 27. Don’t Outrun Your Headlights
