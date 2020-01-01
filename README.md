# [browsercontrollers.store](STORE.md)

:zap: BrowserController - A new [distribution channel](STORE.md) for your apps. More control than a browser extension, more lightweight than an Electron app. Just as powerful as Node.

## Get started

You can develop for Chrome right away, without the need to pass the Chrome Webstore, nor limit yourself to the extension APIs. You can distribute on all Desktop platforms, and package as a binary, or npm global. 

To get started, fork the [browsercontroller-boilerplate](https://github.com/dosyago/browsercontroller-boilerplate). When you're done submit your app to the store.

## Fork the boilerplate

Go to [dosyago/browsercontroller-boilerplate](https://github.com/dosyago/browsercontroller-boilerplate) and fork it. It's a template library so you can start building your new app right away. 

## Submit your app

Once you have your app, make sure you pass our requirements:

- As of now, app must be open source on GitHub and must use [browsercontroller-boilerplate](https://github.com/dosyago/browsercontroller-boilerplate)
- You must package as a binary (using either the built-in nexe script, or using zeit/pkg yourself) for windows, mac and linux.
- You must upload the binaries to your releases page

Then, open a PR to add your app to [`STORE.md`](STORE.md), following the format there. Make sure to include:

- your app name
- a brief description (limit is 250 words)
- a link to the GitHub releases page for your app that lists binaries for windows, mac and linux.

## After you're approved

Once you're approved, we'll merge your PR and you're part of the store.

On the store you'll find useful Chrome-enabled apps that extend the browsing experience in ways you probably never thought possible. 

## FAQ

### Can I make money from my app?

We're not stopping you from monetizing your app in some ways, but right now we don't provide any way to for you to collect fees from your users.

### Will you have a proper website in future?

Yes, if this thing becomes big enough that a GitHub document is no longer a good database, we'll move to a proper website that lists all the browser controllers in the store.
