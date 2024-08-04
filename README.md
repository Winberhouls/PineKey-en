# PineKey BMS/IIDX Dear ImGui-based keystroke input assist display for music games

Highlight the key being pressed, count the number of times each key is pressed, the duration, the frequency, and display it graphically. Display content can be captured using live streaming applications such as OBS.  
Supports keyboard, joystick, game controller (handheld) input.  
Not intended for release, please compile it yourself or + penguin 384065633 to get it from me.

![PineKey_v1.0.1](https://github.com/cstrikest/PineKey/blob/main/PineKey_v1.0.1.jpg?raw=true)

### v1.2 (under development)

- Completely separate each tool to be displayed in a separate window
- Remove enable/disable option for each section. Enable all tools by default
- Obs-oriented optimizations: background transparency and fixed window size (to prevent capture target loss after window size change)
- ESC key to exit bind mode, DEL key to delete bind mapping
- Improve the petri dish input of the analog joystick. The axis of the joystick can be selected automatically and a preview is displayed.
- Bigger and better text value display area

### v1.1.9pre (current)

- Interface Updates
- Fix a problem when using obs to capture the interface
- Made some adjustments to allow obs to better capture the area

## Version history

### v1.1.8pre

- Analog input for turntable

### v1.1.7pre

- Support controller keybinding
- Keyboard controller key input switching
-## v1.1.8pre Analog input for turntable 
### v1.1.6pre

- Optimize code structure
- Update interface layout
### v1.1.5pre

- Overall rendering/input control framework migrated to SDL2
- Add controller key support
- Optimize performance

### v1.0.4

- When switching between 1p and 2p, the data order of histogram is also switched.
- Updated the histogram calculation method for press duration to show the maximum number of frames and milliseconds counted.
- Introduced dinput8

### v1.0.1

- XInput support
- Fixed interface bugs
- Fixed layout bugs

### v1.0

- Add separate window for key UI
- Add total count display switch
- Add kps display switch
- Fix interface bugs
- Fix layout bugs
  
### v0.5.2 (pre)

- Add Petri dish dual button binding
- Adjust interface size and scrolling

### v0.5.1 (pre)

- Improve kps line chart display

### v0.5 (pre)

- Saveable config
- Auto-save global key count
- Add button to zero key count
- Adjust values
- Layout adjustment

### v0.4 (pre)

- Add kps calculation, show kps line graph
- Adjustable histogram of key counts vs. press duration

### v0.3 (pre)

- Keyboard input support

### v0.2 (pre)

- Improve key layout, support inline and iidx style arrangement.

Translated with DeepL.com (free version)
