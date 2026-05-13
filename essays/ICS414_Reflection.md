---
layout: essay
type: essay
title: "ICS 414 Reflection"
# All dates must be YYYY-MM-DD format!
date: 2026-05-13
published: true
labels:
  - ICS 414
  - JavaScript
  - HTML
  - CSS
  - Software Engineering
---

## The Brief
This is my reflection on ICS 414: Software Engineering II.
We were tasked with working on a project for the duration of our semester. For us, this meant building off an existing project from previous students and rewriting it with our desired functional changes. Most of our time was spent deciphering the code from the existing project and figuring out how to implement new functions or modify those that were already implemented. Communication with my team was held over Discord, where we kept each other up-to-date on our CI/CD Github pipeline. Conflicts in Github were very rare, and things went pretty smoothly overall. How lucky!!

## My Contributions
I was responsible for several of the technical sides of our Shelf Awareness website's UI. My goal was to make using the website a more intuitive and receptive experience for the average user. What I first did was update a few pages on the website so that if the user would create or modify an entry on said page, it would update upon submission and be reflected on-screen immediately in real time than require a page refresh. I also added filters to the search functions of some pages, and made user data from certain pages accessible in other pages so that I could add more functions which were capable of referencing the user's data and using it to modify some other data belonging to the user, within the same page.

<div class="text-center p-4">
  <video width="900" controls>
    <source src="../img/SJB/demo1.mp4" type="video/mp4">
  </video>
</div>

You'll see me select a Philip Johnson card to offer into a Marketplace. In exchange, I request a Scott Robertson card. That is to say, I'm offering, to the market, one of my Philip Johnsons. And, in exchange, my request is that the other user gives me one of their Scott Robertsons. The information needed for the user while they're making their trade request is a must. How many copies of their cards do they have? If unknown, they'll be hesitant to trade at all considering said card might be their only copy. Which card(s) are they missing? Ideally, wouldn't they want to receive a card they have 0 copies of? Users should get a look at their card collection before they trade, but displaying a massive window with said collection might be too jarring, so let's make it smaller. But then, how will the user know they've selected the right card to trade when they're all so tiny? Alright, we'll display a zoom-in on the right to ensure the user knows what card they've chosen.

And on top of that, the popup's display text! Users should always be aware of the cards they've selected, so let's show their names on screen. Let's make it obvious which card they're "giving away" and which card they'd like to receive "in exchange" via a text-based confirmation alongside a visual one so that the user can trade with full assurance that their selections are intended. My goal with this entire spiel was to make this screen "obvious". There shouldn't be any fear of the uncertain or unknown in such a simple process, so I always thought to myself: "What if this was my first time doing <i>anything</i>?"

## Functional Programming
My second most favorite part of this semester came from elements of functional programming. There's still so much that I don't understand about Software Engineering safe practices and basic mechanics that I can't proclaim at all that I've truly experienced functional programming, but I've enjoyed what little I've been able to achieve so far. There was a lot of variable passing and inheritance between programs, ergo, giving other functions data using the data generated or defined in prior functions, even between different files, that was present in my last couple weeks of coding that I hadn't done at all in previous months during class. I likely bit off more than I could chew, but that sense of being tossed into the pool and forced to swim lit a fire under me that acted as crucial motivation during these final weeks.

## Conclusion
All in all, what I'm left wondering is what exactly the classes ahead of this one teaches. Are there more basics to learn? Will we now enter the path of specialization and branch off into different skill sets? In terms of now versus then, I'm a lot more confident in being able to pass this course with a much higher score if I take it again. But that doesn't translate into sheer mastery over the course contents. However, what I've got now is a good pace. Best that I keep it going 'lest my learnings atrophy.

