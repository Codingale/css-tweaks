# css-tweaks
A collection of CSS tweaks I use for Discord and other websites.

I made this after people asked for me to update my tweak on Reddit, from this [thread](https://www.reddit.com/r/discordapp/comments/1ev6f4d/how_to_disable_discover_web_version_of_discord/)

If there's any issues, please file an [issue](https://github.com/Codingale/css-tweaks/issues/new/choose).

## Usage
To use these tweaks you should have either a browser extension such as [Stylus][stylus], or Discord client mod such as [Vencord][vencord] (Browser Extension also available)

From there, the steps vary, but you need to copy and paste the tweaks you want into the CSS file, if you need help reach out to a tech-savy friend who can help you. I may add a guide in the future but for now this is all the help I'll provide really unless the style breaks.

If you wish to contribute, please file a pull request, currently I would appreciate someone to write up a how-to guide eiter directly in the repo, or the wiki feature, though doing pull requests on the latter is new to me.

## Discord
Hides the Discovery Tab
```css
@import url('https://raw.githubusercontent.com/Codingale/css-tweaks/refs/heads/main/discord/discord-hide-discovery.css');
```

Hides the Shop and Store tabs
```css
@import url('https://raw.githubusercontent.com/Codingale/css-tweaks/refs/heads/main/discord/discord-hide-shop-n-store.css');
```

Hides the excessive buttons (Gift, Gifs, Stickers, etc) in the chat bar. Please note this shouldn't not effect buttons from [Vencord][vencord] plugins.
```css
@import url('https://raw.githubusercontent.com/Codingale/css-tweaks/refs/heads/main/discord/discord-hide-excessive-buttons.css');
```

Hides the App Launcher from the chat area
```css
@import url('https://raw.githubusercontent.com/Codingale/css-tweaks/refs/heads/main/discord/discord-hide-text-applauncher.css');
```

[stylus]: https://github.com/openstyles/stylus
[vencord]: https://vencord.dev/