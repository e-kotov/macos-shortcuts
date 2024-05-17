This is a repository with useful shortcuts for macOS.

Currently, it contains shortcuts for:

## [Grab Text from a Custom Screenshot](./shortcut-files/Grab%20Text%20via%20Clipboard%20Screenshot.shortcut)

This action allows you to extract text using macOS built-in text recognition from any area of the screen by taking a custom screenshot.

This shortcut uses a shell command to initiate the screenshot, as the "Take Screenshot" action was broken in macOS 14.5. If this issue persists, consider reporting the bug to Apple <a href="https://www.apple.com/feedback/macos.html" target="_blank">here</a>. I did.

### See it in Action

![Grab Text from a Custom Screenshot in Action](./shortcut-demos/Grab%20Text%20via%20Clipboard%20Screenshot.gif)


### What's inside the script

![Logic of the Grab Text from a Custom Screenshot](./shortcut-demos/Grab%20Text%20via%20Clipboard%20Screenshot.png)

### Install and First Run

Download the <a href="https://github.com/e-kotov/macos-shortcuts/raw/main/shortcut-files/Grab%20Text%20via%20Clipboard%20Screenshot.shortcut" target="_blank">raw shortcut file</a>. Double-click to add it to your Shortcuts app. Run it once from the Shortcuts app and allow the script to run shell commands (to execute the `screenshot -ci` command) and access the clipboard (to get the screenshot from the clipboard and put the extracted text back). Feel free to add a keyaboard shortcut for ease of use.

### Related Reddit Threads:

- <a href="https://www.reddit.com/r/shortcuts/comments/1crh37i/macos_sonoma_145_update_seems_to_break_take/" target="_blank">macOS Sonoma 14.5 update seems to break Take Screenshot</a>
- <a href="https://www.reddit.com/r/MacOS/comments/1cteion/screenshot_to_clipboard_is_not_working_with/" target="_blank">Screenshot to clipboard is not working with</a>
