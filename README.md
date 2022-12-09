# React Widget Example

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Enabling non-developers to use our widget

When providing instructions to a customer on how to use the widget, we’d probably send them instructions that look something like this:

> Copy these 3 lines of code and replace SUBREDDIT_HERE with the subreddit of your liking. You can add more than one widget by duplicating only the 3rd line.

```html
<link
  href="https://giologist.github.io/article-react-reddit-widget/index.css"
  rel="stylesheet"
/>
<script src="https://giologist.github.io/article-react-reddit-widget/index.js"></script>
<div class="reddit_widget" data-subreddit="SUBREDDIT_HERE"></div>
```

## Thing to consider

If your widget is going to load its own css, be sure not to include style properties for common elements such as html and body. You don’t want to override the styling on someone else’s page. Keep your styling specific to only your widget.
