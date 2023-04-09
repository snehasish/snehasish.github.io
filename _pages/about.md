---
layout: about
title: about
permalink: /
subtitle: Staff Software Engineer at Google, USA

# profile:
#   align: right
#   # image: prof_pic.jpg
#   image_circular: false # crops the image to make it circular
#   address: >
#     <p>555 your office number</p>
#     <p>123 your address street</p>
#     <p>Your City, State 12345</p>

news: false  # includes a list of news items
latest_posts: false  # includes a list of the newest posts
selected_papers: true # includes a list of papers marked as "selected={true}"
social: true  # includes social icons at the bottom of the page
---
## about
I am a Staff Software Engineer at Google, USA working on profileg guided optimizations for warehouse scale computers. My work on [code layout](https://groups.google.com/g/llvm-dev/c/RUegaMg-iqc/m/wFAVxa6fCgAJ) was featured in [Phoronix](https://www.phoronix.com/news/Machine-Function-Splitter) and (was briefly #1) [HackerNews](https://news.ycombinator.com/item?id=24437459). As part of a larger team, I worked on Propeller a post-link optimization framework. An [academic paper](https://research.google/pubs/pub52144/) describing our work was awarded distinguished paper at [ASPLOS 2023](https://asplos-conference.org/2023/#:~:text=Propeller%3A%20A%20Profile%20Guided%2C%20Relinking%20Optimizer%20for%20Warehouse%20Scale%20Applications).
I am an LLVM [contributor](https://github.com/llvm/llvm-project/commits?author=snehasish).

Service

## academic research
As a PhD student I worked with the Architecture Research Group at Simon Fraser University advised by Arrvindh Shriraman. I was also supervised by Nick Sumner, Viji Srinivasan and Sasha Fedorova. My research can be broadly described as generalized methods for application specific hardware specialization. I have worked on cache memory systems, coherence protocols, workload characterization and application specific hardware specialization.

The semiconductor industry has resorted to hardware specialization as a means to provide the performance and energy benefits consumers have experienced since the invention of the microprocessor. However, specialized hardware units introduce new challenges, namely -- what to specialize, how to specialize and how to integrate specialized units. Current approaches require manual effort to analyse, restructure and rewrite workloads to take advantage of specialized hardware accelerators. My research has focused on automated compiler techniques with a goal of specialization. It is the first to directly address the problems of what to specialize and how to specialize program regions in large, irregular workloads. I recognized the utility of adapting program analysis techniques to address the problem. My work at IISWC'16 demonstrates that analyses at coarser granularities smears characteristics critical to hardware specialization. Using a methodology adapted from program analysis, I have synthesized an accelerator workload suite to assist researchers. I have also developed program abstractions to ease the mapping of irregular programs onto specialized hardware accelerators (HPCA'17). The tools I have built are available as free and open source software. Built upon LLVM, they allow researchers to easily reproduce and extend the work that I have done. In addition to this line of work, I have also conducted research on mitigating energy consumption due to extraneous data movement. In our work presented at ISCA'15, we showed the utility of time-stamp based coherence protocols to reduce the overhead of data movement in accelerator rich architectures. It allows for close integration of multiple specialized units while easing the programming burden of explicit data transfers. Furthermore, I have designed and evaluated adaptive granularity caching mechanisms to eliminate waste (MICRO'12). This technique also provides a convenient substrate for subsequent optimizations such as cache compression.