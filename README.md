# Effects of social media on mental health in times of crisis

## Table of Contents
1. [🫧 Project Description](#project-description)
2. [🔗 Sources](sources)
3. [🔍 Research Summary](research-summary)
4. [🧩 STEEPLE Analysis](steeple-analysis)
5. [🫆 Interactive Model and Results](interactive-model-and-results)
6. [💻 Usage](usage)
7. [💭 Future recommendations](future-recommendations)
8. [👤 Support Information](support-information)

---

## 🫧 Project Description

The rapid advancement of technological tools and increasing usage of social media platforms have reshaped the way people communicate with each other, social perspectives, and coping mechanisms. This project investigates the extent to which social media negatively impacts the mental health of the general population during times of crisis, including wars and periods of economic instability. Through an extensive research of publicly available articles and datasets, this project examines how social media affects mental health and resilienece levels across different demographics such as young adults and the elderly, and how individuals are navigating an increasingly uncertain future shaped by both real-world conflict and its digital representation.

### To what extent does social media have a negative effect on mental health of the general population in times of crisis?

Ultimately, this project aims to develop predictive and interactive models that capture the complex relationship between social media use and mental health outcomes, contributing to a broader understanding of how advancement of technological tools can both challenge and support our society's resilience in times of crisis.

The project outline includes
- Identifying key variables that directly and indirectly influence coping behaviours and resilience levels
- Understanding the role of social media in social support
- Identifying the psychological consequences of war media exposure
- Identifying the interactions of different types of social media engagement on mental health
- Developing predictive and interactive models capturing the relationship between of social media use and mental health outcomes

---

## 🔗 Sources

A total of 5 papers and articles were used in the research, modelling, and visualisation process.

1. Feten Fekih-Romdhane, M. H. (2024, June). Mediating effect of depression and acute stress between exposure to Israel-Gaza war media coverage and insomnia: a multinational study from five arab countries. Retrieved from PubMed Central: https://pmc.ncbi.nlm.nih.gov/articles/PMC11151504/
2. Kübra Gülırmak Güler, E. A. (2024, October 28). Fronts in Minds: A Phenomenological Study on the Effects of War News on Collective Mental Health . Retrieved from Wiley Online Library: https://onlinelibrary-wiley-com.wwwproxy1.library.unsw.edu.au/doi/full/10.1111/phn.13458
3. Nawara Kirallah Abd El Fatah, A. M.-A. (2025, June 16). Unseen Battles: The Impact of War Media Exposure on Stress, Anxiety and Persistent Thinking Among Elderly Community Dwellers: A Cross-Sectional Study. Retrieved from Wiley Online Library: https://onlinelibrary-wiley-com.wwwproxy1.library.unsw.edu.au/doi/full/10.1111/inm.70082
4. Tali Gazit, S. E. (2025, November 6). From Screens to Scars: Understanding the Association Between Social Media Engagement and Trauma During Crises and Emergency Situations. Retrieved from Wiley Online LIbrary: https://onlinelibrary.wiley.com/doi/10.1002/smi.70115
5. Yael Malin, Y. G. (2026, July). Mental health during war: Social media use and protective factors among adolescents and young adults. Retrieved from ScienceDirect: https://www-sciencedirect-com.wwwproxy1.library.unsw.edu.au/science/article/pii/S0747563226000336

---

## 🔍 Research Summary

Across all five papers, it is concluded that social media only affects mental health and resilience of individuals to a moderate extent, as it is usually not the direct driver of distress and trauma during war times and crises. Independent variables such as screen time and media engagement volumes are correlated with increased distressed, anxiety, insomnia, and trauma regardless of demographic group. Dependent variables constantly shift with respect to population groups – distress and well-being for youths, stress and anxiety for the elderly, insomnia and future uncertainty for Arab and Turkish adults. There are also changing variables such as economic instabilities and pandemic aftershocks which affects psychological risks and resilience levels. Protective factors are consistent across the papers, which includes emotional regulation, perceived social support, media literacy, and access to reliable information sources. Most importantly, it is important that while technology tools are convenient and accessible, they cannot fully replace in-person social support as a resilience resource during prolonged crisis.

---

## 🧩 STEEPLE Analysis

| **STEEPLE** | **Description** |
|----------- -|----------------------------------|
| `Social` | Social media platforms such as Twitter, Instagram, TikTok, etc. and online debates can trigger both positive and negative emotions such as distress, anxiety, o mood boosts |
| `Technological` | Personalised algorithm feeds and unfiltered content may increase the exposure of distressing/encouraging images and videos – how unfiltered/filtered/biased are these content? |
| `Economic` | Socioeconomic status may affect the access of social media and resilience resources, and economic instabilities further drives anxiety and future uncertainties of the global economy |
| `Environmental` | Geographic proximity to missile strikes and war zones are significant drivers, but war media exposure can also cause distress for individuals not living in war regions |
| `Political` | Polarised war posts on platforms such as Reddit or Twitter may include online political debates and spreading of misinformation, resulting in further social polarisation |
| `Legal/Ethical` | Interference of war media exposure and media literacies by governments (health and education ministries) is necessary to regularise screen time, fake news, and negative content |

---

## 🫆 Interactive Model and Results

The interactive model is a combination of 3 visualisations that predicts the average distress and trauma levels based on several factors such as social media platform, usage in hours, age group, and content type. The slider on the top left corner is an interactive feature that allows the user to slide from a minimum of 1 hour, to a maximum of 5 hours of time spent on social media platforms. The visualisations are also customisable with other variables such as prediction depression or insomnia, war media exposure hours, and coping levels based on the user’s needs.

<p align="center">
  <img src="tableau_dashboard.png"/>
  <br>
  <em>Interactive Tableau dashboard with predicted distress and trauma levels</em>
</p>

Across all platforms (Facebook, Instagram, Telegram, TikTok, Twitter/X, WhatsApp), the predicted distress levels were between 5.1 to 5.4 (on a scale of 10), which indicates low variance.  This suggests that the social media platform itself does not have a huge significance on distress or trauma levels. It is rather the amount of time spent on social media itself that is overall affecting the mental health of an individual. 

One of the most significant results was the relationship between usage hours and predicted trauma levels. It is noted that e**very additional hour of social media usage increases trauma and decreases mental health**. While all platforms show an upward trend based on the usage time, there is a steeper increase for Twitter/X and TikTok, and a lower increase for WhatsApp. This implies that social media platforms with video-based or real-time content results in higher trauma levels. 

However, **the predicted trauma levels vary slightly across age groups**, with young adults (24 to 30 years old) predicted to have the highest trauma level (5.2 to 5.5) and the elderly (60 years old and above) predicted to have a slightly lower trauma level (4.5 to 5.0). From the research summary, the media exposure time and engagement patterns are the key factors that drive these differences. Hence, age was not a significant predictor to distress and trauma levels.

Overall, the model and visualisations suggest that **social media has a significant negative impact on the mental health** of the general population in times of crisis. The most significant variable was the **amount of time spent on social media and exposure to war content**. Although other variables such as gender and age were explored, these variables were not as significant but still played a moderate role in the predicted distress and trauma levels. This suggests that social media as a whole plays a crucial role in shaping psychological outcomes, with platforms such as Twitter/X and TikTok sitting slightly higher due to their higher polarisation risk and video-based content.

---

## 💭 Future recommendations

---

## 💻 Usage

---

## 👤 Support Information

If you have any questions or suggestions regarding the project, feel free to contact Yu Tyan through yutyanng@gmail.com.
