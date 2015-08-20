![icon][icon] 

#**fineBook**


V1.00 by http://qland.de
finer bookmarks

expands *firefox* bookmark ability by restoring page position and selection

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

###**version 1.00**

- reworked ui and logic
- completely context menu driven
- using current *jpm* framework


###**addon bar icon**

- activate and deactivate *fineBook* by clicking its icon in *firefox* addon bar
- the *fineBook* icon in *firefox* addon bar displays the following states

![on][logo_on] *fineBook* is active

![off][logo_off] *fineBook* is deactivated

![fine][logo_on] current page has a *fineBook* mark

![nofine][logo_nofine] current page has not a *fineBook* mark

![done][logo_done] last action successfully done

![warning][logo_warning] warnings

![errors][logo_exclame] errors


###**menu items**

![update][menu_update] **update**  
stores current url, position, selection

![restore][menu_restore] **restore**  
restores url, position, selection

![fine][menu_fine] **fine**  
expands a regular bookmarks, to a *fineBook* mark

![unfine][menu_unfine] **unfine**  
reverts a *fineBook* mark to a regular bookmark

![about][menu_about] **about**  
opens about panel to check version and make donation


###**options**

- **auto restore**  
  activates/deactivates automatic position and selection restore
 
- **hints**  
  activates/deactivates hint messages  
  error messages are displayed anyway


###**tips**

- select date and time of forum posts to find last reading position
- select version or release date to keep track of favorite software
- if selection is not unique on page  
  first occurrence is restored  
  wrong page position might be restored
- if no selection is made only position is stored
- if page position or selection isn't restored correctly  
  click bookmark again
  or refresh page by pressing F5  
  or click refresh symbol in browser url field
- restore is done after page has loaded completely  
  this might last a while on pages with external content like ads, images etc.
- further clicks on update button will search for further occurrence of selection
- to revert *fineBook* marks to regular bookmarks  
  click menu/fineBook/unfine
- status messages are displayed near the tray bar of the desktop
- deactivate options/hints to reduce status messages


###**test drive**

**installation**

- install *fineBook*
- if you do not see the *fineBook* icon in toolbar  
  right click toolbar/customize  
  draw *fineBook* icon to toolbar

**prepare bookmark for use with *fineBook***
 
- click existing bookmark in *firefox*
- right click *firefox* window to open context menu
- click menu/fineBook/fine

**update *fineBook* mark**

- scroll to arbitrary position in web page 
- optionally select some (unique) text in page
- click menu/fineBook/update  
  url, position and selection is stored with bookmark  
  title of bookmark is not changed

**continue browsing**

- if you visit bookmark later
- url, position and selection is restored


###**restrictions**

- uses bookmark keyword for selection text and position storing
- selection restore is limited to 30 characters
- *fineBook* does not work on pages opened in sidebar
- some web pages need to activate java script to make *fineBook* work 

qrt@qland.de

[icon]: https://github.com/qrti/fineBook/blob/master/images/icon-128.png "icon"
[logo_on]: https://github.com/qrti/fineBook/blob/master/images/logo_on-32.png "on"
[logo_off]: https://github.com/qrti/fineBook/blob/master/images/logo_off-32.png "off"
[logo_nofine]: https://github.com/qrti/fineBook/blob/master/images/logo_nofine-32.png "no fine"
[logo_done]: https://github.com/qrti/fineBook/blob/master/images/logo_done-32.png "done"
[logo_warning]: https://github.com/qrti/fineBook/blob/master/images/logo_warning-32.png "warning"
[logo_exclame]: https://github.com/qrti/fineBook/blob/master/images/logo_exclame-32.png "error"

[menu_update]: https://github.com/qrti/fineBook/blob/master/images/menu_update-32.png "update"
[menu_restore]: https://github.com/qrti/fineBook/blob/master/images/menu_restore-32.png "restore"
[menu_fine]: https://github.com/qrti/fineBook/blob/master/images/menu_fine-32.png "fine"
[menu_unfine]: https://github.com/qrti/fineBook/blob/master/images/menu_unfine-32.png "unfine"
[menu_about]: https://github.com/qrti/fineBook/blob/master/images/menu_unfine-32.png "unfine"