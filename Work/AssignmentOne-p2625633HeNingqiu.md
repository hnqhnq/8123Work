# Assignment One: Developing a Multi-Database Search Strategy Based on PICOS

**Student Name:** He Ningqiu  
**Student ID:** p2625633

## 1. Assignment Title

**The Effectiveness of Artificial Intelligence-Powered Conversational Agents in Supporting Self-Management and Improving Glycemic Control Among Adults With Type 2 Diabetes: A Multi-Database Search for Randomized Controlled Trials**

## 2. Background and Aim

The management of type 2 diabetes involves blood glucose monitoring, medication use, diet, and physical activity. Nurses commonly participate in patient education, behavioral support, and follow-up care. Conversational artificial intelligence tools, such as chatbots, virtual health assistants, and voice assistants, can provide patients with education, reminders, and feedback in their daily lives. However, their effects on diabetes self-management and glycemic control still need to be evaluated through clinical research.

This report uses the PICOS framework to divide the research question into searchable concepts. Sensitive and specific search strategies were developed for PubMed, the Cochrane Library, China National Knowledge Infrastructure (CNKI), CINAHL, and the Web of Science Core Collection. The report documents the search terms, database-specific adaptations, limits, actual results, and access restrictions.

## 3. Clinical Nursing Question

Among adults with type 2 diabetes, are artificial intelligence-powered conversational agents more effective than usual care, standard diabetes education, or no conversational AI intervention in improving self-management and glycemic control?

## 4. PICOS Framework

| PICOS element | Definition | Inclusion criteria |
|---|---|---|
| P: Population | Adults with type 2 diabetes | Adults, as defined by the individual study, who have been diagnosed with type 2 diabetes. Studies of mixed populations must report extractable data for adults with type 2 diabetes. |
| I: Intervention | Artificial intelligence-powered conversational agents | Chatbots, virtual health assistants, embodied conversational agents, voice assistants, and other AI systems capable of automated dialogue with patients. |
| C: Comparison | Usual care or a non-conversational intervention | Usual care, standard diabetes education, a waiting-list control, no use of an AI conversational tool, or another non-conversational digital health intervention. |
| O: Outcomes | Self-management and glycemic control | Blood glucose monitoring, medication use, diet and physical activity management, HbA1c, blood glucose levels, medication adherence, and self-efficacy. |
| S: Study design | Randomized controlled trials | Published randomized controlled trials. Protocol-only publications without trial results are not considered final evidence of effectiveness. |

The comparison concept was not included in the sensitive search strategy because descriptions of control conditions vary considerably across studies and could lead to relevant records being missed.

## 5. Search Concepts and Terms

| Concept | Controlled vocabulary | English free-text terms | Chinese free-text terms |
|---|---|---|---|
| Type 2 diabetes | Diabetes Mellitus, Type 2 | type 2 diabetes; type 2 diabetes mellitus; type II diabetes; type II diabetes mellitus; T2DM; NIDDM | 2型糖尿病; 二型糖尿病; Ⅱ型糖尿病; II型糖尿病; T2DM; NIDDM; 非胰岛素依赖型糖尿病 |
| AI conversational agents | Artificial Intelligence; Natural Language Processing; Intelligent Systems; Generative Artificial Intelligence | chatbot*; conversational agent*; conversational AI; virtual health assistant*; virtual assistant*; voice assistant*; embodied conversational agent*; dialogue system*; dialog system*; voice-based AI; ChatGPT | 人工智能; 对话式人工智能; 对话代理; 会话代理; 对话系统; 聊天机器人; 虚拟健康助手; 语音助手; 人机对话; ChatGPT |
| Self-management and glycemic control | Self-Management; Self Care; Blood Glucose; Glycated Hemoglobin | self-manag*; self care; glycemic control; glycaemic control; blood glucose; HbA1c; A1c | 自我管理; 自我护理; 自我照护; 糖尿病教育; 健康教育; 行为支持; 血糖管理; 血糖控制; 血糖监测; 糖化血红蛋白; HbA1c; 用药依从性 |
| Randomized trials | Randomized Controlled Trial; Controlled Clinical Trial | random*; trial | 随机对照试验; 随机对照研究; 随机分组; 随机; 对照试验; 临床试验; 干预研究; RCT |

The sensitive search combined only the population and intervention concepts. The specific search also included the self-management or glycemic control outcomes and randomized trial terms. The sensitive strategy was intended to maximize recall, whereas the specific strategy was intended to reduce irrelevant results.

## 6. Database Search Strategies and Results

The searches and database access attempts were conducted on **16 October 2026**. Unless otherwise stated, no publication date or language limits were applied.

### 6.1 PubMed

**Database and platform:** PubMed, U.S. National Library of Medicine (NLM)  
**Limits:** No limits were applied to the sensitive search. The final specific search was limited to Humans and Adult: 19+ years. No publication date or language limits were applied.

#### 6.1.1 Sensitive Search

The following sets were created in the History section of Advanced Search:

```text
#1 "Diabetes Mellitus, Type 2"[Mesh]

#2 "type 2 diabetes"[tiab] OR "type 2 diabetes mellitus"[tiab]
   OR "type II diabetes"[tiab] OR "type II diabetes mellitus"[tiab]
   OR T2DM[tiab] OR NIDDM[tiab]

#3 #1 OR #2

#4 "Artificial Intelligence"[Mesh]
#5 "Natural Language Processing"[Mesh]
#6 "Intelligent Systems"[Mesh]
#7 "Generative Artificial Intelligence"[Mesh]

#8 chatbot*[tiab] OR "conversational agent"[tiab]
   OR "conversational agents"[tiab] OR "conversational AI"[tiab]
   OR "virtual health assistant"[tiab] OR "virtual health assistants"[tiab]
   OR "virtual assistant"[tiab] OR "virtual assistants"[tiab]
   OR "voice assistant"[tiab] OR "voice assistants"[tiab]
   OR "embodied conversational agent"[tiab]
   OR "embodied conversational agents"[tiab]
   OR "dialogue system"[tiab] OR "dialogue systems"[tiab]
   OR "dialog system"[tiab] OR "dialog systems"[tiab]
   OR "voice-based AI"[tiab]

#9 #4 OR #5 OR #6 OR #7 OR #8

#10 #3 AND #9
```

Set #10 was the sensitive search and returned **1,446 records**.

![PubMed sensitive search history and results](image/AssignmentOne.draft.zh-CN/1792139452149.png)

*Figure 1. PubMed sensitive search history; set #10 returned 1,446 records.*

#### 6.1.2 Specific Search

The outcome and randomized trial sets were then added to the same History:

```text
#11 "Self-Management"[Mesh] OR "Self Care"[Mesh]
    OR "Blood Glucose"[Mesh] OR "Glycated Hemoglobin"[Mesh]

#12 self-manag*[tiab] OR self-care[tiab] OR "self care"[tiab]
    OR "glycemic control"[tiab] OR "glycaemic control"[tiab]
    OR "blood glucose"[tiab] OR HbA1c[tiab] OR A1c[tiab]

#13 #11 OR #12

#14 "randomized controlled trial"[pt] OR "controlled clinical trial"[pt]

#15 random*[tiab] OR trial[tiab]

#16 #14 OR #15

#17 #3 AND #8 AND #13 AND #16

#18 #17 AND humans[Mesh] AND adult[Mesh]
```

Set #18 was the specific search and returned **7 records**.

![PubMed specific search history and results](image/AssignmentOne.draft.zh-CN/1792140263173.png)

*Figure 2. PubMed specific search history; set #18 returned 7 records.*

### 6.2 Cochrane Library

**Database:** Cochrane Central Register of Controlled Trials (CENTRAL)  
**Platform:** Cochrane Library  
**Limits:** Content Type was limited to Trials. No publication date or language limits were applied.

The following sets were created in the Search Manager under Advanced Search. MeSH terms were searched using Exact Term Match with Explode all trees. Free-text terms were limited to the Title, Abstract, and Keyword fields.

```text
#1 MeSH descriptor: [Diabetes Mellitus, Type 2] explode all trees

#2 ("type 2 diabetes" OR "type 2 diabetes mellitus" OR "type II diabetes"
   OR "type II diabetes mellitus" OR T2DM OR NIDDM):ti,ab,kw

#3 #1 OR #2

#4 MeSH descriptor: [Artificial Intelligence] explode all trees

#5 (chatbot* OR "conversational agent" OR "conversational agents"
   OR "conversational AI" OR "virtual health assistant"
   OR "virtual health assistants" OR "virtual assistant" OR "virtual assistants"
   OR "voice assistant" OR "voice assistants"
   OR "embodied conversational agent" OR "embodied conversational agents"
   OR "dialogue system" OR "dialogue systems" OR "dialog system"
   OR "dialog systems" OR "voice-based AI"):ti,ab,kw

#6 #4 OR #5

#7 MeSH descriptor: [Self-Management] explode all trees
#8 MeSH descriptor: [Self Care] explode all trees
#9 MeSH descriptor: [Blood Glucose] explode all trees
#10 MeSH descriptor: [Glycated Hemoglobin] explode all trees

#11 (self-manag* OR "self care" OR "glycemic control" OR "glycaemic control"
    OR "blood glucose" OR HbA1c OR A1c):ti,ab,kw

#12 #7 OR #8 OR #9 OR #10 OR #11

#13 (random* OR trial):ti,ab,kw
```

![Cochrane Search Manager search history](image/AssignmentOne.draft.zh-CN/1792142128862.png)

*Figure 3. Sets #1-#13 in the Cochrane Search Manager.*

#### 6.2.1 Sensitive Search

```text
#3 AND #6
```

The search returned **78 Trials**.

![Cochrane sensitive search results](image/AssignmentOne.draft.zh-CN/1792142161641.png)

*Figure 4. The Cochrane CENTRAL sensitive search returned 78 Trials.*

#### 6.2.2 Specific Search

```text
#3 AND #5 AND #12 AND #13
```

The search returned **20 Trials**.

![Cochrane specific search results](image/AssignmentOne.draft.zh-CN/1792142200570.png)

*Figure 5. The Cochrane CENTRAL specific search returned 20 Trials.*

### 6.3 China National Knowledge Infrastructure (CNKI)

**Database and platform:** CNKI, Chinese-language literature  
**Search field:** Subject  
**Match type:** Exact  
**Limits:** No publication date limit was applied. OA Publication, Online First, Enhanced Publication, and Funded Literature were not selected. Chinese-English Expansion and Synonym Expansion were not enabled.

Within each concept group, synonyms were joined using the half-width plus sign (`+`). Separate concept groups were joined using `AND`. Chinese-language literature was used as the main CNKI result set, while the foreign-language search was retained as a supplementary record.

#### 6.3.1 Sensitive Search

First row, Subject:

```text
2型糖尿病 + 二型糖尿病 + Ⅱ型糖尿病 + II型糖尿病 + T2DM + NIDDM + 非胰岛素依赖型糖尿病
```

Second row, AND Subject:

```text
人工智能 + 对话式人工智能 + 对话代理 + 对话系统 + 聊天机器人 + 虚拟健康助手 + 语音助手 + 人机对话 + ChatGPT + chatbot + 'conversational agent'
```

The search of the Chinese-language collection returned **142 records**.

![CNKI Chinese-language sensitive search results](<image/Assignment One.draft.zh-CN/1792155727287.png>)

*Figure 6. The CNKI Chinese-language sensitive search returned 142 records.*

The same strategy returned **155 records** in the foreign-language collection. These results were recorded as supplementary information and were not combined with the Chinese-language results.

![CNKI foreign-language sensitive search results](<image/Assignment One.draft.zh-CN/1792155947700.png>)

*Figure 7. The supplementary CNKI foreign-language search returned 155 records.*

#### 6.3.2 Specific Search

First row, Subject:

```text
2型糖尿病 + 二型糖尿病 + Ⅱ型糖尿病 + II型糖尿病 + T2DM + NIDDM + 非胰岛素依赖型糖尿病
```

Second row, AND Subject:

```text
对话式人工智能 + 对话代理 + 会话代理 + 对话系统 + 聊天机器人 + 虚拟健康助手 + 语音助手 + 人机对话 + ChatGPT + chatbot + 'conversational agent'
```

Third row, AND Subject:

```text
自我管理 + 自我护理 + 自我照护 + 糖尿病教育 + 健康教育 + 行为支持 + 血糖管理 + 血糖控制 + 血糖监测 + 糖化血红蛋白 + HbA1c + 用药依从性 + 服药依从性
```

Fourth row, AND Subject:

```text
随机对照试验 + 随机对照研究 + 随机分组 + 随机 + 对照试验 + 临床试验 + 干预研究 + RCT
```

The search of the Chinese-language collection returned **1 record**.

![CNKI Chinese-language specific search results](<image/Assignment One.draft.zh-CN/1792156266901.png>)

*Figure 8. The CNKI Chinese-language specific search returned 1 record.*

The foreign-language search also returned **1 record**. The screenshot shows that Chinese-English Expansion was enabled during this search, making its settings different from those used for the Chinese-language search. It was therefore retained only as supplementary material and was not included in the main comparison.

![CNKI foreign-language specific search results](<image/Assignment One.draft.zh-CN/1792156289143.png>)

*Figure 9. The supplementary CNKI foreign-language specific search returned 1 record.*

### 6.4 CINAHL

**Database and platform:** CINAHL via EBSCOhost; the subscribed CINAHL edition could not be confirmed  
**Access status:** When access was attempted through the institution login page, the system could not identify the account combination. The CINAHL search interface could therefore not be opened. The planned strategy and the screenshot of the failed institution login are retained to document why result counts could not be obtained.

The following sets were intended for the Search History in Advanced Search:

```text
S1 (MH "Diabetes Mellitus, Type 2+")
   OR TI ("type 2 diabetes" OR "type 2 diabetes mellitus" OR "type II diabetes"
          OR "type II diabetes mellitus" OR T2DM OR NIDDM)
   OR AB ("type 2 diabetes" OR "type 2 diabetes mellitus" OR "type II diabetes"
          OR "type II diabetes mellitus" OR T2DM OR NIDDM)

S2 (MH "Artificial Intelligence+") OR (MH "Natural Language Processing")
   OR TI (chatbot* OR "conversational agent*" OR "conversational AI"
          OR "virtual health assistant*" OR "virtual assistant*" OR "voice assistant*"
          OR "embodied conversational agent*" OR "dialogue system*"
          OR "dialog system*" OR "voice-based AI")
   OR AB (chatbot* OR "conversational agent*" OR "conversational AI"
          OR "virtual health assistant*" OR "virtual assistant*" OR "voice assistant*"
          OR "embodied conversational agent*" OR "dialogue system*"
          OR "dialog system*" OR "voice-based AI")

S3 TI (chatbot* OR "conversational agent*" OR "conversational AI"
       OR "virtual health assistant*" OR "virtual assistant*" OR "voice assistant*"
       OR "embodied conversational agent*" OR "dialogue system*"
       OR "dialog system*" OR "voice-based AI")
   OR AB (chatbot* OR "conversational agent*" OR "conversational AI"
       OR "virtual health assistant*" OR "virtual assistant*" OR "voice assistant*"
       OR "embodied conversational agent*" OR "dialogue system*"
       OR "dialog system*" OR "voice-based AI")

S4 TI (self-manag* OR "self care" OR "glycemic control" OR "glycaemic control"
       OR "blood glucose" OR HbA1c OR A1c)
   OR AB (self-manag* OR "self care" OR "glycemic control" OR "glycaemic control"
       OR "blood glucose" OR HbA1c OR A1c)

S5 (PT "Randomized Controlled Trial") OR TI (random* OR trial)
   OR AB (random* OR trial)
```

The planned sensitive combination was `S1 AND S2`, and the planned specific combination was `S1 AND S3 AND S4 AND S5`. Because the database could not be opened, the subject headings and field codes could not be verified against the institution's subscribed version. No CINAHL result counts are therefore reported.

![CINAHL institution access failure](<image/Assignment One.draft.zh-CN/1792158482493.png>)

*Figure 10. Failed CINAHL institution login. The screenshot documents why the database search could not be completed.*

### 6.5 Web of Science Core Collection

**Database:** Web of Science Core Collection  
**Platform:** Web of Science, Clarivate  
**Access status:** After signing in with a personal account, the page displayed only Name Search. It did not provide the Core Collection database selector, Topic field, or Advanced Search query box. The planned strategies and the screenshot of the available page are retained to document why Document Search result counts could not be obtained.

The planned sensitive search was:

```text
TS=("type 2 diabetes" OR "type 2 diabetes mellitus" OR "type II diabetes"
OR "type II diabetes mellitus" OR T2DM OR NIDDM)
AND
TS=("artificial intelligence" OR chatbot* OR "conversational agent*"
OR "conversational AI" OR "virtual health assistant*" OR "virtual assistant*"
OR "voice assistant*" OR "embodied conversational agent*"
OR "dialogue system*" OR "dialog system*" OR "voice-based AI"
OR ChatGPT OR "large language model*")
```

The planned specific search was:

```text
TS=("type 2 diabetes" OR "type 2 diabetes mellitus" OR "type II diabetes"
OR "type II diabetes mellitus" OR T2DM OR NIDDM)
AND
TS=(chatbot* OR "conversational agent*" OR "conversational AI"
OR "virtual health assistant*" OR "virtual assistant*" OR "voice assistant*"
OR "embodied conversational agent*" OR "dialogue system*" OR "dialog system*"
OR "voice-based AI" OR ChatGPT OR "large language model*")
AND
TS=(self-manag* OR "self care" OR "glycemic control" OR "glycaemic control"
OR "blood glucose" OR HbA1c OR A1c)
AND
TS=(random* OR trial)
```

`TS` denotes the Topic field, which searches titles, abstracts, author keywords, and Keywords Plus. Because institutional access to the Core Collection was unavailable, these strategies could not be run and no result counts are reported.

![Web of Science displaying only Name Search](<image/Assignment One.draft.zh-CN/1792158962885.png>)

*Figure 11. The Web of Science personal account page displayed only Name Search. The screenshot documents the lack of access to Core Collection document searching.*

## 7. Summary of Search Results

| Database | Sensitive search results | Specific search results | Potentially relevant studies | Status or explanation |
|---|---:|---:|---|---|
| PubMed | 1,446 | 7 | Not yet screened | Search completed |
| Cochrane CENTRAL | 78 Trials | 20 Trials | Not yet screened | Search completed; authentication is required for full CENTRAL access |
| CNKI Chinese-language collection | 142 | 1 | Not yet screened | Search completed; foreign-language results retained as supplementary material |
| CINAHL | - | - | - | Institution login failed; database search interface could not be opened |
| Web of Science Core Collection | - | - | - | Document Search access was unavailable |

The specific search reduced the PubMed results from 1,446 to 7, the Cochrane CENTRAL results from 78 to 20, and the CNKI Chinese-language results from 142 to 1. This reduction was mainly produced by adding the outcome and randomized trial concepts. The specific strategies provide a more manageable set for screening, although they may miss studies whose abstracts do not clearly state the study design or outcomes.

## 8. Preliminary Screening Criteria for Potentially Relevant Studies

Titles and abstracts will be screened using the following criteria:

1. The study population includes adults with type 2 diabetes.
2. The intervention is an AI tool capable of automated dialogue with patients, rather than a general AI model used only for prediction, diagnosis, or image analysis.
3. The intervention addresses diabetes self-management, education, behavioral support, medication management, or glycemic control.
4. The study is a randomized controlled trial, or the abstract clearly reports random allocation.

Reviews, editorials, purely qualitative studies, non-randomized observational studies, system-design papers, protocol-only publications without trial results, and mixed-population studies without separately extractable data for adults with type 2 diabetes will not be counted as potentially relevant studies.

Title and abstract screening has not yet been completed. The results table therefore reports only the number of records returned by each database and does not give a final number of potentially relevant studies. Results should first be counted separately for each database. If the number of unique studies is subsequently reported, records from all databases will need to be deduplicated.

## 9. Evaluation and Limitations

The sensitive strategies included broad concepts such as Artificial Intelligence and therefore retrieved studies that used AI for risk prediction, diagnosis, image analysis, or data modelling. The specific strategies restricted the intervention to conversational agents and added outcome and study-design concepts. This produced more focused results but may have excluded earlier studies that did not use common terms such as chatbot or conversational agent.

The main limitation was restricted institutional access to CINAHL and the Web of Science Core Collection. Actual result counts were obtained from only three of the five specified databases. The CINAHL and Web of Science strategies are planned strategies and were not included in the results comparison. The CNKI foreign-language specific search used Chinese-English Expansion, making it inconsistent with the settings used for the Chinese-language search; it was therefore excluded from the main comparison.

## 10. Conclusion

This search addressed four concept groups: type 2 diabetes, AI conversational agents, self-management or glycemic control, and randomized trials. The strategy was adapted to the fields and controlled vocabularies available in each database. Results from PubMed, Cochrane CENTRAL, and CNKI showed a clear difference between the sensitive and specific approaches. Whether the retrieved records meet the inclusion criteria still needs to be determined through title, abstract, and full-text screening. CINAHL and the Web of Science Core Collection could not be searched because of institutional access restrictions, and the relevant screenshots have been retained as evidence of these limitations.

## 11. Declaration of Generative AI Use

Generative artificial intelligence was used to help interpret the assignment requirements, organize the initial search terms, and improve written expression. The database operations, screenshots, result counts, and report content were checked by the author against the searches performed.

## 12. Sources Used to Develop the Search Strategies

- PubMed Help: https://pubmed.ncbi.nlm.nih.gov/help/
- NLM MeSH Browser: https://meshb.nlm.nih.gov/
- Cochrane Library Advanced Search: https://www.cochranelibrary.com/advanced-search
- China National Knowledge Infrastructure (CNKI) Advanced Search: https://www.cnki.net/kns8/AdvSearch
- EBSCOhost Searching Tips: https://connect.ebsco.com/s/article/EBSCOhost-Searching-Tips?language=en_US
- Web of Science Core Collection Search Fields: https://webofscience.help.clarivate.com/en-us/Content/wos-core-collection/woscc-search-fields.htm
