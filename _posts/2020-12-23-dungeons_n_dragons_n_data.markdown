---
layout: post
title:      "Dungeon's 'n Dragons 'n Data"
date:       2020-12-23 16:39:01 +0000
permalink:  dungeons_n_dragons_n_data
---



My application (called DnD-Gen) lets a user add to a list of weapons that could be used in any tabletop gaming format. (However, one could use it to keep track of their equipment from anywhere - my individualized example is weapons for their character in Dungeons and Dragons.)

The user can go through the weapons created at the bottom of our page, as well as add their own ideas that will be automatically posted to the bottom, along with their ID number and equipment ID number. (A weapon belongs_to the equipment category of either Spooky, Scratchy, or Splendid.)

The code was created so that if I, in the future, wanted to add my stretch goal of being able to seed data from the Dungeons and Dragons API, it would let me. Therefore, I kept their exact wording in mind while forming the variables, in order to keep that option open.

The other stretch goals I would like to add in the future is more customization (adding the character's name it belongs to in order to search through each character), and the ability to add users (in order to streamline the data, and what comes up for each player). 

------

This project has an HTML/ CSS/ Javascript frontend with a Rails API backend. It also has the has_many relationship between weapons and equipment (equipment has_many weapons, as can be seen by the equipment ID in the weapon model). The user can create and read for the weapons, and read for the equipment, covering the 3 AJAX calls - as well as fetch requests through the javacript code. 
