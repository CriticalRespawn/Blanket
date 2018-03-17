# Blanket
Blanket is an extremely simple and minimalist theme for the [Ghost](http://github.com/tryghost/ghost/).
## Screenshots
<table>
<tr>
<td valign="top">
<img src="https://blanket.jonathanpurvis.co.uk/assets/desktop.png?v=2" />
</td>
<td valign="top">
<img src="https://blanket.jonathanpurvis.co.uk/assets/mobile.png?v=2" />
</td>
</tr>
</table>

## Demo
Blanket covers all the major pages you would find with any theme.
* [Homepage](https://blanket.jonathanpurvis.co.uk/)
* [Post](https://blanket.jonathanpurvis.co.uk/etiam/)
* [Tag Archive](https://blanket.jonathanpurvis.co.uk/tag/getting-started/)
* [Author Archive](https://blanket.jonathanpurvis.co.uk/author/admin-user/)
* [Subscribe Page](https://blanket.jonathanpurvis.co.uk/subscribe/)
* [404 Page](https://blanket.jonathanpurvis.co.uk/404/)

## Theme Features
* AMP Support
* i18n Support
* Responsive Design
* Author Archive
* Tag Archive
* Featured Post Support
* Subscribers Support
* Post Sharing Support
* Syntax Highlighting using [Prism JS](http://prismjs.com/)

## Install Guide
### Git Install
1. Go to the ```ghost/content/themes``` directory.
2. Run ```$ git clone https://github.com/CriticalRespawn/Blanket "blanket"```.
3. Restart Ghost.
4. Navigate to the "Design" section of the Ghost Admin, Blanket should be listed in the "Themes" block.
5. "Activate" Blanket and go to the front end of your website, Blanket should now be the active theme.

### Manual Install
1. [Download the Blanket.zip folder](https://github.com/CriticalRespawn/Blanket)
2. Unzip and rename to "blanket"
3. Copy the renamed folder to the ```ghost/content/themes``` directory
4. Restart Ghost.
5. Navigate to the "Design" section of the Ghost Admin, Blanket should be listed in the "Themes" block.
6. "Activate" Blanket and go to the front end of your website, Blanket should now be the active theme.

## Additional Notes
### Subscribers
If you do not use the Ghost Labs subscribers feature, this isn't a problem. You don't need to make any changes to the code as Blanket checks to see whether this is enabled before showing a little envelope icon in the footer.

### AMP (Accelerated Mobile Pages)
Blanket supports Accelerated Mobile Pages, for more information [Visit the AMP Project Website](https://www.ampproject.org/). The only things to note here is if you're making changes in any file within the ```/assets/css/``` directory, you must also make these changes within the ```amp.hbs``` file too. If you're making any change to ```amp.hbs``` which you intend to open a PR for, you must check that the AMP Validation is successful.

### Grid System
Blanket uses [Simple Grid](http://thisisdallas.github.io/Simple-Grid/) for the Grid System because why bother reinventing the wheel? This solution works perfectly well in this case.

### Icons
Blanket uses [Font Awesome](https://fontawesome.com/) for any icons.

### Content Fallbacks
I've developed Blanket to take into account all the instances where content will be missing. This includes feature images for posts, feature images for tags, author images, author bios, tag descriptions and additional author content. For images, 99% of instances are replaced with a default image. For other content, the containing divs are not shown on the page when there's no content to show.

## Contributing
I welcome any contributions whether they are to fix an issue or to add something new to Blanket. Please note that my vision of this theme has, and always will be "simple". If your contibution means that Blanket starts to edge towards becoming complex, it may not be approved. Submit a PR though and we can work something out!

If you wish to add a contribution in the form of additional i18n support, there's a ```en.json``` file within the ```locales``` directory, simply copy this file and
change the translations into the language of your choice.

## Issues & Support
Blanket has been tested on various platforms and devices however it's always possible bugs may have slipped through the net. If you spot an issue with Blanket you can either submit an issue here, on Github, or [Send me a Tweet](https://twitter.com/CriticalRespawn). Github is probably better though. 

## Copyright & License
Copyright (C) 2018 Jon Purvis - Released under the [MIT License](https://github.com/CriticalRespawn/Blanket/blob/master/LICENSE).
