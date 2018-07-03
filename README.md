# Move YourTravelAgency.hotailors.com to your own domain

##### Before you start

You have to be a [Hotailors](https://hotailors.com/) partner, if you are not, you can 
go to [this page](https://hotailors.com/agents.html) and create an account. Make sure you have access to your own server
 with domain, on which you wish to serve white label. Be aware that
our script demands that it has valid SSL Certificate.

### Steps


Generating index.html file
-   To generate your index.html file go to your  [Hotailors](https://hotailors.com/) 
    admin account in *Settings/ManageDomain* section. Type in your domain url, for example: `https://YourTravelAgency.com` 
    and click *Download index.html file* button.


Modifying
-   You can look up example index.html file in this repository. All required data will be inserted automatically. 
You can modify meta tags, insert your own scripts (ex. Google Analytics) or load your own favicon but you shouldn't
modify the default script that is already there in order for page to work properly.

Upload & Save
-   Upload your index.html file into your server (with your domain) root folder. After this operation go to 
settings page again and click *Test* button. If everything was set properly (make sure you have
valid SSL Certificate) you will be able to save settings. Do it and from now on you can visit your white label
on new domain!


