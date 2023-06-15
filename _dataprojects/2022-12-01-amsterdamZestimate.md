---
title: Amsterdam AirBnB Price Estimation 
subtitle: Researching and modeling AirBnBs for a high demand tourism market.
date: 2022-12-01 00:00:00
description: Amsterdam, like many high-tourism cities, has an issue with balancing its tourism experience with the local supply of housing and resident quality of life. My group created a price estimation model and a sample app to target potential new hosts outside the most popular areas of the city.
featured_image: /amsterdam/building.jpg
accent_color: '#4C60E6'
gallery_images:
  - /amsterdam/building.jpg
---

**Project at the University of Pennsylvania, Fall 2022**

Collaboration between myself, Ann Zi'an Zhang, and Tom Yuhao Sun

One of the most common ways people interface with housing data and forecast models these days is through Zillow's Zestimate. Active price estimates allow all of Zillow's users to see what works best for their own budget, saving them research time. This tool can be applied beyond home prices and curious shoppers for a use case like Airbnb rental estimation while using the same fundamentals. But beyond just curiosity, why look at short term rentals?

#### Why model Amsterdam and Airbnb?

Airbnbs and short-term full-home vacation rentals have a contentious relationship with popular tourism cities like Amsterdam. They can limit housing supply and be a nuisance to nearby residents if the guests are not courteous. Amsterdam went so far as to ban Airbnbs in its historic center, but this rule was overturned soon after, and future regulations are uncertain. This fuzzy future makes for a tumultuous market for those that are trying to host, which is where statistical modeling can be helpful.

If Amsterdam residents outside the city center had access to an accurate daily rental esimation, more may be incentivized to host within the local guidelines. The city wants to promote better experiences for its guests, and tourists want a unique experience, so spreading those experiences outside the most obvious localities may lead to greater satisfaction for all parties. 

![](/images/projects/amsterdam/airbnbPop.png)

#### Analysis and Modeling

With this reasoning, our group approached price modeling by combining significant unit attributes with spatial amenities like transit and highly rated attractions. We figured that there may be latent demand for short term rentals outside the city center, and these could be found with the right factor engineering.

Our group used [2018 AirBnB data](https://www.kaggle.com/datasets/erikbruin/airbnb-amsterdam) and [Amsterdam's public data respository](https://data.amsterdam.nl/) to create this price prediction model, then measured our success by how well it performed on areas outside the city center.

[Explore our research, process, and conclusions in our markdown.](https://bennkeel.github.io/documents/Final-Amsterdam.html)

#### Bringing the model to our audience

This video below outlines the need for short-term rental hosts in other areas of Amsterdam and explains how our model can help and be brought to its intended audience.

{% include post-components/video.html
	url = "https://www.youtube.com/embed/Xr2tM-RtyQQ"
	full_width = true
%}

---

#### Tools Used:
* R Tidyverse Packages and Markdown for spatial and statistical analysis and modeling
* Adobe Premiere Pro & Illustrator for use case and presentation
* Figma for App Design

