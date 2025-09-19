---
layout: single
title: Following Up On Goals From The New Year
header:
  image: /assets/images/laptop-and-coffee.jpg
categories:
  - Programming
tags:
  - goals
  - programming
  - new year
  - jekyll
  - azure
  - github
  - github pages
---

It's been a few months since I have checked in here with the professional and programming goals I set for the New Year.

My overarching goal for the year was to program *every* day. That's a really big goal, and life can happen quickly and throw wrenches into achieving perfect streaks. While I may not have achieved this goal, I have been programming most days. It's often better to aim for progress and growth, rather than *perfection*.

#### New Year's Goals

As a quick recap, here are the other 3 goals I set out for myself:

1. Create a personal blog site
2. Create an improved version of my resume site, including light & dark modes
3. Obtain Azure Data Fundamentals and Azure AI Fundamentals certifications

#### Create a Personal Blog

If you are reading this post, I created a personal blog!

There are infinite possibilities when creating a personal blog, including programming languages, hosting platforms, and additional tools. I decided early on in the development process, that I wanted to create a blog using a static site generator and host with GitHub Pages.

One may ask, why I choose to go the route of using a static site generator? Nothing against dynamic sites, but I personally like how quickly static sites load and how they tend to need less on-going maintenance. I already host my [personal website](https://michelle-heatherly.com) on GitHub Pages. With the easy, free static website hosting already integrated with GitHub Pages, it made is easy to choose for the hosting platform.

Sometimes it is nice to just keep things *simple*.

I tried out a few different libraries to help me get started with creating a static blog website on GitHub Pages.

I'll describe the following libraries in detail more below:

1. [Jekyll](https://jekyllrb.com/)
2. [Jekyll Now](https://github.com/barryclark/jekyll-now)
3. [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/)

##### Jekyll

Jekyll is an open-source tool, based on the Ruby programming language along with HTML & markdown files, that can be used for creating static websites, which means the files are pre-rendered HTML without any dynamically generated content or having to maintain additional back-end services & databases. Some of the benefits of using Jekyll is that it is fully integrated (for **free**) with GitHub Pages, and tends to be faster, more secure, and easier to maintain than working with a CMS (Content Management System).

##### Jekyll Now

[Jekyll Now](https://www.jekyllnow.com/) developed by Barry Clark allows developers to get their jekyll site up and running in a few minutes, without needing install Ruby and other dependencies.

Just as it describes itself, one can create a new static blog site quickly. The out-of-the-box design is minimalistic, nice and simple, allowing for one to focus more energy on creating blog posts and content instead.

My test of forking and using the jekyll now repo can be found [here](https://michelle-heatherly.com/jekyll-now/).

##### Minimal Mistakes

After experimenting with Jekyll Now, though I enjoyed the simplicity, I wanted to use a library that had more features integrated into it out-of-the-box. After some research, I came across [minimal mistakes](https://mmistakes.github.io/minimal-mistakes/), a more flexible, responsive, and customizable jekyll theme created by Michael Rose.

Unlike Jekyll Now, this theme does require having Ruby installed and configured, as well as using Ruby gems for installing and bundling the theme.

I already had Ruby installed on my computer from some previous programming projects. If one does not have it already installed, the [Ruby website](https://www.ruby-lang.org/en/documentation/installation/) lists several different ways to install on your operating system. The documentation on how to get started and configure minimal mistakes is also quite extensive.

I love how customizable and extendable this theme is, while still helping jump-start the creation process. I used minimal mistakes for creating [this](https://michelle-heatherly.com/blog/) blog you are currently reading.

Like many personal programming projects, though, I would say this blog is still a work in progress. Most likely, I will continue to explore other tools in developing my blog websites. Some of the tools I am interested in using in future are [Hugo](https://gohugo.io/) and [11ty](https://www.11ty.dev/).

#### Improve Personal Website with Light and Dark Mode

I have added a lot of updates to my personal website in the past few months.

A few of the updates are:

1. Gradient text for the navigation bar brand, headers, and other places for additional emphasis.
2. Swapped out some of the images to more recent screenshots or ones I felt incorporated better with the overall look and feel of the website.
3. Replaced the video to instead be a gradient background with more dynamic, animated text for the Grace Hopper quote.
4. Added badges to the cards in the portfolio section to display what languages & tools were used in development.

However, I have not added a light and dark mode to my personal website.

I know there is an adage in creative writing (I believe attributed to William Faulkner) that says you should "*kill your darlings*". Meaning, don't get too attached to something. Sometimes it is better to revise or eliminate those creative works that we cherish.

I really am enjoying the dark mode, cyber/galaxy theme I have created for my personal website at the moment. I agree that creating a very different website that incorporates a dark/light theme toggle as a feature, might flow better and ultimately convey my skill set as a software engineer in a more concise and professional way. I just am not confident in a new design for my personal website yet.

I have started experimenting with some other designs for the website, as well as the languages & tools it's programmed with. Probably sometime later this year, I will have a new design that meets this criteria and I feel enthusiastic about. Stay tuned.

However, I have been developing dark/light modes for other things.

For example:

I added a dark/light mode toggle to [this](https://michelle-heatherly.com/blog/) jekyll blog site. You can toggle between light & dark modes by clicking the sun/moon button in the navigation toolbar. The default theme is dark (or the neon skin using minimal mistakes), since it matches the main *aesthetic* of my personal [website](https://michelle-heatherly.com).

I also created a small example Angular Typescript & Angular Material example where you can toggle between dark/light modes. You can preview that by clicking [here](https://michelle-heatherly.com/angular-material-color-toggle/). Additionally, the code for any of these projects are visible on my [GitHub](https://github.com/michelleheatherly) page.

It is also worth noting that the latest (alpha) release of [Bootstrap 5](https://getbootstrap.com/docs/5.3/customize/color-modes/#dark-mode) has dark/light mode toggle functionality built into it. You would still need to create a separate button and write a little bit of additional code to toggle between themes, but this is a also a great option for integrating theme switching if you are already utilizing the Bootstrap framework for styling your website.

#### Become Certified in Azure Data Fundamentals and Azure AI Fundamentals

As of the end of February 2023, I hold 3 Azure Certifications: Azure Fundamentals, Azure Data Fundamentals, and Azure AI Fundamentals.

If anyone is interested in getting certified in Azure, Microsoft periodically holds [virtual training days](https://www.microsoft.com/en-us/trainingdays). Several of these training days, like Azure Fundamentals, Azure Data Fundamentals, and Azure AI Fundamentals, come with a free exam voucher for their corresponding certification. These fundamental certifications are great for those who may be new to cloud computing, or using Azure, and are interested in expanding and validating their cloud computing knowledge.

Even if you already have some experience with Azure, or other cloud platforms like Amazon Web Services (AWS) and Google Cloud Platform (GCP), it's a also a great way to learn about any new services and features available in Azure. I highly recommend taking advantage of the **free** training & voucher, if you are interested in learning more about Azure and its offerings. In terms of preparing for these exams, I also utilized [Microsoft Learn for Azure](https://learn.microsoft.com/en-us/training/azure/), their **free** learning platform that has lots of great study materials, exercises, and short quizzes for evaluating your readiness or learning a new skill using the Azure platform.

With OpenAI and ChatGPT being *impossible* to escape in the latest news, studying for the Azure AI Fundamentals exam inspired a lot of interest in me to further explore the possibilities of Artificial Intelligence and Machine Learning. The Azure AI Fundamentals exam coverts topics such as AI/ML services available on Azure, natural language processing, computer vision, and even touches on some of the ethics and responsibilities of using AI/ML.

With many businesses continuing to adapt, integrate, or create their own AI technologies, there's quite a bit of demand for knowledge and expertise in this area. While this is just a foundational certification, I felt like the study material for the exam could serve as a nice introduction to how you can use Azure services for AI/ML.

Two cool AI tools I recently discovered are:

1. [sudowrite](https://www.sudowrite.com/)
2. [Writesonic](https://writesonic.com/)

##### sudowrite

Sudowrite is an application that uses AI/ML to help writers in creative ways. Some of the features are suggesting alternative words, sentences, character development, brainstorming, generating poems, and more. They also have a canvas mode feature that is really interesting.

##### Writesonic

Writesonic is another AI-powered writing application that helps with generating text, whether that be for blog posts, descriptions, rephrasing paragraphs, outlines, generating ideas, keywords, and much more. They even have a new feature, Photosonic, for generating Art.

Both of these tools have a **free** trial/tier. Feel free to try them out! Like with many other AI/ML tools, results may vary. I find that it takes quite a bit of nuance and experimentation with what parameters you give these tools in order to get the best outputs.

#### Next Steps

Like many other developers, I have an ongoing list of projects and ideas.

In the short-term, I will set my intentions on accomplishing these 3 things:

1. Create a link-tree inspired website
2. Create a blog website for my yoga offerings
3. Create a full-stack CRUD application

Thanks for reading, and I hope these ramblings and resources can be of some inspiration to you in your latest programming projects.

I'll continue to keep myself accountable and will check in again soon with progress in accomplishing these next 3 goals.

Hope your goals are going well!
