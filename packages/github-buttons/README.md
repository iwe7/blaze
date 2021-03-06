# <a href="https://blaze-github-buttons.firebaseapp.com">Blaze GitHub Buttons</a>

Blaze is a framework-free open source UI toolkit. It provides great structure for building websites quickly with a scalable and maintainable foundation.

**https://www.blazeui.com**

[![ci build status](https://img.shields.io/travis/BlazeUI/blaze.svg?style=for-the-badge&logo=travis)](https://travis-ci.org/BlazeUI/blaze)

## Using the GitHub Buttons

Link to it by adding the following to your `<head></head>`.

```html
<script src="https://unpkg.com/@blaze/github-buttons@x.x.x/dist/github-buttons.js"></script>
```

The `x.x.x` is the specific version of the library, you should use specifc versions to prevent against breaking changes.

That's it! Start using the component in your HTML.

```html
<github-button user="BlazeUI"
               repo="blaze"
               type="star"
               text="Like us!"
               large
               count>
</github-button>
```

| Setting | Description                                                                     |
| :-----: | :------------------------------------------------------------------------------ |
| `user`  | The owner of the GitHub repo                                                    |
| `repo`  | The name of the repo                                                            |
| `type`  | Type of button. Can be `star`, `watch`, `follow`, `issue`, `fork` or `download` |
| `text`  | Override the standard button text                                               |
| `large` | Increase size of button                                                         |
| `count` | Display the count bubble next to the button                                     |
