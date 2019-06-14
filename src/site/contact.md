---
title: Contact Us
layout: layouts/page.md
description: Get in touch with Columbia Business School’s Web Project Team.
---

Use the form below to get in touch with the web project team to request support or new features for consideration as part of our website overhaul.

<form name="contact" method="POST" data-netlify="true">
  <p>
    <label for="request-type">What can we help you with?</label>
    <select name="request-type" id="request-type">
      <option value="support" selected>Support</option>
      <option value="feature request">Feature Request</option>
      <option value="feedback">General Feedback</option>
    </select>
  </p>
  <p>
    <label for="name">Name</label>
    <input type="text" name="name" id="name"/>
  </p>
  <p>
    <label for="uni">UNI</label>
    <input type="text" name="uni" id="uni" />
  </p>
  <p>
    <label for="url">Page or Website URL</label>
      <input type="text" name="URL" id="url" />
  </p>
  <p>
    <label for="message">Message</label>
    <textarea name="message" id="message"></textarea>
  </p>
  <p>
    <label for="screenshots">Include a screenshot, if relevant</label>
    <input type="file" name="screenshots" id="screenshots" accept=".jpg,.jpeg,.png,.gif">
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
</form>