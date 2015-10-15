---
layout: post
title: Identifying "Reputable" Doctors
excerpt: Identifying a reputable, "good" doctor can be difficult. Can we use network analysis to help? A network analysis on physician referral patterns  -
---

Generally, finding a "good", reputable doctor can be difficult. We have many resources out there - insurance websites or Zocdoc etc - but rarely do these resources provide reliable information on the quality of care, experience, or even outcome from potential providers. Are there creative ways that we can provide more transparency? Are there public data sources that can help us with that?

Several years ago CMS began publishing a dataset on physician referrals. The dataset contain information for each referring, referred to doctor, and the actual volume of referrals as seen through their medical claims. Using the NPI numbers provided, you can also piece it together with other information on providers, such as their specialty, location, etc. This dataset presents a rich opportunity to analyze the network relationships between physicians.

My goal for this project was to identify and rank the most "influential" doctors, within a specified referring relationship. For example, if I want to look for options in finding a cardiologist, can I find out who is the most influential, based on primary care providers,  through centrality measures? Aka according to primary care doctors, which specialist do they like to refer most of their patients to? 

Now referral patterns/decisions can be driven by many factors - such as a doctor's personal network, previous experience, etc. In continuing analyses I would delve into this more, identify what some of these factors are, how they contribute to referrals, and potentially how we could get a more "pure" view of referrals driven primary due to quality of care/patient experience etc. For this analysis I developed an app to visualize the network relationships, and the top ranking doctors by the Eigenvector Centrality measure.

[![alt text](../images/doctorvis.png "Doctor Network App")] (http://ec2-52-20-33-40.compute-1.amazonaws.com/)

