# pypgh.org

This repository contains assets for the pypgh.org domain name.

One use for pypgh.org is as a URL shortener.
For instance, when sharing a link to a meetup event, you might want a short, memorable URL like `pypgh.org/our-great-event`, rather than something obscure like `www.meetup.com/quite-long-url/events/2934879123874122/`.

To do set this up, you would:

- Create a new HTML file in this repository with the filename `our-great-event.html` and the content `<meta http-equiv="refresh" content="0; URL=https://www.meetup.com/quite-long-url/events/2934879123874122/" />`
- Commit your new file to the `main` branch
- Push to GitHub

Within a few seconds, `pypgh.org/our-great-event` will redirect to the event listing.

Cloudflare Pages serves as the backend to "build", deploy, and serve the "website".
`pypgh.org` is an alias for the Cloudflare Pages application at `pypgh-org.pages.dev`.
Contact [pwharrison](https://github.com/pwharrison) for more information.
