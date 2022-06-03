# Firefox CSS
_Just me forking other people's userChromeCSS and modifying it to my liking._

### 1. Modified Proton
![image](https://user-images.githubusercontent.com/72144072/171836554-9af0e3c2-9d45-41c6-aab8-9fb1d47f5a9f.png)
![image](https://user-images.githubusercontent.com/72144072/171836588-e85426e1-448f-4f48-93b0-bef27dba9af7.png)

### 2. Defaultish Proton 
![image](https://user-images.githubusercontent.com/72144072/171836129-bd1165eb-8044-4860-a4c9-2282b4b39eec.png)
![image](https://user-images.githubusercontent.com/72144072/171835972-0fff6151-0cb6-42a2-bc48-03d0a729d11f.png)

### 3. Vertical Tabs
![image](https://user-images.githubusercontent.com/72144072/171836805-d8ca5c24-dd6a-4602-9e13-64959fb7ab28.png)

### 4. Bottom Tabs 
![image](https://user-images.githubusercontent.com/72144072/171834974-8564aac5-300e-48e1-a785-88345ac6b2b7.png)

### 5. Safari Bottom Tabs
![image](https://user-images.githubusercontent.com/72144072/171837010-e81c04fb-50e4-4a91-af11-09cd6a35e80a.png)

### 6. Safari Tabs
![image](https://user-images.githubusercontent.com/72144072/171837347-2c94b343-ed68-4d5b-964e-9885fe910f94.png)

### 7. Tabs below URL-Bar
![image](https://user-images.githubusercontent.com/72144072/171837533-b87dba98-d6f9-4bb1-bea5-31e76c84c991.png)
![image](https://user-images.githubusercontent.com/72144072/171837627-ae12f0a9-4066-4c03-9946-3c6ea6abe730.png)

## Bonus Nighttab Json!
![image](https://user-images.githubusercontent.com/72144072/171837942-7cc94ef5-43e6-4598-a441-342117cb20d0.png)

## Installing Modified Proton, Defaultish Proton, Bottom Tabs, Safari Bottom Tabs, Safari Tabs or Tabs below URL-Bar:

1. In the searchbar, type **`about:config`**. A dialog will be shown to you. Press the **`I accept the risk`** button.
2. Search for **`toolkit.legacyUserProfileCustomizations.stylesheets`** and change it to **`True`**.
3. Go to your Firefox profile:
   + In the searchbar, type **`about:support`** and press **`Enter`**.
   + Search for **`Profile Directory`** and click on the **`Open Directory`** button.
4. Create a folder and name it **`chrome`** (in lowercase).
5. Paste the file userChrome.css into the folder.
6. Restart Firefox
7. Enjoy your new Firefox!

## Installing Vertical Tabs:

1. In the searchbar, type **`about:config`**. A dialog will be shown to you. Press the **`I accept the risk`** button.
2. Search for **`toolkit.legacyUserProfileCustomizations.stylesheets`** and change it to **`True`**.
3. Go to your Firefox profile:
   + In the searchbar, type **`about:support`** and press `Enter`.
   + Search for **`Profile Directory`** and click on the **`Open Directory`** button.
4. Create a folder and name it **`chrome`** (in lowercase).
5. Paste the file userChrome.css into the folder.
6. Install the [Tab Center Reborn](https://addons.mozilla.org/en-US/firefox/addon/tabcenter-reborn/) extension.
   + Make sure to enable **`Allow this extension to run in Private windows`** so you're not left stranded while browsing.
7. Go to **`about:addons`** in your URL bar, select **`Tab Center Reborn`**, go to **`Preferences`** and set:
   + Animations: on.
   + Use current browser theme: on, if you want to use dark mode.
   + Compact Mode: either "Dynamic" or "Enabled". It works with "Disabled" too but looks nicer with only favicons.
   + Favicon-only pinned tabs: off.
   + Activate **`Custom Stylesheet`** and paste the contents of verttabs.css into the text area below, and click **`Save CSS`** under the textbox.
8. Restart Firefox.
9. Enjoy your new Firefox!

## Installing NightTab:

1. Get the [NightTab](https://addons.mozilla.org/en-GB/firefox/addon/nighttab/) extension.
2. Open a new tab and click the gear/settings icon on the top left/right.
3. Download my nighttab Json file. 
4. Scroll down to **`Data < Restore`** and select the **`Import from file`** option.
5. If you want to add this as your homepage too:- 
   + Open a new firefox window and open two of the new tabs.
   + Navigate to firefox settings and under **`Homepage`**, select **`Use current page`**.
6. Enjoy your new nighttab! 

## Credits

<b>These files are not 100% my original work, they are forked from other repositories and I am grateful for their contribution to the Firefox CSS community :)</b>

1. Modified Proton inspired by [Cascade](https://github.com/andreasgrafen/cascade) 

2. Defaultish Proton inspired by [OneLineProton](https://github.com/lr-tech/OnelineProton)

3. Vertical Tabs inspired by [FF-vertical-tabs](https://git.sr.ht/~ranmaru/ff-vertical-tabs)

<b>Massive thanks to my friend [ZtereoHype](https://github.com/ZtereoHYPE) for his help in the Bottom Safari Tabs CSS, this wouldn't have been possible without him.</b>
