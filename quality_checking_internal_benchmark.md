# Internal Benchmark Instruction Guide

## Web link
[Naturalbench_Video_Viewer](http://xdrzbdsyyz.a.pinggy.link)

## 1. User Registration
- **Username**: Please use your real English name when registering.
- **Role Selection**: Select "Annotator" as your role during registration.

## 2. Navigation
- After logging in, go to the main interface.
- Click on **"Internal Benchmark"** to access the review system.

## 3. Content Review and Standards

### 3.1 Review Task
- **Daily Requirement**: Review 20 randomly selected samples each day.
- **Feedback**: Submit your findings and feedback to **Baiqi**.

### 3.2 Content to Review
For each video pair, please review the following components:
- **Video**
- **Video captions**
- **Multiple Choice Questions (MCQ)**
- **Yes/No questions**

### 3.3 Review Standards

When checking each sample, evaluate the following criteria:

**a) Language Quality**
- Check whether captions and questions are expressed naturally and fluently.
- Look for grammatical errors or awkward phrasing.
- Ensure consistency between the question logic and the provided options or expected answers.

**Example of Logical Inconsistency:**  
The option *"The launched object did not fall off the table"* is logically inconsistent with the following question scenario:

> **Question:** "What happened once the person removed an object from the tabletop?"  
> **Options:** ['No object was removed from the tabletop.', 'The launched object did not fall off the table.']  
> **Answer:** "The launched object did not fall off the table."

❌ This option does not logically address the action described in the question (removing an object). The answer does not logically follow from the question, which focuses on the consequences of removing an object. The selected option instead describes the state of a different object ("the launched object"), making it an illogical response.

**b) Video Quality**
- Check if the video is clear and understandable.
- Ensure that the video contains no sexual, violent, or political content.

**c) Video-Caption Alignment**
- Ensure clarity in references within captions: If there are multiple similar events or objects in the video, captions should make references clear.
- Check that captions accurately align with the video content. Common mistakes include:
    1. Captions contain information not visible in the video, such as assumptions or inferences.
    2. Captions are confusing—check due to vague or inaccurate descriptions of objects, actions, or attributes.
- Within the same sample (which includes two videos and their captions), each caption should only match its video and should not match the other video.

**d) Question/Option/Answer Quality**
- Each sample (2 videos, multiple MCQs, and Yes/No questions) should have every question answered differently for the two videos.
- MCQ options should not have similar meanings or inclusion relationships. (If there is only one correct answer, these types of errors can lead to unreliable evaluation, as LLMs can eliminate options based on textual cues.)
- A question is only considered reasonable if both the question and its options/answers make sense for both videos.
- To judge if a question is reasonable for a video:
    - The question must be related to the video content.
    - References in the question/option/answer should be clear (especially if there are multiple similar objects or events).
    - Each question should have **one and only one correct option** for each video; all other options should be clearly wrong. Typical errors include:
        1. The video does not provide enough information to answer the question (for both Yes/No and MCQ types).
        2. There is ambiguity due to vague or inaccurate descriptions, making it hard to judge (for both Yes/No and MCQ).
        3. Multiple MCQ options fit the video content:
            - More than one distinct option could be correct.
            - Options have similar meanings or inclusion relationships (e.g., one option is a subset of/has a similar meaning to another), and all of them fit the question/video.
        4. No clearly correct option is available for the MCQ.
        5. There is one correct option, but the other options cannot be clearly identified as incorrect.

**e) Question Difficulty**
- Check if questions can be reasonably answered based on the video content.
- Identify questions that may be too difficult or impossible to answer correctly.


## 4. Add Correction Suggestions

### 4.1 How to Use the "Add Suggestion" Feature

**For Captions:**
- Find the caption text you want to modify.
- Click the **"Add Suggestion"** button next to the caption.
- A suggestion form will appear where you can enter your corrections.
- Click **"Save"** to submit your suggestion.
- Click **"Delete"** to remove your suggestion if needed.

**For Questions:**
- Find the MCQ or Yes/No question you want to improve.
- Click the **"Add Suggestion"** button for that question.
- Fill out the suggestion form with your recommended changes.
- Click **"Save"** to submit your suggestion.
- Click **"Delete"** to remove the suggestion if necessary.

### 4.2 What to Fill In

When adding suggestions, please provide the following information:
**a) Suggested Caption/Question/Option/Answer**
- Write your improved version of the caption, question, option, or answer.

**b) Reason for Modification**
- Give a brief explanation of why you are suggesting this change.
- Keep your explanation concise but informative.

## 5. Mark "Needs Revision"
- After identifying a problem and adding suggestions, please check the **"Needs Revision"** box for that video pair.

---

**Note**: Your thorough reviews and constructive suggestions are essential for improving the quality of our benchmark dataset. Please provide detailed feedback to support ongoing improvements.
