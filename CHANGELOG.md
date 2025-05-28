## 3.0.2la (2024-05-16)
* Improved 'move compacted news section to the top of the main page' feature for the old frontpage to be inserted before the highlights section instead of at the top of the page.

## 3.0.2l (2024-05-16)
* Fixed 'move compacted news section to the top of the main page' feature not working with the newest frontpage.
* Fixed 'Konami easter-egg' not working with the newest frontpage.
* Fixed 'About GOG' submenu's hover behaviour.
* Added various script's metadata fields for better compatibility with scripts managers.

## 3.0.2k (2024-05-14)
* Added the ability to highlight new users' posts in a thread by their registered date (two latest months from the current date).
* Added the ability to compact the HowLongToBeat section.
* Added the ability to move compacted news section to the top of the main page.
* Reorganized GOG special links (e.g. 'Blast from the Past') as a 'About GOG' submenu.
* Added Konami room to the 'About GOG' submenu.
* Merged the previously added friends/wishlist menu icons' hiding feature group with an already existing one at the top of the 'Navigation Bar' settings (recheck if needed).

## 3.0.2j (2023-12-13)
* Applied GOG links' similar style for 'Open new topics of this group' links if zero new topics are present.
* Added auto-hiding custom sections (news/giveaways/etc.) if zero new topics are present on loading.
* Added auto-hiding custom sections (news/giveaways/etc.) if zero new topics will be present after clicking 'Open new topics of this group' links.

* Added a 'Blast from the Past' link under the navigation bar 'About' menu (which can be toggled off within 'Navigation bar' settings).
* Added an ability to hide redundant menu icons (such as friends/wishlist) in the navigation bar (which can be toggled on within 'Navigation bar' settings).

## 3.0.2i (2023-05-16)
* Added ability to expand forum thread/post popups to fit content on chromium-based browsers.

## 3.0.2h (2023-04-30)
* Added ability to group spam topics (on a page if a user has 3+ topics with 0 replies all his topics marked as a spam).

## 3.0.2g (2023-04-19)
* Added 'Open new topics of this group' links to forums' main page.
* Added option for 'show more' buttons on forums' main page to load all topics, sorted by 'last update', on a single click (thanks to Adalia for providing a sorting feature).
* Added feature toggles for both features mentioned above.

## 3.0.2f (2023-04-11)
* Added links for all forum groups to open new topics of selected group en masse.

## 3.0.2e (2022-10-03)
* Added ability to group delisting topics.
* Added ability to output various groups above favourites' section.
* Added dedicated icons to the newest grouping sections' headers.

## 3.0.2d (2022-03-20)
* Fixed: some functionalities do not work if a page's URL address is localized.
* Affected pages: /game/, /movie/, /promo/.

## 3.0.2c (2022-03-17)
* Fixed: friends requests/chat messages notifications within the topbar's account menu.
* Restored: forum replies' notifications within the topbar's community menu.

## 3.0.2b (2021-08-28)
* Fixed: cutoff of top navbar's arrow with the number of updates.

## 3.0.2a (2021-05-20)
* New feature: Ability to group together \"forum game\" threads on forums.
* New feature: Ability to group together \"news:\" threads on forums.

## 3.0.2 (2020-01-05)
* Updates to \"Community Wishlist\" theme. Most leftover background and font colours are replaced, forum buttons now resemble buttons from the actual wishlist, most icons with ugly grey backgrounds are replaced with transparent background, and the reply popup window will no longer get the theme applied (at least until the theme is updated to work well with the popup)

## 3.0.1 (2020-01-01)
* Update to \"Community Wishlist\" theme - now closer to completion and works with both light and dark forum colours.

## 3.0 (2019-12-31)
* This is a re-implementation of the entire project. It's entirely possible that this introduced some bugs that didn't get spotted during testing.
* New feature: custom forum theme. So far there is only one custom theme, based on the community wishlist, and that still has a lot of work to be done, but it is usable so far (as long as you set the forum colours to 'dark') so please try it out.
* GOGWiki-related features are removed, as the GOGWiki site is no longer running.
* Hiding of owned games games from front page and catalog has been removed for now, as the website has changed enough that this feature will need to be completely rewritten.

## 2.27.1 (2018-07-18)
* Fixed: made a quick adjustment to the \"Bugfixes-&gt;Keep the footer at the bottom of the page\" style to make it compatible with a recent change to the forum.
* Disabled the \"Avoid letting long activity feed text overflow.\" feature, as I believe the GOG staff have already fixed this issue some time ago.

## 2.27 (2018-07-14)
* New feature: you can now change the official GOG.com user's new avatar back to the old one. Disabled by default, you can enable this in the \"forum\" section of the settings. Thank you to MarkoH01 for the feature request.
* Improved youtube video embedding: now handles start time correctly.
* New presentation for additional information links on game pages.
* In addition to forum, GOG Wiki and GOG database links, there are now also links to PC Gaming Wiki and Wikipedia. Thank you to benpo for suggesting PC Gaming Wiki.

## 2.26 (2018-06-13)
* GOG DB links on game pages. Thank you to drmike for the suggestion.
* Prevent dropdown menus (such the ones when viewing your library on list mode) from being hidden by the footer. Thank you to MarkoH01 for finding this and to HypersomniacLive for pointing it out to me.
* Fading already-owned games on front-page promotions now works in the new \"Notable\", \"Today's highlights\" and \"Recommended for you\" sections. Thank you to Vitek for the suggestion.
* Discount tags added by BE are now coloured according to how good the discount is. Thank you to PromZA for the suggestion. Unfortunately this does not yet apply to \"partner\" promos, as GOG adds its own discount tags to those.

## 2.25 (2018-04-24)
* New feature: option to hide the little activity feed notification to the left of your avatar which tells you that there is new activity on your feed. This is disabled by default - you can enable it in the \"Navigation bar\" section of the Barefoot Essentials settings.
* The menu item to open the Barefoot Essentials settings has finally been removed from the account menu. It can now be found in the About menu.
* <sub>2.25.1</sub> The new feature to hide notification dots on the navigation bar has been reworked so that you can now control the visibility of the activity feed dot and the forum replies dot individually.
* <sub>2.25.1</sub> <b>New feature:</b> You can now change where the navigation bar links for About, Community and Account take you.
* <sub>2.25.2</sub> A correction was made to the implementation of the \"hide notification dots\" feature.
* <sub>2.25.2</sub> Fixed broken link when the \"Clicking on 'Community' takes you to Forum replies\" option is used. (Thanks to HypersomniacLive for pointing this out)
* <sub>2.25.2</sub> New \"Bugfix\" section for changes which simply fix apparent bugs in the site.
* <sub>2.25.2</sub> Removed \"Collapsible footer in forum posts\" and \"smaller spacer before the footer\" options as they would interfere with new bugfixes. Collapsible footers may get re-added in a compatible form.
* <sub>2.25.2</sub> New bugfix: option to keep the page footer at the bottom of the page, even if the page is smaller than the browser.
* <sub>2.25.2</sub> New bugfix: Keep the 5 columns in the footer in a single row. (In some parts of the site, the COMMUNITY column would break to a new row)
* <sub>2.25.2</sub> New bugfix: Avoid letting long activity feed text overflow. Currently this applies to the \"started a topic\" feed items.

## 2.24 (2018-01-09)
* Now compatible with GreaseMonkey 4 and Firefox 57
* Restored feature: navigation bar position absolute/fixed
* Dropped z-index of forum headings so that they don't appear over the menu overlay
* The menu no longer automatically closes when the BE settings window opens, as this was interfering subtly with the menu overlay
* <sub>2.24.1</sub> Compatibility update: custom navbar themes in the forum are working again.
* <sub>2.24.2</sub> Additional fix for 2014 navbar theme.
* <sub>2.24.3</sub> On game pages, discussion links are no longer added if those links point to the General Discussions forum.

## 2.23 (2017-08-31)
* New feature: add click-to-play video frames to forum posts that contain links to YouTube videos.
* <sub>2.23.1</sub> Changed the appearance of video widget to be much smaller.
* <sub>2.23.2</sub> Hovering the mouse over a \"Click to play video\" widget will now highlight the original link to that video.
* <sub>2.23.2</sub> Video frames now have a \"close\" button.
* <sub>2.23.3</sub> Bugfix: prevent the menu overlay from sticking around after the Barefoot Essentials settings popup is opened (those who had the \"remove dark menu overlay\" option enabled were never affected by this)
* <sub>2.23.3</sub> New feature: option to hide the new alerts and friends icons on the nav bar (disabled by default)

## 2.22 (2017-05-16)
* Restored forum reply notifications.
* <sub>2.22.1</sub> Raised the z-index of the footer to prevent quoted text from being rendered on top of it when \"Collapsible footer in forum topics\" is enabled.

## 2.21 (2017-05-10)
* The shadows under forum avatars were replaced with a pure CSS equivalent.
* New feature: Forum avatar style. This gives you the option of giving forum avatars rounded corners or making them circular.
* Bugfix: removed extra tab character that was being added to the end of URLs in quotes when using quick reply.
* <sub>2.21.1</sub> Raised z-index on Connect alert so that it is not concealed by the new navigation bar.
* <sub>2.21.1</sub> Extended avatar styles so that they work on the small avatars in forum quotes.
* <sub>2.21.2</sub> Updated notifications in response to the website's API changing. For now forum reply notifications are gone, but chat and friend request notifications are restored.

## 2.20 (2017-05-06)
* New feature: display notofication for new game updates, enabled by default.
* Copied the \"Barefoot Essentials\" menu item from the Account menu to the About menu. It's a more appropriate place, and it avoids making the already-long Account menu even longer. For the time being, the Account menu item will remain, but with a deprecation notice, to avoid potential confusion when it gets removed.
* <sub>2.20.1</sub> Added styling for update alerts to GOG Classic themes.
* <sub>2.20.1</sub> Made various other improvements to the GOG Classic 2012 and 2014 themes

## 2.19 (2017-04-29)
* Added new navigation bar theme, \"Bright black\", which is based on the current dark design but without the stripe and replacing the logo with the original logo from 2008 to brighten things up. This is now the default theme for new users.
* New feature: option to remove Facebook/Twitter/Twitch links from the Community menu. By default, none of these links are removed.
* New feature: option to add GOG Downloader/GOG Connect links to the About menu, as well as remove the GOG Galaxy link if you wish. By default, the new links are added and none are removed.
* New feature: notifications for chat messages and forum replies are restored.

## 2.18 (2017-04-27)
* Refactored to entirely avoid angular injection entirely, as it was causing problems on many Firefox 53 browsers
* New feature: themes for the navigation bar
* Option to remove the purple stripe has been removed, as this functionality is now handled by themes
* <sub>2.18.1</sub> Historical themes are now more accurate, thanks to archive.org. We now have <i>Second GOG design</i> and <i>Third GOG design, plus colour</i>
* <sub>2.18.2</sub> Renamed the navigation bar themes. Unfortunately, this will revert your theme selection back to the default, so you will need to select your preferred theme again.
* <sub>2.18.2</sub> Several improvements to the <i>GOG Classic 2014</i> theme.
* <sub>2.18.2</sub> Bugfix: the option to disable the dark menu overlay was not working for everyone. It should be fixed now.

## 2.17 (2017-04-26)
* New feature: option to remove the purple stripe from above the navigation bar
* New feature: option to hide the menu overlay, so that the screen no longer goes dark when you open a menu from the navigation bar

## 2.16 (2017-04-26)
* The purpose of this update is to make Barefoot Essentials compatible with GOG's new navigation system
* \"Essentials\" link on the account menu has been restored
* All options pertaining to the navigation bar have been removed, as none of them apply to the new navigation system. Features will be added later to allow you to customise the new navigation bar.

## 2.15 (2017-04-26)
* Compatibility fix for Firefox 53
* The Connect alert can now be dismissed until new games are avaialble without having to disable the entire feature
* Known issue: GOG is currently changing their navigation bar as I am writing this. Compatibility with the new navigation system will be added in the next update

## 2.14 (2017-04-20)
* New feature: Automatically check for GOG Connect offers
* Added code to quick post feature to avoid double-posting

## 2.13 (2017-02-25)
* Compatibility fix for forum \"Always show hover elements\" option.
* Added option to move the forum online/offline status to its original position, below the user's username and title.
* Forum hotkeys can no longer be used while the Alt key is pressed, to avoid conflicts on German keyboards.

## 2.12 (2017-01-05)
* Added \"Library\" tab in options.
* Added option to hide the \"TRY GOG GALAXY\" button when viewing a game in your library.

## 2.11 (2016-11-14)
* Displaying this changelog after updates is now optional. To disable it, uncheck the \"Show changelog after Barefoot Essentials is updated\" option in the \"Misc\" tab of the options.
* Fixed a bug that was stopping the \"display discount % on promo pages\" from working in certain cases.

## 2.10 (2016-11-01)
* New feature: control the visibility of the GOG Galaxy banner on the front page (from the \"Misc\" tab in the settings)
* <sub>2.10.1</sub> New feature: hide \"Is your email address correct\" notice on the front page. Thank you to HypersomniacLive for the suggestion.
* <sub>2.10.1</sub> Changed Galaxy banner control to a simple checkbox for hiding/showing
* <sub>2.10.2</sub> The Galaxy banner in the library page can now also be hidden. Thank you to Melvinica for the suggestion.
* <sub>2.10.3</sub> Updated the feature to fade out tiles for already-owned game tiles from sale mosaic, to work with the 2016 Fall sale
* <sub>2.10.4</sub>Extended the feature for hiding owned games in the sale mosaic to also hide owned games listed under \" Highlights &amp; Bundles \"

## 2.9 (2016-10-15)
* Added forum \"necro\" detection option, enabled by default
* <sub>2.9.2.1</sub> Bugfixes, compatibility with older Chrome versions, some improvement to code correctness (thanks, uchristensen)
* <sub>2.9.2.3</sub> Replaced the \"necropost\" marker on posts more than 30 days newer than the previous post with a separator between the posts indicating how much time has passed. Thank you to Bookwyrm627 for the idea.

## 2.8 (2016-06-30)
* Displaying forum and wiki links on product pages now works on Google Chrome
* Removed \"Firefox-only\" notice on the option to enable the discount on promo pages, as the Firefox dependency was actually eliminated prior to version 2.7's release

## 2.7 (2016-06-26)
* New feature: option to display discount % on promo pages, enabled by default

## 2.6 (2016-06-13)
* New \"Promotions\" tab on options screen, for setting features specific to promo pages and special promo displays on the front page
* New feature: option to fade out any owned items on the mosaic that appears on the front page during special sales, disabled by default
* <sub>2.6.1</sub> New \"Product pages\" tab on options screen, for setting features specific movie and game product pages
* <sub>2.6.1</sub> New feature: forum link on game produt pages (Firefox-only for now)

## 2.5 (2016-06-01)
* Restored the ability to send library/wishlist information to gogwiki using the Chrome extension
* Removed \"Force HTTP\" option; it is no longer useful as GOG is now pure HTTPS

## 2.4 (2016-02-19)
* New feature: option to force HTTP links in navigation bar
* New feature: replace ACCOUNT menu text with username
* Compatibility fix: now sends correct join date to GOGWiki when syncing
* <sub>2.4.1</sub> Bugfix: \"Display your username in the ACCOUNT menu\" now works in HTTPS pages
* <sub>2.4.1</sub> Bugfix: gogwiki sync no longer stops when \"Display your username in the ACCOUNT menu\" is disbled
* <sub>2.4.2</sub> Known issue: On Chrome, ACCOUNT menu changes don't always work properly on first load after installing a 2.4 version of this extension. This is a once-off problem that shouldn't affect you again, but nonetheless will be fixed in the near future.
* <sub>2.4.2</sub> Known issue: On Chrome, the feature to add a wiki link on game cards is temporarily disabled
* <sub>2.4.2</sub> Known issue: When quoting a developer's post in the forum, the special developer text colour is not shown inside the blockquote

## 2.3.7 (2016-01-21)
* New implementation for nav bar notification hiding; should fix issues with incorrect totals
* (2.3.7) Friend request alerts on the navigation bar can now be hidden

## 2.3.6 (2015-08-01)
* New feature: <b>Foelist</b>, which you can use to mark users you want to be cautious around. You'll see a mark on their usernames in the forum, and you can hover over their usernames to see a reminder of why you marked them. This mark can survive even if they change username.
* New feature: Automatically bury posts from users on your foelist.
* <sub>2.3.6.1</sub> bugfix to foelist not persisting across sessions or tabs.
* <sub>2.3.6.2</sub> compatilbility fix for GOGWiki sharing.

## 2.3.3 (2015-07-06)
* Compatibility fix: Share on GOGWiki is back
* Compatibility fix: click-to-zoom on forum avatars
* Overall better compatibility with post-Galaxy GOG website
* New feature: Shortcut keys on the redeem page - when there are multiple pages of items you can now use the left/right arrow keys to change pages
* <sub>2.3.1</sub> Corrected the date in the previous changelog entry (thanks, mrkgnao)
* <sub>2.3.1</sub> Bugfix: corrected issue that may have prevented fresh installs of the script from running correctly
* <sub>2.3.2</sub> Temporarily removed the feature to add icons below the LIBRARY item of the ACCOUNT menu, as the pages linked no longer apply
* <sub>2.3.2</sub> Implemented a workaround to whatever was keeping the ESSENTIALS menu item from workin in non-legacy pages
* <sub>2.3.3</sub> fixed games being sent to gogwiki in the wrong order
* <sub>2.3.4</sub> Experimental feature: Press Ctrl+left/right arrow key to change to the next/previous page almost anywhere on the site where a next/previous page exists.
* <sub>2.3.4</sub> Feature: Option to remove the #fragment that GOG adds to the end of the URL in the forum.
* <sub>2.3.5</sub> \"Share on GOGWiki\" feature now correctly handles wishlists over 100 items long

## 2.2 (2014-11-15)
* Shortcut keys in the forum restored for Chrome users
* Fixed: navigation bar transparency not being applied in the catalogue
* <sub>2.2.1</sub> Fixed: collapsible footer appearing too high in certain cases
* <sub>2.2.2</sub> Fixed: collapsible footer appearing too high in certain cases (Act 2)
* <sub>2.2.2</sub> Old favicons are back

## 2.1.10 (2014-11-08)
* The collapsible-footer feature is back, and now affects the forum topic lists too
* Custom icon added for the giveaways topic group

## 2.1.9.1 (2014-11-07)
* This is mainly a compatibility update so that the script copes with some recent changes to the gog.com website
* GOGWiki links on gamecards are restored
* The collapsible-footer feature is temporarily disabled
* Icon added to \"gifts\" button in account menu

## 2.1.9 (2014-11-04)
* New feature: collapsible footer (default: off)
* New feature: Fix the huge space that appears before the footer in forum topics on some browsers (default: off)
* Fixed: \"hide owned games and movies in catalogue\" not working when filtering games by genre
* Fixed: \"Click here to sync with GOGWiki again\" not working reliably
* Account menu now get a \"gifts\" button alongside the \"shelf\" and \"list\" buttons. The blank icon is temporary - I'll add an icon later.

## 2.1.8 (2014-10-04)
* New feature: toggle visibility of owned games/movies directly from the catalogue
* Restored feature: Hide specific navigation bar notifications (new/updated games, forum replies, new private messages)

## 2.1.7 (2014-09-26)
* New feature: option to hide owned games and movies from the catalogue
* New feature: option to always show Online/Offline status, PM button, and post link number in forum topics

## 2.1.6 (2014-09-25)
* Improved styling for absolute navigation bar position
* Fixed old-school navigation bar style when logged out

## 2.1.5 (2014-09-20)
* New feature: Navigation bar position, which allows you to pin the navigation bar to the top of the page
* Compatiblity with Violent Monkey and Tampermonkey restored

## 2.1.4 (2014-09-17)
* Fixed incorrect URLs on account menu shelf/list icons
* Restored feature: always show total games/movies in library

## 2.1.3 (2014-09-17)
* Quotes are properly styled inside post previews
* Post previews no longer obstruct the button to attach images to posts

## 2.1.2 (2014-09-17)
* Fixed: forum enhancements not being applied when the URL points to any specific post
* Fixed: account menu library icons not appearing in HTTPS pages
* \"Automatically expand descriptions\" feature now applies to both movie and game cards

## 2.1.1 (2014-09-17)
* Fixed: In the settings, checkboxes initially set to default instead of actual setting
* Feature restored: extra-bold bold text in forums
* Feature restored: quick reply
* Feature restored: spoilers
* New option for green account notifications in the navigation bar
* Position of the \"Essentials\" account menu item can now be either \"top\" or \"bottom\"
* Fixed: duplicating the summary paragraph when expanding gamecard descriptions

## 2.1 (2014-09-16)
* Compatible with 2014 GOG website redesign.
* COLOUR
* Complete rewrite of the Barefoot Essentials UI. I think it looks better than before, but there will be additional themes for this too.
* *All* features are now optional, and can be toggled without requiring a page refresh.
* The navigation bar links \"GAMES\" and \"MOVIES\" can be hidden if you so desire.
* The old favicon is back!
* Alternate navigation bar styles.
* Direct links to your shelf and game list in the account menu are now presented as compact icons.
* Descriptions on gamecards can be automatically expanded.
* The feature to suppress notification for new/updated games, forum replies or messages is temporarily removed. I'll re-add this when I can.
* The feature to force your library to display your game count even when there are no games new/updates is also temporarily removed

## 2.0 (2014-05-11)
* New feature: Discrete \"Post edited\" notes in forum (enabled by default).
* Keyboard shortcuts are now displayed next to the quick post area.
* The configuration now uses HTML 5 input boxes. What this means is that mouse-users can edit numbers without needing to reach for their keyboards.
* Fixed minor css issue from previous version, which had been causing the Edit / Add new post page to be slightly larger than the window displaying it

## 1.11 (2014-03-27)
* In Reply/New Post/New Topic popup windows, the preview area now occupies all available space instead of having a fixed height

## 1.10 (2013-12-11)
* New feature: Ability to group together giveaway threads on forums.
* <sub>1.10.1</sub> The experimental \"Always display shelf/list game count \" feature should now be working correctly. This option requires browser features added in Firefox 14, Chrome 26 and Opera 15, and will have no effect on browsers older than that.
* <sub>1.10.2</sub> Fixed: game count on shelf was incorrectly rounding up to the nearest 5 when \"Always display shelf/list game count \" is enabled.
* <sub>1.10.3</sub> Syncing to GOGWiki now takes into account the sort-order selection in your wishlist
* <sub>1.10.4</sub> In the forums you can now click on your forum title to go to your settings page.
* <sub>1.10.5</sub> Fixed issue with some users not being able to sync since GOGWiki's PHP update.
* <sub>1.10.6</sub> Added option to share your birthday on GOGWiki. If you have this option enabled when syncing then you will be listed on the wiki's new Special:Birthdays page when it is your birthday.
* <sub>1.10.6</sub> \"Always display shelf/list game count\" is no longer marked as experimental

## 1.9 (2013-10-27)
* Options added to ignore game updates, private messages and/or forum replies.
* (All that this does is prevent the \"ignored\" updates from counting toward the number in the alert displayed next to \"My Account\" on the top bar. You will still be able to see the updates in the dropdown menu.)
* <sub>1.9.1</sub> Wiki links in game cards now correctly handle titles containing \"en\" dashes
* <sub>1.9.2</sub> Fixed: bug causing wishlists sent to gogwiki to be limited to 50 items
* <sub>1.9.3</sub> Fixed: notifications not being correctly hidden on pages with delayed top navigation bar
* <sub>1.9.4</sub> New feature: On the game list and shelf pages, always display the counter indicating the total games and the number of games new/updated. This feature is off by default and marked as experimental for now because I haven't yet had an opportunity to test when there are updates.

## 1.8 (2013-10-08)
* Click on an avatar in the forum to view it full-size
* 3 forum quote styles are available to choose between
* Blank lines in and around spoilers are now trimmed
* Deeply-nested spoilers now have significantly less padding
* <sub>1.8.1</sub> Cursors to indicate that avatars are clickable
* <sub>1.8.1</sub> \"Full-size\" avatars now have a limit of 420 pixels in height, and their z-index is raised so that they don't go underneath the bottom bookend thingy on the forum
* <sub>1.8.1</sub> Now clicking on an avatar will also shrink any currently-enlarged avatars back to normal size

## 1.7 (2013-07-21)
* Spoilers! Hotkey Ctrl+L
* Fixed: promo link on gamecards used to be unclickable during promotions.
* <sub>1.7.1</sub> Fixed: wishlist images on the wiki.
* <sub>1.7.1</sub> Fixed: wiki links appear on game pages again.
* <sub>1.7.1</sub> Thanks to adambiser for the patch to handle the recent changes to gog.com

## 1.6 (2013-05-23)
* Restyle of forum quotes is now optional.
* Fixed: wrong preview text colour in new/edit post window when using light forum style.

## 1.5 (2013-05-10)
* Shortcut keys from quick posts are now also supported in regular post/edit windows
* Quick-posting a reply to another post now properly causes a forum reply notification. Due to technical limitations, only the first quote in a quick post generates a notification.
* Submit quick post button is now disabled during post, and has a new \"disabled\" style.
* Varius CSS changes. Some fixes to changes in light theme, quoted text in dark theme is now closer to its regular colour, and the preview in post/reply window has been reorganised.

## 1.4 (2013-04-07)
* This changelog now automatically appears once after each update so that you know when new features are available. Don't worry - I'll add an option to disable this in a future version in case you'd rather not have it keep appearing.
* Quick reply added.
* New shortcut: ctrl+space to jump to quick post.
* New shortcuts: ctrl+I, ctrl+B, ctrl+U and ctrl+Y in quick post to add [i], [b], [u] and [url] tags. (Y is for hYperlink - all the more obvious letters conflicted with some-or-other browser hotkey.)
* New shortcut: ctrl+enter in quick post to submit your post.
* Style change to quotes and bold text in forum posts. This change will become optional once in the next version.
* New, improved parser for generating better previews. Now handles quotes and nested tags, and points out missing/incorrect closing tags.
* Improvements to changelog.

## 1.3 (2013-02-27)
* Brand new UI system added, along with this changelog. This looks better, and also allow some functions to be moved out of the over-long \"My Account\" menu.
* Username links are now coloured appropriately when using the light colour scheme
* Wishlist is now sent to GOGWiki in alphabetical order
* Default settings for hiding the navigation bar have been changed (I found that the sliding effect gets old)
* Navigation bar no longer hides when you move the mouse away while typing in the search box
* Wiki links no longer disappear, due to better handling of elements that appear only after pageload (thanks, adambiser)
* <sub>1.3.2</sub> Live preview when writing a forum post.
* <sub>1.3.3</sub> Fixed wiki link on KKnD2 gamecard.
* <sub>1.3.5</sub> Inline \"Quick Post\" feature added.
* <sub>1.3.5.2</sub> Changed textbox shrinking behaviour on \"Quick Post\" to avoid the post button having to be clicked twice.
* <sub>1.3.5.3</sub> Fixed ajax regression in wiki sync
