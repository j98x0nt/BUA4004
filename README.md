java c
BUA4004 Teamwork Assessment – Data Analysis Report
Introduction
In this assessment, you will work in a team of 2, 3 or 4 students including yourself. Formation of each team is left to the students’ autonomy. Your instructor will NOT decide on your team members.
Recall that your instructor has strongly encouraged you to interact with other students since the first workshop session in Week 1, expecting each of you to identify your potential team members. Note that you are NOT required to inform. your instructor of the members of your team before the submission of the work.
If you do not work as part of a team and subsequently submit an individual work, you will not meet one of the five Subject Intended Learning Outcomes, namely SILO5. Therefore, your submission will automatically be penalised by 20%. For example, even if the work is worth 70 out of 100, if it is an    individual submission it will receive only 56.
First of all, select the team leader once a team is formed. The key task of each team leader is to submit the work through her/his LMS account on behalf of the team. Non-leaders MUST NOT submit any file to avoid confusing the LMS system. Only the leader must submit the work. Please note that leaders are NOT expected to do more than non-leaders in terms of analysis and report preparation.In case you have a misunderstanding about the nature of teamwork, please bear in mind that, in this  subject, teamwork is NOT about dividing up tasks among students to reduce workload per student. It is not about the production of patch work. Each student is expected to do ALL tasks.
Teamwork is about improving the submission through comparisons and discussions of answers from different individuals. Research has provided empirical evidence to support the idea that two brains are better than one, three are better than two, etc. (but too many brains don’t seem to work well because of coordination difficulty when there are too many people). All team members are expected to prepare their own response to each task before each team meeting. All team members should have chances to critically examine the answers prepared by the other members of the team.
Typically during each meeting, but ideally before it in order to give everyone enough time to think through and make each meeting productive.
ALL members of a team will receive the SAME mark based on the leader’s submission. Because of the nature of teamwork as described above, we will not accept a common complaint such as “I knew the correct answer but lost lots of marks because of the other students in my team” . Students who make this type of complaint are unaware that the loss of marks is partly due to their fault because they had failed to persuade other students that they were wrong during meetings.
For the same reason, all members of a team will be equally penalised when even just one of the members commits academic misconduct and taints the team’s work. Very unfortunately, we have several such cases in the past semesters. For this reason, students are advised to choose teammates carefully and actively monitor each other whether they are preparing their answers sincerely by themselves (easy check: Can they logically explain when you ask questions about their prepared answers during meetings? – If not, suspect plagiarism).
Another common complaint is for example “That student hasn’t done anything, and we want to exclude him from the team, as it’s unfair that he receives a mark based on our effort.” A reasonable point. But it is problematic if you suddenly drop such a lazy student closer to the submission deadline, as he will have no time left to change his heart and work harder. For this reason, I suggest every team to have the first meeting in Week 7 at the latest and to meet at least once a week after  that. Face to face, online, hybrid – all are acceptable forms of team meeting. As everyone has a different schedule, one hour or less is recommended for each meeting, unless all members want to have a longer meeting. If a student does not turn up in the first meeting, you may already communicate to the student that he is no longer part of the team. If a student turns up without any preparation, again you may decide to ask him to leave the team. The point is that, if you notice a student who shows a sign of free riding, do not keep him in the team until the last minutes in order to avoid further issues. Cutting him off early is kind, as it will give the student a second chance.
Please however keep in mind that you should not expect everyone to contribute equally. Everyone has different strengths and weaknesses, and it is not possible for everyone to contribute literally equally. The point is that team members should be able to recognise everyone is making efforts and are reasonably happy with each other even though different members contribute differently.
I’ve heard that many have maintained their friendships created through this teamwork assessment, even after the semester. Hope you will also enjoy working in a team and make friends! (That’s in addition to the benefit of your being able to provide potential employers with some good evidence of teamwork.)
Scenario
Bostin Consulting Group (BCG hereafter) was approached by the government of the Kingdom of
Kampuchea (Cambodia hereafter). They are concerned with the fact that some children are not
receiving as much school education as they’d like to see. They believe that children are the future of the country, and well educated people are crucial for the development of the country. BCG was
asked to assist the government in school education-related policy making.
You are a BCG employee and have been appointed to be part of the team assigned to this public policy consulting project. Currently the team is preparing for the first meeting where BCG will
present preliminary findings to the government staff. Preliminary findings will illustrate and
summarise the current situation about schooling-age children and are important inputs for thinking about appropriate policy making.
For the preliminary analysis, the team has been referred to the Cambodia Living Standards Measurement Survey (LSMS hereafter) 2019-2020, conducted by the World Bank and the
Cambodian National Institute of Statistics. (This survey is not fiction, and you can read about it at https://microdata.worldbank.org/index.php/catalog/4045
Download the following three PDF files that are located together with this PDF file inside the Assessments box.
.    cambodia_lsms_basic_information_document.pdf
.    cambodia_lsms_plus_questionnaire_english_public.pdf
.    cambodia_living_standards_measurement_study_plus_manual_english.pdf
Those documents are original documents from the World Bank. You’ll need to refer to those documents when you examine and interpret the data.
As for the data set, the statistical expert team of BCG has already processed the original data set to some extent for ease of analysis by your team. Download the following Excel file, also located together with this PDF file.
.    From LSMS Cambodia 2019.xlsxThe following list of variables in the data file has also been provided to you. Please note that the   variables following HHID are household-level variables (that is, the information is the same for all individuals within the same household) while the variables following PID are individual-level variables (that is, the info is specific to the person in question). The data is organised such that individuals are grouped by household, e.g. 7 persons from the same household are presented from row 2 to row 8.
The data file contains the information on 6,351 persons.
Familialise yourself with the data set before you tackle the tasks below. It will help you better
understand the data set if you also read pages 1-3, 24-27 of the questionnaire PDF file while you browse the data set.
Task 1. Preparing the data for analysis
Task 1.1
First of all, in order to focus on the children of schooling age, remove from the provided data set anyone who is either younger than 6 years old or older than 17.
In this assessment, let us concentrate only on the children of the household head because they are the majority of the children in the data set and the number of children of the other household members in the data set are too small to be representative. Therefore, also remove anyone who is not a child of the household head.
Hint: You are free to take any approach to do this task, but one relatively straightforward procedure is the following: First, create a dummy variable by using the AND function inside the IF function.
Then, delete all rows with 0 in the dummy variable by using Custom Sort. (Visit the Microsoft Excel Support website where you can find example of using the AND function inside the IF function, if you are unsure of how to do that.) The use of Filter is not recommended, as it does not remove unwanted observations from the data set but only hides them. Note that your reduced data set should contain 1,288 children.


Task 1.2
Second, remove 6 years old children who had not yet started schooling because of their birthday and the timing of the beginning of an academic year. Otherwise, we will overestimate the number of eligible children who did not go to school.Hint: Use the variable “Why not attending school?” where their parents stated that they were “Too  young” to go to school. Again, the use of the AND function inside the IF function will be useful. Note that your further reduced data set should now contain 1,266 children.
Task 2. Inspecting the distribution of children
The team decides to begin with an inspection of the distribution of children. The team is specifically interested in knowing whether there is any relationship between being out of school and age, and    also between being out of school and sex.
Task 2.1Construct a relative frequency table to observe the distribution of the schooling-age children by age, sex and the incidence of currently schooling. Present each relative frequency only up to 3 digits after the decimal point.
Hint: First of all, carefully examine the 3 variables “Age”, “Sex” and “Currently schooling” . You’ll notice that there are 34 missing entries in “Currently schooling” . You’ll also notice that we can fill those empty cells with “No” because those children have an entry in “Why not attending/attended school?” . Use Replace under Find  S代 写BUA4004 Teamwork Assessment – Data Analysis Report
代做程序编程语言elect in Excel, to fill all empty cells with “No” in the column “Currently schooling” . This will ensure that you can retain all 1,266 children in the data set.Treat the variable “Age” as a discrete variable. Then, create 4 categories using “Sex” and “Currently schooling”, e.g., Currently schooling male, Currently not schooling male, etc. because a table is only two-dimensional but we want to disaggregate the children by three criteria.
Task 2.2
Visualise the distribution above by creating a multiple bar chart where age is on the horizontal axis. Briefly comment on the chart by pointing out any two features you notice in the chart.
Task 2.3
Assuming that the data set represents the population of schooling-age children in the country, …
a)    What is the probability that a randomly selected schooling-age boy is currently out of school?
b)   What is the probability that a randomly selected schooling-age girl is currently out of school?
c)    Considering your answers above, are girls more likely to be out of school than boys?
d)   What is the probability that a randomly selected primary school-age child (age 6 to 11) is currently out of school?
e)    What is the probability that a randomly selected lower secondary school-age child (age 12 to 14) is currently out of school?
f)    What is the probability that a randomly selected upper secondary school-age child (age 15 to 17) is currently out of school?


g)    Considering your answers above, are older children more likely to be out of school than younger children?
Hint: Use your answer to Task 2.1 above.
Task 3. Examining the distribution of education-related expenditures
The data set provides information on the total education-related expenditure for each child during    the last academic year if the child went to school during the period. The team would like to examine the expenditures across different school levels.
Task 3.1
First, the expenditure data should be disaggregated by school-age group. Follow the instructions
below to create 3 new variables based on “Total educational expenditure for the last school year (in riels)” and “Age” .
1)    Use the 3 columns next to “Total educational expenditure for the last school year (in riels)” . Label the columns. For example, “Expenditure, age 6-11”, “Expenditure, age 12-14”,
“Expenditure, age 15-17” .
2)    For the first column, in the first cell under the label, type
=IF(AND($R2<12,$AV2<>""),$AV2,"")
3)   Then, copy and paste it to the remaining cells in the column.
4)    For the second column, you’d type =IF(AND($R2>11,$R2<15,$AV2<>""),$AV2,"")
5)    For the third column, think by yourself.
6)    Examine the 3 new columns to check if you successfully disaggregated “Total educational expenditure for the last school year (in riels)” by school-age group.
We used "" to ensure that the empty cells in “Total educational expenditure for the last school year (in riels)” are preserved, instead of being automatically converted to the value 0. This is important    because it is unclear whether the empty cell represents zero spending or missing information.
However, while the use of "" generates empty cells to our eyes, it prompts Excel to insert a so-called  zero-length string in those cells. As a result, Excel will not recognise them as empty. Because this text information in each empty-looking cell will interfere with computation, we should remove them before analysing the 3 created variables. How do we remove something that is already invisible to our eyes? 
1)    Copy the 3 new columns. Then, paste onto the Task 3 sheet from cell A1, using “Paste” => “Paste Values” => “Values” . This way, the entries are no longer formulae.
2)   To see if the empty cells are really empty, type =ISBLANK(A2) and press Enter at any cell
except columns A to C. You will then see FALSE to confirm that cell A2 is actually not empty. (If empty, you’ll get TRUE.)
3)   We first change the entry in the empty-looking cells to any visible entry, such as letter z. It is recommended to use a letter instead of a number in order to avoid any potential mix-up with actual expenditure data. Highlight the block A2:C1267. Go to Find  Select. Choose
Replace. Do not type anything in “Find what”. Type any letter (say, z) in “Replace with” . Tick “Match entire cell contents” . Click Replace All. Now you’ll see all previously empty looking    cells contain the letter you used. Do not close the “Find and Replace” menu yet.
4)    Now, type the letter you used in “Find what” . Then, delete the letter in “Replace with” . Click  Replace All. Now you’ll see the letter entries are gone, and the cells are looking empty again. Do the same procedure as Step 2 above to check if you’ve successfully removed zero-length   strings. You should get TRUE this time.
This procedure exploits the fact that the Find and Replace function cannot distinguish between zero length and true blank and that no entry in “Replace with” returns true blank. Admittedly, the procedure is long-winded, but is necessary for handling empty-looking non-blank cells (which, if not eliminated, will frustrate you during data analysis).
Task 3.2
a)    Produce a table of descriptive statistics to understand the distribution of each of the 3 expenditure variables. (Hint: Excel’s Data Analysis will not produce some of the useful  statistics you’ve learned.)
b)   Also produce a chart presenting 3 box-whiskers plots.
c)    Discuss the distributions of the 3 expenditure variables, using the statistics and chart that
you produced above. (Hint: Your discussion will become systematic if you talk about central location, symmetry and spread. Write one short paragraph about each of those three distributional features. Within each paragraph, in addition to discussing each variable’s distribution, do not forget to point out differences and similarities across the 3 expenditure variables.)
Task 3.3
Does the average educational expenditure per upper-secondary school child exceed 1,380,000 riels   per academic year in Cambodia? Support your answer by providing a step-by-step hypothesis test at the 5% level of significance.
Task 4. Exploring the causes of education-related expenditures
The team now would like to conduct preliminary analysis on the determinants of household expenditure on child education. The members discussed potential factors affecting the expenditure and, as a result, formulated the following linear regression model:
Ei,h  = β0  +β1Ai,h  +β2Mi,h +β3kh +β4yh +β5ch  +ε
with Ei,h denoting the total expenditure on the education of child i in household h (in riels), Ai,h denoting the age of child i in household h (in years),
Mi,h denoting the indicator of child i in household h being male,
kh denoting the indicator of the head of household h (that is, a parent of child i) being Khmer,
yh denoting the number of years the head of household h attended school,
ch denoting the total number of children under the age of 18 in household h.
Task 4.1First of all, in order to conduct this regression analysis, create the dummy variables Mi,hand kh, as  they are not available in the data set. (Ei,h  is “Total educational expenditure for the last school year (in riels)”,Ai,h is “Age”, yh  is “#years Head attended school”, and ch  is “#children under 18”.)
Task 4.2
Regression in the Data Analysis menu does not handle blank cells well. It does not run regression when there are missing observations in any variable. You can see that the outcome variable has   many missing observations. Therefore, remove all children who do not have expenditure
information. Use the following instruction if the team does not have any other favourite procedure.
1)    Copy and paste the 6 variables of the model onto the Task 4.2a worksheet.
2)    Fill the blank cells in “Total educational expenditure for the last school year (in riels)” with
any letter (say, “z”) using Replace. (Remember the issue of zero-length strings, raised in Task 3.1? The current procedure will avoid generating zero-length strings, instead of generating
them first and deleting them later.)
3)    Create a new variable “A” using both “Age” and “Total educational expenditure for the last school year (in riels)” as follows. In the cell under the label “A”, type =IF($F2="z","z",A2) if
“Age” is in column A and “Total educational expenditure for the last school year (in riels)” is in column F. Then, copy and paste the formula to fill the column. This procedure will copy
the data in “Age” only if the expenditure info is available and enter letter “z” otherwise.
4)   Apply the same procedure to each of the remaining 4 explanatory variables.
5)    Now copy the 6 variables that contain letter “z” . Then, Paste => Paste Values => Values on the Task 4.2b worksheet.
6)   Select from A1 to F1267. Use Replace to delete z. Keep the data range selection.
7)    Go to Find  Select again. Select “Go To Special …” . Choose “Blanks” . Then, right-click at any of the selected blank cell. Choose “Delete” . Choose “Shift cells up” and then click OK.
You have now created a data set without a missing observation, containing 999 children.
Task 4.3
Run the regression, and answer the following questions.
a)    Are all slope coefficients statistically significant at the 5% level of significance? If not, which slope coefficients are statistically significant at that level?
b)    Interpret each of the statistically significant slope coefficients.
c)    Is there a sign of gender bias in household expenditure on child education? Briefly explain your answer.
d)    Is there a sign of ethnicity bias in household expenditure on child education? Briefly explain your answer.
e)    Is the model overfitting? Briefly explain your answer.
f)     Is the model explaining the variation in household expenditure on child education very well? Briefly explain your answer.
g)    Can we maintain the assumption that the error term of the model is normally distributed? Support your answer by a step-by-step hypothesis test.
h)   Suggest any other explanatory variable that is likely to impact household expenditure on child education (and hence the team might consider to include in the regression model if such a variable is available in the data set). Briefly explain why and how it may affect the  expenditure.



         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
