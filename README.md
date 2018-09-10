# Reveal.js Presentation Template

This repository contains my template for presentations.
I build my presentations with Reveal.js, a framework
for building web-ready presentations in HTML. [Check out the live demo of Reveal.js](http://revealjs.com/). I then host them on Github Pages, making them available to users without having to ship Powerpoint files around.

More details on how I did it: [Building Web-Ready Slideshows With Reveal.js](https://lisawilliams.github.io/lisa/tech/2018/03/04/reveal-js-slideshows.html).

I relied on Chen Hui Jing's [excellent tutorial on doing slide decks in Reveal.js](https://www.chenhuijing.com/blog/revealjs-and-github-pages/#%F0%9F%91%9F) to get started.

## Instructions

Click "Clone or Download" and then click "Download As Zip."  Place the .zip file in the directory you want it in, and then unzip it. Rename the folder to the name of your presentation.

At the command line, switch into the newly renamed directory and run `npm install`. This will download all the packages listed in package.json.

To see your deck locally, run `grunt serve` at the command line. You will be able to see your presentation at `http://localhost:8000/` in a web browser.

### Hosting using Github Pages

If you want your presentation on the web and you have a Github account, make a new repository on Github.com and follow the instructions to connect your local directory to Github. When you have pushed your changes up to Github, click Settings and scroll down to the part where it talks about Github Pages. Enable publishing for the branch you worked on and wait a minute -- pretty soon you'll have a web accessible version of your presentation that will update every time you push changes to Github. For a step by step tutorial, see the link above. 
