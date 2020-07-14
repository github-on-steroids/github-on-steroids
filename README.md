# Github on Steroids :pill:

### Project Setup
the project has several repositories associated with it, the usage and reasons are mentioned here:
- [Idea Sharing and Broadcast](https://github.com/github-on-steroids/github-on-steroids.github.io) : To share ideas and create a mind map behind the project development.
- [powered-up-editor](https://github.com/github-on-steroids/powered-up-editor) : the text component which replaces the default github component is managed here
- [chrome-extension-injector](https://github.com/github-on-steroids/chrome-extension-injector) : lean chrome extension codebase which injects the [powered-up-editor](https://github.com/github-on-steroids/powered-up-editor) into all github sites.
- [github-on-steroids](https://github.com/github-on-steroids/github-on-steroids) : all code is bootstrapped here, to enable working on different components separately, and have a single reference point for user. this becomes the chrome extension the user loads. depends on `powered-up-editor` and `chrome-extension-injector`

<div align="center">

![Image](https://user-images.githubusercontent.com/14032427/87386813-f9957080-c5be-11ea-9a4a-f6547bd560be.png)</div>