![Background](images/new_bg.png)
# SMART+ER PROMPT
A smarter SMART+ER prompt template provided by Everyone's AI
---
## 1. Background of the SMARTER Prompt Template

> **Q: "Do I need to learn prompt engineering to make proper requests/instructions/questions to AI?"**

> **A: "You don't study engine structures to drive a car. Just as you learn how to drive well, to give proper instructions to AI, you only need to learn the art of AI conversation rather than prompt engineering."**

With the advancement of generative AI's large language models (LLM-Large Language Model), AI's capabilities have improved dramatically. However, to fully utilize these capabilities, "**clear and specific instructions**" are necessary.

> **The difficulty users face in writing prompts → "How exactly should I phrase it so that you understand my intention correctly?"**

Based on feedback analysis from participants of **"Living with ChatGPT for a Month," "The Art of Prompting," and "Creating My Own AI Employee"** online/offline courses conducted by Everyone's AI over the past year, the following major issues were identified:

1. **Vague Instructions**: Many instances where AI could not provide proper answers due to unclear requests like "Give me a good idea."
2. **Lack of Context**: AI sometimes fails to grasp the user's intent due to insufficient background information or situational explanation.
3. **Excessive Information**: Conversely, providing too much information at once can prevent AI from grasping the core.
4. **Lack of Step-by-Step Instructions**: When requesting complex tasks, the absence of step-by-step instructions can confuse AI.
5. **Absence of Feedback Loop**: Many users are unaware of effective feedback methods to improve AI's responses.

Due to these issues, **users often fail to get the desired results and repeatedly reach the 3-hour 80-prompt limit by adding additional instructions.**

To address these issues, the **SMART+ER Prompt Template** was created. This template is a **structured guideline designed to help even general users easily write effective prompts.** The **SMART+ER template systematizes the core principles of prompt engineering** to enable anyone to communicate more effectively with AI.

---

# 2. What is the SMART+ER Prompt?

## Definition and Purpose

The main features and purposes of the SMART+ER prompt are as follows:

1. **User-Friendly Structure**: Provides a systematic structure that even general users can easily understand and apply.
2. **AI Performance Optimization**: Designed to maximize the capabilities of AI models.
3. **Support for Various LLMs**: Applicable to various large language models (LLM) such as ChatGPT, Claude, Gemini, etc.
4. **Minimization of Revisions**: Aims for **One Shot Prompting (instructions that end in one go)** by presenting clear instructions and specific requirements.
5. **Improved Context Understanding**: Helps AI accurately grasp the user's intent and situation.

## SMART+ER Acronym Explanation

SMARTER represents the core components of the template:

### **5 Essential Elements**

- **S**: Situation - Describes the current **situation** or **background**.
- **M**: Mission - Specifies the **goal** to be achieved.
- **A**: Action Steps - Lists the **steps** AI needs to perform.
- **R**: Result - Specifies the **format of the desired outcome**.
- **T**: Tone & Style - Specifies any **special requirements** or **style for the generated result**.

### **2 Additional Elements**

- **E**: Example - Provides **examples to aid AI's understanding**.
- **R**: Resource - **Details additional information or resources** needed for AI's generation task.

This template systematizes prompt writing, helping users clearly convey their requirements and obtain the desired results from AI.

---

# 3. Components of the SMART+ER Template

## S: Situation

- **Purpose**: Provides the current situation or background to AI.
- **How to Write**: AI knows nothing about your situation, so provide concise yet sufficient context.
- **Example**:

    ```markdown
    ## S(Situation)
    Our company is planning to launch an eco-friendly product line. Reducing plastic usage is a major task.
    ```

## M: Mission

- **Purpose**: Clearly state the specific goal you want to achieve with this prompt.
- **How to Write**: Set clear and measurable goals (e.g., time frame, numbers, scope, country, target).
- **Example**:

    ```markdown
    ## M(Mission)
    We aim to develop a strategy to reduce plastic usage in product packaging by 50% within 6 months.
    ```

## A: Action Steps

- **Purpose**: List the specific steps AI needs to perform.
- **How to Write**:
    - Provide clear instructions in order.
    - If necessary, add: **"Important: After each step is completed, the user should confirm the result and decide whether to proceed to the next step."** 
    -> Adding this content enriches the output (maximizing Max Output Token usage) and allows for text savings in the conversation window by requesting modifications only for each step's content.

- **Example**:

    ```markdown
    ## A(Action Steps)
    "Important: After each step is completed, the user should confirm the result and decide whether to proceed to the next step."
    1. Analyze the current plastic usage in product packaging.
    2. Propose three eco-friendly materials that can replace plastic.
    3. Compare and analyze the pros and cons of each alternative material.
    4. Calculate the expected cost and time for transitioning to the selected material.
    5. Develop a step-by-step transition plan for 6 months.
    ```

## R: Result

- **Purpose**: Specify the format and content of the desired outcome.
- **How to Write**: Specify the format, length, and elements to be included.
- **Example**:

    ```markdown
    ## R(Result)
    Please write a 5-page report including the following elements:
    - Current situation analysis
    - Comparison table of alternative materials
    - Cost and time estimates
    - 6-month transition plan timeline
    - Expected environmental impact
    ```

## T: Tone & Style

- **Purpose**: Specify any special requirements or preferred style.
- **How to Write**: Specify tone, format, and any specific constraints.
- **Example**:

    ```markdown
    ## T(Tone & Style)
    - Use non-technical terms that are easy for executives to understand in the report.
    - Include summary bullet points in each section.
    - Cite reliable sources for environmental statistics.
    ```

## E: Example

- **Purpose**: Provide examples or templates for reference.
- **How to Write**: Present examples of similar projects or desired outcomes.
- **Example**:

    ```markdown
    ## E(Example Reference)
    Please refer to the report format in the following link: 
    - [Example of Environmental Impact Assessment Report]
    - "Please write in the same style as I have written."
    ```

## R: Resource

- **Purpose**: Provide additional information or resources needed for the task.
- **How to Write**: Present related data, links, and reference documents.
- **Example**:

    ```markdown
    ## R(Resource Reference)
    - Current product packaging specifications: [Link]
    - Market research report on eco-friendly packaging materials: [Attached file]
    - Company environmental policy document: [Link]
    ```

---

# 4. Detailed Explanation and Writing Method for Each Component

## S: Situation

### Detailed Explanation

The Situation section provides the current situation or background to AI. This helps AI understand the overall context and generate appropriate responses.

### How to Write

- Include all essential information concisely.
- Consider the 5W1H (Who, What, When, Where, Why, How) questions when writing.
- If industry-specific terms or new terms require background knowledge, provide a brief explanation. Example: MCP (Model Context Protocol)

### Caution

- Avoid overwhelming AI with too much information.
- Do not include unnecessary personal information.

### Example

```markdown
## S(Situation)
- Our company is a small to medium-sized fashion brand OOO. We are concerned about the increasing attrition of Gen Z customers.
- Compared to the third quarter of 2024, the purchase rate of Gen Z customers decreased from 85% to -30% in January 2025, and social media engagement dropped from 60% to -20%.
- The marketing budget for 2025 is 500 million KRW annually, and we lack digital marketing experts.
```

## M: Mission

### Detailed Explanation

The Mission section specifies the specific goal you want to achieve. It is crucial for determining the direction of the solutions AI proposes.

### How to Write

- Present quantifiable goals whenever possible.
- You can distinguish between short-term and long-term goals.

### Caution

- Avoid goals that are too broad or vague.
- Set realistic and achievable goals.

### Example

```markdown
## M(Mission)
- Increase the purchase rate of Gen Z customers by 20% from the current level within the next 6 months.
- Improve social media engagement by 50% within 3 months.
- Achieve the above goals while reducing the annual marketing budget by more than 10%.
```

## A: Action Steps

### Detailed Explanation

The Action Steps section lists the specific steps AI needs to perform. It guides AI to work systematically.

### How to Write

- Provide clear instructions in order.
- Each step should be specific and executable.
- You can subdivide into sub-steps if necessary.
- If necessary, add: **"Important: After each step is completed, the user should confirm the result and decide whether to proceed to the next step."**

### Caution

- Do not present too many steps at once. If necessary, divide them into multiple requests.
- Ensure logical connections between each step.

### Example

```markdown
## A(Action Steps)
"Important: After each step is completed, the user should confirm the result and decide whether to proceed to the next step."
1. Analyze the latest fashion trends and consumer behavior of Gen Z based on the attached materials (Deep Research materials).
2. Identify the gap between our brand's current marketing strategy and Gen Z trends.
3. Propose three digital marketing strategies targeting Gen Z. Each strategy should include:
   a. Utilization plan for major social media platforms
   b. Influencer marketing strategy
   c. Estimated costs and ROI
4. Select the most cost-effective strategy and explain the reason.
5. Develop an implementation plan for the second half of 2025 for the selected strategy.
```

## R: Result

### Detailed Explanation

The Result section clearly specifies the format and content of the desired outcome. It helps clarify the structure and details of the expected output.

### How to Write

- Specify the format of the desired outcome (e.g., report, list, script).
- List the key elements or sections that should be included in the outcome.
- If possible, specify the desired length or level of detail.

### Caution

- Avoid being too strict, which may limit AI's creativity.
- Choose an appropriate format considering the purpose or target audience of the outcome.

### Example

```markdown
## R(Result)
Please write a 5-page marketing strategy report including the following elements:
1. Summary of the current market situation (1 page, 3 paragraphs, each paragraph over 500 characters)
2. Target customer analysis (1 page, 3 paragraphs, each paragraph over 500 characters)
3. Proposal of three major marketing strategies (0.5 pages per strategy, 2 paragraphs, each paragraph over 200 characters)
4. Cost and ROI analysis (1 page, 3 paragraphs, each paragraph over 500 characters)
5. 6-month implementation plan timeline (0.5 pages, 2 paragraphs, each paragraph over 300 characters)
6. Summary and conclusion (0.5 pages, 3 paragraphs, each paragraph over 100 characters)
```

## T: Tone & Style

### Detailed Explanation

The Tone & Style section instructs AI to adjust the outcome to specific requirements or preferences. This allows for more customized results.

### How to Write

- Specify preferences for specific styles, tones, or formats.
- Mention specific elements or topics to include or exclude.
- Make customization requests considering the target audience or usage context.

### Caution

- Avoid imposing too many constraints that may limit AI's performance.
- Ensure customization requests do not contradict instructions in other sections.

### Example

```markdown
## T(Tone & Style)
- Write the report in simple language that non-experts can understand.
- Provide key summaries in bullet points at the beginning of each section.
- Use real-life examples or statistics to support arguments whenever possible.
- Maintain a positive and solution-oriented tone throughout.
- Use the company's brand color, blue (#0000FF), as an accent color.
```

## E: Example / R: Resource

### Detailed Explanation

Example and Resource are optional sections that provide examples or additional resources for AI to reference. These sections can help AI generate more accurate and relevant results.

### Important Notice

**E(Example) and R(Resource) are not mandatory sections.** They are used only when necessary and can be omitted depending on the situation. Particularly, these sections can be omitted in the following cases:

- For simple or general requests
- When specific examples or additional resources are not needed
- When sufficient information is already provided in other sections

### How to Write (When Used)

- Example: Provide examples or formats similar to the desired outcome.
- Resource: Provide related data, documents, links, etc., as additional information sources.

### Example

```markdown
## E(Example Reference)
- Refer to the structure and analysis method of the attached "Successful_Marketing_Campaign.pdf" document.
- For press release content, refer to the style of the attached link.

## R(Resource Reference)
- Latest market research data: [Link]
- Company brand guidelines: [Attached file]
- Competitor analysis report: [Document link]
```

---

# 5. Example of the SMARTER Template
## How to Use the Example
[Content] 'Content' should be modified to fit your situation.

---

```markdown
# Request for Meeting Minutes and Sharing Email

## S: Situation
You are an AI specialized in analyzing meeting content to draft official meeting minutes and a sharing email.

## M: Mission
Based on the meeting content provided by the user, summarize and organize the meeting minutes according to the specified format and draft the email body for sharing the minutes.

## A: Execution Plan
Important: After each step is completed, the user should confirm the content before proceeding to the next step.
1. Analyze the meeting content and draft: Analyze the meeting content (text, summary of transcripts, etc.) provided by the user and draft the meeting minutes according to the provided "Meeting Minutes Format."
2. Information Confirmation and Supplementation: If essential information (e.g., meeting title, date, location, attendee list, decisions, action items) required by the meeting minutes format is missing, clearly ask the user to supplement the necessary information.
3. Request for Review of Draft Minutes: Present the completed draft minutes to the user after supplementing information and request review and confirmation of any modifications.
4. Final Meeting Minutes Creation: Reflect the user's feedback to create the final meeting minutes text.
5. Drafting the Email Body: Based on the finalized meeting minutes, draft the email body summarizing the meeting content and guiding the reference to the minutes according to the provided "Email Format." (*Note: AI cannot actually attach files, so inform the user that they need to attach the minutes file themselves when sending the email.*)
6. Request for Review of Email Body: Present the drafted email body to the user and obtain final confirmation.

## R: Outcome

* Final Meeting Minutes: Meeting minutes text written according to the "Meeting Minutes Format" below.
* Email Body: Sharing email body text written according to the "Email Format" below.

## T: Tone & Style
Concise and professional business document style

## E: Example and Format

[Meeting Minutes Format]

Meeting Title: [Enter Meeting Title]
Date: [YYYY-MM-DD] [HH:MM] ~ [HH:MM]
Location: [Meeting Location]
Attendees: [List of Attendees (including positions recommended)]
Author: [Author's Name or AI]

1. Meeting Overview:
   [Summarize the main purpose and background of the meeting in 1-2 sentences]

2. Main Discussion Points:
   ① [Discussion Item 1]
      - Key Remarks/Content:
         - [Summary of Key Discussion Content 1]
         - [Summary of Key Discussion Content 2]
      - Decisions: [Specify agreed or decided content, if none, specify 'Further Discussion']

   ② [Discussion Item 2]
      - Key Remarks/Content:
         - [Summary of Key Discussion Content 1]
         - [Summary of Key Discussion Content 2]
      - Decisions: [Specify agreed or decided content]

   *(Add items as needed)*

3. Decisions and Action Items:
| Action Item | Responsible Person | Deadline | Remarks |
|---|---|---|---|
| [Specific Action Content 1] | [Responsible Person's Name] | [YYYY-MM-DD] | [Optional Additional Remarks] |
| [Specific Action Content 2] | [Responsible Person's Name] | [YYYY-MM-DD] | |

4. Other/Notable Items:
   [Additional information to be shared or other items such as the schedule for the next meeting]

---

[Email Format]

Subject: [Meeting Title] Meeting Results Sharing (YYYY-MM-DD)

To: [Attendees or Related Team]

Cc: [Reference if necessary]

Hello, this is [Author's Name or Team].

We are sharing the results of the '[Meeting Title]' meeting held on [YYYY-MM-DD].

Summary of Key Discussion Topics:
* [Summary related to Key Discussion Topic 1]
* [Summary related to Key Discussion Topic 2]
* Please refer to the attached minutes for major decisions and action items.

Attachment:
* [Meeting Title] Minutes_[YYYYMMDD].docx (or .pdf, etc.) *(The user must attach the actual file themselves)*

Thank you for attending despite your busy schedule.
Please feel free to reply if you have any questions.

Thank you.
[Author's Name or Team Name]
```
```markdown
# Everyone's AI Meeting Minutes

## Date
Date: April 1, 2025, 12:00~13:30
Location: Everyone's AI Meeting Room

## Meeting Attendees
- Jinwoo Kim (Secretary General)
- Seoyeon Lee (Operations Team Leader)
- Seongho Park (Planning Team Manager)

---

## :speaking_head: Virtual Meeting Conversation (Approx. 12 minutes)

Jinwoo Kim:
Alright, let's start the meeting. Today, we'll discuss the main schedule for the next quarter and improvements to the onboarding process for new member companies. First, could you briefly summarize the next quarter's schedule, Team Leader Seoyeon?

Seoyeon Lee:
Yes. First, the startup policy meeting scheduled for the end of April is the most important, followed by the member company networking day in mid-May, and the semi-annual forum in June. Especially for the policy meeting, we're coordinating the schedule with the Ministry of SMEs and Startups, so finalizing the detailed program is urgent.

Jinwoo Kim:
I also talked to the Ministry of SMEs and Startups, and they said we need to deliver the program proposal by early next week. Manager Seongho, how is the planning team preparing the content?

Seongho Park:
The first draft is ready, and we're organizing the startup positions by policy issue. However, it's taking some time to gather opinions by industry, so I think we can share the entire draft by this Friday.

Seoyeon Lee:
Alright, then our operations team will immediately conduct a survey to gather opinions from member companies and deliver it to the planning team by Friday morning.

Jinwoo Kim:
Sounds good. How about presenting statistics on the startup ecosystem at this meeting? Like growth indicators and investment trends compared to last year.

Seongho Park:
That's a good idea. We'll prepare a simple infographic using existing data and research from KDB and KOSPO. Including it in the presentation will add persuasiveness.

Seoyeon Lee:
Yes, we'll collaborate with the designer from the operations team to assist with the design part. It would be good to schedule a rehearsal before the policy meeting.

Jinwoo Kim:
Let's schedule the rehearsal for two days before the meeting, on April 24th at 3 PM. I'll confirm the attendees and presenters and share it on the calendar.

Seoyeon Lee:
Got it. Let's wrap up the policy meeting and move on to the next agenda item, the onboarding of new member companies. We've received internal feedback that the current response method is insufficient as the number of new sign-ups increases.

Seongho Park:
Yes, especially the initial communication is often slow. There are inquiries about not receiving guidance even after a few days of joining.

Seoyeon Lee:
So, I'd like to propose two main things this time. First, regular online onboarding sessions every other week, and second, composing the welcome kit in digital content form. We're considering moving away from paper-based guides to videos, web guides, and chatbot connections.

Jinwoo Kim:
Sounds good. Especially for the onboarding session, it would be nice to include a Q&A session. Previously, we only responded individually, but summarizing common questions and answering them all at once could be much more efficient.

Seongho Park:
Our planning team will assist with preparing the onboarding session materials. It would be better to create a conversational format rather than a presentation format to keep the representatives from getting bored.

Seoyeon Lee:
Great. For the video content, we'll shoot it in a format where each team leader shares team introductions and tips in under a minute. Short and to the point.

Jinwoo Kim:
Let's create both PDF and web versions of the practical guide, and update the FAQ for frequently asked questions. Also, it seems necessary to revise the welcome email to a more friendly tone than before.

Seongho Park:
Lastly, I'd like to propose one more thing. A method to regularly check the utilization status of new member companies during the initial three months. For example, once a month, the operations team could make a simple contact to check what resources have been used and if there are any needs.

Seoyeon Lee:
That's a really needed part. It's important to have a structure that not only encourages sign-ups but also ensures they are well settled, so continuous participation is possible. The operations team will design that process.

Jinwoo Kim:
Yes, very good. I'll organize the action items based on today's discussion and share them with you by the end of the day. The next meeting will be two weeks from now, on Wednesday at 10 AM, and if there are any special requests, informal meetings are also possible in between.

Seoyeon Lee:
Yes, I'll register the schedule on the calendar. Thank you for your hard work!

Seongho Park:
Thank you all for your hard work. I'll deliver the organized materials by Friday morning!

---
## Office Planning and Business Management - Project Management

Prompt for Project Management for Office Planning and Business Management

### Prompt Writing Tips

- Situation: Describe the current project situation for office planning and business management in detail.
- Goal: Set specific goals for project management.
- Execution Plan: Present a step-by-step plan for effective project management.
- Deliverables: Clearly specify the desired form of the project management plan or schedule.
- Tone and Style: Use a professional and systematic tone.

### Prompt Example

```markdown
## S: Situation
- [You] are [in charge of office planning and business management], currently working on a [new business launch project].
- The project must be completed [within 6 months] with a budget of [100 million KRW].
- The team consists of various departments such as [planning, marketing, development, design], and is currently in the [initial planning stage].
- Previous projects faced issues of [schedule delays and budget overruns], so improvements are sought this time.

## M: Goal
- Successfully complete the [new business launch] within [6 months].
- Maximize project efficiency by adhering to the [project schedule] and operating within the [budget].
- Enhance [project quality] by strengthening smooth collaboration and communication among teams.

## A: Execution Plan
- Important: After each step, the user should confirm the generated deliverables and decide whether to proceed to the next step.

1. Establish Project Schedule
   - Divide the entire project into phases and set milestones for each phase.

2. Budget Management
   - Break down budget items and allocate budgets for each item.
   - Prevent overspending through regular budget reviews.

3. Team Composition and Role Assignment
   - Clearly define the roles and responsibilities of each department.
   - Share progress and resolve issues through regular team meetings.

4. Risk Management
   - Identify potential risks during project execution and establish response plans.
   - Minimize project delays through immediate response to risks.

## R: Deliverables
- Write a [project management plan] including the following items:
  - Project overview
  - Schedule and milestones
  - Budget details
  - Team composition and roles
  - Risk management plan

## T: Tone and Style
- Tone: Professional and systematic
- Style: Concise and clear sentences, use tables and lists to enhance readability
- Target Audience: Project team members and management
```

---

## CEO - Legal Consultation and Contract Review

Prompt for Legal Consultation and Contract Review for the CEO

### Prompt Writing Tips

- Situation: Describe in detail the current legal issues or contract situation of the CEO.
- Goal: Set specific goals for legal consultation and contract review.
- Execution Plan: Present a step-by-step approach for legal review.
- Deliverables: Clearly specify the form of the legal consultation report or contract amendment.
- Tone and Style: Use a professional and reliable tone.

### Prompt Example

```markdown
## S: Situation
- [You] are the [CEO], currently reviewing a [new partnership contract].
- The contract includes various clauses such as [joint marketing, technical cooperation, revenue sharing], and requires [legal consultation].
- Due to previous experiences with [legal disputes] in past contracts, a more cautious review is desired this time.
- Currently, the contract is being reviewed in collaboration with the [legal team] and external legal advisors.

## M: Goal
- Ensure that the [new partnership contract] is legally sound and maximizes the company's interests.
- Minimize [legal risks] and enhance the clarity of the contract.
- Complete the [review and approval] within [two weeks].

## A: Execution Plan
- Important: After each step, the user should confirm the generated deliverables and decide whether to proceed to the next step.

1. Review of Contract Draft
   - Review the draft contract focusing on key clauses.
   - Verify the accuracy of legal terms and amend ambiguous sections.

2. Risk Analysis
   - Identify risk elements included in the contract and prepare countermeasures.
   - Evaluate the potential for legal disputes.

3. Amendments and Negotiations
   - Reflect necessary amendments in the contract.
   - Conduct negotiations with the partner company to promote mutual benefits.

4. Final Review and Approval
   - Conduct a final review of the amended contract and obtain approval from the legal team and management.
   - Ensure all amendments have been incorporated.

## R: Deliverables
- Prepare a [legal consultation report] including the following items:
  - Analysis of key contract clauses
  - Legal risk assessment
  - Amendment and negotiation proposals
- Provide the [amended contract] with all amendments clearly reflected.
- Draft a [final approval document] to record the final approval status of the contract.

## T: Tone and Style
- Tone: Professional and reliable
- Style: Polite and formal language, precise use of legal terminology
- Target Audience: Management, legal team, external legal advisors
```

---
## Planning - Creating Meaningful Content for Senior Users

Planning prompt for creating content for senior users

### Tips for Writing Prompts

- Situation: Describe the current content requirements and background for senior users.
- Goal: Set specific goals for creating meaningful content for senior users.
- Execution Plan: Outline the step-by-step plan for content creation.
- Deliverables: Clearly specify the format or form of the desired content.
- Tone and Style: Use a friendly and easy-to-understand tone suitable for senior users.

### Example Prompt

```markdown
## S: Situation
- [You] are a [planner], currently planning a [digital education program for senior users].
- Senior users are experiencing [low confidence in using digital devices] and [technical barriers].
- Existing content has primarily focused on [basic usage], but does not meet the [advanced learning needs] of senior users.
- This project aims to provide [meaningful and practical content] tailored to senior users' needs.

## M: Goal
- [Complete the digital education program within 6 months] and aim to [improve senior users' digital device utilization skills].
- Achieve [participant satisfaction of 90% or higher] and measure success through [practicality assessment after program completion].
- Enhance [content accessibility and understandability] to maximize senior users' learning outcomes.

## A: Execution Plan
- Important: After each step, the user should confirm the generated deliverables and decide whether to proceed to the next step.

1. Senior User Needs Analysis
   - Conduct surveys and interviews to understand senior users' needs and expectations.
   - Analyze feedback from previous programs to identify areas for improvement.

2. Content Planning
   - Include diverse topics such as [advanced feature utilization], [safe internet usage], and [online communication methods] beyond [basic usage].
   - Design learning materials and practice exercises for each topic.

3. Content Creation
   - Use easy-to-understand language and visual aids to create content.
   - Provide content in various formats such as video lectures, PDF materials, and practice guides.

4. Testing and Feedback
   - Operate a pilot program to collect feedback from senior users.
   - Modify and supplement content based on feedback.

## R: Deliverables
- Prepare a [digital education program curriculum] including the following items:
  - Learning objectives and content for each week
  - Lecture materials and practice exercises
  - Evaluation and feedback methods
- Produce a [video lecture series] in a format easy for senior users to follow.
- Develop a [participant satisfaction survey] to evaluate the program's effectiveness.

## T: Tone and Style
- Tone: Friendly and easy to understand
- Style: Clear and concise language, abundant use of visual aids and examples
- Target Audience: Senior users, education program planners

```

---
## Designer - Design and Video Production

Design and video production prompt for designers

### Prompt Writing Tips

- Situation: Describe the background and purpose of the design or video production.
- Goal: Set specific goals for the design or video production.
- Execution Plan: Present step-by-step plans for the design or video production.
- Deliverables: Clearly define the desired form or format of the design or video.
- Tone and Style: Use a creative and visually appealing tone.

### Example Prompt

```markdown
## S: Situation
- [You] are a [designer], currently responsible for designing and producing videos for a [new product launch campaign].
- The new product is an [innovative smart device], and visual materials are needed to effectively promote it.
- Collaborate with the marketing team to create creative content while maintaining a [consistent brand image].
- Feedback from previous campaigns indicates that the design did not [sufficiently capture customers' attention].

## M: Goal
- Produce [three key design materials] and [one promotional video] for the new product launch.
- Ensure design materials include [creative elements while adhering to brand guidelines].
- The video should be [under 2 minutes] and intended for [social media and website posting].
- Complete all materials within the [launch campaign period].

## A: Execution Plan
- Important: After each step, the user should confirm the generated deliverables and decide whether to proceed to the next step.

1. Concept Development
   - Develop design and video concepts that reflect the new product's core values.
   - Create a storyboard to plan the video's flow.

2. Design Planning
   - Plan design elements such as [product images, banners, posters].
   - Consistently apply brand colors, logos, typography, and other visual elements.

3. Video Planning
   - Plan the promotional video through filming and editing.
   - Suggest using music, subtitles, and graphic effects to enhance the video's completeness.

4. Collaboration Proposal Writing
   - Write a 5-page proposal to review design and video materials with the marketing team.

## R: Deliverables
- [Three design plan documents]:
  - Product poster (A3 size)
  - Social media banner (1080x1080 pixels)
  - Website banner (1920x1080 pixels)
- [One promotional video plan document]:
  - Length: [under 2 minutes]
  - Resolution: [1080p]
  - Format: [MP4]
- [Design and video collaboration proposal]:
  - Collaboration request proposal

## T: Tone and Style
- Tone: Creative and passionate
- Style: Emphasize visually appealing elements, dynamic design, and video editing
- Target Audience: Marketing team, potential customers, internal employees
```

---

## Video Production and Administration - Video Production

Video production and administration prompt for video production

### Prompt Writing Tips

- Situation: Describe the background and purpose of the video production.
- Goal: Set specific goals for the video production.
- Execution Plan: Present step-by-step plans for the video production.
- Deliverables: Clearly define the desired form or format of the video.
- Tone and Style: Use a tone and style suitable for the message to be conveyed to the audience.

### Example Prompt

```markdown
## S: Situation
- [You] are a [video production and administration officer], currently producing a [video series for internal training].
- The target audience is [new employees], aiming to help them understand the company's culture and work processes.
- Feedback from previous training materials indicates that they are [text-centric] and lack engagement.
- This project aims to increase educational effectiveness through [visually engaging and interesting videos].

## M: Goal
- Produce [three educational videos] for use in [internal training programs].
- Each video should be [under 10 minutes] and aim to [increase audience understanding and engagement].
- Complete all video productions by [next quarter].

## A: Execution Plan
- Important: After each step, the user should confirm the generated deliverables and decide whether to proceed to the next step.

1. Content Planning
   - Define the educational content and key messages.
   - Write a storyboard for each video to plan the overall flow.

2. Scriptwriting
   - Write scripts that make the educational content easy to understand.
   - Include visual elements and explanations.

3. Filming Preparation
   - Suggest necessary equipment and locations.
   - Suggest talent and filming schedules.

4. Video Filming
   - Write a storyboard for filming.
   - Create a checklist for filming quality, including lighting and sound.

## R: Deliverables
- [Three educational video plan documents]:
  - Topic-divided videos (e.g., company culture, work processes, team collaboration)
  - Resolution: [1080p]
  - Format: [MP4]
- [Storyboard and script]:
  - Storyboard and script for each video

## T: Tone and Style
- Tone: Friendly and educational
- Style: Emphasize visual elements, dynamic style, and clear explanations and examples
- Target Audience: New employees, training officers
```
---
## Program Operation Assistant - Customer Service and Inquiry Response

Prompt for customer service and inquiry response for program operation assistant

### Tips for Writing Prompts

- Situation: Describe the current customer service situation and the types of inquiries being received.
- Goal: Set specific goals for effective customer service and inquiry response.
- Execution Plan: Outline the step-by-step plan for customer service.
- Deliverables: Clearly specify the desired format or form of the response.
- Tone and Style: Use a friendly and prompt tone suitable for customer service.

### Example Prompt

```markdown
## S: Situation
- [You] are a [program operation assistant], currently receiving customer inquiries on the [online education platform].
- The majority of inquiries are related to [membership registration, payment issues, course accessibility], and there has been a significant increase in inquiries due to recent user growth, necessitating prompt and accurate responses.
- The existing FAQ does not provide sufficient answers to some inquiries.

## M: Goal
- [Reduce the response time to customer inquiries to an average of 24 hours or less].
- [Achieve a resolution rate of 95% or higher] to increase customer satisfaction.
- [Update the FAQ] to reduce repetitive inquiries.

## A: Execution Plan
- Important: After each step, the user should confirm the generated deliverables and decide whether to proceed to the next step.

1. Inquiry Type Analysis
   - Analyze customer inquiry data from the past three months to identify key inquiry types.
   - Reconstruct the FAQ focusing on frequent inquiry points.

2. Response Manual Writing
   - Write standard response procedures for each inquiry type.
   - Prepare response templates to maintain consistency in responses.

3. Automation Tool Introduction
   - Design an automated scenario response for basic inquiries using chatbots.
   - Suggest the introduction of AI-based customer support tools to increase efficiency.

4. Team Training
   - Prepare training materials for customer service representatives on the new manual and tool usage.
   - Design regular training to maintain response quality.

## R: Deliverables
- [Updated FAQ]:
  - Includes detailed answers to key inquiry types
  - Enhanced search functionality for easy access
- [Response Manual]:
  - Includes response procedures and templates for each inquiry type
  - Distributed in markdown format for easy sharing
- [Chatbot Response Script]:
  - Automated response script for frequently asked questions

## T: Tone and Style
- Tone: Friendly and prompt
- Style: Clear and concise language, customer-centric response approach
- Target Audience: Customers, customer support team members
```