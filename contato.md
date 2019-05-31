---
id: 47
title: Contato
date: 2019-03-05T14:31:02-03:00
author: PGANME
layout: page
guid: http://imersive.tech/?page_id=47
slide_template:
  - ""
---

<style>

input[type=text] {
  width: 100%;
  padding: 12px 20px;
  margin: 8px 0;
  box-sizing: border-box;
}

input[type=email] {
  width: 100%;
  padding: 12px 20px;
  margin: 8px 0;
  box-sizing: border-box;
}

input[type=submit] {
  z-index: 1;
  position: relative;
  font-size: inherit;
  font-family: inherit;
  color: white;
  padding: 0.5em 1em;
  outline: none;
  border: none;
  background-color: hsl(236, 32%, 26%);
  overflow: hidden;
  transition: color 0.4s ease-in-out;
}

input[type=submit] {
    padding:5px 15px; 
    background:#ccc; 
    border:0 none;
    cursor:pointer;
    -webkit-border-radius: 5px;
    border-radius: 5px; 
}

textarea {
  width: 100%;
  height: 150px;
  padding: 12px 20px;
  box-sizing: border-box;
  border: 2px solid #ccc;
  border-radius: 4px;
  background-color: #f8f8f8;
  resize: none;
}

</style>

<div role="form" class="wpcf7" id="wpcf7-f50-o1" lang="pt-BR" dir="ltr">
  <div class="screen-reader-response">
    <form action="https://formspree.io/pganme@gmail.com" method="POST">
      <p><label for="name">Your Name:</label>
      <input type="text" name="name" id="name"></p>
      
      <p><label for="email">Your Email:</label>
      <input type="email" name="_replyto" id="email"></p>

      <p><label for="message">Your Message:</label>
        <textarea name="message" id="message"></textarea></p>

      <p><input type="submit" value="Send"></p>
    </form>
  </div>
</div>