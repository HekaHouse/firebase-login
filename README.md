# firebase-login
`<firebase-login>` is a firebase login prompt presented in a paper-dialog

    <firebase-login firebase-root="https://YOUR-FIREBASE.firebaseio.com"></firebase-login>

After authentication a paper-fab logout button is displayed in lower right corner

Authentication triggers an iron-signal to fire named <i>logged-in</i> with the users uid as the data property

Depends on <a href="https://github.com/hejty/social-media-icons">social-media-icons</a>

@group HekaHouse
@element firebase-login
@demo demo/index.html
