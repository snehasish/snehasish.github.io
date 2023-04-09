---
layout: about
title: about
permalink: /
subtitle: <a href='#'>Affiliations</a>. Address. Contacts. Moto. Etc.

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  address: >
    <p>555 your office number</p>
    <p>123 your address street</p>
    <p>Your City, State 12345</p>

news: false  # includes a list of news items
latest_posts: false  # includes a list of the newest posts
selected_papers: true # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page
---
## About
I joined Google in Sep '17. As a PhD student I worked with the Architecture Research Group at Simon Fraser University advised by Arrvindh Shriraman. I was also supervised by Nick Sumner, Viji Srinivasan and Sasha Fedorova. My research can be broadly described as generalized methods for application specific hardware specialization. I have worked on cache memory systems, coherence protocols, workload characterization and application specific hardware specialization.

Publications : HPCA'18, HPCA'17, IISWC'16, MICRO'16, ICS'16, ISCA'15, ICS'15, ISCA'13, MICRO'12

## Academic Research
The need for computational power has increased with emerging workloads such as machine learning driving the information economy. Yet data center and embedded computing alike desire reduced power consumption. With the breakdown of semiconductor technology scaling, we no longer attain improved performance and reduced energy consumption by using smaller transistors. The semiconductor industry has resorted to hardware specialization as a means to provide the performance and energy benefits consumers have experienced since the invention of the microprocessor. However, specialized hardware units introduce new challenges, namely -- what to specialize, how to specialize and how to integrate specialized units. Current approaches require manual effort to analyse, restructure and rewrite workloads to take advantage of specialized hardware accelerators.

My research has focused on automated compiler techniques with a goal of specialization. It is the first to directly address the problems of what to specialize and how to specialize program regions in large, irregular workloads. I recognized the utility of adapting program analysis techniques to address the problem. My work at IISWC'16 demonstrates that analyses at coarser granularities smears characteristics critical to hardware specialization. Using a methodology adapted from program analysis, I have synthesized an accelerator workload suite to assist researchers. I have also developed program abstractions to ease the mapping of irregular programs onto specialized hardware accelerators (HPCA'17). The tools I have built are available as free and open source software. Built upon a modern compiler framework, they allow researchers to easily reproduce and extend the work that I have done.

In addition to this line of work, I have also conducted research on mitigating energy consumption due to extraneous data movement. In our work presented at ISCA'15, we showed the utility of time-stamp based coherence protocols to reduce the overhead of data movement in accelerator rich architectures. It allows for close integration of multiple specialized units while easing the programming burden of explicit data transfers. Furthermore, I have designed and evaluated adaptive granularity caching mechanisms to eliminate waste (MICRO'12). This technique also provides a convenient substrate for subsequent optimizations such as cache compression.