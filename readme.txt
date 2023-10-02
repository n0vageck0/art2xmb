# art2xmb - PS3 XMB Image and Audio Converter

art2xmb is a versatile Python GUI tool designed to simplify the process of creating custom game art for the PlayStation 3's XrossMediaBar (XMB) interface. This tool allows users to select the images of the game art they'd like to use, and paste in a YouTube link, and have them processed into PS3-ready files in seconds. The processed images can then to be copied straight the the correct game folder on your PS3 using an FTP client like FileZilla. art2xmb does not provide any FTP transfer functionality.

## Features

- **Image Processing:** art2xmb facilitates the loading and processing of the disc, logo, and background images, processing them for use with the PS3.

- **Preview Generation:** Generate a preview of your custom game art to visualize how it will look on your PS3.

- **Audio Support:** Download audio files from YouTube, preview audio using playback controls, and process audio files for your custom game art.

- **No Installation Required:** art2xmb is available as a standalone download, eliminating the need for users to install Python or libraries.

## How to Use

1. **Load Disc Image:** Click the "Load Disc Image" button to select a disc image file. This will be displayed in the 'Disc Image' box.

2. **Load Logo Image:** Click the "Load Logo Image" button to select a logo image file. This will be displayed in the 'Logo Image' box.

3. **Load Background Image:** Click the "Load Background Image" button to select a background image file. This will be displayed in the 'Background Image' box.

4. **Load All Images:** Click the "Load All Images" button to quickly select the Disc, then Logo, then Background Images, and display them in their respective boxes.

5. **Generate Preview:** After loading images, click the "Generate Preview" button to create a preview of your custom game art. The preview will be displayed in the "All Images" section.

6. **Process All Images:** After loading images, click the "Process All Images" button to process all loaded images for PS3 use.

7. **Load Audio Link:** Enter a YouTube link in the "YouTube Link" text box and click the "Load Audio File" button to download the audio from the video, trim it to 60 seconds with a 5-second fade-out. The temporary audio file will be saved in "__ bin __/" as "youtube_audio.wav".

8. **Play/Pause Audio:** Use the "Play" button to playback the "youtube_audio.wav" file, and press "Stop" to stop the playback.

9. **Adjust Volume:** Use the volume slider to adjust the audio volume of the preview. This will not affect the processed sound file's volume level.

10. **Process Audio:** Click the "Process Audio" button to convert the downloaded audio into AT3 format.

## Note

- Each file can be loaded and processed separately, although the preview generation feature requires all three image files to be selected.
- The three processed images, and the sound file, will be saved into "art2xmb/Processed Files/". This folder will be created if it does not already exist.
- Remember to move the processed files to your desired location after processing.
- This tool is a work in progress, and some planned features are not yet fully implemented.

## License

This tool is provided under the MIT License. See the [LICENSE](LICENSE) file for details.

## Support and Contributions

For questions, bug reports, or contributions, please create an issue or pull request on the [GitHub repository](https://github.com/n0vageck0/art2xmb).

Thank you for using art2xmb! Enhance your PS3 XMB experience with custom themes and icons.

