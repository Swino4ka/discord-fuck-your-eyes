# Vencord CSS Extension

This extension is a custom CSS file that modifies the appearance of your Discord client when using Vencord. It leverages Vencord’s built-in support for importing custom CSS and BetterDiscord themes, letting you tailor the UI to your liking.

## Features

- **Custom Theming:** Modify colors, fonts, and layout of the Discord client.
- **Easy Configuration:** Use Vencord’s CSS editor to preview and adjust styles live.
- **Compatibility:** Works with both the official installer and custom builds.

## Installation

### For Official Installer Users

1. **Launch Discord with Vencord Installed:**  
   Ensure you are running Discord with Vencord active.
2. **Open the Custom CSS Editor:**  
   In the Vencord settings, locate the **Custom CSS** section.
3. **Import the CSS File:**  
   Click the **Import CSS** button and select this `.css` file from your computer.
4. **Apply the Styles:**  
   The new styles should load automatically. If they do not, try reloading Discord.

### For Advanced Users (Using Vencord from Source)

1. **Clone or Download Vencord Source:**  
   Follow the official [Vencord installation from source](https://vencord.dev/download) guide.
2. **Create a Themes Folder (if not present):**  
   Navigate to the `src` directory and create a folder for custom themes:
   ```bash
   mkdir themes
   ```
3. **Place the CSS File:**  
   Copy your `.css` file into the newly created `src/themes` folder.
4. **Rebuild Vencord:**  
   Follow the build instructions provided in the Vencord documentation.
5. **Restart Discord:**  
   Your custom styles should now be applied.

## Customization

Feel free to modify the CSS file to suit your preferences. After editing, re-import the file in the Custom CSS Editor or rebuild your client if using the source method.

## Troubleshooting

- **Styles Not Applying:**  
  Verify that your CSS file has no syntax errors. Use a CSS validator if needed.
- **Rebuild Issues (Advanced Users):**  
  Ensure the file is correctly placed in the `src/themes` folder and that you have rebuilt Vencord properly.
- **Further Assistance:**  
  Visit the [Vencord support server](https://discord.gg/D9uwnFnqmd) or consult the official documentation.

## License

This extension is released under the MIT License. See the [LICENSE](LICENSE) file for details.
