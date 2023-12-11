# DERMA SITE

#### Video Demo: [Link](https://youtu.be/aOjpP8IcYDM)

#### Live website: [Link](https://derma-site.vercel.app/)

#### Description:

This is the final project for CS50. It is an appointment website for a dermatology clinic with a small twist of AI.<br><br>
The project was created with NextJS and tailwindCSS. The UI components were made using Shadcn-ui.
<br><br>
The AI twist is a facial detection AI model from [Huggingface](https://huggingface.co) that takes an image as an input and checks for any skin diseases it can detect.
Calendly was used to create the appointment system.
<br><br>

The project first takes in an image from the user, uploads it with the help of [Uploadthing](https://uploadthing.com), and then sent to huggingface using their integrated API services. then once the results are in, you can go ahead and book an appointment.
