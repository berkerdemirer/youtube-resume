# Youtube Resume Chrome Extension

Don't let your YouTube browsing history fade away. YouTube Resume Tab replace the default browser new tab screen with your previous YouTube videos paused. Just click on the video to resume watching.

Built with React.

![screenshot](./images/screenshot_1.png)
![screenshot](./images/screenshot_2.png)

## Installation

### Install through Chrome Web Store

[![https://chrome.google.com/webstore/detail/youtube-resume/fkpmbbdgedgcpolfhedngemgnenfokid](https://raw.githubusercontent.com/tulios/json-viewer/master/tryitnow.png)](https://chrome.google.com/webstore/detail/youtube-resume/fkpmbbdgedgcpolfhedngemgnenfokid)

### Install through Developer Mode

> Make sure you have latest **NodeJs** version installed

Clone repo

```
git clone git@github.com:sbeaury/youtube-resume.git
```

Go to `youtube-resume` directory and run

```
yarn install
```

Now build the extension using

```
yarn build
```

You will see a `build` folder generated inside the project directory named `youtube-resume`

## Adding React app extension to Chrome

In Chrome browser, go to chrome://extensions page and switch on developer mode. This enables the ability to locally install a Chrome extension.

Now click on the `LOAD UNPACKED` and browse to `[PROJECT_HOME]\build`. This will install the React app as a Chrome extension.

When opening a new tab, extension will be triggered.

## Feedback

Just write me an [email](mailto:sbeaury@gmail.com), or create an [issue](issues).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/sbeaury/youtube-resume.

## License

The repo is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
