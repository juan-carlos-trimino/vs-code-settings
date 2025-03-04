# The vs-code-settings repo

VS Code provides different scopes for settings:<br>
**(a) User settings** - These settings are applied globally to any instance of VS Code you open.<br>
**(b) Workspace settings** - These settings are specific to a project and override User settings. VS Code stores workspace settings at the root of the project in a ***.vscode*** folder.<br>

VS Code stores setting values in a ***settings.json*** file:<br>
**(a) User settings.json location** - Depending on your platform, the user settings file is located here:<br>
&nbsp;&nbsp;&nbsp;&nbsp;**(a) Windows** - %AppData%\Code\User\settings.json<br>
&nbsp;&nbsp;&nbsp;&nbsp;**(b) macOS** - $HOME/Library/Application\ Support/Code/User/settings.json<br>
&nbsp;&nbsp;&nbsp;&nbsp;**(c) Linux** - $HOME/.config/Code/User/settings.json<br>
**(b) Workspace settings.json location** - The workspace settings file is located under the ***.vscode*** folder in your root folder. When you add a Workspace Settings ***settings.json*** file to your project or source control, the settings for the project will be shared by all users of that project.<br>

The Settings editor ([File > Preferences > Settings] or [Ctrl + ,]) is the user interface that enables you to review and modify setting values that are stored in a settings.json file.


