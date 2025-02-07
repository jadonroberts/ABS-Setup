# Audiobookshelf Setup

<p>There are two apps that require setup in order to access the Audiobookshelf server. </p>
- Tailscale
- Audiobookshelf(Android)/Plappa(IOS)

## Tailscale setup

Tailscale is the VPN client used to access the network that Audiobookshelf is hosted on. You will recieve a invite link from me. **DO NOT CLICK ON THIS INVITE LINK UNTIL AFTER YOU HAVE LOGGED IN WITH YOUR OWN ACCOUNT** 

1. Install [Tailscale](https://play.google.com/store/apps/details?id=com.tailscale.ipn&hl=en-US&pli=1)

![Tailscale](/Tailscale_icon.png)

2. Open the app and click *Get Started*
![Tailscale](/tailscale_welcome.png)

3. Allow any connection requests for a VPN. May require enabling in phone settings.
![accept](/tailscale_vpn_accept.png)

4. The welcome screen will present you with and option to *Log in*. There are several ways to sign in to Tailscale. Use one of the availble third party accounts to sign in.
![login](/tailscale_login.png)

5. After logging in you should be able to connect to your own tailnet (Should be named after the email used in your login option).

6. At this point locate and click on the invite link you recieved. You will be taken to a webpage and will have to resign in using the same sign in method you used before. Click on the *Join tailnet* to join the **jadonroberts.github** tailnet.

7. After you have confirmation that you have joined the **jadonroberts.github** tailnet you can close the webpage and return to the tailscale app. 

8. Click on your profile picture in the top right, select you account and sign out.

9. Click *Log in* and log in using the selected method one last time.

10. You should then be presented with the option to select a tailnet. Select the **jadonroberts.github** tailnet and click *Connect*.

11. You should then see that you are connected to the **jadonroberts.github** on the top of your screen. You should also see multible different devices and users on the tailnet.

12. The last step is to set your exit node to the server so you can access the files stored there. At the top of your screen click where is says *EXIT NODE*.
![exit_node](/tailscale_tailnet.png)

13. Select *truenas-scale*. You will be taken back to the homepage after this selection. Click on *EXIT NODE* again to return to the page. Make sure that *Allow LAN access* is enabled. 

You are now setup with the VPN. Don't worry, this is the hardest part. Some important notes. 

- This is not an actual VPN. Your traffic is not obscured as with an actual VPN. This only gives your access to my network for file sharing purposes. 
- Only connect to the tailnet when downloading or browsing audiobooks. DO NOT STAY CONNECTED. This will greatly reduce your network speed and general usability. Once you are done downloading the book you want, disconnect and listen to the book 'offline'. The audiobookshelf app is really awesome in offline mode and will sync progress of your books next time you connect.


## Audiobookshelf setup

The Audiobookshelf is your client for accessing the library. You can browse books, create collections, download and listen to books in the app. You will be sent a username and password for logging in. SAVE THESE CREDENTIONS SOMEWHERE SAFE. The app will not save your login on your phone and I connot recover your password. Your username will always be your first name (capital first letter). 

1. Download the [Audiobookshelf](https://play.google.com/store/apps/details?id=com.audiobookshelf.app&hl=en-US) app
![abs](/abs.png)

2. You will be prompted to add a new server when you first open the app. When prompted for a server address paste in:

>http://192.168.11.65:30067

3. After successful connection you will need to login using your given credentials.

You know have access to the entire audiobook library. Please note there is constant maintance on the organization of the files on the backend. You may see books with odd nameing formats and many missing covers. If you find a book is playing out of order of are missing tracks please let me know and I will fix it. 

To request books simply send the book to me and I will add it as soon as I can (I will try <48 hr). The best way to send the book is a link to the book on audibles website. 