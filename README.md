# Chrome Extension: Communication Coach for Slack

A Chrome Extension that overrides the Slack web app text input box and provides message suggestions for better communication based on GPT-4.

## Requirements

1. The extension should work with the Slack web app.
2. The extension should override the default text input box in Slack.
3. The extension should provide message suggestions based on GPT-4.
4. The extension should be built using Manifest v3.

## Technical Needs

1. Chrome Extension APIs
2. GPT-4 API integration
3. JavaScript, HTML, and CSS for UI and functionality

## User Interactions

1. The user installs the extension and grants necessary permissions.
2. The user opens the Slack web app and starts typing a message.
3. The extension provides message suggestions based on the user's input.
4. The user can select a suggestion or continue typing their message.

## Inputs

1. User's message input in the Slack web app text input box.

## Error Handling Procedures

1. If the GPT-4 API fails to provide suggestions, display an error message to the user.
2. If the extension fails to override the Slack text input box, display an error message and disable the extension.

## Instructions

1. Create a new Chrome Extension using Manifest v3.
2. In the `manifest.json` file, declare the necessary permissions, content scripts, and background scripts.
3. Create a `content.js` file in the root of the extension.
4. In `content.js`, write a script to override the Slack web app text input box.
5. Integrate the GPT-4 API to generate message suggestions based on the user's input.
6. Display the message suggestions to the user as they type.
7. Handle errors gracefully by displaying appropriate error messages to the user.

## Dependencies

1. axios: For making API requests to GPT-4.
2. jQuery: For DOM manipulation and event handling.
3. Bootstrap: For styling the UI components.

## Available Scripts

In the project directory, you can run:

### `npm test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## License

This project is licensed under the MIT License.