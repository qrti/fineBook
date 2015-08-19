
![icon][icon]



#**fineBook**

V1.00 by http://qland.de
finer bookmarks

expands *firefox* bookmark ability by page position and selection

- save and restore reading positions and small selections in web pages
- especially useful for following forum threads
- also usable as software version tracker

if a regular bookmark is created a title and url are stored,
invoking it fetches a page corresponding the saved url,
thereby the page is always displayed from top

imagine following a thread with some ten posts a day,
so if you resume reading after some days the thread will
have lots of new posts and pages and it might be difficult
to find the position you stopped reading at your last session

*fineBook* allows to restore your reading position and makes it
easy to follow up reading with some additional clicks only

**version 1.00**
- reworked ui and logic
- completely context menu driven
- using current *jpm* framework

###**test drive**

> **installation**
>
> - install *fineBook*
> - if you do not see the *fineBook* icon in toolbar
>   right click toolbar/customize
>   draw *fineBook* icon to toolbar
  
> **prepare bookmark for use with *fineBook***
> 
> - click existing bookmark in *firefox*
> - right click *firefox* window to open context menu
> - click menu/fineBook/fine

![update][update] 
> **update *fineBook* mark**
> 
> - scroll to arbitrary position in web page 
> - optionally select unique text in page
> - click menu/fineBook/update
>   url, position and selection is stored with bookmark
>   bookmark title is not changed

> **continue browsing**
> 
> - if you visit bookmark later
> - url, position and selection is restored

###**addon bar icon**

> - activate and deactivate *fineBook* by clicking its icon in *firefox* addon bar
> - the *fineBook* icon in *firefox* addon bar displays the following states
> *fineBook* active
> *fineBook* deactivated
> current tab is a *fineBook* mark
> current tab is not a *fineBook* mark
> warnings
> errors

###**tips**

> - select date and time of forum posts to find last reading position
> - select version or release date to keep track of favorite software
> - if selection is not unique on page
>   first occurrence is restored
>   wrong page position might be restored
> - if no selection is made only position is stored
> - if page position or selection isn't restored correctly click bookmark  again or refresh page by pressing F5 or circle symbol in browser url field
> - restore is done after page has loaded completely
>   this might last a while on pages with external content like ads, images   etc.
> - further clicks on update button will search for further occurrence of selection
> - to restore *fineBook* marks to regular bookmarks click menu/fineBook/unfine
> - status messages are displayed near the tray bar of the desktop
> - deactivate menu/fineBook/settings/hints to reduce status messages


###**menu items**

> - **update**
>   stores current url, position, selection
> - **restore**
>   restores url, position, selection
> - **fine**
>   expands a regular bookmarks, to a *fineBook* mark
> - **unfine**
>   reverts a *fineBook* mark to a regular bookmark
> - **about**
>   opens about panel to check version and make donation

###**options**

> - **auto restore** 
>   activates/deactivates automatic position and selection restore
> - **hints**
>   activates/deactivates hint messages
>   error messages are displayed anyway

###**restrictions**

> - uses bookmark keyword for selection text and position storing
> - selection restore is limited to 30 characters
> - *fineBook* does not work on pages opened in sidebar
> - some web pages need to activate java script to make *fineBook* work correctly

qrt@qland.de

[icon]: https://github.com/qrti/fineBook/blob/master/images/icon-128.png "icon"
[update]: https://github.com/qrti/fineBook/blob/master/images/update-641.png "update888"