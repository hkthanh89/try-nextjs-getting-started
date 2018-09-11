Pages folder contains web pages.

To support client-side navigation, use Link API.

Don't need to put components in a special directory. `components` folder can be named anything.

Support route masking: it will show a different URL on the browser than the actual URL that app sees. It only works with client side navigations, if page is reloaded, it gives 404 error because there is no such page (in `pages` folder) to load on server.

Style was written inside style tag and template string
Styled jsx works as a babel plugin. It will parse all of the CSS and apply it in the build process.
It also supports having constraints inside styled-jsx. In the future, you will be able to use any dynamic variable inside styled-jsx. That is why CSS needs to go inside of a template string. ({``})