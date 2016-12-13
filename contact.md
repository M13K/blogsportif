---
layout: page
title: Contact
permalink: /contact/
---

Vous pouvez me contacter pour des questions, soumettre des exercices ou autres.
Il vous suffit pour cela de remplir le formulaire qui suit : 

<div class="form">

<form id="contactform" method="POST">
    <p><input type="text" name="name" placeholder="Your name"></p>
    <p><input type="email" name="_replyto" placeholder="Your email"></p>
    <p><input type="hidden" name="_subject" value="Website contact" /></p>
    <p><textarea name="message" placeholder="Your message" rows="10" cols="50" style="width: 410px; height: 197px;"></textarea></p>
    <p><input type="text" name="_gotcha" style="display:none" /></p>
    <p><input type="submit" value="Envoyer"></p>
</form>
</div>

<script>
    var contactform =  document.getElementById('contactform');
    contactform.setAttribute('action', '//formspree.io/' + 'malikalmo' + '@' + 'gmail' + '.' + 'com');
</script>
