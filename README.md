# Firefox CSS
_Just me forking other people's userChrome CSS and modifying it to my liking._

## Types

### 1. Modified Proton
![image](https://user-images.githubusercontent.com/72144072/136144170-929ab3a9-631a-4c26-9e27-e197731a3a79.png)
![image](https://user-images.githubusercontent.com/72144072/136144182-64bad7e3-1e73-4276-9fed-0986dca2d7fc.png)

### 2. Defaultish Proton 
![image](https://user-images.githubusercontent.com/72144072/136144226-c0794cf3-5210-4d74-9746-69fae39b4230.png)
![image](https://user-images.githubusercontent.com/72144072/136144234-acc65654-cead-45b7-8cdb-46fbdb722d9a.png)

### 3. Vertical Tabs (WIP)
![image](https://user-images.githubusercontent.com/72144072/136144272-d5d30a27-e7c6-44c0-abec-f53f9277a85e.png)
![image](https://user-images.githubusercontent.com/72144072/136144289-c678fd9f-d72d-4cc1-9d41-8ce7de9342c7.png)


## Install Modified Proton and Defaultish Proton

1. In the searchbar, type `about:config`. A dialog will be shown to you. Press the **I accept the risk** button.
2. Search for **`toolkit.legacyUserProfileCustomizations.stylesheets`** and change it to **True**.
3. Go to your Firefox profile:
   - In the searchbar, type `about:support` and press `Enter`.
   - Search for **`Profile Directory`** and click on **`Open Directory`** button.
4. Create a folder and name it **`chrome`** (with lowercase).
5. Paste userChrome.css file into the folder.
6. Restart Firefox
7. Enjoy your new Firefox!

## Install Vertical Tabs

1. In the searchbar, type `about:config`. A dialog will be shown to you. Press the **I accept the risk** button.
2. Search for **`toolkit.legacyUserProfileCustomizations.stylesheets`** and change it to **True**.
3. Go to your Firefox profile:
   - In the searchbar, type `about:support` and press `Enter`.
   - Search for **`Profile Directory`** and click on **`Open Directory`** button.
4. Create a folder and name it **`chrome`** (with lowercase).
5. Paste userChrome.css file into the folder.
6. Install the [Tab Center Rborn](https://addons.mozilla.org/en-US/firefox/addon/tabcenter-reborn/) extension.
  + Make sure to enable "Allow this extension to run in Private windows" so you're not left stranded while browsing.
- Go to =about:addons= in your URL bar, select /Tab Center Reborn/, go to /Preferences/ and set:
  + /Animations/: on.
  + /Use current browser theme/: on, if you want to use dark mode.
  + /Compact Mode/: either "Dynamic" or "Enabled". It works with "Disabled" too but looks nicer with only favicons.
  + /Favicon-only pinned tabs/: off.
  + Activate /Custom Stylesheet/ and paste the contents of [[https://raw.githubusercontent.com/ranmaru22/firefox-vertical-tabs/main/tabCenterReborn.css][tabCenterReborn.css]] into the text area below, and click "Save CSS" under the textbox.
- Restart Firefox.

## Credits

<b>These files are not 100% my original work, they are forked from other repositories and I am grateful for their contribution to the Firefox CSS community :)</b>

1. Modified Proton inspired by [Cascade](https://github.com/andreasgrafen/cascade) 

2. Defaultish Proton inspired by [OneLineProton](https://github.com/lr-tech/OnelineProton)

3. Vertical Tabs inspired by [FF-vertical-tabs](https://git.sr.ht/~ranmaru/ff-vertical-tabs)
