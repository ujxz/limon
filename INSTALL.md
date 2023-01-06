### [PowerShell Terminal](https://learn.microsoft.com/pt-br/powershell/scripting/overview?view=powershell-7.3)

#### Install using Git

If you are a git user, you can install the theme by cloning the repo:

    $ git clone https://github.com/Kodaiwya/limon.git

#### Install .zip

Download using the [GitHub .zip download](https://github.com/Kodaiwya/limon/archive/main.zip) option and unzip them.

#### Activating theme

1. Start Windows Terminal.
2. Click on the down arrow icon and select "Settings" option.
3. In the settings.json file, find the section called "Schemes" and paste the content of [limon.json](./limon.json) inside of [].
4. Find the profiles section and set a "colorScheme" value on the default profile as the example

```json
"profiles": {
    "defaults": {
        "colorScheme" : "Limon"
    }
}
```