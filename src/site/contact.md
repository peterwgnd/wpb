---
title: Contact Us
layout: layouts/base.njk
---

Use the form below to get in touch with the web project team to request support or new features for consideration as part of our website overhaul.

<form name="contact" method="POST" data-netlify="true">
  <p>
    <label for="request-type">What can we help you with?</label>
    <select name="request-type" id="request-type">
      <option value="support" selected>Support</option>
      <option value="feature request">Feature Request</option>
      <option value="information">General Information</option>
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
    <label for="screenshots">Include screenshots, if relevant</label>
    <input type="file" name="screenshots" id="screenshots" accept=".jpg,.jpeg,.png,.gif" multiple>
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
</form>