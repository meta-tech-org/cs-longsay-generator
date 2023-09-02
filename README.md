# LongSay Generator for Counter-Strike

A simple, user-friendly tool designed for generating longsay commands for Counter-Strike. Share your favorite quotes, lines, or any custom text seamlessly in-game with this handy generator.

The tool can be tested [here](https://longsay.meta-tech.org/)

## Features

- **Real-time Generation**: The tool updates as you type, giving you a live preview of the `longsay` commands.
- **Character Sanitization**: Characters that could potentially break the commands, such as `"` and `;`, are automatically sanitized.
- **Downloadable CFG**: With just a single click, the generated commands can be downloaded as a `longsay.cfg` file for direct use in Counter-Strike.

## How to Use

1. **Input Text**: Open the `longsay-generator.html` in your browser. Type or paste the lines you want to use as `longsay` commands into the text area.
2. **Download CFG**: Once you're satisfied with the preview, click the "Download CFG" button. This will give you a `longsay.cfg` file.
3. **Move to CFG Directory**: Place the downloaded `longsay.cfg` into your Counter-Strike's `cfg` directory. Typically, this can be found at:
    ```
    C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\csgo\cfg\
    ```
4. **Modify autoexec.cfg**: If you already have an `autoexec.cfg` file, open it. If not, create one. Add the following line at the end of the file:
    ```
    exec longsay.cfg
    ```
    This ensures your longsay commands are loaded every time you start Counter-Strike.
5. **Use In-Game**: While in-game, simply type `longsay` into the console to initiate your set of messages.

## Contributing

Feel free to fork the project, submit PRs, and raise issues if you find any. Your contributions are always welcome!

## License

This project is open source and available under the [MIT License](LICENSE).
