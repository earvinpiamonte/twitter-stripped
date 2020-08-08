## Twitter Stripped

A Google Chrome extension for minimal [Twitter](https://twitter.com/) experience for web.

The extension removes components that are less important than just reading the feed (at least for me).

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
