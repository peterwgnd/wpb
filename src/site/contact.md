---
title: Contact
layout: layouts/base.njk
---

Use the form below to get in touch with the web project team to request support or new features for consideration as part of our website overhaul.

<form name="contact" method="POST" data-netlify="true">
  <p>
    <label>Request support or a new feature <select name="request-type[]">
      <option value="support" selected>Support</option>
      <option value="feature request">Feature Request</option>
    </select></label>
  </p>
  <p>
    <label>Your Name: <input type="text" name="name" /></label>   
  </p>
  <p>
    <label>Your UNI: <input type="text" name="uni" /></label>
  </p>
    <p>
    <label>Page or Website URL: <input type="url" name="URL" /></label>
  </p>
  <p>
    <label>Message: <textarea name="message"></textarea></label>
  </p>
  <p>
    <label>Include screenshots, if relevant <input type="file" name="screentshots" accept=".jpg,.jpeg,.png,.gif"></textarea></label>
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
</form>