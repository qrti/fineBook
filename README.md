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

![active][logo] *fineBook* is active

![deactivated][logoff] *fineBook* is deactivated

![isfine][logo] current page has a *fineBook* mark

![isnofine][logonf] current page has not a *fineBook* mark

![warning][logowa] warnings

![errors][logoex] errors


###**menu items**

![update][update] **update**  
stores current url, position, selection

![restore][restore] **restore**  
restores url, position, selection

![fine][fine] **fine**  
expands a regular bookmarks, to a *fineBook* mark

![unfine][unfine] **unfine**  
reverts a *fineBook* mark to a regular bookmark

![about][logo] **about**  
opens about panel to check version and make donation


###**tips**

- select date and time of forum posts to find last reading position
- select version or release date to keep track of favorite software
- if selection is not unique on page  
  first occurrence is restored  
  wrong page position might be restored
- if no selection is made only position is stored
- if page position or selection isn't restored correctly click bookmark again
  or refresh page by pressing F5  
  or click refresh symbol in browser url field
- restore is done after page has loaded completely
  this might last a while on pages with external content like ads, images etc.
- further clicks on update button will search for further occurrence of selection
- to revert *fineBook* marks to regular bookmarks click menu/fineBook/unfine
- status messages are displayed near the tray bar of the desktop
- deactivate options/hints to reduce status messages


###**options**

- **auto restore**  
  activates/deactivates automatic position and selection restore
 
- **hints**  
  activates/deactivates hint messages
  error messages are displayed anyway


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
[logo]: https://github.com/qrti/fineBook/blob/master/images/logo-32.png "logo"
[logoff]: https://github.com/qrti/fineBook/blob/master/images/logoff-32.png "off"
[logonf]: https://github.com/qrti/fineBook/blob/master/images/logonf-32.png "no fine"
[logowa]: https://github.com/qrti/fineBook/blob/master/images/logowa-32.png "warning"
[logoex]: https://github.com/qrti/fineBook/blob/master/images/logoex-32.png "error"

[update]: https://github.com/qrti/fineBook/blob/master/images/update-32.png "update"
[restore]: https://github.com/qrti/fineBook/blob/master/images/restore-32.png "restore"
[fine]: https://github.com/qrti/fineBook/blob/master/images/fine-32.png "fine"
[unfine]: https://github.com/qrti/fineBook/blob/master/images/unfine-32.png "unfine"
