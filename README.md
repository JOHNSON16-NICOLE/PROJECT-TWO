# The Pierce County WA Employee Survey ( interactive dashboard creation using power bi)

## Project Objectives 
To analyze the employee engagement survey responses voluntarily provided by government employees of Pierce County, in order to assess employee engagement, identify key workplace trends, and generate insights that can support informed organizational decision-making and improve employee satisfaction.

## Data set used 
https://docs.google.com/spreadsheets/d/1nbhfp2ModgqDAPveYQG9CknRw2PYJQxbOTs3xSKOB8E/edit#gid=61186505

## Questions
1.  Which survey questions did respondents agree with or disagree with most? 
2. Do you see any patterns or trends by department or role? 
3. As an employer, what steps might you take to improve employee satisfaction based on the survey results?
4. What is the overall employee sentiment?

Dashboard interactions   https://drive.google.com/file/d/1j0P1DAsc1RFE_Bs5aNc58CnLq-7RHgTe/view?usp=sharing

## process
•	Correctly typed each column (IDs and role flags as whole numbers, Response as a number, remaining fields as text)
•	Propagated the nearest valid answer label downward into blank cells left by incomplete submissions
•	Propagated the nearest valid numeric answer code upward into blank Response cells
•	Collapsed the four binary Director/Manager/Supervisor/Staff columns into one readable category, defaulting to "Not Specified" when none were flagged
•	Mapped all 11 raw question-text variants to 10 standardized codes using keyword matching.
•	Assigned a numeric sort order to the Role field (Staff → Not Specified → Supervisor → Manager → Director) so dashboard visuals display roles in a logical hierarchy

## Dashboard screenshot 
<img width="984" height="554" alt="PIERCE EMPLOYEE" src="https://github.com/user-attachments/assets/2fe77b93-877c-436c-b8c2-689e1a643c54" />

