---
layout: page
titlebar: true
ft-image: ''
title: Contact [beta]
customTitle: Samenwerken?
subTitle: Laat een berichtje achter
permalink: Contact-beta
add-to-menu: true
fullWidth: false
short-desc: ''
pageWidgets:
- template: widget-page
  buttonShow: true
  title: Mail me
  subtitle: Direct mailen
  body: Antwoord binnen een paar uur tot 2 dagen
  buttonLabel: Mailen
  buttonHref: hello@lennertderyck.be?subject=Hallo!
- template: widget-page
  buttonShow: true
  title: Linked In
  subtitle: Zakelijk
  body: Antwoord binnen een paar uur
  buttonLabel: Linked In
  buttonHref: https://www.linkedin.com/in/lenndertderyck/
- template: widget-page
  buttonShow: true
  title: Messenger
  body: Antwoord binnen een paar uur
  subtitle: Let's have a chat
  buttonHref: https://www.messenger.com/t/1997323257173637
  buttonLabel: Messenger

---

<div class="row">
  <div class="col-12">
    <form action="https://forms.lennertderyck.be/setup/process.php" method="post" id="formContact">
      <input type="hidden" name="form_tools_form_id" value="5" />
      <div class="form-group mb-4">
        <label for="contactFormName">naam</label>
        <input type="text" name="name" class="form-control" id="contactFormName" placeholder="Fons Van Calleberghe">
      </div>
      <div class="form-group mb-4">
        <label for="contactFormEmail">email</label>
        <input type="email" name="email" class="form-control" id="contactFormEmail" placeholder="willyfons@gmail.com">
      </div>
      <div class="form-group mb-4">
        <label for="contactFormCompany">organisatie / bedrijf</label>
        <input type="text" name="org" class="form-control" id="contactFormCompany" placeholder="Planeet Jamaica">
      </div>
      <div class="form-group mb-4">
        <label for="contactFormSubject">onderwerp</label>
        <input type="text" name="subject" class="form-control" id="contactFormSubject" placeholder="Zalmtoastjes en Orvallekes">
      </div>
      <div class="form-group form-control-textarea">
        <label for="contactFormMessage">bericht</label>
        <small class="d-block mb-3 fontw-700"><i class="fab fa-markdown"></i><span class="ml-1">Markdown ondersteund</span></small>
        <textarea class="form-control" name="message" id="contactFormMessage" rows="2"></textarea>
      </div>
      <!-- <input class="btn" type="submit" value="Submit"> -->
      <!-- <a class="btn" href="#">verzenden</a> -->
      
      <button type="submit" class="btn" form="formContact" value="Submit">verzenden</button>
    </form>
  </div>
</div>