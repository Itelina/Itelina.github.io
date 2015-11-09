---
layout: post
title: Get Better with Data Health Hackathon 2015
excerpt: Awesome hackathon where we spent 1 day analyzing publically available healthcare data. My team did an analysis on procedure code cost variables.
---

[Get Better with Data](http://getbetterwithdata.com/) was awesome!! This was my first hackathon ever and I was lucky to have an awesome team including [Ting Feng] (https://www.linkedin.com/in/tingfeng) , [Angel Wong] (https://www.linkedin.com/in/angelywong), and [Gerardo Sierra] (https://www.linkedin.com/in/gerardo-sierra-79a99b44). We were assigned to do visualization, so we decided to use the [Medicare Utilization and Payment Dataset] (https://www.cms.gov/Research-Statistics-Data-and-Systems/Statistics-Trends-and-Reports/Medicare-Provider-Charge-Data/Physician-and-Other-Supplier2013.html) to analyze  variations in procedure costs. 

One of the visualizations we created was looking at the overall expenditure, and the cost dispersion within CPT procedure code groups.  We grouped the CPT procedure codes into high level categories based on the designations [here] (https://en.wikipedia.org/wiki/Current_Procedural_Terminology). 

One of the things that caught our attention was cataracts - this contributed to the majority of procedure codes within the "eye and ocular adnexa" category. Why is there such a high cost variation? One of our hypotheses was that it can be performed at private clinics who may charge significantly higher prices for premium services like anesthetics and laser procedures. We would love to explore reasons for the variations in costs - this dashboard represents a starting point for us to explore variations in costs further.

<script type='text/javascript' src='https://public.tableau.com/javascripts/api/viz_v1.js'>{newline}</script><div class='tableauPlaceholder' style='width: 990px; height: 869px;'><noscript><a href='#'><img alt='Dashboard 1 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Pr&#47;ProcedureCodeVariationAnalysis&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz' width='990' height='869' style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='site_root' value='' /><param name='name' value='ProcedureCodeVariationAnalysis&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Pr&#47;ProcedureCodeVariationAnalysis&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='showVizHome' value='no' /><param name='showTabs' value='y' /><param name='bootstrapWhenNotified' value='true' /></object></div>

A quick note on our tools - we mostly used SQL to analyze the dataset and Tableau to visualize the results. 

A BIG shoutout to my teammates Ting, Angel, and Gerardo for such an awesome hackathon!! 
