# art2xmb - PS3 XMB Image and Audio Converter

art2xmb is a powerful Python GUI tool designed to streamline the creation of custom game art files for the PlayStation 3's XMB. With art2xmb, users can choose their preferred game art images, input a YouTube link, and seamlessly convert them into PS3-compatible files. These processed files can be instantly transferred to the appropriate folder on your PS3, all within the intuitive art2xmb interface.

## Features

- **Image Processing:** art2xmb facilitates the loading and processing of the disc, logo, and background images, processing them for use with the PS3.

- **Preview Generation:** Generate a preview of your custom game art to visualize how it will look on your PS3.

- **PS1/PS2 Classics Placeholder:** Apply the Classics Box Cover Placeholder for either PS1 or PS2 to the in-gui preview and to processed images.

- **Audio Support:** Download audio files from YouTube links, preview audio using playback controls, and process audio files for your custom game art.

- **FTP transfer to PS3:** Instantly transfer the processed files to your PS3, and optionally copy the original files from your PS3 first.

- **No Installation Required:** art2xmb is available as a standalone download, eliminating the need for users to install Python or libraries.

 ---

(See instrutions.txt for a step-by-step guide on how to use art2xmb)

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

