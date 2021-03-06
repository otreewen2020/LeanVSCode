# LeanVSCode
Develop trading strategies locally on VSCode for the [QuantConnect](https://www.quantconnect.com) cloud platform

## Features
* Fully manage your QuantConnect projects from VSCode
* See current project status
* Capable of adding and editing multiple files in multiple projects concurrently
* See backtest results from VSCode (work in progress)
* Save and sync your files to the clouda

## Requirements

## Extension Settings

This extension contributes the following settings:

* `quantconnect.apiKey`: User API key. You can get this value from the [accounts](https://quantconnect.com/accounts) page. Required
* `quantconnect.userId`: User ID. You can get this from the [accounts](https://quantconnect.com/accounts) page. Required.
* `quantconnect.cloudApiUrl`: API to use. Defaults to `https://www.quantconnect.com/api/v2/`
* `quantconnect.workspaceAsRootPath`: Establish the workspace root folder as the project directory
* `quantconnect.uploadOnSave`: Save/sync the file to the cloud on file save
* `quantconnect.uploadSkipDialog`: Lets you skip the dialog box asking for confirmation before saving to the cloud

These settings can be configured by editing the global or workspace `settings.json` file. You can access it by doing the following:

* For global settings.json: `File > Preferences > Settings > User Settings (tab) > Extensions > QuantConnect Backtesting Configuration`
* For workspace settings.json: `File > Preferences > Settings > Workspace Settings (tab) > Extensions > QuantConnect Backtesting Configuration`

# **This extension is currently under development**
It is currently not stable enough for use in production.