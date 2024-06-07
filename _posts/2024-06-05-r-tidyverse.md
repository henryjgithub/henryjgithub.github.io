---
layout: post
title: "R: TIDYVERSE"
katex: true
---
<details class="collapse-box"><summary class="collapse-box-title"><b>RESOURCES</b></summary><div markdown="1"><sup><hr>

- [Github - Tidy Tuesday](https://github.com/rfordatascience/tidytuesday)

- [Youtube - David Robinson](https://www.youtube.com/playlist?list=PL19ev-r1GBwkuyiwnxoHTRC8TTqP8OEi8)
<hr>

<p class="collapse-box-p">END</p></div></details>

<details class="collapse-box"><summary class="collapse-box-title"><b>June 06, 2024 - Tidy Tuesday live screencast: Analyzing water access points in R</b></summary><div markdown="1"><p class="collapse-box-source"><a href="#s1">[SOURCE]</a></p><hr>

- Potential Structure
  - (1) Understanding Data
  	- 02:42 "a lot of categorical data"
  	- Scan entire data set using tt$
  - (2) Clean Data & Structure to User
  	- lubridate package
      - mutate() fuct. used to change date to mdy
      - rename() to rename columns
  - (3) Looking at categorical data
    -  view() general overview of data similar to df.head() in python
    -  count(column_name, sort=True) to see categories
    - look for documentation if possible of datatypes
    - 06:10 connection between water_tech and water_source for N/A data
    - (3.1) Data Cleaning
      - seperate brand from tech
      - seperate() func.
  - (4) Missing Data
  - (5) Visualizing water locations
  	- Africa
  	- Uganda
  	  - Trying to add google maps to put lakes/rivers inside
    - Uganda Report by Year
      - good to look at first
    - Uganda Install Year + Report Year
    - Uganda Install Year Animation
<hr>
- Structure:
  - [Data Familiarization] -> [Data Cleaning & Restructuring] -> [Visualization]
  - Data Types
    - Country, Report Date, Install Date -> Visualizations
      - Country Map + Locations + Map(Cities, Lakes, Rivers)
      - Country Map + Animation + Install Date


<p class="collapse-box-p">END</p></div></details>

<sup id="s1"><a href="#s1">(1)</a></sup>
[Tidy Tuesday live screencast: Analyzing water access points in R](https://www.youtube.com/watch?v=5ub92c-5xFQ&list=PL19ev-r1GBwkuyiwnxoHTRC8TTqP8OEi8&index=1)

[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
