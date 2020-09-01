# Example App: Host Angular app on Firebase

```
npm install -g firebase-tools
```

```
firebase login
```

```
firebase init
```

- Arrow down to Hosting and press spacebar and enter.
- Use existing project that you have already created.
- Arrow down to that project and press enter
- What do you want to use as your public directory? dist/***your-firebase-project-name***
- Configure as a single-page app (rewrite all urls to /index.html)? (y/N) ***y***
- Overwrite index? ***N*** (default)

```
firebase deploy
```

**Hosting URL:** https://***your-firebase-project-name***.web.app


## To run this example

With [Angular CLI](https://github.com/angular/angular-cli) version 9.1.9 installed ...

Clone or download this repo and run `npm install`

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. 

The app will automatically reload if you change any of the source files.

## Demo

Unless you are using a custom domain, you can see your deployed page at https://your-firebase-project-name.web.app

Example URL: https://example-firebase-hosting.web.app (Note: I may delete this project at anytime when I approach the maximum number projects allowed on Firebase.)


