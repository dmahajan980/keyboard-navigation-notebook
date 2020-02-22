# Keyboard Navigation Notebook

A diary/repository for jotting down all relevant observations related to navigating a browser using keyboard keys and shortcuts.

## Keyboard shortcuts and their functionality

Below is the list of keys and keyboard shortcuts that I tried out for navigation using keyboard. Most of these key combinations are being used by me all the time for the corresponding functionality or purpose.

| Keys | Functionality |
| :---: | :---: |
| `↑` or `Up Arrow` | Scrolls up the page |
| `↓` or `Down Arrow` | Scrolls down the page |
| `Spacebar` | Toggles the focused checkbox's state or open/close the focused dropdown list or move down the page at a time |
| `Shift + Spacebar` | Move up the page at a time |
| `Home` | Move to the top of the page |
| `End` | Move to the bottom of the page |
| `Alt + ←` or <br> `Alt + Left Arrow` | Goes back a page |
| `Alt + →` or <br> `Alt + Right Arrow` | Goes forward a page |
| `Tab` | Move from the current focusable item to the next focusable item |
| `Shift + Tab` | Move from the current focusable item to the previous focusable item |
| `Enter` while focused on a hyperlink or an object | Opens the link or the data that the hyperlink redirects to in the current tab or execute the action the object performs. Similar to a mouse click event |
| `Ctrl + Enter` while focused on a hyperlink | Opens the link or the data that the hyperlink redirects to in a new tab |
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

## My experience with using keyboard for navigation

Before I begin, I would like to mention that I have been using keyboard shortcuts for a very long time for various utilities including the ones mentioned here for navigation.

I started off by searching anything random on _[Google](https://google.com)_ from _Google Chrome_. I started tabbing (`Tab` / `Shift + Tab`) to navigate across the various search results. I noticed that the focused element had a blue outline which was same on other websites I opened. I repeated this for _Mozilla Firefox_ and it had also outlined (not blue though) the focused element. So, it seems that all browsers have some predefined outline style for the focused element. 

One thing that I noticed in _[YouTube](https://youtube.com)_ was the elements, when they are being hovered by the mouse shows some label. But it was not so in case of keyboard probably due to hover state only available for mouse cursor. But on _[Facebook](https://facebook.com/)_, the currently focused elements did show the labels (for the buttons on the navbar). So it seems that only a few sites don't have any elements that show labels on being focused. This could possibly be resolved if we pass all the properties of the hover state to the focus state or by using focus state instead of hover state. 

After going through some other websites, I noticed some strange behaviour. A carousel with two buttons (previous and next), the buttons change color on being focused and the focus state still remained on the button after `Enter` key was pressed. This was normal and expected and is helpful for a keyboard user, but when I clicked upon it using mouse and moved the cursor away, the color doesn't turn back to what it was before the element was focused. Rather it stays as if it is currently being focused, which it shouldn't be after being clicked. This is something I noticed that would be confusing for the mouse user but rather helpful for the keyboard user. 

Another thing to notice is that in some websites, such as _[Facebook](https://facebook.com/)_ have some hidden menu which automatically shows up on top of the page when user starts navigation through keyboard and allows the users to jump directly to any section of the page. This is definitely something that improves the user experience, especially for a keyboard user as the user won't have to tab through all the elements on the page before the target element to reach there. Something similar is being offered by _[GitHub](https://github.com)_ as well, it's the **Skip to Content** option that shows up on the top left corner of the webpage which allows the user to skip directly to the main content. 

![Imgur](https://i.imgur.com/nhEmsjh.png)
![Imgur](https://i.imgur.com/PjZxjwC.png)

Other than all of the above, I also tried other commands (as mentioned in the table) to do other things such as opening, closing and re-opening tabs and windows, switching across them, jumping to new websites on the same tab and many more. The only thing that I missed was the ability to move the mouse cursor via keyboard. One idea that I had in mind was to use arrow keys to move the cursor but it would then interfere with the behaviour of keyboard navigation so it's better to keep both of them separated.

Overall, I enjoyed doing the activity/task and I feel that the lessons learnt from this experience shall be helpful during the implementation of some features later in the project.
