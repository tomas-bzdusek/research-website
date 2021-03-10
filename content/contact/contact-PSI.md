---
# An instance of the Contact widget.
# Documentation: https://wowchemy.com/docs/page-builder/
# widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 15

title: PSI Contact
# subtitle:

# content:
  # Automatically link email and phone or display as text?
#  autolink: true
  
  # Email form provider
#  form:
#    provider: netlify
#    formspree:
#      id:
#    netlify:
#      # Enable CAPTCHA challenge to reduce spam?
#      captcha: true

# design:
#  columns: '1'
---


<div class="section-heading col-12 mb-3 text-center"><h1 class=mb-0>Contact</h1></div><div class=col-12><p>You can reach me via the following form, or using the contact information appended below.</p><div class=mb-3><form name='contact' method='post' data-netlify-recaptcha='true'><input type='hidden' name='form-name' value='contact' /><div class="form-group form-inline"><label class=sr-only for=inputName>Name</label>
<input type=text name=name class="form-control w-100" id=inputName placeholder=Name required></div><div class="form-group form-inline"><label class=sr-only for=inputEmail>Email</label>
<input type=email name=email class="form-control w-100" id=inputEmail placeholder=Email required></div><div class=form-group><label class=sr-only for=inputMessage>Message</label>
<textarea name=message class=form-control id=inputMessage rows=5 placeholder=Message required></textarea></div><div class=d-none><label>Do not fill this field unless you are a bot: <input name=welcome-bot></label></div><div class='form-group'><script src='https://www.google.com/recaptcha/api.js'></script>
<div class='g-recaptcha' data-sitekey='6LdAvUIUAAAAAHjrjmjtNTcXyKm0WKwefLp-dQv9'></div>
<noscript>
  <div>
  <div style="width: 302px; height: 422px; position: relative;">
  <div style="width: 302px; height: 422px; position: absolute;">
  <iframe src="https://www.google.com/recaptcha/api/fallback?k=6LdAvUIUAAAAAHjrjmjtNTcXyKm0WKwefLp-dQv9" frameborder="0" scrolling="no"
    style="width: 302px; height:422px; border-style: none;">
  </iframe>
  </div>
  </div>
  <div style="width: 300px; height: 60px; border-style: none; bottom: 12px; left: 25px; margin: 0px; padding: 0px; right: 25px; background: #f9f9f9; border: 1px solid #c1c1c1; border-radius: 3px;">
    <textarea id="g-recaptcha-response" name="g-recaptcha-response" class="g-recaptcha-response"
      style="width: 250px; height: 40px; border: 1px solid #c1c1c1; margin: 10px 25px; padding: 0px; resize: none;" >
    </textarea>
  </div>
  </div>
</noscript>
</div><button type=submit class="btn btn-outline-primary px-3 py-2">Send</button></form></div><ul class=fa-ul><li><i class="fa-li fas fa-envelope fa-2x" aria-hidden=true></i><span id=person-email><a href=mailto:tomas.bzdusek@uzh.ch>tomas.bzdusek@uzh.ch</a></span></li><li><i class="fa-li fas fa-phone fa-2x" aria-hidden=true></i><span id=person-telephone><a href=tel:+41%2044%2063%2055750>+41 44 63 55750</a></span></li><li><i class="fa-li fas fa-map-marker fa-2x" aria-hidden=true></i><span id=person-address>Y36 J34, Winterthurerstrasse 190, Zürich, 8057</span></li><li><i class="fa-li fas fa-clock fa-2x" aria-hidden=true></i><span>9:00 to 17:30 Monday to Friday</span></li><li><i class="fa-li fas fa-calendar-check fa-2x" aria-hidden=true></i><a href=https://tomasbzdusek.youcanbook.me/ target=_blank rel=noopener>Book an appointment</a></li></ul><div class=d-none><input id=map-provider value=mapnik>
<input id=map-lat value=47.3980024>
<input id=map-lng value=8.5504917>
<input id=map-dir value="Y36 J34, Winterthurerstrasse 190, Zürich, 8057">
<input id=map-zoom value=15>
<input id=map-api-key value></div><div id=map></div></div></div></div></section>
