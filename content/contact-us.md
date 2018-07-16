---
title: "Contact Us"
date: 2018-07-13T04:05:26+01:00
draft: false
---
<style>
    label {width:20px;}
    input {width:300px;}
</style>
<form name="contact" method="POST" netlify>
  <p>
    <label>Name: <input type="text" name="name" /></label>   
  </p>
  <p>
    <label>Email: <input type="email" name="email" /></label>
  </p>  
  <p>
    <label>Message: <textarea name="message" rows=5 cols=50></textarea></label>
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
</form>