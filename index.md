# My Experience with using Keyboard for Navigation

Before I begin, I would like to mention that I have been using keyboard shortcuts for a very long time for various utilities, including the ones mentioned here for navigation.

I started by searching for anything random on _[Google](https://google.com)_ from _Google Chrome_. I started tabbing (`Tab` / `Shift + Tab`) to navigate across the different search results. I noticed that the focussed element had a blue outline, which was the same on other websites I opened. I repeated this for _Mozilla Firefox_, and it had also outlined (not blue though) the focussed element. So, it seems that all browsers have some predefined outline style for the focussed element. 

<p align="center">
  <img src="https://i.imgur.com/vSTy7XT.png">
  <p align="center"><i>Focussed element with the blue outline on Google Chrome</i></p>
</p>

One thing that I noticed in _[YouTube](https://youtube.com)_ was the elements/buttons, when the mouse pointer is hovering them, it shows some label which tells the user what the element or the button is. But it was not displayed when the element is focussed (from the keyboard) probably because the label was set to show only when the hover state of the corresponding button/element is active.

<p align="center">
  <img src="https://i.imgur.com/nDX61vs.png">
  <p align="center"><i>YouTube icons doesn't show any labels on being focussed</i></p>
</p>

But on _[Facebook](https://facebook.com/)_, the focussed elements did show the labels (at least, for the buttons on the navigation bar). So it seems that some sites do not have any elements that show the corresponding labels on being focussed. The issue could be resolved if we pass all the properties of the hover state to the focus state or by activating the hover event handler when the element is being focussed by the use of JavaScript. 

<p align="center">
  <img src="https://i.imgur.com/JhPeLPj.png">
  <p align="center"><i>Facebook icons show the corresponding labels on being focussed</i></p>
</p>

After going through some other websites, I noticed some behavior that might confuse the mouse user. A carousel with two buttons (previous and next), the buttons change color on being focussed and the button stays focussed even after `Enter` key was pressed. It was normal and is helpful for a keyboard user to know the element at which it is currently focussed. But when I clicked upon the button using mouse and moved the mouse cursor away, the color does not turn back to what it was before the element was focussed. Instead, it stays as if it is currently being focussed. To the mouse user, it can be quite confusing that the clicked button is still focussed after moving the cursor away. But, to the keyboard user, this is a plus.

Another thing to notice is that some websites, such as _[Facebook](https://facebook.com/)_ have some hidden menu, which automatically shows up on top of the page when user starts navigation through keyboard and it allows the users to jump directly to any section of the page. This is something that improves the user experience, especially for a keyboard user, as the user won't have to tab through all preceding elements on the page to reach the target element.

![Imgur](https://i.imgur.com/nhEmsjh.png)

Something similar is being offered by _[GitHub](https://github.com)_ as well, which they call as the **Skip to Content** option and it shows up on the top left corner of the webpage which allows the user to skip directly to the main content. 

<p align="center">
  <img src="https://i.imgur.com/PjZxjwC.png">
</p>

Other than all of the above, I also tried other commands (as mentioned in the table below) to do other things such as opening, closing, and re-opening tabs and windows, switching between them, jumping to new websites on the same tab and many more.

Overall, I enjoyed doing the activity, and I feel that the lessons learned from this experience shall be helpful during the implementation of some features later in the project.

## Suggestions

- Some key shortcuts for online media players can be added such as `Space` for play/pause, `J` for skip 5 or 10 seconds previous, `L` for skip 5 or 10 seconds ahead, `K` for jumping to the beginning of the media or replay, `A` for moving to the previous media in the playlist, `D` for moving to the next video in the playlist, `S` for disable/enable autoplay, `+` for increasing media player volume, `-` for decreasing volume, `X` for mute/unmute volume and many more.

- For all the search engine websites, a key shortcut can be added, such as `Ctrl + Space` that allows the user to focus directly on the page's search bar after which they simply type in the search query, instead of tabbing through other elements to reach and focus on the search bar. This can be useful when the user wants to modify the recent search query a bit.

- There are some websites which use some carousel on their pages. When the user tabs through the page and the focus moves to the carousel, the user has to tab through each of its child elements or the cards to move past the carousel. An escape sequence such as `Ctrl + Esc` to get over the currently focused element's parent div or element (carousel div, in this case) and move the focus to the next sibling of the parent div/element. An extra shortcut can be added as well, such as `Ctrl + Shift + Esc` to get over the currently focused element's parent div or element and move the focus to the previous sibling of the parent div/element.

- I had this in the back of my mind for a long time; it was to provide the flexibility to user to move the mouse cursor and trigger mouse-button click events via keys on the keyboard. Surprisingly, I came across that **Microsoft** has provided this feature in _Windows 7_ (Kindly refer to this [article](https://support.microsoft.com/en-in/help/14204/windows-7-use-mouse-keys-to-move-mouse-pointer) for more info). The article explains about how the _Windows_ user can set up keyboard keys to move the mouse pointer and perform click events. If modern browsers could also offer something similar to this, then it will add an extra dimension to the keyboard navigation and would make the user experience better than ever.

## Keyboard shortcuts and their functionality

Below is the list of keys and keyboard shortcuts that I tried out for navigation using keyboard on ***Google Chrome***. Most of these key combinations are being used by me all the time for the corresponding functionality or purpose.

| Keys | Functionality |
| :---: | :---: |
| `↑` or `Up Arrow` | Scrolls up the page |
| `↓` or `Down Arrow` | Scrolls down the page |
| `Spacebar` | Toggles the focussed checkbox's state or open/close the focussed dropdown list or move down the page at a time |
| `Shift + Spacebar` | Move up the page at a time |
| `Home` | Move to the top of the page |
| `End` | Move to the bottom of the page |
| `Alt + ←` or <br> `Alt + Left Arrow` | Goes back a page |
| `Alt + →` or <br> `Alt + Right Arrow` | Goes forward a page |
| `Tab` | Move from the current focusable item to the next focusable item |
| `Shift + Tab` | Move from the current focusable item to the previous focusable item |
| `Enter` while focussed on a hyperlink or an object | Opens the link or the data that the hyperlink redirects to in the current tab or execute the action the object performs. Similar to a mouse click event |
| `Ctrl + Enter` while focussed on a hyperlink | Opens the link or the data that the hyperlink redirects to in a new tab |
| `Ctrl + T` | Opens a new browser tab in the current window |
| `Ctrl + Tab` | Move from currently selected browser tab to the next browser tab in the series |
| `Ctrl + Shift + Tab` | Move from currently selected browser tab to the previous browser tab in the series |
| `Ctrl + W` | Closes the current tab |
| `Ctrl + Shift + T` | Reopens the last closed tab (_non-incognito_) |
| `Ctrl + N` | Opens a new browser window |
| `Alt + ~` | Switch between multiple opened browser windows |
| `Ctrl + Shift + N` | Opens a new incognito browser window |
| `Ctrl + Shift + W` | Closes the currently selected window |
| `Ctrl + (+)` | Zoom into the page |
| `Ctrl + (-)` | Zoom out of the page |
| `Ctrl + R` | Refreshes current page |
| `Ctrl + L` | Focuses on the browser's address bar and selects the URL |
| `Ctrl + E` | Focuses on the browser's address bar and prompts for a Google Search |
