# Use custom JSON
Custom JSON support is implemented in all official clients. In order to make your own JSON, you need:
- Something that lets you deploy websites (ex: GitHub Pages)
- JSON knowledge

Ready? First, make a folder. Name it anything you want, it doesn't matter, as long as you can deploy it to the internet.

Create a JSON file. Call it anything you want, it doesn't matter.

Next, you can start making your JSON! It needs to be a specific structure for our clients. Here's an example (which is the official JSON from 9/28/25):

```json
{
    "sitelink": ["intro_site/bob.html", "know_your_stuff/index.html", "https://freakybob.site", "https://fs.freakybob.site", "https://www.youtube.com/watch?v=dQw4w9WgXcQ"],
    "sitename": ["hi.bob", "know.bob", "freaky.link.bob", "fs.link.bob", "rick.roll"]
}
```

As you can see, the sitelink that's 1st goes with the 1st sitename (ex: intro_site/bob.html is 1st sitelink, and hi.bob is 1st sitename).

You can set it up like that, and you'll have a compatible JSON.

You can deploy it to the internet in any way you'd like, but we use [GitHub Pages](https://docs.github.com/en/pages/quickstart).

Last, you can use it on supported clients. For our client, you can click "use custom JSON source (for experienced users)" and put in your URL.
> [!WARNING]
> Custom JSON in our web client has not been tested yet. If you experience problems, [report an issue](https://github.com/Freakybob-Team/bobnet/issues/new).