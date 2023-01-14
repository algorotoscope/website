---
published: true
layout: works
title: Rebuilding the Texture Transfer ML Process
date: 2023-01-14T12:00:00.000Z
tags:
  - Models
  - Machine Learning
  - Amazon Web Services
  - Texture Transfer
image: >-
  https://s3.amazonaws.com/kinlane-productions2/algo-rotoscope/stories/markets/feed-the-people-economics.jpg
---
I had an AWS machine image that had my texture transfer process all setup. I had my AWS account compromised and someone spun up servers across almost every AWS region—my bill was pushing $25K. Luckily it was due to anything I had done and AWS didn’t charge me for any of it. However, in the shuffle from that account to a new API Evangelist specific account, my AWS machine image got lost—forcing me to have to rebuild from scratch. It is always a daunting thing to dive back into the world of TensorFlow and machine learning, but I finally made time over this last holidays season. 

I am using [lengstrom/fast-style-transfer](https://github.com/lengstrom/fast-style-transfer) for my texture transfer process. It really isn’t that hard to implement, but every time there is some learning curve around getting the server setup, all the TensorFlow libraries properly setup, and he keeps updating his process. This round I see he is using Jupiter Notebooks, which I am not that interested in using, so I beat my own path forward. I am glad I did it one more time because there are a number of libraries I had to find from Archive.org to get to work, but finally I ended up with a working implementation. This time I have backed up on S3, and a local location. Ensuring that even if I lose my AMI I won’t lose the whole approach, cause I don’t think I will be able to rebuild again. The web is fragile that way. Not all of this is due to technical fragility, it is due to business fragility, disposability, and velocity. 

Like many things, this approach to doing texture transfer will fall victim to what is next. You already see this happening with MidJourney and Dall-E approaches to images ML. It is compelling, exciting, and superior to what came before. I am just going to fork what is and keep applying in my own way off over here in this cul-de-sac. I’ll pay attention to what is new, cause I can’t help it, but I will also be experimenting with what was. For me, the layer of expression uses this particular ML model, but also a mix of textures and photos to find the sweet spot. Honestly, this sweet spot varies depending on what my mood is, how I am feeling about the world, and whether I have the money to create a new model or experiment with  the ones I already have.