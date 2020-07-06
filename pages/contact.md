---
layout: page
title: "Contact"
description: "Please use the form below to contact us. Don't forget to enter your name and email in the message box"
date: "2020-06-10"
permalink: "/contact/"
id: "contact"
---
Please use the form below to contact us. Don't forget to enter your name and email in the message box.<br>

<div class="container">
  <form action="{{site.url}}{{page.url}}/"  autocomplete="off">
    <label for="fname">Name</label>
    <input type="text" id="fname" name="name" placeholder="Name..">

    <label for="lname">E-mail</label>
    <input type="text" id="lname" name="mail" placeholder="E-mail..">



    <label for="subject">Subject</label>
    <textarea id="subject" name="subject" placeholder="Subject.." style="height:200px"></textarea>

    <input type="submit" value="Submit">
  </form>
</div>