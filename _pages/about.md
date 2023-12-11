---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

Hi! I'm a student at Duke University studyin data science. 

I was a game data scientist at [Tencent Global Publishing brand Level Infinite](https://www.levelinfinite.com/), providing data-science support to multiple mobile gamaes like [AOV](https://www.arenaofvalor.com/), [Alchemy Stars](https://www.alchemystars.com/), etc. Our primary responsibility involves transforming real-world business challenges into actionable data science problems and providing scientific support to other teams. I love the combination of data science and game-playing, especially from the perspective from machine learning and causal inference. 

I regularly share my thoughts and reflections from my daily job through articles on Medium. If you're interested in these articles and game data science, free free to discuss with me~

My research focuses on the interdisciplinary research in Artificial Intelligence and data science, solving real-world challenges in areas like climate, environment, etc. I'm enthusiastic about leveraging data-science tools to uncover insights and drive decision-making processes in the tech world. 

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2023</div><img src='images/thumbnail.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Augmenting Ground-Level PM2.5 Prediction via Kriging-Based Pseudo-Label Generation**

**Lei Duan**, Ziyang Jiang, David Carlson

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- We propose a *data-augmentation* strategy to augment the training dataset by introducing unlabeled satellite images paired with pseudo-labels generated through *Ordinary kriging*.
</div>
</div>

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

# Blogs and Reflections:
<!-- - [Introducing a new Approach for Revenue Prediction Utilizing the Cobb-Douglas Production Function](https://medium.com/@503823696/introducing-a-new-approach-for-revenue-prediction-utilizing-the-cobb-douglas-production-function-7098aa2cc40d)
- [Simpson’s Paradox in daily data analysis work](https://medium.com/@503823696/simpsons-paradox-in-daily-data-analysis-work-51d28c9c7967)
- [Data Science in Gaming- Practical Applications of Propensity Score Matching (PSM)](https://medium.com/@503823696/data-science-in-gaming-practical-applications-of-propensity-score-matching-psm-6529227afe5f)
-  -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Medium</div><img src='images/psm.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Data Science in Gaming - Practical Applications of Propensity Score Matching (PSM)**](https://medium.com/@503823696/data-science-in-gaming-practical-applications-of-propensity-score-matching-psm-6529227afe5f)

**Lei Duan**

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- This article demonstrates the practical application of Propensity Score Matching (PSM) in the gaming industry to assess player retention rates. Faced with the challenge of comparing retention rates between players engaged in both Matching and Ranking modes versus those in just Matching mode
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Medium</div><img src='images/cd.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Introducing a new Approach for Revenue Prediction Utilizing the Cobb-Douglas Production Function**](https://medium.com/@503823696/introducing-a-new-approach-for-revenue-prediction-utilizing-the-cobb-douglas-production-function-7098aa2cc40d)

**Lei Duan**

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- The articl introduces the Cobb-Douglas production function, adapted to analyze the diminishing impact of increasing key metrics like session count and duration on revenue. This approach underscores the influence of a platform's maturity stage on revenue growth, highlighting the principle of marginal diminishing returns for more effective and rapid revenue modeling.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Medium</div><img src='images/sp.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Simpson’s Paradox in daily data analysis work**](https://medium.com/@503823696/introducing-a-new-approach-for-revenue-prediction-utilizing-the-cobb-douglas-production-function-7098aa2cc40d)

**Lei Duan**

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
- The article discusses an instance of Simpson's Paradox in data analysis.
</div>
</div>


# Research Experience
- *2022.09 - (now)*, Carlson Lab
  - Augmenting Ground-Level PM2.5 Prediction via Kriging-Based Pseudo-Label Generation
  - ENS10 Data
- *2023.05 - 2023.08*, WILSON Center for Science and Justice at Duke Law
  - North Carolina Failure-to-comply (FTC) and failure-to-appear (FTA) Inferential Research
    - we performed a series of mixed-model linear regressions ("MLM") to understand the relationship between race, poverty, and driver's license suspensions, which allowed us better control for random variation between counties and with better precision estimate the relationship between the predictor variables we care about and outcome variables on North Carolina driver's license suspensions from 2010-2017. 
  - Fines and Fees
- *2023.06 - 2023.08*, Duke Dataplus
  - [Quantifying wetland carbon emissions in the Southeastern US](https://bigdata.duke.edu/projects/quantifying-wetland-carbon-emissions-in-the-southeastern-us/)

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Educations
- *2022.08 - (now)*, Master, Duke University. Durham, NC. 
  - Tuition Grant (2022-2024)
  - TA for Fraud Detection 523 at *Fuqua* (2023 Spring and 2023 Fall)
  - GPSG Representative of Pratt School of Engineering
- *2015.08 - 2019.06*, Undergraduate, Xiamen University. Xiamen, Fujian. 

# 💻 Full-time
- *2022.02 - 2022.08*, [Tencent Level Infinite](https://www.levelinfinite.com/) (Full time), China.
  - DataBrain data Calibration: Calibrate our internal Intelligence and public opinion platform data based on AppAnnie and SensorTower. The repo link is [here](https://gitfront.io/r/leiduan/BEoMZSitb4pG/data-calibration/)
  - Churn Prevention:
    - Identify the probability of user churn in advance before they churn, and intervene in the game to lower churn rate.
    - cluster users with a high probability of churn in dimensions such as gameplay, social interaction, payment, and depth, and implement differentiated intervention strategies for different types of users to achieve the best user experience and intervention effects.
  - User Churn Analysis: A Comparison Between Players Engaged in Both Matching and Ranking modes and those Only Playing Matching modes.(See how I approach this problem here)
  - Implementing A/B tests and result interpretation

# Internships
- *2021.12 - 2022.01*, [Kearney](https://www.kearney.com/), China.
- *2021.06 - 2021.12*, [Bilibili](https://www.bilibili.tv/en), China.
- *2021.04 - 2021.06*, [Tencent Smart Retailing](https://retail.tencent.com/), China.
- *2020.11 - 2021.01*, [Accenture](https://www.accenture.com/ca-en), China.