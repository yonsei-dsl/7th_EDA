# MBTI 데이터

MBTI와 관련된 총 2종류의 3가지 파일로 이루어져 있습니다.
## 1. MBTI별 "PersonalityCafe forum"이라는 카페에 작성한 글(text) <== mbti_text.csv<br>
<strong> mbti_text.csv </strong><br>
Content : <br>
This dataset contains over 8600 rows of data, on each row is a person’s:<br>

- Type (This persons 4 letter MBTI code/type)<br>
- A section of each of the last 50 things they have posted (Each entry separated by "|||" (3 pipe characters))
---
## 2. KPMI(MBTI mod) Test <= kpmi_data.csv, kpmi_questionnaire_schema.json<br>
The KPMI technique is a modified version of the MBTI — introspective self-report questionnaire indicating differing psychological preferences in how people perceive the world and makes decisions (Wikipedia). You can read more about the changes regarding the original methodology here (in Russian).<br>
Content : <br>
This dataset contains 21,846 questionnaire answers collected online by KeyHabits.
Each record contains:
- answers to 142 questionnaire questions;
- raw values of scales;
- computed psychotype;
- answer to the question "I'm satisfied with my job".
<br>
<br>
<strong>kpmi_data.csv</strong> <br>
Main datafile with answers to questionnaire questions.

Fileds:

- jobtitle: employee position;
- jobfield: employee area;
- q1-q142: answers on questions, 0 — if the first answer is selected, 1 — for the second answer;
- scale_[e|i|s|n|t|f|j|p]: calculated raw value of the psychotype scale;
- psychotype: psychotype letter designation based on scale values;
- satisfied: the answer to the question "I'm satisfied with my job" (1 for "yes" and 0 for "no"). <br>

<strong>kpmi_questionnaire_schema.json</strong>
<br>
JSON array with position (starts with 1) and text of each question in the questionnaire. Each question has a subarray of answers with position (starts with 1) and answers text. The texts are presented in Russian and English.

kpmi이라는 mbti랑 비슷한 검사 질문표(json 형식으로 제공) 그리고 사람별로 직업과 kpmi 질문 정답, mbti scale, 

출처 : <br>
https://www.kaggle.com/datasnaek/mbti-type <br>
https://www.kaggle.com/pmenshih/kpmi-mbti-mod-test?select=questionnaire_schema.json
