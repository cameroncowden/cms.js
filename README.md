![CMS.js Logo](https://raw.githubusercontent.com/cdmedia/cms.js/gh-pages/img/logo-md.png)

## meets

# p2p 


>CMS.js is fully client-side, Javascript site generator in the spirit of [Jekyll](https://github.com/jekyll/jekyll)
>that uses plain ol' HTML, CSS and Javascript to generate your website. CMS.js is like a file-based CMS.
>It takes your content, renders Markdown and delivers a complete website in Single-Page
>App fashion...without the aid of server-side scripting (no Node.js, PHP, Ruby, etc.).

![CMS.js Screenshot](https://raw.githubusercontent.com/cdmedia/cms.js/gh-pages/img/screenshot.png)


## Demo

Check out a working [demo here](dat://0d9e0bafd274f8ddee3327d1c2d6c196095d911ba64b73e0aed4d4e6087116e6)
*** Requires Beaker Browser or other dat-compatible modern browser ***

## Quick Start

>CMS.js currently supports two website modes, Github and Server.
>
>**Github Mode**
>
>This is the default mode for CMS.js. Host your website on Github using
>Github Pages, similar to Jekyll.
>
>**Server Mode**
>
>Use server mode if you choose to self host your content. Apache and NGINX servers are supported.
>If using server mode, make sure the server's directory indexing feature is enabled.
>
>* Apache - Make sure `htaccess` is enabled OR `Options Indexes` is set for your directory.
>* NGINX - Make sure `autoindex on` is set for your directory
>
>More info on server setup is available on the [wiki](https://github.com/cdmedia/cms.js/wiki/Server-Support-&-Setup)

No more need for external hosting, do it yourself with [Beaker!](https://beakerbrowser.com/)

Just visit the demo site using Beaker, then Fork the site to create a local copy for yourself which you'll serve up to the swarm whenever your computer is online. 

To create new posts, add files to the posts folder

**Install**

1. Visit the [demo site](dat://0d9e0bafd274f8ddee3327d1c2d6c196095d911ba64b73e0aed4d4e6087116e6/)
2. Configure `js/config.js` to your liking
3. Publish your changes within Beaker
4. ??
5. View your site!


## How it works

**Github Mode**

In Github mode, CMS.js uses the Github API to get the content of your gh-pages repo
and serve them as a full website.

**Server Mode**

In Server mode, CMS.js takes advantage of the Server's Directory Indexing feature. By allowing indexes,
CMS.js sends an AJAX call to your specified folders and looks for Markdown files.
After they are found, it takes care of everything else and delivers a full website.


## Migration from Jekyll

**Importing Posts**

Once you've forked this site and CMS.js is up and running, you'll see an exact duplicate of this site, but on your own new dat url. Now go to the folder on your local drive where it's stored (available under Beaker > Library > Sites > ( whatever you just named it ), and then delete all the existing posts (mine) and paste in yours!

**note it only supports .md**

**Importing Pages**

Copy all of your Markdown pages from your Jekyll projects root folder into your designated
CMS.js pages folder.


## Thanks!

* [Poole](https://github.com/poole/poole) (*Default Theme*)
* [CMS.JS](https://github.com/cdmedia/cms.js) (non-p2p original version, i.e. 99.9% of what you see here)
* [jQuery](https://jquery.com/)
* [Marked](https://github.com/chjj/marked)


## Contributing

All forms of contribution are welcome: bug reports, bug fixes, pull requests and simple suggestions.
If you do wish to contribute, please follow the [Airbnb Javascript Style Guide](https://github.com/airbnb/javascript/tree/master/es5) Thanks!


## List of contributors

You can find the list of contributors [here](https://github.com/cdmedia/cms.js/graphs/contributors).
