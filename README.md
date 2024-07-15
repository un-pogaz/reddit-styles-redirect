> [!NOTE]  
> If you're wondering why the chrome extension recently requested new permissions, please see https://github.com/tom-james-watson/old-reddit-redirect/issues/117

# Reddit Styles Redirect

[Latest version](https://github.com/un-pogaz/reddit-styles-redirect/releases/latest)

Dislike Reddit's redesign? Reddit Styles Redirect will ensure that you always load the wanted design instead.

Will force all reddit.com usage to the reddit url of the style, between "Old classic" (old.reddit.com), "Legacy boxy" (new.reddit.com) and "Flat and round" (sh.reddit.com) styles.<br>
Will work when navigating to the site, opening links, using old bookmarks. Works regardless of whether you are logged in or not, and in incognito mode.

Also has a new minor fixes and quality of life improvements like:

- Removing the undismissable cookie banner
- Rewriting links to galleries to the raw old reddit comments page

#### Redirected domains

- `reddit.com`
- `www.reddit.com`
- `np.reddit.com`
- `amp.reddit.com`
- `i.reddit.com`

#### Whitelisted domains

- `old.reddit.com`
- `new.reddit.com`
- `sh.reddit.com`

## Development

> [!NOTE]  
> There are currently two separate versions of this extension - manifest V2 and manifest V3.
> Chrome is phasing out manifest V2, so we're forced to migrate to to avoid the extension getting removed. However, the V3 version currently doesn't seem compatible with Firefox, so V2 will be hanging around for a while.
> TL;DR: Chrome = V3, Firefox = V2

Ensure you have [`node`](https://nodejs.org/en) installed. Then run `make run` to start the live-reloading development server. This will open a browser window with the extension installed for testing.

Once you've verified things are working correctly locally you can fork this repo and submit a pull request with your changes.

## License

Code copyright Tom Watson (original) and un_pogaz (fork). Code released under [the MIT license](LICENSE.txt).
