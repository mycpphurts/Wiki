---
layout: doc
---

# Customization
Decorate the Editor to your liking

:::info
This section is completely optional!
:::

## 1. External Assets
You don't need to touch the Editor's cached assets to edit these.

### Editor BG
You may have noticed an image in the SSQE folder called _background_editor_.  
That image is the mapping menu's **background image**, you can replace it with another **.png** file.

### Settings Menu
In _Settings_, you have plenty of options to choose from:  
![Settings](/src/map/settings.png)   
- **<u>Colors</u>**:
These are the colors that the Editor uses, and what they're used for:
    - **Color 1**: Text and BPM Lines. 
    - **Color 2**: Checkboxes, sliders, numbers and BPM Lines. 
    - **Color 3**: Bookmarks and BPM Lines. 
    - **Note Colors 1, 2** are alternated (1-2-1-2...) for the notes on the track.  

To change them, simply click over them and a **color display** will open.  
You'll be able to either input [HSL](https://en.wikipedia.org/wiki/HSL_and_HSV) or [RGB](https://en.wikipedia.org/wiki/RGB_color_model) values, or drag around the color selector and the brightness bar to get a color of your liking.

- **<u>Autosaving</u>**:
_Enable Autosave_ allows the Editor to save your progress, and _Autosave Interval_ measures how frequent these saves are (in minutes).

- **<u>Correct Errors on Copy</u>**:
Corrects notes which are out of bounds (>±0.85) so the map can be played. **Not related to customizing**.

- **<u>Waveform</u>**:
Enables/disables the sound waves on the track.

- **<u>Opacity</u>**:
These settings allow to change the Opacity value (from **0**: invisible to **255**: fully visible) of certain components:
  - **Background Opacity**: Changes the mapping menu's background image opacity.
  - **Track Opacity**: Changes the track opacity.
  - **Grid Opacity**: Changes the grid opacity.

- **<u>Change Keybinds</u>**:
All the Editor's **keybinds** are listed in this menu. You may change them to your liking by editing the boxes' content.  
Enabling the checkboxes below acts as if they were being held with the input (like in "_Shift_ + H", for example).  
Once you're done, click _Return to Settings_ to go back.

- **<u>Open Editor Folder</u>**:
When clicked on, this button opens the folder where the editor program is.

- **<u>Reset to Default</u>**:
Resets everything mentioned earlier to the default values.
:::warning
This setting has NO confirmation, for now.
:::

## 2. Internal Assets
In case you want further customization, you'll need to access the content inside the _assets_ folder, in the Editor folder.
Said folder contains 3 distinct folders, which contain the Editor's main assets:
- **_fonts_**: Contains the Editor's text fonts.
- **_sounds_**: Contains the Editor's sound files.
- **_textures_**: Contains the Editor's textures.

### Fonts
You can replace any of the Editor's fonts by downloading another font file (**.ttf** format) from any font websites like [DaFont](https://www.dafont.com/).  
- **main.ttf**: Used for the text labels in the mapping menu.
- **SourceSans.ttf**: Used for the changelog in the main menu.
- **Square.ttf** and **Squareo.ttf**: Used for the button labels in the main menu.

### Hitsounds 
In this folder, you'll find:  
- **hit.wav**: Note hitsound (for notes on the track).
- **click.wav**: Click sound.
- **metronome.wav**: Metronome tick sound.

Replacing any of those with another **.wav** file will cause them to be overridden.

### Textures
This folder contains the textures used for Editor: for now, only a single file called _widgets_, which contains the Editor's play/pause button.
You can edit this image however you like, but keep in mind how the images are displayed.
