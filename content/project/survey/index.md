---
author: Kristina Becvar
categories:
- plans
- next steps
- options
date: "2022-08-02"
draft: false
excerpt: In order to create an accurate plan for amplifying member messages, we need accurate data on our target demographic. The best way to accomplish this is to put a survey out in the public sphere.
featured: true
layout: single
links:
- icon: door-open
  icon_pack: fas
  name: website
  url: https://allisonhorst.github.io/palmerpenguins/
- icon: github
  icon_pack: fab
  name: code
  url: https://github.com/allisonhorst/palmerpenguins/
- icon: newspaper
  icon_pack: far
  name: Blog post
  url: https://education.rstudio.com/blog/2020/07/palmerpenguins-cran/
subtitle: ""
tags:
- survey
title: YouGov Survey
---

### Putting a YouGov survey in action to understand a sample of American citizens and how they interact with our messaging and offerings will help us to better understand how to communicate our mission.

*— [YouGov Sample Survey Options](https://g4-us.yougov.com/vbzZG4hBNpwDmh)* [^1]

---

We suggest conducting a survey through YouGov, a firm that is used by UMASS Amherst Department of Social and Behavioral Sciences, and has conducted polls for a variety of clients, including the Economist and CBS News. YouGov relies on cutting edge statistical techniques to recruit survey respondents online and produce a representative sample of the target population.

In 2018, Nate Silver of Fivethirtyeight.com rated YouGov among the top ten of pollsters to trust during the midterm elections. According to Nate Cohn of the New York Times, while the average error of online polls during the 2018 midterm election was 5.3 percentage points, YouGov posted an industry best average of 2.5 percentage points in their 2018 midterm election polls.

The YouGov and UMASS Poll produced one of the most accurate polls in the closing days of the 2016 Massachusetts general election. The final poll conducted in Massachusetts showed that 54% of the state’s residents would support the legalization of marijuana in the state (Question 4).  On Election Day, Question 4 passed 54% to 46%.  

---

### <iframe src="https://www.pewresearch.org/internet/chart/which-social-media-platforms-are-most-popular/iframe/" id="pew17383" scrolling="no" width="100%" height="100px" frameborder="0"></iframe> <script type='text/javascript'id='pew-iframe'>(function(){function async_load(){var s=document.createElement('script');s.type='text/javascript';s.async=true;s.src='https://www.pewresearch.org/internet/wp-content/plugins/pew-refactor-shim/pew-scripts/js/iframeResizer.min.js';s.onload=s.onreadystatechange=function(){var rs=this.readyState;try{iFrameResize([],'iframe#pew17383')}catch(e){}};var embedder=document.getElementById('pew-iframe');embedder.parentNode.insertBefore(s,embedder)}if(window.attachEvent)window.attachEvent('onload',async_load);else window.addEventListener('load',async_load,false)})();</script>	


> ##### CSS Grid Layout Module
>
> This CSS module defines a two-dimensional grid-based layout system, optimized for user interface design. In the grid layout model, the children of a grid container can be positioned into arbitrary slots in a predefined flexible or fixed-size layout grid.
>
> — _W3C_

CSS Grid is a total game changer, IMHO. Compared to the bottomless pit of despair that is the old way, the new way of building a site structure can be done in as little as 5 lines of CSS. Of course, it always takes more than that, but not much. I mean this is really the meat of the deal:

```css
.grid-container {
  display: grid;
  grid-template-columns: repeat(6, 1fr);
  grid-template-rows: repeat(3, auto);
}
```

#### What an amazing time to be a web developer. Anyway, I hope you enjoy this "feature" that you'll probably never notice or even see. Maybe that's the best part of a good user interface – the hidden stuff that just works.

[^1]: The original article cited here is now updated and maintained by the staff over at CSS-Tricks. Bookmark their version if you want to dive in and learn about CSS Grid: [A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)
