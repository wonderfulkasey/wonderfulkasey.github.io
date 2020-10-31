---
layout: post
title:      "Rails Search Bar"
date:       2020-10-31 13:46:02 +0000
permalink:  rails_search_bar
---


In order to pass my third assessment at Flatiron School, I had to build a working search bar function in my world-creator application, called Worlding. The two pages I worked in were my WorldsController and the index page within my Worlds’ views. 

Within the controller, I made sure that the params included what I would be searching, which was the World’s name. Since I used that param in order to build the actual Worlds, it was all set to go. Afterward, I go to my Index action and add an if/else statement - this makes it so if the user is not searching for any specific world, they can still see the full list of worlds available. 

On the index page I make the actual search bar - I used the form_tag in order to generate the bar, and put in the methods (including ‘get’) that would show my actual search results on the page. Some ways to build the search bar include creating a separate results page, however since I wanted everything to be shown within the index page, that was an unneeded step. 

