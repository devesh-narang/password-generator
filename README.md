Recently started learning js(Javascript) and this is the first thing that I bulit using it Be Nice:)



# Password Generator

A password generator built with plain HTML, CSS and JavaScript. You pick a length,
choose which character types to include, and it builds a password you can copy to
your clipboard with one click.

## Features

- Adjustable password length
- Toggle lowercase letters, uppercase letters, numbers and symbols
- Copy the result to the clipboard

## Running it

No build step and no dependencies. Clone the repo and open `index.html` in a browser.

```bash
git clone https://github.com/devesh-narang/password-generator.git
cd password-generator
```

## A note on security

This uses `Math.random()`, which is not cryptographically secure. It's fine as a
learning project, but don't use it to generate passwords you actually rely on.
`crypto.getRandomValues()` would be the right call for that.
