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

## 총괄 경영 대표이사 - 법률 자문 및 계약 검토

총괄 경영 대표이사를 위한 법률 자문 및 계약 검토 프롬프트

### 프롬프트 작성 팁

- 상황: 대표이사의 현재 법률적 이슈나 계약 상황을 상세히 설명합니다.
- 목표: 법률 자문 및 계약 검토의 구체적인 목표를 설정합니다.
- 실행 계획: 법률 검토를 위한 단계별 접근 방식을 제시합니다.
- 결과물: 법률 자문 보고서나 계약서 수정안 등의 형태를 명확히 합니다.
- 톤과 스타일: 전문적이고 신뢰성 있는 어조를 사용합니다.

### 프롬프트 예시

```markdown
## S: 상황
- [당신]은 [총괄 경영 대표이사]로, 현재 [신규 파트너십 계약]을 검토하고 있습니다.
- 계약 내용은 [공동 마케팅, 기술 협력, 수익 배분] 등 다양한 조항을 포함하고 있으며, [법률 자문]이 필요합니다.
- 이전 계약에서 [법적 분쟁]이 발생한 경험이 있어, 이번에는 더욱 신중하게 검토하고자 합니다.
- 현재 [법무팀]과 외부 법률 자문가와 협력하여 계약을 검토 중입니다.

## M: 목표
- [신규 파트너십 계약]이 법적으로 문제가 없으며, 회사의 이익을 최대화할 수 있도록 검토합니다.
- [법적 리스크]를 최소화하고, 계약의 명확성을 높이는 것이 목표입니다.
- [검토 완료 및 승인]을 [2주 내로] 완료합니다.

## A: 실행 계획
- 중요 사항: 각 단계마다 생성된 결과물에 대해 사용자가 추가/수정 사항을 확인한 후, 다음 단계로 진행합니다

1. 계약서 초안 검토
   - 주요 조항을 중심으로 계약서 초안을 검토합니다.
   - 법률 용어의 정확성을 확인하고, 모호한 부분을 수정합니다.

2. 리스크 분석
   - 계약서에 포함된 리스크 요소를 식별하고, 이에 대한 대응 방안을 마련합니다.
   - 잠재적인 법적 분쟁 가능성을 평가합니다.

3. 수정 및 협상
   - 필요한 수정 사항을 반영하여 계약서를 수정합니다.
   - 파트너사와 협상을 진행하여 상호 이익을 도모합니다.

4. 최종 검토 및 승인
   - 수정된 계약서를 최종 검토하고, 법무팀 및 경영진의 승인을 받습니다.
   - 모든 수정 사항이 반영되었는지 확인합니다.

## R: 결과물
- [법률 자문 보고서]를 작성하며, 다음의 항목을 포함합니다:
  - 계약서 주요 조항 분석
  - 법적 리스크 평가
  - 수정 및 협상 제안 사항
- [수정된 계약서]를 제공하며, 모든 수정 사항이 명확히 반영되어 있습니다.
- [최종 승인 문서]를 작성하여 계약의 최종 승인 상태를 기록합니다.

## T: 톤과 스타일
- 어조: 전문적이고 신뢰성 있는 어조
- 스타일: 정중하고 공식적인 문체, 법률 용어의 정확한 사용
- 대상 독자: 경영진, 법무팀, 외부 법률 자문가
```

---

## 기획 - 시니어 유저에게 유의미한 콘텐츠 생성

기획자를 위한 시니어 유저 대상 콘텐츠 생성 프롬프트

### 프롬프트 작성 팁

- 상황: 시니어 유저의 현재 콘텐츠 요구사항과 배경을 설명합니다.
- 목표: 시니어 유저에게 유의미한 콘텐츠를 생성하는 구체적인 목표를 설정합니다.
- 실행 계획: 콘텐츠 생성의 단계별 계획을 제시합니다.
- 결과물: 원하는 콘텐츠의 형태나 형식을 명확히 합니다.
- 톤과 스타일: 시니어 유저에 맞는 친절하고 이해하기 쉬운 어조를 사용합니다.

### 프롬프트 예시

```markdown
## S: 상황
- [당신]은 [기획자]로, 현재 [시니어 유저를 위한 디지털 교육 프로그램]을 기획 중입니다.
- 시니어 유저들은 [디지털 기기 사용에 대한 낮은 자신감]과 [기술적 장벽]을 경험하고 있습니다.
- 기존의 콘텐츠는 주로 [기초적인 사용법]에 초점을 맞추었으나, 시니어 유저의 [심화된 학습 욕구]를 충족시키지 못하고 있습니다.
- 이번 프로젝트는 시니어 유저의 요구에 맞춘 [유의미하고 실용적인 콘텐츠]를 제공하고자 합니다.

## M: 목표
- [6개월 내에 디지털 교육 프로그램을 완료]하고, [시니어 유저의 디지털 기기 활용 능력 향상]을 목표로 합니다.
- [참여자 만족도 90% 이상]을 달성하며, [프로그램 완료 후의 실용성 평가]를 통해 성공을 측정합니다.
- [콘텐츠의 접근성과 이해도]를 높여 시니어 유저의 학습 효과를 극대화합니다.

## A: 실행 계획
- 중요 사항: 각 단계마다 생성된 결과물에 대해 사용자가 추가/수정 사항을 확인한 후, 다음 단계로 진행합니다

1. 시니어 유저 요구 분석
   - 설문조사 및 인터뷰를 통해 시니어 유저의 필요와 기대를 파악합니다.
   - 기존 프로그램의 피드백을 분석하여 개선점을 도출합니다.

2. 콘텐츠 기획
   - [기초 사용법] 외에 [고급 기능 활용], [안전한 인터넷 사용법], [온라인 소통 방법] 등 다양한 주제를 포함합니다.
   - 각 주제에 맞는 학습 자료와 실습 과제를 설계합니다.

3. 콘텐츠 제작
   - 이해하기 쉬운 언어와 시각적 자료를 활용하여 콘텐츠를 제작합니다.
   - 동영상 강의, PDF 자료, 실습 가이드 등 다양한 형식으로 제공합니다.

4. 테스트 및 피드백
   - 파일럿 프로그램을 운영하여 시니어 유저의 피드백을 수집합니다.
   - 피드백을 바탕으로 콘텐츠를 수정 및 보완합니다.

## R: 결과물
- [디지털 교육 프로그램 커리큘럼]을 작성하며, 다음의 항목을 포함합니다:
  - 각 주차별 학습 목표 및 내용
  - 강의 자료 및 실습 과제
  - 평가 및 피드백 방법
- [동영상 강의 시리즈]를 제작하여, 시니어 유저가 따라하기 쉬운 형식으로 제공합니다.
- [참여자 만족도 설문지]를 통해 프로그램의 효과를 평가할 수 있는 도구를 마련합니다.

## T: 톤과 스타일
- 어조: 친절하고 이해하기 쉬운 어조
- 스타일: 명확하고 간결한 문체, 시각적 자료와 예시를 풍부하게 활용
- 대상 독자: 시니어 유저, 교육 프로그램 기획자

```

---

## 디자이너 - 디자인 및 영상 제작

디자이너를 위한 디자인 및 영상 제작 프롬프트

### 프롬프트 작성 팁

- 상황: 현재 디자인 또는 영상 제작의 배경과 목적을 설명합니다.
- 목표: 디자인 또는 영상 제작의 구체적인 목표를 설정합니다.
- 실행 계획: 디자인 또는 영상 제작을 위한 단계별 계획을 제시합니다.
- 결과물: 원하는 디자인 또는 영상의 형태나 형식을 명확히 합니다.
- 톤과 스타일: 창의적이고 시각적으로 매력적인 어조를 사용합니다.

### 프롬프트 예시

```markdown
## S: 상황
- [당신]은 [디자이너]로, 현재 [신제품 런칭 캠페인]을 위한 디자인 및 영상 제작을 담당하고 있습니다.
- 신제품은 [혁신적인 스마트 기기]로, 이를 효과적으로 홍보하기 위한 시각적 자료가 필요합니다.
- 마케팅 팀과 협력하여 [일관된 브랜드 이미지]를 유지하면서 창의적인 콘텐츠를 제작하고자 합니다.
- 이전 캠페인에서 사용된 디자인은 [고객의 관심을 충분히 끌지 못함]이라는 피드백을 받았습니다.

## M: 목표
- [신제품 런칭을 위한 3개의 주요 디자인 자료]와 [1개의 홍보 영상]을 제작합니다.
- 디자인 자료는 [브랜드 가이드라인에 맞추면서도 창의적인 요소]를 포함하도록 합니다.
- 영상은 [2분 이내]로 제작하여, [소셜 미디어 및 웹사이트에 게시]할 예정입니다.
- [런칭 캠페인 기간 내에 모든 자료를 완성]하는 것이 목표입니다.

## A: 실행 계획
- 중요 사항: 각 단계마다 생성된 결과물에 대해 사용자가 추가/수정 사항을 확인한 후, 다음 단계로 진행합니다

1. 콘셉트 개발
   - 신제품의 핵심 가치를 반영한 디자인 및 영상 컨셉을 개발합니다.
   - 스토리보드를 작성하여 영상의 흐름을 계획합니다.

2. 디자인 제작 기획
   - [제품 이미지, 배너, 포스터] 등의 디자인 요소를 기획합니다.
   - 브랜드 색상, 로고, 타이포그래피 등을 일관되게 적용합니다.

3. 영상 제작 기획
   - 촬영 및 편집을 통해 홍보 영상을 콘티 기획합니다.
   - 음악, 자막, 그래픽 효과 등을 활용하여 영상의 완성도를 높이기 위해 제안하세요

4. 협업 제안서 작성
   - 마케팅 팀과 협력하여 디자인 및 영상 자료를 검토하도록 5page분량의 제안서를 작성하세요

## R: 결과물
- [3개의 디자인 기획서]:
  - 제품 포스터 (A3 사이즈)
  - 소셜 미디어 배너 (1080x1080 픽셀)
  - 웹사이트 배너 (1920x1080 픽셀)
- [1개의 홍보 영상 기획서]:
  - 길이: [2분 이내]
  - 해상도: [1080p]
  - 형식: [MP4]
- [디자인 및 영상 협업 제안서]:
  - 협업 요청 제안

## T: 톤과 스타일
- 어조: 창의적이고 열정적인 어조
- 스타일: 시각적으로 매력적인 요소를 강조, 동적인 디자인과 영상 편집
- 대상 독자: 마케팅 팀, 잠재 고객, 내부 임직원

```

---

## 영상제작 및 행정 - 영상 제작

영상제작 및 행정을 위한 영상 제작 프롬프트

### 프롬프트 작성 팁

- 상황: 현재 영상 제작의 배경과 목적을 설명합니다.
- 목표: 영상 제작의 구체적인 목표를 설정합니다.
- 실행 계획: 영상 제작을 위한 단계별 계획을 제시합니다.
- 결과물: 원하는 영상의 형태나 형식을 명확히 합니다.
- 톤과 스타일: 시청자에게 전달하고자 하는 메시지에 맞는 어조와 스타일을 사용합니다.

### 프롬프트 예시

```markdown
## S: 상황
- [당신]은 [영상제작 및 행정 담당자]로, 현재 [사내 교육용 영상 시리즈]를 제작하고 있습니다.
- 교육 대상은 [신입사원]으로, 회사의 문화와 업무 프로세스를 이해시키는 것이 목적입니다.
- 기존의 교육 자료는 [텍스트 중심]으로, 이해도가 낮고 흥미를 유발하지 못한다는 피드백을 받았습니다.
- 이번 프로젝트는 [시각적이고 흥미로운 영상]을 통해 교육 효과를 높이고자 합니다.

## M: 목표
- [3개의 교육용 영상]을 제작하여 [내부 교육 프로그램]에 활용합니다.
- 각 영상의 길이는 [10분 이내]로 하며, [시청자의 이해도와 흥미 유발]을 목표로 합니다.
- [다음 분기까지 모든 영상 제작 완료]를 목표로 합니다.

## A: 실행 계획
- 중요 사항: 각 단계마다 생성된 결과물에 대해 사용자가 추가/수정 사항을 확인한 후, 다음 단계로 진행합니다

1. 콘텐츠 기획
   - 교육 내용과 주요 메시지를 정의합니다.
   - 각 영상의 스토리보드를 작성하여 전체 흐름을 계획합니다.

2. 대본 작성
   - 교육 내용을 쉽게 이해할 수 있도록 대본을 작성합니다.
   - 시각적 요소와 연계된 설명을 포함시킵니다.

3. 촬영 준비
   - 필요한 장비와 장소를 준비를 제안하세요
   - 출연자 및 촬영 일정을 제안하세요

4. 영상 촬영
   - 촬영을 위한 스토리 보드를 작성하세요
   - 조명, 음향 등 촬영 품질을 위한 체크리스트를 작성하세요

## R: 결과물
- [3개의 교육용 영상 기획안]:
  - 주제별로 나누어진 영상 (예: 회사 문화, 업무 프로세스, 팀 협업)
  - 해상도: [1080p]
  - 형식: [MP4]
- [스토리보드 및 대본]:
  - 각 영상의 스토리보드와 대본

## T: 톤과 스타일
- 어조: 친근하고 교육적인 어조
- 스타일: 시각적 요소를 강조한 동적 스타일, 명확한 설명과 예시 사용
- 대상 독자: 신입사원, 교육 담당자
```

---

## 프로그램 운영 보조 - 고객 서비스 및 문의 응대

프로그램 운영 보조를 위한 고객 서비스 및 문의 응대 프롬프트

### 프롬프트 작성 팁

- 상황: 고객 서비스 상황과 현재 문의 유형을 설명합니다.
- 목표: 효과적인 고객 서비스 및 문의 응대의 구체적인 목표를 설정합니다.
- 실행 계획: 고객 응대를 위한 단계별 계획을 제시합니다.
- 결과물: 원하는 응대 방식이나 자료의 형태를 명확히 합니다.
- 톤과 스타일: 친절하고 신속한 어조를 사용합니다.

### 프롬프트 예시

```markdown
## S: 상황
- [당신]은 [교육 프로그램 운영 보조]로, 현재 [온라인 교육 플랫폼]에서 고객의 문의를 받고 있습니다.
- 주로 [회원 가입, 결제 문제, 강의 접근성] 관련 문의가 많습니다.
- 최근 사용자 증가로 인해 문의량이 급격히 증가하였으며, 신속하고 정확한 응대가 필요합니다.
- 기존의 FAQ는 일부 문의에 대한 충분한 답변을 제공하지 못하고 있습니다.

## M: 목표
- [고객 문의에 대한 응답 시간을 평균 24시간 이내]로 단축합니다.
- [문의 해결률 95% 이상]을 달성하여 고객 만족도를 높입니다.
- [FAQ]를 업데이트하여 [반복적인 문의 감소]를 목표로 합니다.

## A: 실행 계획
- 중요 사항: 각 단계마다 생성된 결과물에 대해 사용자가 추가/수정 사항을 확인한 후, 다음 단계로 진행합니다

1. 문의 유형 분석
   - 최근 3개월간의 고객 문의 데이터를 분석하여 주요 문의 유형을 파악합니다.
   - 빈번한 문의 사항을 중심으로 FAQ를 재구성합니다.

2. 응대 매뉴얼 작성
   - 각 문의 유형별로 표준 응대 절차를 작성합니다.
   - 응답 템플릿을 마련하여 일관된 응대를 유지합니다.

3. 자동화 도구 도입
   - 챗봇을 활용하여 기본적인 문의에 대한 자동 시나리오 응답을 설계하세요
   - AI 기반의 고객 지원 도구를 도입하여 효율성을 높이기 위한 제안을 해주세요

4. 팀 교육
   - 고객 응대 담당자들에게 새로운 매뉴얼과 도구 사용법을 교육하기 위한 자료를 작성하세요
   - 정기적인 교육을 통해 응대 품질을 유지할 수 있도록 설계하세요.

## R: 결과물
- [업데이트된 FAQ]:
  - 주요 문의 유형에 대한 상세한 답변 포함
  - 검색 기능 강화하여 사용자가 쉽게 찾을 수 있도록 함
- [응대 매뉴얼]:
  - 문의 유형별 응대 절차와 템플릿 포함
  - 매뉴얼을 노션 페이지 형식으로 배포를 위한 마크다운 형식
- [챗봇 응답 스크립트]:
  - 자주 묻는 질문에 대한 자동 응답 스크립트 작성

## T: 톤과 스타일
- 어조: 친절하고 신속한 어조
- 스타일: 명확하고 간결한 문장, 고객 중심의 응대 방식
- 대상 독자: 고객, 고객 지원 팀원
```
