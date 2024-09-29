# vscode-jenkins

Jenkins Extension for Visual Studio Code

## Features

* Manage Jenkins views, builds and nodes.

## Extension Settings

The extension contributes the following settings:

* `jenkins.url`: Jenkins instance URL. Pass username and token in URL for authentication. (required)

## Quick Guide

In your Jenkins dashboard go to your account and hit configure. Then in the API section generate a new token. You'll need to copy this token for the next step.

In vscode press ctrl+shift+p or cmd+shift+p and press **Preferences: Open User Settings (JSON)** to open your user settings.json

Add the following to your settings.json
```jenkins.url = "https://{username}:{jenkins-api-token}@{your-jenkins-url}"```

Restart vscode

## Known Issues

The extension is in early stage. Feel free to report bugs.
