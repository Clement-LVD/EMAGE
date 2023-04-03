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
      title: <br> Contactez E-MAGE consulting 
      text:    '<h1 style="color: navy; font-size: 40px;">  <div>  {{< spoiler text=" 📧 Cliquez pour voir mon adresse mail" >}}
       {{< global_param "email" >}}
        {{< /spoiler >}} </div> </h1> '
--- 
  
           