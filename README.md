# Stream a Video Chat With Vonage Video API

This series of tutorials will explore the [Vonage Video API (formerly TokBox OpenTok)](https://tokbox.com/developer/) and what you can build with it. The Video API is very robust and highly customisable, and in each post, we’ll show how to implement a specific feature using the API. This time we will look at how to stream your video chat to an audience who is not in the chat.

We will not be using any front-end frameworks for this series, just vanilla Javascript to keep the focus on the Video API itself. At the end of this tutorial, your video chat application should also provide an option to simply watch the video chat stream.

![Screenshot of viewer page](https://cdn.glitch.com/19f09a76-139f-49d3-9031-bb23315fae17%2Fviewer.jpg?v=1586797944330)

## Running on your local machine

1. `git clone https://github.com/nexmo-community/stream-video-chat.git`
2. `npm install`
3. `node server.js`

OPEN chrome at http://localhost:3000/

1. Enter as Participant 1, room-one
2. Enter as Participant 2, room-one

## Code of Conduct

In the interest of fostering an open and welcoming environment, we strive to make participation in our project and our community a harassment-free experience for everyone. Please check out our [Code of Conduct][coc] in full.

## Contributing

We :heart: contributions from everyone! Check out the [Contributing Guidelines][contributing] for more information.

[![contributions welcome][contribadge]][issues]

## License

This project is subject to the [MIT License][license]

[contribadge]: https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat 'Contributions Welcome'
[coc]: CODE_OF_CONDUCT.md 'Code of Conduct'
[contributing]: CONTRIBUTING.md 'Contributing'
[license]: LICENSE 'MIT License'
[issues]: ./../../issues 'Issues'
