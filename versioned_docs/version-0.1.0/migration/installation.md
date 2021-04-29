---
id: install
title: Install MLAPI
---

Multiple methods are available to install the MLAPI package.

To install MLAPI, use the Unity Package Manager passing a git URL to the MLAPI release:

1. Install [Git](https://git-scm.com/) if you do not have it installed on your PC. After installing Git, restart your system. A full restart is required to update for Git or you may receive an error adding packages.

1. Open the Unity Package Manager by navigating to **Window** > **Package Manager** on Unity’s main menu.
1. Click ![Add](/img/add.png) in the status bar.

  You have the following options:

   - Add package from disk...
   - Add package from tarball...
   - Add package from git URL...

1. Select **Add package from git URL...**
1. Enter the Git URL to the MLAPI release package. For example, for version 0.1.0, use this link:

  ```html
  https://github.com/Unity-Technologies/com.unity.multiplayer.mlapi.git?path=/com.unity.multiplayer.mlapi#release/0.1.0
  ```
:::info How to Copy
We recommend that you use the **Copy** function in the code block above to copy the URL as other methods may result in errors. Just hover and click.
:::

1. Click **Add**.

   The following example walks through the Package Manager. Provide the correct release branch URL.
    ![installing MLAPI from Git URL](/img/installingmlapiurl.gif)

You have now installed MLAPI.

## Next Steps

See the following content to continue your journey using MLAPI:

* [Migrating From UNet to MLAPI](migratingtomlapi.md) for UNet users
* [Updating to the Unity Package](migratingfrommlapi.md) for migrating from previous MLAPI versions to Unity MLAPI
* [Your First Networked Game "Hello World"](../tutorials/helloworldintro.md) to get started from install to project creation

## Troubleshooting

**Errors adding package**

MacOS users may receive the following errors:

* `Cannot perform upm operation: Unable to add package... Error when executing git command. xcrun: error: invalid active developer path`
* `Error adding package...`

These are common errors for MacOS users that have not installed or updated Xcode or Xcode developer tools. You may need to upgrade your Xcode installation. In a terminal, use this command: `xcode-select --install`.

If you newly installed or updated Git, you may also need to restart your system. Restarting Unity may not be enough if you added Git and could receive a package loading error.