---
title: Low Carb, High Fat
toc: true
toc_sticky: true
layout: single 
permalink: /lchf
author_profile: true
excerpt: "Many ask me if I’ve lost weight. I have and here’s how."
categories:
  - lchf
header:
  overlay_image: /assets/images/pork-rinds.jpg
  overlay_filter: 0.5 # same as adding an opacity of 0.5 to a black background
  caption: "Delicious pork rinds, awaiting mastication"
---
{% include figure image_path="/assets/images/before-after.png" alt="Before and after photo" caption="Me, June 2016, left and September 2018, right" %}

## Summary

For the last umpteen years if not decades, nutritionists have poorly advised us, or, most certainly me, critically so. By ignoring this mainstream nutritional advice, the food pyramid, and other common myths about what’s healthy, I’ve been able to lose weight, keep it off, and increase my health markers, a.k.a. a low carbohydrate, high fat diet, or LCHF.

I will endeavor to keep this page as inclusive and salient to my experience on the LCHF way of eating.

## Introduction

Many people have been very kind, commenting on my weight-loss. Most commonly, I hear; “You look great! You must be hitting the gym pretty hard?” My answer is, it’s not the gym. I’ve been hitting the gym “pretty hard” for at least a decade, if not longer. I started my running habit in college, back in 1982. In my youth, exercise seemed helpful for weigh-management. However, as I aged, my amount of exercise ceased to benefit my weight management.

I have been overweight my whole life. The term in the 70’s for us overweight teens was “husky.” Since then, I’ve been on nearly every diet, from Weight-Watchers, Shaklee, Nutrisystem, Jenny Craig, South Beach, standard calories-in, calories-out diets, Atkins, to, finally, LCHF. 

## It Begins

In the spring of 2016, after my yearly checkup, my general practitioner had noted on my chart that I was obese, with a latin term that meant “belly fat.” My weight was 285. “What should I do?” I asked. His prescription was essentially mirroring all the failed advice I listed above. Nevertheless, I was resolved to chip away at this problem with renewed zeal. That summer, I tracked what I ate closely. I tried reducing sugar but ate robust amount of “healthy” starches, such as corn or whole wheat. I dramatically increased protein, most usually by way of protein-whey shakes. I saw moderate weight loss, 20 pounds, but the holiday triumvirate of Thanksgiving, Christmas and New Year’s Day cause my weight number to stall and then increase into January and February.

One day, while incidentally checking out the official [Duke University](https://www.youtube.com/user/Duke "Duke University YouTube video channel") video feed, I found a presentation featuring Dr. Westman, giving a talk on [“The Science and Practice of Low Carb Diets.”](https://www.youtube.com/watch?v=toLvGpk3HLE "Dr Westman presents on LCHF") I had done Atkins with great weight-loss success, only the maintenance part failed to the point of complete remission. What if I had the help of a doctor? I asked for, and got, a referral from my GP to see Dr. Westman.

## The Road to Damascus

On June 8th, 2017, I started LCHF, under the direction of Dr. Eric Westman of Duke University. His method is both radical and simple. He flips the food pyramid upside-down, with his “page four” guidance. He hands us patients a list of what foods to eat, and in what quantities, per day. Stick below 20 total grams of carbohydrates.

I find great value in his simplified approach. He eschews macro-counting. While there’s a lot of exciting research, analysis and testing around all this, all the details can make this wealth of information, sometimes self-conflicting, dispiriting for the neophyte.

## Stasis, homey

I love this way of eating, and despise all the lies that have messed up an entire nation’s culture and understanding on something as essential and basic as food. This is the longest time I’ve remained below 225 pounds, and I’m only getting started.

I have seen a lot of wrinkles, hiccups, delights, failures, along the way, and I’ll be sharing my experiences on this blog. I expect to continually update this page, refining it to reflect my evolving understanding of the science and art of LCHF.

I came for the weight-loss and found a healthier way of living.

## Resources

### Websites

* Dr. Eric C Westman’s [ Scholars@Duke profile ](https://scholars.duke.edu/person/ewestman "Dr Westman's Scholars at Duke profile page")
* Dr. Westman's [Heal Clinics](https://healclinics.com/ "Heal Clinics home page") initiative.
* Dr. Westman's [Facebook group](https://www.facebook.com/groups/DukeLowCarbSupportGroup "Dr. Westman's facebook group page") page.

## My most recent LCHF-related posts

<div class="relatedPosts">
  
{% assign maxRelated = 8 %}
{% assign minCommonTags =  1 %}
{% assign maxRelatedCounter = 0 %}

{% for post in site.posts %}

    {% assign sameTagCount = 0 %}
    {% assign commonTags = '' %}

    {% for category in post.categories %}
      {% if post.url != page.url %}
        {% if page.categories contains category %}
          {% assign sameTagCount = sameTagCount | plus: 1 %}
          {% capture tagmarkup %} <span class="label label-default">{{ category }}</span> {% endcapture %}
          {% assign commonTags = commonTags | append: tagmarkup %}
        {% endif %}
      {% endif %}
    {% endfor %}

    {% if sameTagCount >= minCommonTags %}
      <div>
      <p><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}{{ commonTags }}</a></p>
      </div>
      {% assign maxRelatedCounter = maxRelatedCounter | plus: 1 %}
      {% if maxRelatedCounter >= maxRelated %}
        {% break %}
      {% endif %}
    {% endif %}

  {% endfor %}

</div>
