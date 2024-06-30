# OutFoxed

A sidebar centric config for firefox

![ScreenRecording2024-06-30](https://github.com/TrisBentall/outfoxed/assets/83300014/486816f6-ab41-4166-a967-a0b9c102cd60)

## Prerequisites

- [Sidebery](https://addons.mozilla.org/firefox/addon/sidebery/) 
- Optional Addons:
    - [Adaptive Tab Bar Color](https://addons.mozilla.org/en-GB/firefox/addon/adaptive-tab-bar-colour/)
    - [PywalFox](https://addons.mozilla.org/en-GB/firefox/addon/pywalfox/)

## Features
- Sidebar Modifications
	- Auto-collapse sidebar into just icons
	- Auto-hide url bar
- Custom Sidebery theme
- `Pywal only` custom theme to match your wallpaper


## Usage
### Step 1 - Prerequisites

<details>
  <summary> 🔵 Install recommended addons </summary>


- [Sidebery](https://addons.mozilla.org/firefox/addon/sidebery/)
- [Adaptive Tab Bar Colour](https://addons.mozilla.org/en-GB/firefox/addon/adaptive-tab-bar-colour/)

</details>

<details>
  <summary> 🔵 Install and Configure Base theme </summary>
  
  - Clone or download the repository to your local machine.
  - Copy the contents of the `chrome` folder into your Firefox profile's `chrome` folder.
  - Add the user.js file to your Firefox profile's folder, or:

 - Please make sure you also have the following perquisites set to `true` 

     `toolkit.legacyUserProfileCustomizations.stylesheets`

  
  </details>


### Step 2 - Import Sidebery configs
Import the following into sidebery  (`Sideberry Settings` > `Help` > `Import Addon Data`)
- `sidebery.json` Contains settings for the addon that **will** overwrite your own settings. you dont *have* to use this if you dont want to. 
**IF** you are not using `sidebery.json` please make sure you copy the contents of `sidebery.css` into the Sidebery Style Editor custom css editor.


### Step 3 - Set up Adaptive Tab Bar Color settings
<img width="673" alt="Screenshot 2024-06-30 at 20 19 51" src="https://github.com/TrisBentall/outfoxed/assets/83300014/e6f8324d-dc97-44d1-8c0b-4e0291b27d1e">


## Issues and Contributions

If you encounter any issues or have suggestions for improvement, please [open an issue](https://github.com/artsyfriedchicken/EdgyArc-fr/issues). Contributions are always welcome!

## License

This project is licensed under the [Mozilla Public License 2.0](https://opensource.org/licenses/MPL-2.0).
  
