# Apps Script

A template repository to develop [Google Apps Script](https://developers.google.com/apps-script) with Typescript including [ESLint](https://eslint.org/), [Prettier](https://prettier.io/) & [Husky](https://typicode.github.io/husky/#/).

## Getting started

Enable Google Apps Script API from [user settings](https://script.google.com/home/usersettings) in order to use the CLI [clasp](https://github.com/google/clasp).

Create a Google Apps Script by `clasp create` or pull an existing one by `clasp clone`.

Push changes to Google Apps Script with `clasp push`, which automatically compiles Typescript `.ts` into Google Script `.gs` code. Note that `git push` triggers `clasp push` to keep the Git remote repository and Apps Script project in sync.
