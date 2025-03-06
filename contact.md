---
layout: layouts/pagewithpic.njk
picture: /img/angel2-cropped.jpg
title: Contact
---
Please use the contact form if you are curious about or wish to book a session, or book a time to meet up in person to discuss options, if that is more comfortable for you.

<form action="https://formspree.io/f/{form_id}" method="post">
  <div class="form-group">
    <label for="name">Name</label>
    <input class="form-control" name="Name" id="name" type="text" placeholder="Name">
  </div>

  <div class="form-group">
    <label for="email">Email</label>
    <input class="form-control" name="Email" id="email" type="email" placeholder="Email">
  </div>

  <div class="form-group">
    <label for="help">How Can I Help?</label>
    <textarea id="help" rows=4 class="form-control"
              placeholder="What are you looking for/curious about?"
              ></textarea>
  </div>

  <div class="form-group">
    <label for="questions">Questions/Concerns</label>
    <textarea id="questions" rows=4 class="form-control"
              placeholder="Do you have any other questions or concerns?"
              ></textarea>
  </div>

  <div class="form-group">
    <button style="width:100%;" class="btn btn-primary mb-2" type="submit">Contact Me</button>
  </div>
</form>
