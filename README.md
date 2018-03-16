# Alexa, ask React Rally what's up next?
Giving React a Voice

## Abstract
Whether it's Deep Thought, Hal 9000, or Jarvis, our vision of the future has always been about using our voice to control technology. And now, with Google Assistant, Siri, and Alexa, that future is closer than ever. So how can we, as React developers, play our part in shaping this future? See how I used React and a custom renderer to build an Alexa voice skill to enchance the React Rally experience.

## Details
I'm going to build a custom React renderer that lets developers define an Alexa Skill using React and JSX. It will use the Alexa Skills Kit SDK for Node.js under the hood. Then I plan to build a voice skill specifically for React Rally that will allow attendees to ask about the day's schedule, get more info on a speaker, and more. (Might need some help pulling this data from some kind of endoint but site scraping and hard-coding would work as well.) For the talk, I want to bring an Amazon Echo up on stage and have it say hello to everyone and introduce my talk. I'll give a brief history about the progression of voice technologies. Then I'll show off the skill and talk about how I built it. If the wifi gods are in a good mood I'll be able to test the skill live using the Echo. Alternatively, I can tether to my phone and use the online Alexa simulator.

## Pitch
When I first got an Amazon Echo I knew immediately that I wanted to build a skill for it. So I came up with an idea, researched how to code up a skill in JS and got to work. (At the time, the Alexa Skills Kit SDK for Node.js was still in its infancy.) When I was finally done, I enabled the skill on my Echo and as my son called out, "Alexa, ask the lunch lady what's for lunch?", I eagerly awaited her reply. Alexa responded in turn, spouting off the items on the school lunch menu for that day as I marvelled at what I had built.

Fast forward to today, the Alexa Skills Kit SDK for Node.js is officially released and makes building Skills super easy. But being a React developer I wanted to explore the idea of building a Skill using React. With projects like redocx, react-pdf, and react-slack-renderer as references, I'll build a React voice renderer. The initial goal is to use it to build a skill for Alexa but longer term it could be made to support other platforms, like Google Assistant. Thus leveraging one of the main benefits of React, write once and share the code accross devices and platforms.

I'm a huge fan of voice technologies and how far they've come. The way we use our voices to interact with each other every day is a natural part of life. I believe using our voices to interact with technology is slowly becoming just as natural. Whether it's saying "I'm home" to turn on the house lights or "it's TV time" to lower the shades and settle in to watch a movie, I often think to myself, "Wow. We live in the future." And I think we as developers need to understand the importance in building this future and in exploring new ways to open up the experience to more of the community.

This talk would be my first conference talk which is both terrifying and exciting. I sat in the audience at last year's conference and came away feeling incredibly inspired. It made me want to get more involved in the community and push myself to try new things. I decided this year I want to pay it forward and hopefully inspire someone else to do the same.

## Bio
Some info about me goes here.
