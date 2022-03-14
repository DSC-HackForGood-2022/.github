# DSC Hack for Good Submission
- Cui Shen Yi
- Jason Qiu

## Rationale
## Problem Statement
_How can we get employers to be open and hire women who have less social mobility and may not have access to livelihood opportunities?_

## Our Solutions
### NeuralizeIt
- Gender discrimination when hiring is not the fault of the employer alone. Employers may be guilty of their unconscious biases; however, women are implicitly discouraged from applying to jobs due to the gendered verbs in many job application adverts.

- Women need to be more empowered to apply for open job opportunities. However, studies have shown that "masculine worded job descriptions significantly deterred women from applying to jobs regardless of whether the job was stereotypically male, female, or gender-neutral" [(Gaucher et al., 2011)](https://doi.apa.org/doiLanding?doi=10.1037%2Fa0022530) [(Gender Discrimination and Bias in Job Descriptions)](https://www.paycor.com/resource-center/articles/are-your-job-descriptions-driving-away-talent-with-unconscious-gender-bias/). Therefore, our Chrome Extension Application **NeutralizeIt** attempts to resolve this issue. 

- The Chrome Extension will curate any HTML page and replace gendered verbs with neutral alternatives. The hope is to help empower women to shed their own biases to job opportunities and, in turn, increase their employment.

### AnonymizeIt
- While NeutralizeIt addresses the issue of women not applying for jobs due to their own perceived biases. The problem still exists on the employer side. 79% of HR professionals agree that unconscious bias exists in the hiring process [(CMiC, 2021)](https://cmicglobal.com/resources/uncovering-unconscious-bias-in-workplace-hiring-practices-key-statistics-and-proven-solutions/#:~:text=Racial%20Bias%3A&text=75%25%20higher%20likelihood%20to%20secure,with%20%E2%80%9CLatino%2Dsounding%E2%80%9D%20names). Furthermore, research has shown that applicants with male names are 40% more likely to be called for an interview than female names [(Souza & Doyle, 2020)](https://www.brighttalk.com/webcast/17947/438643). While many places in the hiring process can be improved, we have focused our next solution on the interview process. 

- Employers should have the choice to conduct "blind interviews" to reduce their own unconscious biases that could affect the hiring process. The Telegram Bot **AnonymizeIt** addresses this issue by allowing two parties to communicate completely anonymously and privately. AnonoymizeIt is a telegram bot that acts as a third party between an interviewer and interviewee

### Challenges
- Recursively parsing through elements in an HTML dom to effectively edit HTML without destroying the already established structure. 
- Generating word bank of gendered words with accurate and neutral replacements

### What We Learned
- jQuery
- How to make a Telegram bot
- How to make a Google Chrome Extension

### Potential Improvements
- Expand word bank for NeutralizeIt to include more gendered words and variations
- Implement a management system for AnonymizeIt for recruiters to communicate with multiple applicants at the same time

## NeutralizeIt
- [User Guide and Demo](https://dsc-hackforgood-2022.github.io/NeutralizeIt/)
- [Repository and Installation](https://github.com/DSC-HackForGood-2022/NeutralizeIt)

## AnonymizeIt
- [User Guide and Demo](https://dsc-hackforgood-2022.github.io/AnonymizeIt/)
- [Repository and Installation](https://github.com/DSC-HackForGood-2022/AnonymizeIt)

