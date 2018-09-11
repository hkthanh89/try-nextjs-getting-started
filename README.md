Pages folder contains web pages.

To support client-side navigation, use Link API.

Don't need to put components in a special directory. `components` folder can be named anything.

Support route masking: it will show a different URL on the browser than the actual URL that app sees. It only works with client side navigations, if page is reloaded, it gives 404 error because there is no such page (in `pages` folder) to load on server.

