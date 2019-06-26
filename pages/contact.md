---
layout: misc
title: Contact Erosion QLD
description: Contact form for email
---

<form id="contactform" method="POST">
    <input cols="30" type="text" name="name" placeholder="Your name"><br />
    <input cols="30" type="email" name="_replyto" placeholder="Your email"><br />
    <input type="hidden" name="_subject" value="Website contact" />
    <textarea cols="30" rows="5" name="message" placeholder="Your message"></textarea>
    <input type="text" name="_gotcha" style="display:none" />
    <input type="submit" value="Send">
</form>
<script>
    var contactform =  document.getElementById('contactform');
    contactform.setAttribute('action', '//formspree.io/' + 'evan.millwood' + '@' + 'gmail' + '.' + 'com');
</script>