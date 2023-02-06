# File Share Microservice
### How it works: <br/>
Upload a file you want to share. A password is NOT required, but if a password is entered, the person you're sharing the file with will need to enter it before
they're able to view or download it. Passwords are encrypted on the back-end. Once you click share, a link to the file will appear at the top of the page for you 
to share with the other person. Remeber to also give them the password you entered if you required one. It will automatically download for them when clicking the 
download link.<br/><br/>

![file-sharing-app](https://user-images.githubusercontent.com/75797321/216910439-c47c283c-d806-4ff7-b92f-999e001c26b0.png)
<br/><br/>

A document has been selected:
<br/><br/>
![file-sharing-doc-selected-cropped](https://user-images.githubusercontent.com/75797321/216909370-265357e4-9a75-47bc-b1ea-67ae7223e800.png)
<br/> <br/>

Upon successfully uploading a file to share, the url to the file will appear at the top of the page for you to send the the recipient. <br/><br/>
![file-sharing-doc-uploaded](https://user-images.githubusercontent.com/75797321/216910731-78a084df-d30f-46ee-9fcd-d43a2766b419.png)
<br/><br/>

If the person sharing the file required a password to be entered before downloading the document:
<br/><br/>
![file-sharing-enter-password](https://user-images.githubusercontent.com/75797321/216910818-8f957a3b-25d7-4971-b12c-70f5665d497b.png)
<br/><br/>

If the password entered is incorrect:
<br/><br/>
![file-sharing-pw-incorrect](https://user-images.githubusercontent.com/75797321/216910877-1d77d208-2c5a-4bf9-b866-87b74dc9a279.png)
<br/><br/>

If no password is required, or if the password entered is correct, the recipient can successfully download the file:
<br/><br/>

![file-sharing-doc-download](https://user-images.githubusercontent.com/75797321/216912543-90afcc1b-892b-4c40-85b1-5adecb461293.png)

# NOTE:
This microservice requires MongoDB to be installed locally on your computer to work. If you don't want to use the localhost mongoDB url and want it attached to a
MongoDB database server, you'll need to update the .env file with the appropriate MongoDB server credentials.
