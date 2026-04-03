
## thinking
there are already 2 good players who have decent image. but the problem is that. builiding a platfrom for this requires a lot of questions searching and more importantly making individuals vidoes for that. 




what are the easiest to ship?

i am only gonna focus on 2 subjects: maths, physics and chemistry 


IA and EE essay graded is easier to ship
Question banks are easier to ship. but providing ans to those questions is a bit hard: - so this could be in terms of 
	1. plan basic ans (MCQ) without steps
	2. gpt based ans 
	3. video based ans 

gpt based ans will requrire systems design to think on bringing down the cost of token

video based ans will require man power 


but there are sheer amount of enormous questions and idk how much will be the cost of cloud and hosting these services 


the real question is : can i justify the actual cost to percieved cost. 

if i am charing $25 a month. can i justify that and show a percived cost of this as 250 dollars. 


but never the less lets go and build the low hanging fruits 
1) EE AND IA and TOK grader / although that doesn't have a lot of monthly use 
2) building a repository of question bank and ans for that. assuming - 300-400 questions/ subject 
3) + showing ans to these questions in a good way 
although the question and ans part shoudn't be dynamic. it can be static 


**product stand point**: 
would love to add feature of : giving previous year question with year

% likelyhoood of this coming in end exam. 


**how am i making things more efficient** and what **real problem am i solving** ?

lets rate finding past year papers in terms of efficiency (1-5): 2-3

me making it in one place where many people are doing the same at less price is: 4

its marginally efficient but its reversible behaviour. 
although as a student what do i llove while learning complex stuff: teach me like a 5yr old. that works always. 


the IA AND EE graded is efficient. 
current rating: its expensive and private - 2-3
with AI - 5-6
delta = 3


----



## master prompt for commet

You are an expert in the IB Further Mathematics HL syllabus, exam structure, and markschemes.

Your task is to transform a set of IB exam PDFs into **student-friendly, workbook-style documents**.

You will be given four PDFs for each session:

- Paper 1 (questions)
    
- Paper 1 markscheme
    
- Paper 2 (questions)
    
- Paper 2 markscheme
    

For each paper, produce a **separate .docx file**:

**“Further Math HL – [Session] – Paper 1 (Q&A).docx”**  
2.  
**“Further Math HL – [Session] – Paper 2 (Q&A).docx”**

Each document must follow these rules:

STRUCTURE

- Preserve the exact question order from the original paper.
    
- Group each main question with its sub-parts (a), (b), (i), (ii), etc.
    
- Each question block must begin with:
    
    ```
    Further Mathematics HL – [Session]
    Paper X – Question Y   [Total marks]
    ```
    
- Each sub-part must show its individual mark allocation, exactly as in the exam.
    

STYLE

- The document must read like a **guided workbook**, not an exam script.
    
- The flow must be simple enough that even a 7-year-old can follow it:
    
    - Question
        
    - Immediate answer
        
    - Then move on
        
- Do not force the reader to flip pages or search for solutions.
    

ANSWERS

- For **every question and sub-part**, insert the corresponding IB markscheme answer immediately below it.
    
- Clean the markscheme language:
    
    - Remove examiner-only codes (M1, A1, AG, etc.)
        
    - Keep all mathematical correctness
        
    - Preserve logical steps and working
        
- Do NOT invent solutions—only use the official markscheme logic.
    

DIAGRAMS

- All diagrams, graphs, and figures from the question papers must be preserved as **images** and placed directly under the relevant question.
    

FORMATTING

- Use clear section headers:
    
    - “Paper 1 – Question 3”
        
    - “Answer:”
        
- Maintain spacing so that each question feels like a self-contained lesson.
    
- Keep the tone neutral and instructional.
    

OUTPUT

- Export each paper as a **.docx** file.
    
- The files must be ready for direct upload to Google Drive and conversion into Google Docs without any cleanup.
    

This transformation must be mechanical and faithful:

- No skipping questions
    
- No merging papers
    
- No rewording questions
    
- No removing marks
    
- No altering IB intent
    

You are converting raw exam papers into a **private IB workbook system** with perfect traceability from question → answer.

# ideas

what if we build a growth loop where students themself upload the ans of while explaining the question and the ans - in return they get free credits 

upvote and down vote feature to choose the best video for that solution. and show at the top 