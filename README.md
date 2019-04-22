# Fedihub

Fedihub is an electron app made to connect to many fediverse instances (mastodon, pleroma, etc.). It only needs to have web interface. It's inspired from Tweeten, a client for Twitter.

# Installation & manual

The app is pretty dumb. To add another instances you have to duplicate the following code from `index.html`:

```
tab = {
    title:"Niu.moe",
    src:"https:niu.moe"
}

tabGroup.addTab(tab);
```

Edit it with the `title` you want and your instance's URL `src`.

You only need `npm` as installed package.

* Install dependencies: `npm i`
* Launch the app: `npm start`.

# Note

Currently in alpha. You are free to contribute to increase quality! :-)
