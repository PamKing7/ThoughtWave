# ThoughtWave

<p align="center">English&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a href='./README - ch.md'>简体中文</a></p>

​	*Commentary, as a form of news and opinion, typically adhere to a certain fixed paradigm, which sets them apart from other types of articles. In contrast, commentary articles usually follow the following structure: introduction, main argument, supporting arguments, evidence, and ending.*



## Single Prompt

*I will provide you with a news background:*

​	*{**Event detail**}*

*Based on this news, with the title '{**Title**}', please create a commentary article. The article should have clear and profound arguments, true and abundant evidence, smooth logical reasoning, reasonable structure, and appropriate commentary language. Your article should reference the following argument and evidence:*

​	*Argument 1: {**Argument 1**}*

​	*Evidence 1: {**Evidence 1**}*

​	*Argument 2: {**Argument 2**}*

​	*Evidence 2: {**Evidence 2**}*

​	*Argument 3: {**Argument 3**}*

​	*Evidence 3: {**Evidence 3**}*

### Sample

*I will provide you with a news background:*

​	*{**On the morning of October 23rd at 7:39 AM, as a down jacket purchased online was dispatched from Qingdao, the National Postal Service's express delivery big data platform showed real-time monitoring data indicating that the 100 billionth express delivery of this year in China was generated, 39 days earlier than last year.**}*

*Based on this news, with the title '{**"Express 'small packages' reflect the economic 'big chessboard'."**}', please create a commentary article. The article should have clear and profound arguments, true and abundant evidence, smooth logical reasoning, reasonable structure, and appropriate commentary language. Your article should reference the following argument and evidence:*

​	*Argument 1: {**"The rapid growth in express delivery volume is the result of a dual push from supply and demand in the market."**}*

​	*Evidence 1: {**Looking at the demand side, China's consumer market continues to recover, with significant advantages in the super-large-scale market. It continuously meets people's online shopping needs for clothing, food, housing, and transportation, thereby transforming into strong momentum for the express delivery industry. On the supply side, the construction of urban and rural express delivery infrastructure continues to improve, reducing regional disparities, making it more convenient for consumer goods to reach villages and agricultural products to enter cities. These favorable factors not only drive the continuous expansion of the express delivery industry but also signify a more active market with a warm atmosphere of development, adding vivid annotations to China's stable and improving economy.**}*



## 5-Step Generation Prompt

*Please refer to Appendix **A.3** for detailed information.*



## Structure

*The project structure is as follows:*

```
ThoughtWave
    ├─5_step_generation_prompt	--	5-Step inference and scoring files, corresponding to Table 3
    │  ├─Baichuan2-Turbo
    │  ├─GPT-4
    │  ├─Qwen-72B-Chat
    │  └─kdd_task_data_sample.json	--	5-Step Sample
    └─single_prompt	--	Single inference and scoring files, corresponding to Table 2
        ├─Baichuan2-Turbo
        ├─ERNIE-4
        ├─GLM-4
        ├─GPT-3.5-Turbo
        ├─GPT-4
        └─Qwen-72B
```

