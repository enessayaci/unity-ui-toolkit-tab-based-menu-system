
<img src="https://raw.githubusercontent.com/enessayaci/unity-ui-toolkit-tab-based-menu-system/main/Assets/UI/Public/Readme/colors.png" width="48">

# UI Toolkit template for unity mobile game

![App Screenshot](https://raw.githubusercontent.com/enessayaci/unity-ui-toolkit-tab-based-menu-system/main/Assets/UI/Public/Readme/presentation.gif)


This is not a completed UI/UX design; it is just a template that you can use to enhance your game.

Provides a tab system for main panels(settings, shop, home vs.)


# Folder Structure
All icons and images will be placed into "Public" Folder
Components like Buttons, Labels or Header Footer eg will be placed in "Components"

Panels like Settings, Shop, Home ... will be placed into "Panels" folder. 

General uss file like the uss codes to effect everywhere of uı will be placed in USS, otherwise, custom uss files like only for Header component will take place in its own folder in Components folder(for example: Header component has labels inside it and has coin icon on one of that labels. So, in Header.uss we have a line of code to place that icon to there.)
![App Screenshot](https://raw.githubusercontent.com/enessayaci/unity-ui-toolkit-tab-based-menu-system/main/Assets/UI/Public/Readme/general-folder.png)

![App Screenshot](https://raw.githubusercontent.com/enessayaci/unity-ui-toolkit-tab-based-menu-system/main/Assets/UI/Public/Readme/header-folder.png)

# Customization
Colors and general configs are available to customize as you wish (of course you should keep consistent )

/Assets/UI/USS/config.uss file
![App Screenshot](https://raw.githubusercontent.com/enessayaci/unity-ui-toolkit-tab-based-menu-system/main/Assets/UI/Public/Readme/config.png)

/Assets/UI/USS/colors.uss file
![App Screenshot](https://raw.githubusercontent.com/enessayaci/unity-ui-toolkit-tab-based-menu-system/main/Assets/UI/Public/Readme/colors.png)

I used https://maketintsandshades.com/#e1c5c5 to create color scheme

I personally recommend customize colors only!

# Creating new tabs and contents
Creating Tab Steps

1)Create a new Label

2)Name it with "...Tab" at the end of it (example: LeaderboardTab)

3)Add "currentlySelectedTab" to newly created Label#LeaderboardTab(label named as LeaderboardTab) only if it will be active on start(as default HomeTab and its content HomeContent will be active on start so Label#HomeTab has "currentlySelectedTab" class)


Creating Content of the tab just created Steps

1)It doesnt matter which element you use(Visual Element or Label etc.), Create a node

2)Name it with "...Content" at the end of it and related tab name as begining  (example: LeaderboardContent)

3)Add "unselectedContent" if it is not active as default when app start (as default except HomeContent , all other contents has "unselectedContent" class)

## License


[![apache-2.0 License](https://img.shields.io/badge/License-Apache2.0-green.svg)](https://choosealicense.com/licenses/apache-2.0/)


## Contributors
- https://github.com/enessayaci


## Contact
sayacienes@gmail.com
