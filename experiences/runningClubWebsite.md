---
layout: experience
title: UC Running Club Team Website
active: exp-website
---

<a href="https://runningclubwebsite.herokuapp.com/">
    <img src="/assets/website/websiteHome.png" style="width:80%" class="centered">
</a>
<br>
<br>
 &emsp;&emsp;Since my freshman year, I have been a part of the University of Cincinnati Running Club. Currently we use a Weebly website for our recruiting and Slack and Google forms to communicate to group members, so this website was created with the goal in mind of creating a hub that the running club can use to disseminate information as well as become a portal for all club activities. I used the club’s old website as a reference attempted to do everything that that website did in a more straight forward and visually appealing way, while also allowing club leadership to update information from an admin page rather than updating the static text on the screen. Where I believe this project fell short is that I was unable to implement sign ups, it is something I could do in the future but decided against it for the time being as I did not want to force users to share their information with a site that may not be secure.
<br>
<hr>
 <div style="display:flex">
    <div style="flex:3">
        <h2>Important Sites</h2>
    </div>
    <div style="flex:7">
        <div style="display:flex">
            <div style="flex:3">
                <p>Website</p>
                <p>Weebly Site</p>
                <p>Github</p>
            </div>
            <div style="flex:7">
                <a href="https://runningclubwebsite.herokuapp.com/"><p>runningclubwebsite.herokuapp.com</p></a>
                <a href="http://ucrunningclub.weebly.com/"><p>ucrunningclub.weebly.com</p></a>
                <a href="https://github.com/jakeocinco/RunningClubWebsite"><p>github.com/jakeocinco/RunningClubWebsite</p></a>
            </div>
        </div>
    </div>
 </div>
 <hr>
 <h2>Site Tour and Features</h2>

 <ul style="list-style-type:disc">
    <li> <p> Landing Page <a href="https://runningclubwebsite.herokuapp.com/">(https://runningclubwebsite.herokuapp.com/)</a></p>
    </li>
    <ul style="list-style-type:circle">
        <li>This page is very simple and at face value provides a quick run down of our running club, it offers a quick paragraph of general information as well as information on how to get involved. Below that it features a little bit of our social media as well as Vlog from our trip to Nationals in 2017. On the top right it also features a 'Contact Us' button, this is important as it provides any potential new members with a place to reach out to club leadership who will get back to them with info on how to join. Below that is a little bit of news to keep everyone updated with the recent accomplishments of the club.</li>
    </ul>
    <li> <p> News Page <a href="https://runningclubwebsite.herokuapp.com/news/">(https://runningclubwebsite.herokuapp.com/news/)</a></p>
    </li>
    <ul style="list-style-type:circle">
        <li>This page very simply shows a news feed of all of the articles that we have written after attending races and event. If you want to find events from specific months, you can use our archive panel on the right to open up those articles in their own page. You call also accomplish this by appending the url with either '/[four digit year]/' or '/[four digit year]/[two digit month]/' to get all articles from that year or that specific month. All of this content can be updated by administrators who update the 'Posts' model on the admin page.</li>
    </ul>
    <li> <p> Schedule Page <a href="https://runningclubwebsite.herokuapp.com/schedule/">(https://runningclubwebsite.herokuapp.com/schedule/)</a></p>
    </li>
    <ul style="list-style-type:circle">
        <li>This page features the club schedule in the coming season, it features the name of the event with the location and prospective start time. They are all ordered with the soonest event first. These can also be added by adding an entry to the 'Meet' model on the admin page. There administrators will also have the ability to add signup link which they can decide to show or hide at anytime.</li>
    </ul>
    
 </ul>