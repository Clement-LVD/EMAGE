---
header:
  navbar:
    enable: true
content: 
  page_type: landing
active: true
date: 2023-03-13
title: Contacts
type: landing
sections:

- block: markdown
  id: contact
  design: 
    spacing:
    # Customize the section spacing. Order is top, right, bottom, left.
      padding: ["40px", "0", "10px", "0"] 
    background:
      gradient_end: lightgrey 
      gradient_start: white
      gradient_angle: -180
  content:
      title: <hr> <br> Contactez E-MAGE consulting 
      text:    '<h1 style="color: navy; font-size: 40px;">  <div> 📧 {{< global_param "email" >}} </div> </h1> 
      
      <h1> <i class="fa fa-paper-plane" ></i>   Formulaire de contact </h1>
      
                 
                 <h3-little> <form name="contact" method="POST" data-netlify="true">
  <p>
    <label>Votre prénom et nom : <input type="text" name="name" /></label>
  </p>
  <p>
    <label>Votre email : <input type="email" name="email" /></label>
  </p> 
    <label>  <div> Vos besoins (vous pouvez indiquer plusieurs réponses<br> en maintenant "ctrl") : </div> <select name="role[]" multiple>
      <option value="analyse">   Analyse de données   </option>
      <option value="conseil">   Conseils</option>
      <option value="autre">   Autre</option>
    </select> </label> 
  <p>
    <label>Message : <textarea name="message"></textarea></label>
  </p>
  <p>
    <button type="submit">Envoi</button>
  </p>
  <br> Merci </h3-little>
</form>
                  '
 
--- 
  
           