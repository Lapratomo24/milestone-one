# The GameHub

Welcome to GameHub!

The GameHub is a gaming venue website, with which the owners intend to attract members of the gaming community and them to come visit a brand new this brand new gaming venue located in central Berlin and try their hands on the latest gaming apparatus available on site. Gamers can come alone or bring up to 4 friends to the site to enjoy some fun time together.

The website showcases the available types of gaming activities on both the homepage and gallery page. It also informs interested visitors of the business' opening times, prices, guidelines during the pandemic, and directions. On the contact page, one can also use the contact form to contact GameHub, whether it be for general inquiries or reservation purposes.

The website is easily navigable and fully responsive across all screen sizes.

[Live Website HERE](https://lapratomo24.github.io/the-gamehub/)

![Responsive Mockup](assets/readme-img/mockup.png)

## User Experience (UX)

### User Stories

- #### New users are able to:
    - Learn about the gaming venue, its offerings, its business hours, and its location.
    - Navigate through the pages easily and find all relevant information.
    - Be able to use the contact form for any inquiry regarding the venue.
    - Have a positive experience using the website.

- #### Returning users are able to:
    - Remind themselves of its business hours.
    - Get in contact with GameHub for any inquiry.
    - Find social media buttons to follow and see any updates from the venue.

### Design

- #### Color Scheme
    - Only two main colors are used, namely red #990000 and white #fafafa.

- #### Typography
    - The main font for headlines or headings is Bungee Shade with cursive as the fallback font in case the user's browser does not support the main font. The font used for most of the content is Fira Sans with sans-serif as the fallback font.

- #### Imagery
    - The image used for the hero image is of a game controller, which should give a good idea of what the site might be about for users who visit it for the first time. Other images used throughout the website represent the imaginary business well, with gaming apparatus and activities that can raise users' interest to come and visit the GameHub venue.

## Features

### Navigation Bar

    A website begins with a visible header which is, as per norm, is filled with a business logo and top navigation items. The GameHub logo is created on Canva and colored white so it contrasts well with red as the background. Fully responsive top navigations bar consists of 4 items, namely Home, Visit, Gallery, and Contact Us. Each item reacts when one hovers over it or when the page represented by each button is active after clicking. This header is identical on all four pages of the website, and it will allow users to navigate through the pages easily across devices without having to click the 'back' button.

    ![Logo and navigation bar](assets/readme-img/header.png)

### 




A blue button should appear to click: _Make Public_,

Another blue button should appear to click: _Open Browser_.

To run a backend Python file, type `python3 app.py`, if your Python file is named `app.py` of course.

A blue button should appear to click: _Make Public_,

Another blue button should appear to click: _Open Browser_.

In Gitpod you have superuser security privileges by default. Therefore you do not need to use the `sudo` (superuser do) command in the bash terminal in any of the lessons.

To log into the Heroku toolbelt CLI:

1. Log in to your Heroku account and go to *Account Settings* in the menu under your avatar.
2. Scroll down to the *API Key* and click *Reveal*
3. Copy the key
4. In Gitpod, from the terminal, run `heroku_config`
5. Paste in your API key when asked

You can now use the `heroku` CLI program - try running `heroku apps` to confirm it works. This API key is unique and private to you so do not share it. If you accidentally make it public then you can create a new one with _Regenerate API Key_.

------

## Release History

We continually tweak and adjust this template to help give you the best experience. Here is the version history:

**September 1 2021:** Remove `PGHOSTADDR` environment variable.

**July 19 2021:** Remove `font_fix` script now that the terminal font issue is fixed.

**July 2 2021:** Remove extensions that are not available in Open VSX.

**June 30 2021:** Combined the P4 and P5 templates into one file, added the uptime script. See the FAQ at the end of this file.

**June 10 2021:** Added: `font_fix` script and alias to fix the Terminal font issue

**May 10 2021:** Added `heroku_config` script to allow Heroku API key to be stored as an environment variable.

**April 7 2021:** Upgraded the template for VS Code instead of Theia.

**October 21 2020:** Versions of the HTMLHint, Prettier, Bootstrap4 CDN and Auto Close extensions updated. The Python extension needs to stay the same version for now.

**October 08 2020:** Additional large Gitpod files (`core.mongo*` and `core.python*`) are now hidden in the Explorer, and have been added to the `.gitignore` by default.

**September 22 2020:** Gitpod occasionally creates large `core.Microsoft` files. These are now hidden in the Explorer. A `.gitignore` file has been created to make sure these files will not be committed, along with other common files.

**April 16 2020:** The template now automatically installs MySQL instead of relying on the Gitpod MySQL image. The message about a Python linter not being installed has been dealt with, and the set-up files are now hidden in the Gitpod file explorer.

**April 13 2020:** Added the _Prettier_ code beautifier extension instead of the code formatter built-in to Gitpod.

**February 2020:** The initialisation files now _do not_ auto-delete. They will remain in your project. You can safely ignore them. They just make sure that your workspace is configured correctly each time you open it. It will also prevent the Gitpod configuration popup from appearing.

**December 2019:** Added Eventyret's Bootstrap 4 extension. Type `!bscdn` in a HTML file to add the Bootstrap boilerplate. Check out the <a href="https://github.com/Eventyret/vscode-bcdn" target="_blank">README.md file at the official repo</a> for more options.

------

## FAQ about the uptime script

**Why have you added this script?**

It will help us to calculate how many running workspaces there are at any one time, which greatly helps us with cost and capacity planning. It will help us decide on the future direction of our cloud-based IDE strategy.

**How will this affect me?**

For everyday usage of Gitpod, it doesn’t have any effect at all. The script only captures the following data:

- An ID that is randomly generated each time the workspace is started.
- The current date and time
- The workspace status of “started” or “running”, which is sent every 5 minutes.

It is not possible for us or anyone else to trace the random ID back to an individual, and no personal data is being captured. It will not slow down the workspace or affect your work.

**So….?**

We want to tell you this so that we are being completely transparent about the data we collect and what we do with it.

**Can I opt out?**

Yes, you can. Since no personally identifiable information is being captured, we'd appreciate it if you let the script run; however if you are unhappy with the idea, simply run the following commands from the terminal window after creating the workspace, and this will remove the uptime script:

```
pkill uptime.sh
rm .vscode/uptime.sh
```

**Anything more?**

Yes! We'd strongly encourage you to look at the source code of the `uptime.sh` file so that you know what it's doing. As future software developers, it will be great practice to see how these shell scripts work.

---

Happy coding!
