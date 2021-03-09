### Introduction

Congratulations on receiving your Pikatea Macropad GB2! This quick guide will walk you through how to use it. 

For Macropads bought in 2020, [Follow this guide](https://www.pikatea.com/pages/firmware-update-guide) to update the firmware to version 1.2

### What’s in the Box

*   (1) Pikatea Macropad GB2
*   (1) micro SD card
*   (1) USB micro SD card reader
*   (1) USB Mini Cable
*   (2) Screws
*   (1) Sticker

### Mounting

Mounting can be done with the included screws or the doubled sided tape already attached. Remove the red plastic to reveal the adhesive part of the mounting tape. Align the Macropad to the underside of your desk or monitor and press firmly for 10 seconds. The bond will grow stronger over time. **Be careful not to cover up any monitor buttons.** More mounting tape can be bought on Amazon or a hardware store. We can ship mounting tape for a small fee.

**Note: The USB cable can act as a lever and pry the macropad off if you accidently pull the cord. We would recommend you secure the cable a bit behind the macropad so that if the cable is pulled, it doesn't pull directly on it and cause it to fall off.**

### Programming and Usage

Programming can be done with an SD card (default option) or with an interface on the computer using VIAL. Scroll down to the bottom to find information on using VIAL

The Pikatea Macropad uses an SD card to read the configuration for how it should function. This makes it so the only software required is a **basic text editor** Like Notepad.exe (Mac OS X should use [VSCode](https://code.visualstudio.com/download "VSCode")). Configuration is simple, **Just follow these steps:**

1.  Remove the SD card from the Macropad.
2.  Place the SD card into the USB SD card reader and plug it into a computer.
3.  Open the file "Config.txt" with a text editor.
4.  Edit the Text file - (**More details below**).
5.  Save the file and remove the SD card.
6.  Place the SD card back into the Macropad.
7.  Press the small button on the backside to load the configuration to memory.

### Details on Editing the Text File

The configuration text file is used to tell the Pikatea Macropad what to do after each button press, hold, or knob rotation. Use the starter configuration and examples to get started. 

The configuration for each button (or knob) is defined after the equals sign on each line. To edit button 1, for example, change the text after 'Button1='.

#### **Hotkeys or a combination of key presses**

Each button press, hold, or knob rotation configuration can include a combination of keys that will be pressed all at once. Using the table below, specify each action with a '+' sign in between them. Examples and a starter configuration are listed below:

Note 1: There is a small delay between each action (5 milliseconds). Sometimes various programs don't like the small delay between keypress and an extra delay should be added. For example Ctrl+Delay(40)+Alt

Note 2: A single UPPERCASE letter is not the same as a single lowercase letter. Menu+T will actually press menu and shift and t. Menu+t will press only menu and t.

#### Starter configuration - [download starter configuration](https://www.mediafire.com/file/3srt1rztk352adb/CONFIG.txt/file "Download Pikatea Macropad Starter Configuration")

deejmode=false  
deejSensitivity=32  
  
EncoderConstant=3  
KnobButton=Mute  
KnobCW=VolumeUp  
KnobCCW=VolumeDown  
  
Button1=F13  
Button2=F14  
Button3=Previous  
Button4=PlayPause  
Button5=Next  
  
Button1Hold=  
Button2Hold=  
Button3Hold=  
Button4Hold=  
Button5Hold=

#### Example configuration

deejmode=false  
deejSensitivity=32  
  
EncoderConstant=3  
KnobButton=Mute  
KnobCW=VolumeUp  
KnobCCW=VolumeDown  
  
Button1=Ctrl+Alt+t  
Button2=Alt+Tab  
Button3=Previous  
Button4=PlayPause  
Button5=Next  
  
Button1Hold=Menu+Shift+s  
Button2Hold=Ctrl+p  
Button3Hold=  
Button4Hold=  
Button5Hold=UpArrow+Release+Delay(500)+DownArrow

#### All Keys and the correct definition for the configuration file

 **Key**

**Defined in the Config**

**Notes/Example**

Up Arrow

UpArrow

Down Arrow

DownArrow

Right Arrow

RightArrow

Left Arrow

LeftArrow

Volume Up

VolumeUp

KnobCW=VolumeUp

Volume Down

VolumeDown

KnobCCW=VolumeDown

Backspace

Backspace

Space

Space

the space character

+

PlusSign

Button3=Ctrl+PlusSign

\-

MinusSign

Tab

Tab

Button1Hold=Alt+Tab

Return

Return

the enter key

Escape

Escape

Insert

Insert

Delete

Delete

Page Up

PageUp

KnobCCW=PageUp

Page Down

PageDown

KnobCW=PageDown

Home

Home

End

End

Caps Lock

CapsLock

Play/Pause

PlayPause

Plays or pauses the current music/media

Next

Next

Plays the next song/media

Previous

Previous

Play the previous song/media

Mute

Mute

Sets the volume to zero

Left Shift or Shift

LeftShift or Shift

Button1=LeftShift+2

Left Ctrl or Ctrl

LeftCtrl or Ctrl

Button4=Ctrl+p

Left Alt or Alt

LeftAlt or Alt

Button5=Alt+Tab

Left Menu or Menu

LeftMenu or Menu

Windows Menu or Mac Command Key

Right Shift

RightShift

Right Ctrl

RightCtrl

Right Alt

RightAlt

Right Menu

RightMenu

WindowsMenu or Mac Command Key

F1-F12

F1, F2, F3, etc

Button4Hold=Ctrl+F11 or Button2=Alt+RightShift+F5

Left Mouse Click

MouseLeft

Right Mouse Click

MouseRight

Middle Mouse Click

MouseMiddle

Scroll Up

ScrollUp

scrolls the mouse wheel at a slower speed

Scroll Down

ScrollDown

scrolls the mouse wheel at a slower speed

Scroll Up Fast

ScrollUpFast

scrolls the mouse wheel 3x faster

Scroll Down Fast

ScrollDownFast

scrolls the mouse wheel 3x faster

Scroll Right

ScrollRight

Scrolls up while holding the shift key for you

Scroll Left

ScrollLeft

Scrolls down while holding the shift key for you

Any other character

a, b, c, d, -, &, #, etc

presses the character

Type a word or sentence

This is a sentence for example

types 'This is a sentence for example' (**NOTE: the configuration file and the Pikatea macropad has a maximum memory size. We would highly recommend not trying to type out entire paragraphs of text**)

Delay in milliseconds

Delay(x)

Delay(500) delays the program by half a second

Button1=LeftShift+2+Delay(50)

**Version 1.2 adds additional functions and actions outlined in the table below. Macropads purchased in 2020 need a firmware update  
**

 **Key**

**Defined in the Config**

**Notes/Example**

Number Pad 0-9

Keypad1, Keypad2, etc

Number Pad Dot

KeypadDot

Number Pad Enter

KeypadEnter

Number Pad Add/Plus

KeypadAdd

Number Pad Subtract/Minus

KeypadMinus

Number Pad Multiply/Star

KeypadMultiply

Number Pad Divide

KeypadDivide

Num Lock

KeyNumLock

F13-F24

F13, F14, F22, etc

Button3=F17

Media Rewind

Rewind

Rewinds the current song/media

Media Fast Forward

FastForward

Button1Hold=FastForward

Media Stop

Stop

Stops the current media

Release/action chaining

Release

Used to release the current keys. This is useful for chaining multiple actions for a single keypress.

Example: UpArrow+Release+Delay(500)+DownArrow

This will press the up arrow and then press the down arrow 500 milliseconds later.

### Example Uses

This is a list I've generated of useful ways and programs to use the Pikatea Macropad with. This is just an example. In reality, the possibilities are endless.

*   **Music control** - My favorite way to use the Pikatea Macropad. I usually configure 3 buttons for Play/Pause, Next and Previous songs. The knob is used to control volume. This works well with Spotify. 

Note: A recent Spotify update has made it difficult to control the music while spotify is in the background and out of focus. Try turning off "show desktop overlay when using media keys" in the spotify settings.

*   **Screenshots** - Configure a button to press LeftMenu+LeftShift+s to open up the screenshot tool on Windows 10.
*   [**SoundSwitch**](https://soundswitch.aaflalo.me/ "SoundSwitch") \- This is an amazing computer program that makes it very easy to switch audio devices. I've setup my first button to switch between my headphones and speakers when held. Button1Hold=Ctrl+Alt+F11
*   **In conjunction with AutoHotkey** \- AutoHotkey is a powerful scripting language that can do automated tasks. It can be triggered by a hotkey press so it's perfect to use with the Pikatea Macropad
*   **Streaming** \- Configure OBS or other streaming platforms to change scenes or camera angles. We like to have a button to blank my display.

Note: OBS requires an extra delay attached to the end of a configured hotkey. For example Button1=Ctrl+Alt+Shift+1+Delay(50) will work but Button1=Ctrl+Alt+Shift+1 will not. 

*   **Video Editing** \- Program the knob to press the correct keys to move the timeline back and forth for any video editing program. 

### deej Software Usage

The Pikatea Macropad works with deej. deej is an open-source hardware volume mixer for Windows and Linux PCs. It lets you use real-life sliders (or in this case, your Pikatea Macropad) to seamlessly control the volumes of different apps (such as your music player, the game you're playing and your voice chat session) without having to stop what you're doing.

Important note: deej is a 3rd-party program. The macropad uses a rotary encoder - which isn't officially supported w/ deej - and as such might not interact super-intuitively with config options such as "noise\_reduction"

Enable deej mode by changing the configuration from deejmode=false to deejmode=true

Once enabled, button holds will not work as usual. They will instead activate 1 of 5 virtual sliders which can then be adjusted with the knob. If you want to control the program attached to slider 3 for example, hold down button 3 for a moment and then turn the knob. You'll have to find out what port your macropad is connected to your computer with as well. More information on deej setup can be found on the [deej Github](https://github.com/omriharel/deej "deej Github"). Please email Pikatea support if you have questions.

### QMK and VIA and VIAL Programming

The Pikatea Macropad is compatible with QMK, VIA and VIAL firmware. 

VIAL is a great choice for configuring your macropad. VIAL is an open source program that makes it easy to configure the device with a simple interface. (macros that include delays are not possible with VIAL currently). 

![](https://cdn.shopify.com/s/files/1/0322/9637/0235/files/Screenshot_2021-03-09_094517_480x480.png?v=1615304742)

To use VIAL, update the firmware on the device with the VIAL compatible firmware. [The guide for updating firmware is here](https://www.pikatea.com/pages/firmware-update-guide). Download VIAL from [get.vial.today](https://get.vial.today).

After updating the device with VIAL compatible firmware and installing VIAL, connect the device, open VIAL and click "refresh". VIAL should recognize the device and you can easily configure the buttons with the interface.

[Pikatea QMK Fork](https://github.com/JackPikatea/qmk_firmware) - Use this fork to create your own firmware powered by QMK.

A pre-built QMK VIA compatible firmware is available to download and is outlined in the [firmware update guide here](https://www.pikatea.com/pages/firmware-update-guide)

### Troubleshooting

Sometimes the device doesn't work as expected or doesn't seem to work at all. If this is the case, we can do a replacement/repair up to 3 months after receiving your device. 

[Follow this guide here](https://www.pikatea.com/pages/pikatea-macropad-gb2-functionality-verification-guide) to install the debugging firmware and use it to determine if parts of the macropad are not working.
