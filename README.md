# ballmaxxing.com

This is the source code for [ballmaxxing.com][site], a website.

The website is about ballmaxxing.

Ballmaxxing is a thing.

[site]: https://ballmaxxing.com
[x]: https://x.com/ballmaxxed

---

## What is in here

One HTML file. One stylesheet. Three public-domain images. A `CNAME`. A
`.nojekyll`. A favicon shaped, gently, like the topic.

```
ballmaxxing.com/
├── index.html        the website
├── styles.css        what the website looks like
├── favicon.svg       a single small circle
├── CNAME             ballmaxxing.com
├── robots.txt        yes, the robots are allowed
├── sitemap.xml       there is one page on the sitemap
└── assets/
    ├── cantaloupe.jpg     Wellcome Collection, 1890, chromolithograph
    ├── testis-gray.png    Gray's Anatomy, 1918, plate 1148
    ├── phrenology.jpg     19th-century engraving, artist unknown
    └── CREDITS.md         attribution and licenses
```

That is the whole project. Anyone who tells you the project is more
ambitious than that is mistaken.

## Why does this exist

A domain was available. A topic was in the news. Someone had ten minutes
and three espressos. The rest assembled itself.

## Tech stack

- HTML
- CSS
- A grudging acceptance that some pages should not be a single-page
  application

There is no JavaScript on the live page. There is no build step. There is
no framework. There are no dependencies. There is, conspicuously, no
analytics. If you would like to know how many people have visited the
site, the answer is: enough.

## Running it locally

```sh
python3 -m http.server 8765
# then open http://127.0.0.1:8765
```

If `python3 -m http.server` feels too modern, you can also double-click
`index.html`. The fonts will look slightly worse and the relative paths
will still work. This is a feature of the early-2000s web that we have
chosen to preserve.

## Deployment

GitHub Pages, from `main`, root directory. The `CNAME` file does the
custom-domain work. There is no CI. There is no preview environment.
There is a commit, and then there is a website.

## Pledge

The site is the site. There is no shop, no Substack, no Patreon, no
podcast, no Discord, no Telegram, no DM-for-info account, no coaching
tier, no app, no $499 newsletter, no Tulum retreat, no five-step morning
routine, and no book with a subtitle like *A Practitioner's Guide*.

This repository will not be the first place that pledge breaks.

## Contributing

Pull requests are welcome on these terms:

- Typo fixes, accessibility improvements, and broken-link fixes: yes.
- New press citations as the story develops: yes.
- New "Field observation" entries that are funny and clearly fictional: yes.
- Anything pitching a supplement, a coaching tier, a course, a podcast
  collaboration, an "exclusive media partnership," or a brand
  integration: closed without comment.

## Where to find us

- Site: [ballmaxxing.com][site]
- X: [@ballmaxxed][x]

That is the entire public surface.

## Acknowledgments

- The reporters at Vice, *Men's Health*, and OutKick, who did the
  legwork. (The other dozen outlets mostly aggregated.)
- The Wellcome Collection, for letting people use their images.
- Henry Gray, 1827–1861, for the anatomy.
- The unnamed engraver of the phrenology head.
- The cantaloupes, who have, throughout, declined to comment.

## License

MIT. Do what you want with the markup and the styles. Image attributions
and their separate licenses are listed in
[`assets/CREDITS.md`](assets/CREDITS.md).
