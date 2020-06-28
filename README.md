# CV Website

This website will serve as my online resume, with recruiters and prospective employers as my primary target audience.  It will highlight the studies I have done in order to make a career change from administration and finance into web development, and touch on the industry experience I have gained in my career.  The information will be presented in the following pages:
* About Me / Home
* Studies
* Skills
* Work History

## Features

* Navigation on mobile devices is at the bottom of the screen for easy reach with a thumb. Expected audience here would be followers from my social networks.
* Navigation on desktop or larger tablets is across the top, to fall in line with user expectations on those platforms. Expected audience here would be recruiters and prospective employers.
* Information shown on smaller devices is more concise. This allows for better presentation, and should not impact the experience of the primary target audience.

## Deployment

This website was created in Sublime text, and deployed via Github Pages using the default instructions for Github Pages.  No changes to the code or directory structure was required for successful deployment.

## Testing

As this is purely an HTML and CSS website, there was no automated testing.  The code was run on various devices, operating systems and browsers, at a variety of screen sizes, to ensure the site looked as intended across all resolutions.  I also asked friends and family of varying tech capabilities to test ease of use.

### Devices:

* iMac (running macOS High Sierra)
* Gigabyte Netbook (running Windows 10)

### Browsers:
* Safari (desktop & mobile)
* Microsoft Edge (desktop)
* Chrome (desktop & mobile)
* Firefox (desktop & mobile)
* Firefox Focus (mobile)
* Opera / Opera mini (desktop & mobile)
* Brave (desktop & mobile)
* Maxthon (desktop & mobile)
* Vivaldi (desktop only)
* Tor (mobile app)

### Mobile Devices:
* iPhone SE, running iOS 11.2.6
* iPad Mini, running iOS 11.2.2
* iPad Pro, running iOS 11.2.6
* OnePlus One, running Android 7.1.2 (LineageOS)
* Huawei P8 lite, running Android Marshmallow
* Kindle Fire


### Bugs Found:
* Initially the nav links were nested inside button tags and this caused a conflict in the desktop version of Firefox only.  The button tags were removed, and the conflict was resolved.
* Initially used flexbox for sizing the three panels on the studies page, as bootstrap wasn't looking the way I wanted it to. However I did not like that the third panel would be a larger than the first two at resolutions where it fell to a second row. So the page was reconfigured back to bootstrap to ensure panel width uniformity.
* on iPhone 5 / SE (4 inch screens) the main content on the index page falls below the bottom nav bar, and will not scroll up for viewing.  This cannot be replicated on any other device or desktop browser, and therefore no solution has been found at this time.  This bug will remain until further resources can be devoted to it, as the site's target audience will most likely be accessing it via desktop browsers, and thus will not encounter the bug.

## Built With

* [HTML5](https://getbootstrap.com/docs/3.3/)
* [CSS3](https://www.w3schools.com/css/)
* [Bootstrap 3.3.7](https://getbootstrap.com/docs/3.3/) - Used for the grid layout, nav bars, and panels
* [Sublime Text](https://www.sublimetext.com) - text editor
* [favic-o-matic](http://www.favicomatic.com) - automated favicon generation
* [Adobe Illustrator](https://www.adobe.com/uk/products/illustrator.html?sdid=V6NZKW2K&mv=search&s_kwcid=AL!3085!3!247459081366!b!!g!!%2Billustrator%20%2Badobe&ef_id=WpAeRQAAAIfFvxhn:20180223135933:s) - nav icon and pie chart design

## Contributing

No contributors are permitted as the purpose of the site is to showcase my personal coding proficiency.

## Version Control

I use [GitHub](https://github.com) for versioning. For the versions available, see my [cv-website repo](https://dawnm.github.io/DawnM-Resume/). 

## Authors

* **DawnM Calder-Murphy**

## Acknowledgments

* Code Institute for the work history timeline lesson that I adapted for this site.
* Yoni Lavi, my Code Institute mentor.
* Bim Williams, Simen Daehlin, and many other Code Institute students who were always on hand for testing, critical feedback and help with any questions I had.
* JP Pfeiffer, for assisting with content wording.
* My wife, Coralize Calder-Murphy, for her proof reading skills, assistance in researching the code I needed to implement my ideas, and general support.

