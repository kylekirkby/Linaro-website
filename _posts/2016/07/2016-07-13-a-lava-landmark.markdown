---
author: dave.pigott
comments: true
date: 2016-07-13 10:32:53+00:00
excerpt: At 18:23 UTC on July 5th, 2016, a landmark was reached in the LAVA Lab. Job
  number 1,000,000 was submitted by the kernel-ci bot to the main production instance.
layout: post
link: https://www.linaro.org/blog/a-lava-landmark/
slug: a-lava-landmark
title: A LAVA Landmark
wordpress_id: 11157
categories:
- Linaro Blog
---

[vc_row][vc_column width="2/3"][mk_custom_box background_style="gradient_color" bg_grandient_color_from="#5e1f21" bg_grandient_color_to="#f49a84" bg_grandient_color_fallback="#5e1f21" background_hov_color_style="gradient_color"][vc_custom_heading text="At 18:23 UTC on July 5th, 2016, a landmark was reached in the LAVA Lab. Job number 1,000,000 was submitted by the kernel-ci bot to the main production instance. Three minutes later, at 18:26, the scheduler picked the job up and passed it to a dispatcher to run on Highbank node 02. As with all kernel-ci jobs, it ran quickly and was complete two and a half minutes later, and yes: It did complete. This is important, because various improvements to LAVA and the Lab infrastructure over the past six months mean that the majority of failures (> 99%) are due to failing kernels or missing resources - i.e. links on external sites that do not exist." font_container="tag:h2|font_size:20px|text_align:center|color:%23ffffff|line_height:1.6em" google_fonts="font_family:Radley%3Aregular%2Citalic|font_style:400%20regular%3A400%3Anormal" href="``https://validation.linaro.org/scheduler/job/1000000/log_file``" link="url:https%3A%2F%2Fvalidation.linaro.org%2Fscheduler%2Fjob%2F1000000%2Flog_file||target:%20_blank"][/mk_custom_box][vc_column_text]**A Little Bit of History**

LAVA ran its first job at 15:48:58 on Wednesday 27th July 2011 on a Pandaboard. The job was submitted by Frans Gifford, and now, almost exactly 5 years later, we have processed job number 1,000,000.

When LAVA first went live we were running around 20 jobs a day on average. Compare this with today where we run around 2,000 jobs per day on 40 different device types, some physical and some virtual, with a total of 129 device instances. Don’t forget, this is just the main production instance. We also have the LNG, TCWG, PMWG and OpenStack micro-instances.


### History in Context


To illustrate the difference between the start of LAVA and the present day, here are two animations, one from the first month of execution and the other covering just the last week, and the 1,000,000th job. In the animation, each spur from the centre represents a device type (e.g. panda and beaglexm), each spur from that is an active device instance, the number on that spur is the job ID, and the little figures flashing lasers at the devices are the job submitters, either human or, more frequently, automated submission bots.[/vc_column_text][vc_row_inner][vc_column_inner width="1/2"][vc_video title="First month of Lava
in 2011" link="https://youtu.be/4tLKBXqMj5s"][/vc_column_inner][vc_column_inner width="1/2"][vc_video title="Last week leading up to job One Million
(July 2016)" link="https://youtu.be/4e_2K2BdL_4"][/vc_column_inner][/vc_row_inner][vc_column_text]We created these animations using a tool called ‘gource’, which was actually designed to visualise the usage of source code control systems such as ‘git’ over time. I cannot claim sole responsibility for this, since it was Paul Larson, the original LAVA Tech Lead, who first ran it for our first San Francisco event, then known as LDS, in February 2012. I’ve modified and improved the database extraction, but the original concept is Paul’s.


## Where Next?


So, when will we run job number 2,000,000? Well, what may happen is that we will actually hit 1,000,000 again because we’re going to be switching over to LAVA V2 in the next 12 months, and when we have completed that transition we may well start the jobs back at 1, because the results format of the new LAVA is significantly different from V1. We will maintain the old database for historical purposes, but we’re envisaging a clean start.

What’s so special about V2? That is worthy of a blog post all on it’s own, but one of the main advantages we’ve seen is that it is significantly more efficient for deployment and test runs because test writers have much finer control over what to do when actions fail. If we take into account the efficiency and the rate of job submission growth, along with our projected growth in the number of Lab devices, we could well see job 1,000,000 within the next three years.

I’ll keep you posted.

To find out more about LAVA, please follow this [link](http://www.linaro.org/initiatives/lava/).[/vc_column_text][/vc_column][vc_column width="1/3"][vc_single_image image="11163" img_size="full" alignment="center" onclick="img_link_large" img_link_target="_blank"][vc_cta h2="Do you want to see how LAVA can help your company?" h4="Email Dave Pigott for more info" txt_align="center" style="outline" color="black" css_animation="top-to-bottom"]dave.pigott@linaro.org[/vc_cta][/vc_column][/vc_row]
