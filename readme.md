Adds the ability to close and save mutliples tab at once.

The idea of this extension comes from one of my favourites Firefox add-ons by piro http://piro.sakura.ne.jp/xul/_multipletab.html.en

Usage is very simple, you just click and hold your mouse a little bit, the selection of tabs will starts after 200ms. You just move your mouse hover the tabs you want to select and when you just release the click a popup with options will appear.

<img src="http://dl.dropbox.com/u/9303546/komodo/tab-multiple-handler/screenshot.png" border="0"/>

Version-changes:

<ul> 0.1 - 
<br/>https://github.com/titoBouzout/komodo-tab-multiple-handler/tree/0.1
<br/>http://community.activestate.com/files/tabMultipleHandler_0.xpi
  <li> Fix style for selected tabs on linux.
  <li> Allows select tabs from multiples browsers (tabbedViews)
  <li> Adds API:
  <javascript>
	//will return an array with the view object of the selected tabs.
	var selectedViewsObjects = titoTMH.getSelectedTabs()
	
	//will return an array with the view object of the non-selected tabs.
	//this will return "other tabs" from same browser (tabbedView) if the selected tabs comes from only one view.
	//this will return "other tabs" from all browsers (tabbedViews) if the selected tabs comes from many browsers
	var nonSelectedViewsObjects = titoTMH.getNonSelectedTabs()
  </javascript>
</ul>


<ul> 0 - 
<br/>https://github.com/titoBouzout/komodo-tab-multiple-handler/tree/fce239958f90c8721f2cc9613b31acc86c5b4ef4
<br/>http://community.activestate.com/files/tabMultipleHandler.xpi
  <li>Initial release
</ul>



License:
GNU GENERAL PUBLIC LICENSE Version 3, 29 June 2007

Source-code:
https://github.com/titoBouzout/komodo-tab-multiple-handler

Home-page:
http://community.activestate.com/node/6830