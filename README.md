Sublime Text 2 - sublime-settings Snippets
==========================================

This is a Collection of Snippets for Sublime-Settings Files. It aims to help with editing the Sublime settings.
Needs [AAAPackageDev](https://github.com/SublimeText/AAAPackageDev) for the Sublime Settings Syntax.

Installation
------------

**With Git:**
Goto your User Package-Dir (`Preferences -> Browse Packages`)
* Windows: `%APPDATA%\Sublime Text 2\Packages\User`
* OS X: `~/Library/Application Support/Sublime Text 2/Packages/User`
* Linux: `~/.config/sublime-text-2/Packages/User`
* Portable Installation: `Sublime Text 2/Data/Packages/User`

then

    git clone git@github.com:ketos/sublime-settings.git

So the structure should look like this:

    .../Packages/User/sublime-settings/

**With Package Manager:** *Not possible yet.*

Associate Syntax to file-types
------------------------------

In order to get the Snippets working you must associate the setting files with the syntax, otherwise the snippets will not show up.
To do this, simply create or edit the file named `Sublime Settings.sublime-settings` in your `Packages/User` directory so it looks like this:

    {
        "extensions":
        [
            "sublime-settings",
            "sublime-project",
            "sublime-workspace"
        ]
    }


Example
-------

`tabsize + Enter` expands to `"tab_size": 4,`


