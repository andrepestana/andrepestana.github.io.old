---
title: Projects
permalink: /projects/
layout: page
excerpt: Some of my personal projects
comments: false
---
# NodeJS auth api + VueJS auth frontend
![alt text](/projects/vue_auth1.png "VueJS Auth Frontend signin"){:height="200px"} ![alt text](/projects/vue_auth2.png "VueJS Auth Frontend user session"){:width="400px"} 
{: style="text-align: center"}

This is a api for authentication and authorization with NodeJS. This api has the following features:
- signup (creates a new user for the application)
- signin (authenticates and creates a session through Jason Web Token (jwt))
- persistent session in the browser (if the user closes the browser and reopen their session is still ok until the token expiration)
- user email confirmation (user needs to confirm their email for the application to trust them)
- change password (an authenticate user can change their password any time)
- list all sessions for the current user (an authenticate user can see all their current sessions)
- logout from sessions in other devices (logs out any current session from the current one)
- recover lost password through email with link to change password (the user can ask for a link sent to their email to change password)

Source code: 
- Api: <https://github.com/andrepestana/nodejs_auth>
- Frontend: <https://github.com/andrepestana/vue_auth>

Live demo: 
- <http://138.197.154.122/>

* * *

# Chuck Norris Jokes

![alt text](/cn/phone.jpg "Chuck Norris Jokes app on phone"){:height="300px"} 
{: style="text-align: center"}

This is a Quasar Framework project. Quasar is a framework based on VueJS that helps you build websites, mobile and desktop applications. In this project I just created a mobile application. The application consumes a free api: [The Internet Chuck Norris Database](http://www.icndb.com/api/){:target="_blank"}

You can check it out on Google Play Store:

<a href='https://play.google.com/store/apps/details?id=com.github.andrepestana&pcampaignid=pcampaignidMKT-Other-global-all-co-prtnr-py-PartBadge-Mar2515-1'><img alt='Get it on Google Play' src='https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png' style="height:100px;" /></a>
{: style="text-align: center"}

Google Play and the Google Play logo are trademarks of Google LLC.
{: style="text-align: center"}

* * *
  
  
# Pestana World

[![alt text](/projects/pestana_world.png "Pestana World"){:height="300px"}](/pestana-world/)
{: style="text-align: center"}

It's just a simple arcade game I started developing to learn [Phaser3](https://phaser.io/phaser3) and have some fun. Phaser 3 is a javascript framework and it makes development really fun. [Click here to play](/pestana-world/)

