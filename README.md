# Simple Password Generator 🔐

This is a straightforward password generator web application created using HTML, CSS, and JavaScript. It allows you to generate a random password of a specified length.

## How to Use 🤔

1. Open `index.html` in your web browser.
2. Click the "Generate Password" button to create a random password.
3. The generated password will be displayed in the input box.
4. Optionally, you can click the copy icon to copy the generated password.

## Password Complexity ℹ️

The generated password includes:

- Uppercase letters (A-Z)
- Lowercase letters (a-z)
- Numbers (0-9)
- Special symbols (!@#$%^&*()_+|{}<>?)

## Contributing 🛠️

Feel free to fork this repository and customize the code to meet your needs. You can adjust the length of the generated password or modify the set of characters used.


## Development Notes 📝

### HTML Structure 🌐

- `index.html`: Contains the basic layout of the password generator, including the password display area, input box, and buttons.

### Styling 🎨

- `style.css`: Provides basic styling for the password generator.

### JavaScript Logic 🧠

- `main.js`: Contains the logic for generating random passwords and copying them to the clipboard.

### Password Generation Logic 🔑

- The length of the generated password is set to 12 characters (`length` variable).
- The character sets (`upperCase`, `lowerCase`, `number`, `symbol`) define the possible characters that can be used in the password.
- The `allChars` variable combines all character sets.

### Functions ⚙️

- `createPassword()`: Generates a random password by randomly selecting characters from the combined character set until the desired length is reached.
- `copyPassword()`: Copies the generated password to the clipboard.

### Start Generating Passwords 🚀

The password generator is ready to use. Click the "Generate Password" button to get started!

---

Feel free to customize and enhance this simple password generator to suit your specific requirements! 🌟