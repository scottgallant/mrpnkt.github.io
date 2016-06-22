---
title: Howto create a github/jekyll page with a few clicks
date: '2016-06-22 06:39:00'
categories: []
layout: post
slug: howto-create-a-github-jekyll-page-with-a-few-clicks
tags: []

---
![]({{ site.baseurl }}/forestryio/images/JekyllLogo.jpg)

In this first post I'm going to explain how to create a github page in three easy steps using Jekyll, the static page generator. If you don't want to go through the hassle of installing dozens of dependencies, pulling and pushing from your terminal this is one easy option to do it:

1.  Find a theme you like and clone the repository

Browse to http://jekyllthemes.org/ and find a theme you like. We'll choose http://jekyllthemes.org/themes/jekyll-resume/ for demonstration. Click on `Homepage` to get to the themes repository and fork it:

![]({{ site.baseurl }}/forestryio/images/2016-06-22 08_51_45-mattcouchman_jekyll-resume-1.png)

Once the theme is cloned to your github account, enter the Settings and change the Repository name to `your-username-here.github.io`

![]({{ site.baseurl }}/forestryio/images/2016-06-22 09_06_09-andilukas_jekyll-resume_-1.png)

2.  Sign up for the Forestry.io-beta and import your repository

![]({{ site.baseurl }}/forestryio/images/2016-06-22 08_57_36-Forestry.io.png)

Once you receive the invite log in to your [forestry.io](https://forestry.io/) account and click `+Add Site` and add from github:

![]({{ site.baseurl }}/forestryio/images/2016-06-22 09_16_09-Forestry.io.png)

Click through the options and select the branch you want to deploy to. Save your settings and you're done setting up the site in forestry:

![]({{ site.baseurl }}/forestryio/images/2016-06-22 09_17_49-Forestry.io.png)

3.  Your site will show up in the `My Sites` section of the dashboard. Use the `Edit content` button to add and edit pages and posts

![]({{ site.baseurl }}/forestryio/images/2016-06-22 09_29_43-Forestry.io-1.png)