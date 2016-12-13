---
layout: page
title: Contact
permalink: /contact/
---

Vous pouvez me contacter pour des questions, soumettre des exercices ou autres.
Il vous suffit pour cela de remplir le formulaire qui suit : 

<div class="form">

<form id="contactform" method="POST">
    <input type="text" name="name" placeholder="Your name">
    <input type="email" name="_replyto" placeholder="Your email">
    <input type="hidden" name="_subject" value="Website contact" />
    <textarea name="message" placeholder="Your message"></textarea>
    <input type="text" name="_gotcha" style="display:none" />
    <input type="submit" value="Send">
</form>
</div>

<script>
    var contactform =  document.getElementById('contactform');
    contactform.setAttribute('action', '//formspree.io/' + 'malikalmo' + '@' + 'gmail' + '.' + 'com');
</script>
