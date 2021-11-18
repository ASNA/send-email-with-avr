
### Send email with ASNA Visual RPG

> This project was compiled with AVR 15x. You cannot open this project with an earlier version of AVR, but if you copy and pasted the code as-in to older versions I am pretty sure it will works at least down to AVR 12.x and maybe even older versions. 

This repo provides a reusable Emailer class that you can use to send emails through an SMTP server with ASNA Visual RPG. 

It uses these two .NET classes as its primarily enabler:

* System.Net.Mail.SmtpClient 
* System.Net.Mail.MailMessage 

> Very early versions of .NET included a `System.Web.Mail` namespace which uses the old COM-based `Collaboration Data Objects` API to send email. The `System.Net.Mail` supercedes the `System.Web.Mail` namespace should be used instead. 

This repo also provides a TestEmail class that provides a `SendEmail` method that you can copy to your code. 

[Read the fully annotated coder here.](https://asna.github.io/send-email-with-avr/master-index.html)