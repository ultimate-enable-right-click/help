[Homepage](https://ultimate-enable-right-click.github.io)
[한국어](./help-ko.md)


# What to expect

When you right click on a website, it will display a context menu. This is browser's _default behavior_. But unfortunately, some websites try to block it. The app Ultimate Enable Right Click will restore browser's _default behavior_ for the following actions.

 1. Right clicking to open a context menu
 2. Drag on website elements (image, texts) to 'block select' them
 3. Drag objects (images, hyperlinks) outside of the web browser to create a desktop icon
 4. Copy and cut things to clipboard either via shortcuts (Ctrl + C, Ctrl + X) or via clicking on context menu commands
 5. Opening developer tools by pressing F12 or other shortcuts

Regarding 4, websites may try to modify the copied content instead of blocking copy as a whole. The app blocks it as well. 

If for some reason these behaviors cannot be restored using the app on certain site, I'd appreciate if you report it at the respective extension store's review section, or as a disqus comment [here](https://ultimate-enable-right-click.github.io).

#### False-positives

It is not possible for such an app to have zero side effects. For example, when you are dragging a certain button on a website, it is possible that certain texts near the cursor will be unintentionally selected. Some other websites may add their own context menus when user right-clicks, and the app will make both the website's menu and browser's context menu to appear. In such cases, you can turn off the app on a domain where it happens. This app comes with a set of predefined domains of such websites (google docs, etc.), so you don't need to manually whitelist those.

# How to use

It will work on most of sites even if you don't tweak anything about the app. Chances are there will be websites where context menus can be opened, but text cannot be selected by dragging. Click on the app's icon at the browser toolbar and toggle "Enable block selection (CSS)" for such websites. 

## Components 

As seen in the extension's popup, there are 2 separate components in the app.

### Enable right click

This deals with Javascript-based blocking methods. This is enabled on every website by default.

### Enable block selection(CSS)

This deals with CSS-based blocking methods. With CSS, website can prevent selecting texts (2) or images by dragging on it (3).



## Extension popup

You can open the extension's popup by clicking on the extension's icon at the browser toolbar.

There are 2 sliders that represents that state of each of the components of the app of the top-level frame of the current tab. 

You can toggle sliders by dragging its knob or by clicking on its slider bar toward the direction you want to move the knob.

Move the knob all the way to the other side to toggle the current top-level domain's setting. Move it to the middle to temporarily toggle the app's component without modifying settings permanently. Such a temporary setting will be applied to every child frames of the current tab. 

## Dashboard

 - Each setting for a domain is applied to the domain itself and all of its subdomains.
 - A special domain "(Default)" acts as a top-level domain for every domains. By changing settings for "(Default)", you can specify how the app will work on domains on which no specific settings were applied.
 - A switch with dimmed colors indicates that no setting for the corresponding domain is present, and the setting is inherited from its super-domain.
 - The extension comes with a few predefined settings for popular websites. You can remove those just like manually added settings if you want.
 - Everything is automatically saved.

### Adding a setting

Press the "+" button at the right side, enter a domain at the input field, and press the "+" button that is located at the left side of the input field, or press enter. Then a setting entry will be created. Toggle switches on its row as you wish.

### Filtering domains

Press the glass button at the right side, enter any text at the input field. Then only the domains which have the entered string as a substring will be displayed.

### Deleting a setting

Hover over a row that contains a setting that you want to remove. Click on the "trash bin" icon. 

# Support

If you want to support this addon you can donate to the following addresses:
 - Bitcoin(BTC): bc1qau3m4v43ttgn8x0xt3vsc332e6pseag5v9pwph
 - Monero(XMR): 87DZ6oXCYzLbyu2R3Q4Y7AWTFjmqKwBvz5PVYmYWpHpqcK9BeuK2zJYPM4AubtxwGU8CAH7DzVXks5uWTMo1fH5dR3Wu68a
