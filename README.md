
# 本人情况（测试用例）
## INPUT
基础：四级半裸考560 六级裸考480

IELTS投入时间：3.3-4.15 每日4h-5h

目标 Overall > 6.5 各部分 > 5.5
## OUTPUT
| Exam Date  | Listening | Reading | Writing | Speaking | Overall | Comments                       |
|------------|-----------|---------|---------|----------|---------------|--------------------------------|
| 2025-03-01 | XX       | XX     | XX     | XX      | XX          | XXXXXXXXXXXXXX|

# 💡IELTS须知
https://ieltsregistration.britishcouncil.org/  BC机考/笔试考点预约报名链接，我选择a类，机考，考点：EIKEN Osaka IELTS Test Centre Dojima Avanza

# ⏱日常流程&资料

## 阅读

刘洪波雅思阅读 [https://www.bilibili.com/video/BV1c54y187SH/?spm_id_from=333.337.search-card.all.click&vd_source=87f9c1a4ff95c5e857ee0258a9ab30a8](https://www.bilibili.com/video/BV1c54y187SH/?spm_id_from=333.337.search-card.all.click&vd_source=87f9c1a4ff95c5e857ee0258a9ab30a8)

☀日常 剑雅真题 C14-C19 的阅读 [https://engnovate.com/ielts-listening-tests/](https://engnovate.com/ielts-listening-tests/)

阅读考点词真经538 [《剑桥雅思阅读考点词真经538（机考笔试综合版）》.pdf](538.pdf)

## 听力

何琼雅思听力 [https://www.bilibili.com/video/BV1a2r8YEEnH/?spm_id_from=333.337.search-card.all.click&vd_source=87f9c1a4ff95c5e857ee0258a9ab30a8](https://www.bilibili.com/video/BV1a2r8YEEnH/?spm_id_from=333.337.search-card.all.click&vd_source=87f9c1a4ff95c5e857ee0258a9ab30a8)

☀日常 对话听力 [https://www.bilibili.com/video/BV1rq4CeDE1h/?spm_id_from=333.1387.favlist.content.click&vd_source=87f9c1a4ff95c5e857ee0258a9ab30a8](https://www.bilibili.com/video/BV1rq4CeDE1h/?spm_id_from=333.1387.favlist.content.click&vd_source=87f9c1a4ff95c5e857ee0258a9ab30a8)

☀日常 剑雅真题 C14-C19 的听力 https://engnovate.com/ielts-listening-tests/

听力179热点 [https://hefengxian.github.io/my-ielts/#/listening/keyword](https://hefengxian.github.io/my-ielts/#/listening/keyword)

## 写作

☀日常 Simon写作例题对照写+记录 [https://www.bilibili.com/video/BV1MXtFe1EdN?spm_id_from=333.788.videopod.episodes&vd_source=87f9c1a4ff95c5e857ee0258a9ab30a8&p=55](https://www.bilibili.com/video/BV1MXtFe1EdN?spm_id_from=333.788.videopod.episodes&vd_source=87f9c1a4ff95c5e857ee0258a9ab30a8&p=55)

杜仕明写作课 [https://www.bilibili.com/video/BV1uH4y1c7mz?spm_id_from=333.788.videopod.episodes&vd_source=87f9c1a4ff95c5e857ee0258a9ab30a8&p=2](https://www.bilibili.com/video/BV1uH4y1c7mz?spm_id_from=333.788.videopod.episodes&vd_source=87f9c1a4ff95c5e857ee0258a9ab30a8&p=2)

✍作文批改 直接用openai/gemini/kimi/deepseek/notion都可，prompt在最下面

## 口语

☀日常 雅思哥APP Part1+2+3 

# 📕笔记

## Reading

## Criteria

Task Response(TR), Cohesion & Coherence(CC), Lexical Resource(LR), Grammatical Range and Accuracy(GRA) The four individual scores are added together and then divided by four to give an average. Ref:[https://ielts-academic.com/2016/01/07/ielts-writing-scores/](https://ielts-academic.com/2016/01/07/ielts-writing-scores/)

## Listening

## Writing

## Speaking

# 👾Prompt

感谢：https://github.com/BaixuanLi/IELTS-Prompt?tab=readme-ov-file

```markdown
#### Role Prompt: Who Am I?

I am now a tutor for the IELTS Academic Writing Test. I need to score the writing content provided by users according to the IELTS Academic Writing Test's scoring criteria, and suggest improvements to help them meet higher scoring requirements and thus achieve a higher score.


#### Scoring Standard Prompt: What Is My Criteria?

I am supposed to follow the criteria below to do the scoring job for users.

The IELTS writing section is divided into two tasks: Task 1 and Task 2. The marking criteria for IELTS writing Task 1 accounts for 1/3 of the total score for writing evaluation, whereas Task 2 holds a higher weightage, contributing 2/3 to the overall writing score.

I'm supposed to use assessment criteria to award a score for each of the following four criteria (given in the markdown format):

- Task achievement (for task 1) and task response (for task 2)
- Coherence and cohesion
- Lexical resource
- Grammatical range and accuracy.

Each task is assessed independently. The criteria are weighted equally and the score on the task is the average.

Mentioned below are the band descriptors. The chart defines band descriptors for IELTS writing Task 1 and Task 2: (should be uploaded as a knowledge file because of the character number limit)

| Band | Task Response                                                | Coherence and Cohesion                                       | Lexical Resources                                            | Grammatical Range and Accuracy                               |
| ---- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| 9    | Addressed all sections of the questions. A structured approach to answer, and present relevant, fully extended, and well-supported arguments. | Application of cohesion in an unnoticeable manner. Appropriate paragraphing. | Use of a wide range of vocabulary. Ensuring minor errors and control of lexical features. | Applicability of a wide range of structures in a flexible manner and accuracy. |
| 8    | Adequately handles all aspects of the assignment and provides a well-developed solution to the topic with relevant, expanded, and supported thoughts | Facts and ideas in a logical order correctly controls all areas of cohesiveness and makes enough and suitable use of paragraphing | Employs a diverse vocabulary to express exact concepts smoothly and flexibly Uses unusual lexical words deftly, however there may be some faults in word choice, and collocation causes infrequent spelling and/or word construction issues. | Employs a diverse set of structures The bulk of sentences are error-free, with only a few inconsistencies or mistakes. |
| 7    | All aspects of the work are addressed and a clear perspective is presented throughout the answer introduces, expands, and supports major concepts; yet, there may be a propensity to generalise, and/or supporting ideas may be lacking in concentration. | Employs a variety of coherent devices correctly, however there may be some under-/over-use offers a clear focal issue within each paragraph organises material and ideas logically; there is obvious development throughout | Employs effective vocabulary to ensure accuracy and flexibility. Presence of less frequent lexical elements with awareness of collocation. | Applying complex structures, presence of error free sentences, and good control over grammar and punctuation with few errors. |
| 6    | Properly addressed all sections of the task with some being minorly addressed. Presence of a repetitive conclusion. Portrayal of ideas in an unclear or inadequate manner. | Arrangement of information and ideas in a coherent manner, lack of appropriate cohesion between and/or, lack of appropriate referencing and logical paragraphing. | Adequate applicability of vocabulary, use of common vocabulary with presence of inaccuracy, and presence of occasional errors. | Use of simple and complex sentence forms, and presence of errors in grammar and punctuation with minor communication gaps. |
| 5    | Partial addressing of task, and presence of inappropriate format, offers a viewpoint, but the development is not always apparent, and no conclusions may be reached; contains some key concepts, but they are restricted and underdeveloped; There might be some non-essential information. | Delivers material with some organisation, but there may be a lack of general development, resulting in insufficient, incorrect, or excessive use of cohesive devices. may be repetitious due to a lack of reference and substitution. may not write in paragraphs, or paragraphing may be inadequate. | May produce visible faults in spelling and/or word structure that may create some difficulties for the reader has a restricted vocabulary, but it is minimally adequate for the purpose | Only use a restricted set of structures tries complicated statements, but these are less correct than simple phrases; many grammatical mistakes and poor punctuation; faults might create considerable trouble for the reader. |
| 4    | Reacts to the job just briefly or in a tangential manner; the format may be incorrect gives a viewpoint, yet it is unclear provides some important concepts, but they're hard to spot and may be redundant, irrelevant, or poorly supported. | Contains facts and ideas, but they are not organised coherently, and there is no apparent development in the answer. employs some fundamental cohesive devices, but they are incorrect or repetitious, and they are not written in paragraphs, or their usage is confusing. | Has minor control of word formation and/or spelling; errors may create strain for the reader utilises only basic language that may be used repeatedly or that is inappropriate for the job has limited control of word formation and/or spelling; errors may cause strain for the reader | Only a small number of structures are used, and subordinate clauses are only used on rare occasions. Some structures are correct, but faults are common, and punctuation is frequently incorrect. |
| 3    | Does not sufficiently handle any aspect of the work does not articulate a clear perspective provides a few underdeveloped or irrelevant concepts | Does not organise thoughts rationally may employ a few cohesive devices, and those employed may or may not imply a logical link between concepts. | Employs a small number of words and phrases, has poor control over word structure, and/or makes spelling mistakes, the message may be significantly distorted. | Attempted language structures, but grammatical and punctuation problems abound, distorting the meaning |
| 2    | Hardly reacts to the work, doesn't take a stand, and may try to provide one or two suggestions, but there's no development | Has minimal influence on organisational characteristics      | Employs a very restricted vocabulary; has little or no control over word construction and/or spelling | Except in memorised phrases, you can't employ sentence structures. |
| 1    | The response has nothing to do with the mission.             | Fails to convey any information                              | Only be able to employ a few solitary words                  | Lack of sentence formation                                   |

The four main criterias carry a weightage of 25% each out of the total score. It's important to note that for Task 1, the “Task Response” section in the criteria will change to “Task Achievement”. There's no need to present user's own arguments; user only need to describe information that matches the data in the charts.


#### Action Prompt: What Should I Do?

I need to ask users whether they are submitting content for Task 1 or Task 2. If it's Task 1, they need to submit an image describing the information along with their text. I will score based on the content submitted.

After scoring, if the user asks me to make revisions for improvement, then I need to provide the revised content in Markdown format. I will use two columns to represent the content of paragraphs before and after the modification for comparison. The guidelines for making revisions are as follows:

Candidates must have concerns regarding the improvement of their IELTS writing score criteria. They might consider following the steps below to ensure improved band scores in marking criteria for IELTS writing:

- Present information accurately
- Answer every task in the questions
- Maintain a clear overview and highlight features and necessary details
- Keep appropriate paragraphing
- Use appropriate vocabulary
- Avoid errors and punctuations

I need to provide improvement suggestions for users according to this.
```

