---
layout: post
title: "Christos Petalotis won the first place in the VERSEN Master Thesis Award"
tags: [awards]
comments: true
---

Christos Petalotis won the first place in the VERSEN Master Thesis Award. Congrats Christos!

His thesis is titled "A First Investigation Into the Detection of Energy-related Issues in Microservice-based Systems via Anomaly Detection and Root-Cause Analysis" and it was carried out under the supervision of [Ivano Malavolta](https://www.ivanomalavolta.com). 

The work has been supported by the [uDevOps European project](https://microdevops.wordpress.com/) in collaboration with Roberto Pietrantuono, Antonio Guerriero, Luca Giamattei, and Luka Krumpak. 

You can find further info about the award and its procedure [here](https://www.versen.nl/contents/procedure-thesis-award).

![CHRISTOSPETALOTISAWARD](/files/posts/christos_petalotis_award.jpeg){: .mx-auto.d-block :}

Below you can find the abstract of the thesis.

_Context_. As the trend toward microservice-based architecture gains traction in software application development and deployment, system complexity experiences a significant upsurge. This, in turn, has a detrimental influence on observability and maintainability. To tackle these challenges, numerous solutions that conduct anomaly detection and root cause analysis have been developed. These solutions make use of logged metrics pertaining to hardware resource utilization. However, these solutions commonly overlook the incorporation of system energy consumption. While prior research has predominantly focused on the fundamental techniques underpinning anomaly detection and root cause analysis, as well as their performance assessment in conjunction with hardware utilisation metrics, the aspect of system energy consumption has remained noticeably unaddressed.

_Goal_. In this paper, we examine the effectiveness of anomaly detection and root cause analysis tools for microservice-based applications, particularly emphasizing on energy consumption metrics. We investigate whether and how energy consumption metrics, can enhance anomaly detection’s ability to identify energy-related anomalies and aid root cause analysis in revealing their true causes. 

_Method_. This study is centered on two distinct systems, namely SockShop and Zahori, varying in complexity and purpose. From a large pool of tools, PyCaret was selected for anomaly detection and RCD for root cause analysis in our experimentation efforts. Metrics were gathered from the target systems using a cross-over paired comparison design, involving multiple randomised runs to establish robust measures.

_Results_. The anomaly detection solution employed shows weak performance in terms of adjusted recall, and F1-score, indicating poor ability detecting anomalies related to energy consumption. These values are around 19.5%, and 32.1% accordingly for both target systems. Precision stands around 90%. The results for root cause analysis in terms of precision at the top 3 predictions by the employed solution tend to be weak, with the average value (AP@3) standing at 43.6% for SockShop and 37.2% for Zahori.

_Conclusions_. The research findings demonstrate that anomaly detection yields precise forecasts regarding anomalies within metric segments. Nonetheless, both anomaly detection and root cause analysis exhibit a tendency to miss several instances that require identification as anomalies or their causal factors. Consequently, further research efforts are imperative to develop tools and methodologies that can harness energy consumption metrics from microservice-based applications effectively, ensuring satisfactory performance. Practitioners are encouraged to employ AD solutions together with other tools to cover a wider spectrum of energy consumption anomalies. The performance of RCA on energy consumption data and related anomalies was found lacking, thus it is advised system operators rely on other tools to find the root causes of energy consumption anomalies.