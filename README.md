# firebase-login

`<firebase-login>` is a firebase login prompt presented in a paper-dialog

[API Docs and Demo](https://heka-house-firebase-login-demo.firebaseapp.com/)

[Source](http://github.com/hekahouse/firebase-login/)

## Install

    bower install --save HekaHouse/firebase-login

## Example

    <firebase-login firebase-root="https://YOUR-FIREBASE.firebaseio.com"></firebase-login>

## Note

After authentication a paper-fab logout button is displayed in lower right corner

Authentication triggers an iron-signal to fire named <i>logged-in</i> with the users uid as the data property

Currently supports Google and Facebook logins

## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install

firebase-login depends on

[social-media-icons](https://github.com/hejty/social-media-icons)
