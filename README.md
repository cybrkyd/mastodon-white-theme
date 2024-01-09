
# Mastodon White Theme


## About

A beautiful, minimalistic white theme for Mastodon Web UI with blue colour scheme. In ~400 lines of CSS.

This theme has only been tested with the Mastodon (Light) system theme; it probably will not look so cool if run on Mastodon (Dark) or Mastodon (High Contrast).


### Home Page

The UI has been slimmed down and various changes have been applied.
- Borders between the three columns have been removed
- The Mastodon logo is gone
- Right-side navigation tab marker added (also blue)
- Bookmarks, Favourites and Lists links have been removed from the right-side navigation
	- Be mindful of the spelling of 'Favourites' or 'Favorites', depending on what dialect of English you spell in! :-)
- Hashtags, links and buttons have the colour scheme applied
- Bigger compose box
- The footer is gone - no more bottom-left links and no more right-side top-three trends


[![Mastodon White Theme - Home](https://github.com/cybrkyd/mastodon-white-theme/blob/main/images/theme-home.png "Mastodon White Theme - Home")](https://github.com/cybrkyd/mastodon-white-theme/blob/main/images/theme-home.png)


#### The Timeline

- The main timeline column is wider at resolutions above 1,300px
- The action button 'Bookmark' has been removed
- The action buttons (Reply, Boost, Favourite) have been aligned to the right
- Link preview card - the links do not change colour when hovering

#### Alt Text

Whilst I always try adding alt-text to images, I do not like being made to police other people's images, checking whether they have added alt-text or not. I have therefore removed the alt-text overlay on images in my timeline. 


[![Mastodon White Theme - Alt-text](https://github.com/cybrkyd/mastodon-white-theme/blob/main/images/theme-alt-text.jpg "Mastodon White Theme - Alt-text")](https://github.com/cybrkyd/mastodon-white-theme/blob/main/images/theme-alt-text.jpg)


#### The Glow

When a new post arrives in the timeline, the top will glow.


[![Mastodon White Theme - New Timeline Post Glow](https://github.com/cybrkyd/mastodon-white-theme/blob/main/images/theme-glow.png "Mastodon White Theme - New Timeline Post Glow")](https://github.com/cybrkyd/mastodon-white-theme/blob/main/images/theme-glow.png)


### About Page

My instance's 'About' page has been heavily customised: https://s.pfm.cx

- The Mastodon logo is gone
- About, Server Rules and Moderated Instances links are not shown
- The footer is gone - no more bottom-left links and no more right-side top-three trends
- All Mastodon marketing links - gone, bye-bye!

What remains is the centre column with a brief 'Hello' and a link to log-in. That's all I need until I figure out how to make my very own custom landing page.


[![Mastodon White Theme - About Page](https://github.com/cybrkyd/mastodon-white-theme/blob/main/images/theme-about.png "Mastodon White Theme - About Page")](https://github.com/cybrkyd/mastodon-white-theme/blob/main/images/theme-about.png)


### Preferences and Admin Pages

The Preferences and Admin pages are mostly themed with the blue colour scheme but I have not really paid too much attention to the back-end.


[![Mastodon White Theme - Preferences Pages](https://github.com/cybrkyd/mastodon-white-theme/blob/main/images/theme-preferences.png "Mastodon White Theme - Preferences Pages")](https://github.com/cybrkyd/mastodon-white-theme/blob/main/images/theme-preferences.png)


## Install

For instance admins only:

- On your instance, navigate to **admin/settings/appearance**
- Paste the CSS into the 'Custom CSS' field on that page
- Wait for it to auto-refresh (takes about 5 min on mine)

This will override everything and become the site-wide theme so maybe check with your users first if this is what they really want. There are alternative methods to install this theme as a user-selectable theme but that will not be covered here.

