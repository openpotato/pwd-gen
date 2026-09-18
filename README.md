# Password Generator

A small, dependency-free password generator that creates cryptographically random passwords entirely in your browser.

No password is uploaded, stored or transmitted.

## Features

+ Generate one or multiple passwords
+ Password length from 4 to 128 characters
+ Generate up to 100 passwords at once
+ Lowercase letters
+ Uppercase letters
+ Numbers
+ Special characters
+ Letters-only mode
+ Option to exclude ambiguous characters
+ Guarantees at least one character from every selected character class
+ Cryptographically secure randomness with the Web Crypto API
+ Rejection sampling to avoid modulo bias
+ Cryptographically secure Fisher-Yates shuffle
+ Copy individual passwords
+ Copy all generated passwords
+ Automatic light and dark mode
+ Responsive layout
+ No dependencies
+ No build step
+ Runs completely locally in the browser

## Privacy

All generation happens locally in the browser.

The application has no backend, sends no generated passwords over the network, and requires no analytics or external libraries.

## Live version

The tool is deployed using [GitHub Pages](https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages) and can be used directly in a modern web browser. 

[![Live version](https://img.shields.io/badge/Open%20Password%20Generator-2563eb?style=for-the-badge)](https://openpotato.github.io/pwd-gen/)

## Development

The tool is intentionally implemented as a single HTML file using plain [HTML](https://html.spec.whatwg.org/), [CSS](https://www.w3.org/Style/CSS/) and [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript).

## Can I help?

Yes, that would be much appreciated. The best way to help is to post a response via the Issue Tracker and/or submit a Pull Request.