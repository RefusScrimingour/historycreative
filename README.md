# Garv: The Musical
This repository is for a history project I had to do for school, where we had to depict our assigned medieval character in a creative way. I was assigned a king, so my project surrounded the history of the Normans and William the Conqueror. I made a video in the form of a musical, which this website presents.

## How it works:
As for security, the contents of the website are nowhere to be seen in this repo (besides some image assets) as I don't necessarily want just anyone to be able to access the site. The login system is handled through Okta, where the index.html is a login page. All the other html files get a token from the user's account and then parse it into the page. As such, all the code for the website along with the video is all on the Okta servers, and can only be accessed with a valid login. This repo merely acts as a shell to access that information! :D
