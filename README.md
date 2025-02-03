# Text Layout Conversion From Arabic to English Back And Forth

This project provides a simple and efficient way to convert text between Arabic and English layouts. It is particularly useful for users who frequently switch between these two languages and need a quick method to convert their typed text without changing keyboard layouts manually.

## Features

- **Bidirectional Conversion**: Easily convert text from Arabic to English and vice versa.
- **Custom Character Mapping**: Utilizes a predefined mapping of characters to ensure accurate conversions.
- **Hotkey Support**: Use a simple keyboard shortcut to trigger the conversion process.
- **Clipboard Management**: Automatically handles clipboard content to ensure seamless text replacement.
- **User Feedback**: Provides visual feedback when switching between conversion modes.

## Requirements

- [AutoHotkey](https://www.autohotkey.com/) installed on your system.

## Installation

1. **Download AutoHotkey**: If you haven't already, download and install AutoHotkey from the official website.
2. **Clone or Download this Repository**: You can clone this repository using Git or download it as a ZIP file.
3. **Run the Script**: Open the `.ahk` file with AutoHotkey. The script will run in the background.

## Usage

1. **Select Text**: Highlight the text you want to convert.
2. **Trigger Conversion**: Press `Win + Shift` to convert the selected text.
   - The first press will convert from English to Arabic.
   - The second press will convert from Arabic to English.
3. **Paste Converted Text**: The converted text will automatically replace the selected text.

## Customization

You can customize the character mappings in the script if needed. The mappings are defined in the `InitializeMappings()` function. Feel free to add or modify any characters according to your requirements.

## Troubleshooting

- **No Text Selected**: If you press the hotkey without selecting any text, a message box will appear indicating that no text is selected.
- **Clipboard Issues**: If the clipboard does not contain text after pressing the hotkey, ensure that you have selected text before triggering the conversion.

## Contributing

Contributions are welcome! If you have suggestions for improvements or additional features, feel free to open an issue or submit a pull request.

## License

This project is licensed under the  CC0-1.0 license.

## Acknowledgments

- Thanks to the AutoHotkey community for their support and resources.
- Special thanks to contributors who help improve this project.

## Contact

For any inquiries or feedback, please contact noahmoustafa87@gmail.com.
