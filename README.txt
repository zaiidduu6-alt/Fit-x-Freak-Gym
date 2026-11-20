FIT X FREAK - ready-to-upload website (index.html is at the root of this folder)

UPLOAD: drag this whole folder (or the extracted ZIP contents) into Netlify Drop, or push it to GitHub Pages. No install or build step is needed.
CALLING: on the website itself every phone icon, Call Now button and phone number is a plain link <a href="tel:+916354661053">: one tap opens the phone's native dialer (the phone's own Call button places the call). Only when the page is shown inside another app's frame (such as the Claude app preview, which blocks tel: links) the icons and Call Now buttons show the number list instead.
PHONE TEST PAGE: /call-test.html (plain tel: link, no JavaScript).
FREE TRIAL EMAIL: needs Netlify Functions. Deploy with Git or the Netlify CLI and set RESEND_API_KEY (see .env.example); with a plain drag-and-drop upload the form still opens WhatsApp but the e-mail notification is not sent.
The editable source project is in the other ZIP (fit-x-freak-final.zip).
