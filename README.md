# art2xmb - PS3 XMB Image and Audio Converter + Instant FTP transfer

art2xmb is a powerful Python GUI tool designed to streamline the creation of custom game art files for the PlayStation 3's XMB. With art2xmb, users can choose their preferred game art images, input a YouTube link, and seamlessly convert them into PS3-compatible files. These processed files can be instantly transferred to the appropriate folder on your PS3, all within the intuitive art2xmb interface.

## v1.1.0 Changelog

### New Additions:
- **Added FTP Functionality:** Easily transfer processed files from your PC to your PS3.
- **Optional Original File Copy:** You can choose to copy existing files from your PS3 before transferring new ones.
- **Added PS1/PS2 Classics Placeholder Options:** Preview and process Disc/Cover images with PS1/PS2 classics placeholders applied.

### Bug Fixes:
- **Fixed Bug:** Addressed an issue where the "youtube_audio.wav" file wasn't being deleted during audio processing.
- **Fixed Traceback Error:** Resolved a traceback error that occurred when loading logo and background images.

### Quality of Life Improvements:
- **Modified Pre-loaded Logo Image:** Modified the pre-loaded logo image to better reflect the actual placement.
- **Enhanced Shell Messages:** Added more informative messages in the shell for improved clarity during script execution.

## Features

- **Image Processing:** art2xmb facilitates the loading and processing of the disc, logo, and background images, processing them for use with the PS3.

- **Preview Generation:** Generate a preview of your custom game art to visualize how it will look on your PS3.

- **PS1/PS2 Classics Placeholder:** Apply the Classics Box Cover Placeholder for either PS1 or PS2 to the in-gui preview and to processed images.

- **Audio Support:** Download audio files from YouTube links, preview audio using playback controls, and process audio files for your custom game art.

- **FTP transfer to PS3:** Instantly transfer the processed files to your PS3, and optionally copy the original files from your PS3 first.

- **No Installation Required:** art2xmb is available as a standalone download, eliminating the need for users to install Python or libraries.

## How to use

1. **Load Disc Image**: Click "Load Disc Image" to choose a disc image file. It will be displayed in the 'Disc Image' box.

2. **Load Logo Image**: Click "Load Logo Image" to select a logo image file. It will be displayed in the 'Logo Image' box.

3. **Load Background Image**: Click "Load Background Image" to pick a background image file. It will be displayed in the 'Background Image' box.
   - Alternatively, you can click "Load All Images" to quickly select Disc, Logo, and Background Images.

4. **PS1/PS2 Placeholder**: Optionally, if you're using box cover art for your Disc Image, you can choose to apply a PS1/PS2 Classics placeholder to it.

5. **Generate Preview**: After loading images, click "Generate Preview" to create a preview of your custom game art. The preview will appear in the "All Images" section.
   - The placeholder will be applied to both the Preview and the Processed File, as long as the checkbox is ticked and PS1 or PS2 is selected when the "Generate Preview" or "Process Image" button is pressed.

6. **Process All Images**: After loading images, click "Process All Images" to process all loaded images for PS3 use. These will be saved to "/art2xmb/Processed Files/"
   - Alternatively, you can process images individually using the correct "Process" button.

7. **Load Audio Link**: Enter a YouTube link in the text box and click "Load Audio File" to download the audio from the video, trim it to 60 seconds with a 5-second fade-out.
   - The temporary audio file will be saved in "/art2xmb/__ bin __/" as "youtube_audio.wav".

8. **Audio Preview**: Use the playback controls to preview the "youtube_audio.wav" file before conversion.

9. **Process Audio**: Click "Process Audio" to convert the downloaded audio into AT3 format. This file will be saved as "/art2xmb/Processed Files/SND0.AT3/"

10. **Enter FTP Information**: Enter your PS3's IP address and the serial number of the game you're making art for into their text boxes.
    - You can edit the settings.ini file in "/art2xmb/__bin__/" and add your PS3's IP address to autofill the IP address box every time you open the application.

11. **Transfer to PS3**: Click "Copy Processed Files to PS3" to instantly send the processed files to your PS3, into the folder for the game's serial number you entered.
    - Optionally, tick the "Copy original files from PS3 first" checkbox to first copy the original files to /art2xmb/[Serial Number]/ and then copy the new ones to your PS3.

12. **Check your XMB**: Check out the art for the game on your PS3's XMB.
    - You do not need to restart your PS3 for changes to take effect, but you may need to hover over another game first and then check the game you edited.

---

**NOTES:**

- Read the Python Shell to gain a better understanding of exactly what the script is doing.

- You can follow this process regardless of if you're creating just one file or all four files - the program will simply skip to the next file when processing or FTP transferring (all three image files are required for generating a preview).

- After transferring the files from "Processed Files" to your PS3, these will be moved to a new folder in /art2xmb/ called "[Serial Number]"
   - If you ticked the "Copy original files from PS3 first" checkbox, they will be copied to "/art2xmb/[Serial Number]" and renamed ".OLD {Filename}"

- The preview generation feature requires all three image files to be selected.

- The three processed images, and the sound file, will be saved into "art2xmb/Processed Files/". This folder will be created if it does not already exist.

- Remember to move the processed files to your desired location after processing and transferring to PS3.

- This tool is a work in progress, and some planned features are not yet fully implemented.

## License

This tool is provided under the MIT License. See the [LICENSE](LICENSE) file for details.

## Support and Contributions

For questions, bug reports, or contributions, please create an issue or pull request on the [GitHub repository](https://github.com/n0vageck0/art2xmb).

Thank you for using art2xmb! Enhance your PS3 XMB experience with custom themes and icons.
