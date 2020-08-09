# Twitter Stripped

A Google Chrome extension for minimal [Twitter](https://twitter.com/) experience for web.

The extension removes components that are less important than just reading the feed (at least for me).

### Before

![alt text](screenshot-1.jpg "Twitter web screenshot 1")

### After

![alt text](screenshot-2.jpg "Twitter web screenshot 2")

### White display color

![alt text](screenshot-3.jpg "Twitter web screenshot 2")

## Install

(link to Google Web Store)

## Removes the following components:

- "Search Twitter"
- "Trends for you"
- "Who to follow"
- "Explore" link
- "Tweet" button
- "Messages" tab on footer
- dropdown icon on profile link
- likes counter
- retweets counter
- comments/ sub-tweets counter
- who liked a Tweet
- who retweeted a Tweet
- footer

## How it works?

The extension removes the components by setting each of the element's `display` property to `none`.

eg.

```css
component {
  display: none !important;
}
```

## Found an issue?

If you found an issue or you have some recommendation, send me an email at [earvin.piamonte@gmail.com](mailto:earvin.piamonte@gmail.com).

If you are a developer and have a GitHub account, you may submit an issue at [https://github.com/earvinpiamonte/twitter-stripped-chrome/issues/new](https://github.com/earvinpiamonte/twitter-stripped-chrome/issues/new).

## Credits

Twitter icon made by [Pixel perfect](https://www.flaticon.com/authors/pixel-perfect) from [www.flaticon.com](https://www.flaticon.com/).
