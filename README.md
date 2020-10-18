
![WiTeX screenshot](https://raw.githubusercontent.com/jsmaniac/WiTeX/master/screenshot.gif)

# WiTeX
*If Donald Knuth had designed Wikipedia*

This is a fork of [Andrew Belt](https://github.com/AndrewBelt/WiTeX)'s WiTeX which shows the wikipedia toolbars when they are hovered, in a semi-transparent, non-obtrusive way.

## Install
If you have a Wikipedia account, open your [Preferences](https://en.wikipedia.org/wiki/Special:Preferences), go to the Appearance tab, and edit the Custom CSS for the Vector skin.
Paste the contents of [`style.css`](https://raw.githubusercontent.com/jsmaniac/WiTeX/master/style.css) into the editor, and save.
For better alignment of mathematical equations, enable MathML or Mathjax in the Appearance tab.

On some Wikipedia languages, it is necessary to check the "Use Legacy
Vector" checkbox in Preferences -> Appearance.

Alternatively, you can load the CSS using a browser plugin (such as [Stylish for Firefox](https://addons.mozilla.org/en-US/firefox/addon/stylish/?src=external-userstyleshome) or [Stylish for Chrome](https://chrome.google.com/webstore/detail/fjnbnpbmkenffdnngjfgmeleoegfcffe)) for the domain `https?://*.wikipedia.org`.


#### I want the old Wikipedia design back!
While logged in, go to the [edit `vector.css` page](https://en.wikipedia.org/w/index.php?title=Special:MyPage/vector.css&action=edit), delete the contents, and save.