# File Share Microservice
How it works: <br/>
Upload a file you want to share. A password is NOT required, but if a password is entered, the person you're sharing the file with will need to enter it before
they're able to view or download it. Passwords are encrypted on the back-end. Once you click share, a link to the file will appear at the top of the page for you 
to share with the other person. Remeber to also give them the password you entered if you required one. It will automatically download for them when clicking the 
download link. Voila! <br/><br/>
Here is a side-by-side screenshot of the file-sharing microservice. If you require the person to enter a password and they enter the wrong password, 
screenshot 2 is the error the get with a prompt to re-enter the password. <br /><br/>
![file-sharing-microservice](https://user-images.githubusercontent.com/75797321/211467686-1945f6df-2936-4394-b4a5-be9c47c58259.png)
<br/><br/>
Upon successfully uploading a file to share, the url to the file will appear for the other person to download. If you entered a password, they will have 
to enter the password before viewing/downloading the file. <br/><br/>
![file-sharing-microservice-success](https://user-images.githubusercontent.com/75797321/211467709-b47499c5-bf9a-499e-84d3-dfd5618b2e1a.png)

# NOTE:
This microservice requires MongoDB to be installed locally on your computer to work. If you don't want to use the localhost mongoDB url and want it attached to a
MongoDB database server, you'll need to update the .env file with the appropriate MongoDB url.
