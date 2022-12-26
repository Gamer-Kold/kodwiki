# kodwiki
A minimalist tiddlywiki spin for productivity and knowledge management.

This wiki is what I've comfied up into as I (re) set up a proper workspace for knowledge management. The main motivator behind the overhaul is that I tried Obsdian for a little while and while I didn't end up sticking with it; it's design choices made me reconsider my approach to knowledge management.

## Features
* Autocompletion of tiddler titles
* A self-written writing inbox that uses spaced repitition (written completely in wikitext to prove a point)
* Contexual Backlinks; so you can see the relationships between your notes in context.
* A kanban board for project management

And probably some other stuff that I have forgotten about.

## Points to Note
* This is very much intended to be used as nodejs wiki; it doesn't _have_ to be. But several design choices become less _convincing_ in a single file enviroment. Such as, for example, the Markdown by default philosophy; intended to make export to other software easier, doesn't really help in a single file wiki.
* Dark palletes don't really play well with Muuri; which makes the default story layout and the kanban boards; well retina-searing. I don't really have a problem with this as SolarizedLight, Blue and DesertSand are more than dark enough to not sear my retinas while still working well with Muuri.

## Installation 

### For a Single File
* Go to https://gamer-kold.github.io/kodwiki/
* Click on the install button shown in Getting Started Tiddler / Click on the checkmark on the side bar
* A copy of the wiki should download as an html

### For Node.js
* Install tiddlywiki from npm
* Clone this repo
* Navigate to the repo's folder in a terminal
* Run `tiddlywiki . --listen`
* You should be able to access to your wiki by visiting `https://127.0.0.1:8080`
