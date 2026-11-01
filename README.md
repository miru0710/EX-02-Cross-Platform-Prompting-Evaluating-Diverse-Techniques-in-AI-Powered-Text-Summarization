# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization
Name: Mirudhula N

Register number:212225220063

# EXPERIMENT: AI-Based College Notification Summarization System

## AIM

To design, execute, and evaluate different prompting techniques by progressively improving prompts from basic instructions to structured prompts for summarizing college notifications using AI platforms.

## SCENARIO

In colleges, students regularly receive notifications regarding examinations, assignment submissions, workshops, seminars, holidays, and other academic activities. These notifications sometimes contain lengthy information, making it difficult for students to identify the most important details quickly.

An AI-Based College Notification Summarization System can help students by converting lengthy college announcements into short and understandable summaries. It identifies important information such as dates, deadlines, timings, venues, and instructions.

The experiment uses different prompting techniques to generate clear and useful summaries of college notifications.

## APPLICATION SELECTED

**AI-Based College Notification Summarization System**

## SAMPLE COLLEGE NOTIFICATION

**Announcement: Internal Assessment Examination and Assignment Submission**

All second-year Information Technology students are hereby informed that the second internal assessment examination will commence on 18 November 2026. The examinations will be conducted from 9:30 AM to 12:30 PM in the respective classrooms.

Students must complete and submit their assignments for all subjects on or before 15 November 2026. Late submissions will not be accepted without prior permission from the concerned faculty members.

Students are instructed to bring their college identity cards and necessary stationery items for the examinations. They must arrive at the examination hall at least 15 minutes before the commencement of the examination.

For further clarification, students can contact their respective subject faculty members.

---

## PROMPTING TECHNIQUES USED

### 1. Basic Prompt

**Prompt Used:**

Summarize the following college notification about the internal assessment examination and assignment submission.

Notification:

[Paste the sample college notification here]

**Purpose:**

To generate a general summary of the college notification using a basic instruction.

**Sample Output:**

Second-year IT students are informed that the second internal assessment examination will begin on 18 November 2026, from 9:30 AM to 12:30 PM. Assignments must be submitted by 15 November 2026. Students should bring their identity cards and necessary stationery and arrive 15 minutes early.

### 2. Role Prompt

**Prompt Used:**

Act as a college academic assistant responsible for communicating important announcements to students. Summarize the following college notification in a clear and student-friendly manner.

Make sure students can easily understand the examination schedule and assignment submission instructions.

Notification:

[Paste the sample college notification here]

**Purpose:**

To generate a summary from the perspective of a college academic assistant.

**Sample Output:**

**Important Announcement for Second-Year IT Students**

The second internal assessment examination will commence on 18 November 2026, between 9:30 AM and 12:30 PM.

- Assignment submission deadline: 15 November 2026.
- Examination requirement: Bring your college ID card and stationery.
- Reporting time: Arrive at least 15 minutes early.
- For doubts, contact the respective subject faculty members.

Students are advised to complete their assignments before the deadline and prepare for the examinations.

### 3. Context Prompt

**Prompt Used:**

I am developing an AI-based notification system for college students. The system should help students understand lengthy college announcements without reading the entire notice.

Summarize the following notification for second-year Information Technology students. Focus on the examination date, examination timing, assignment deadline, and important instructions.

Notification:

[Paste the sample college notification here]

**Purpose:**

To provide sufficient background about the application and target audience so that the AI generates a relevant summary.

**Sample Output:**

**Second Internal Assessment – Important Details**

The second-year IT students' internal assessment examinations will start on 18 November 2026.

- **Examination Timing:** 9:30 AM – 12:30 PM.
- **Assignment Deadline:** 15 November 2026.
- **Reporting:** Reach the examination hall 15 minutes early.
- **Required Items:** College ID card and stationery.

Late assignment submissions will not be accepted without prior faculty permission. Contact the respective subject faculty for clarification.

### 4. Constraint Prompt

**Prompt Used:**

Summarize the following college notification by following these conditions:

1. Keep the summary within 80–100 words.
2. Use simple and direct English.
3. Include all important dates and timings.
4. Highlight the assignment submission deadline.
5. Mention the examination requirements.
6. Do not add any information that is not included in the original notification.
7. Avoid unnecessary explanations and repeated information.

Notification:

[Paste the sample college notification here]

**Purpose:**

To control the length, language, and content of the generated summary using specific restrictions.

**Sample Output:**

**Important Notice for Second-Year IT Students**

The second internal assessment examination starts on 18 November 2026, from 9:30 AM to 12:30 PM.

**Assignment Deadline:** Submit all subject assignments by 15 November 2026. Late submissions require prior faculty permission.

Students must bring their college ID cards and necessary stationery. They should reach the examination hall at least 15 minutes before the examination begins. For clarification, contact the respective subject faculty members.

### 5. Output Format Prompt

**Prompt Used:**

You are an AI assistant working in a college notification summarization system. Summarize the following college notification using the exact structure given below.

**Required Output Format:**

1. Notification Title
2. Target Students
3. Important Dates
4. Examination Timings
5. Assignment Deadline
6. Important Instructions
7. Contact Information

Additional Instructions:

- Use bullet points wherever appropriate.
- Highlight important dates and deadlines.
- Use simple and clear English.
- Keep the summary concise and organized.
- Include only details available in the original notification.

Notification:

[Paste the sample college notification here]

**Purpose:**

To generate a well-organized summary in a predefined structure so students can quickly identify important information.

**Sample Output:**

**1. Notification Title:** Second Internal Assessment Examination and Assignment Submission

**2. Target Students:** Second-Year Information Technology Students

**3. Important Dates:**
- Examination Start Date: 18 November 2026.

**4. Examination Timings:**
- 9:30 AM to 12:30 PM.

**5. Assignment Deadline:**
- Submit all subject assignments by 15 November 2026.

**6. Important Instructions:**
- Bring the college identity card and necessary stationery.
- Reach the examination hall 15 minutes early.
- Late submissions require prior permission from faculty.

**7. Contact Information:**
- Contact the respective subject faculty members for clarification.

---

## COMPARISON OF PROMPTING TECHNIQUES

 Basic Prompt - Gives a general summarization instruction , Produces a quick summary 
 Role Prompt - Assigns the role of a college academic assistant ,Makes the summary student-friendly 
 Context Prompt - Explains the purpose and target audience , Improves relevance 
 Constraint Prompt - Specifies word limits and content restrictions , Produces concise and focused summaries 
 Output Format Prompt - Defines the exact structure of the response , Makes information easier to locate 

## EVALUATION CRITERIA

The generated summaries can be evaluated using the following criteria:


Accuracy - Checks whether dates, timings, and instructions are correctly summarized 
Completeness - Checks whether all important notification details are included 
Clarity - Measures how easily students can understand the summary 
Relevance - Checks whether the summary focuses on important academic information 
Conciseness - Evaluates whether unnecessary information is avoided 
Organization - Checks whether the information is presented in a readable structure 

## OVERALL FINDINGS

The experiment demonstrates how different prompting techniques influence the quality of college notification summaries.

- Basic Prompting provides a general overview of the announcement.
- Role Prompting makes the response more suitable for students.
- Context Prompting helps the AI understand the purpose of the notification system.
- Constraint Prompting controls the summary length and prevents unnecessary information.
- Output Format Prompting organizes the important details into clearly defined sections.

Among these techniques, Output Format Prompting is particularly useful for a college notification system because students can quickly identify examination dates, assignment deadlines, and instructions.

## RESULT

The experiment successfully demonstrates the design and progressive improvement of five prompting techniques for an AI-Based College Notification Summarization System.

The prompts were developed from basic instructions to more detailed and structured instructions. The results show that providing a clear role, relevant context, specific constraints, and a predefined output format can improve the usefulness and readability of AI-generated notification summaries.

## CONCLUSION

Prompt engineering plays an important role in developing effective AI-based applications. By applying different prompting techniques, lengthy college notifications can be converted into concise, understandable, and organized summaries. Such a system can help students identify important academic information quickly and reduce the possibility of missing essential announcements.

