# Casper Fork

A minimalist fork of the default theme for [Ghost](http://github.com/tryghost/ghost/).

This theme makes a few assumptions on how your blog is configured. For this reason, this theme may not suit everyone's needs.

## Changes

Below is a listing of features that have been removed or modified.

You can view the code changes by going [here](https://github.com/gchan/Casper/compare/TryGhost:master...master).

### Header
* Removed blog logo and blog cover.
* Simple blog heading title and blog description.

### Index/Tag (Listing of posts)
* Date and tags comes after the post title.
* Removed post excerpts.
* Removed pagination (assumes you have configured your blog to have '0 posts per page' i.e. no pagination).

### Post/Page
* Removed blog logo and blog title.
* Date format changed from `DD MMM YYYY` to `D MMMM YYYY` (for example `09 Sep 2014` is now `9 September 2014`).
* Post author is incorporated in the blog meta, appearing after the post date and before the tags. The post author links back to the blog home page.

### Footer
* Minimalist footer `A blog by <a href="{{@blog.url}}">{{@blog.title}}</a>` (assumes your blog title is the author's name).
* Removed RSS/subscribe link (although still accessible).
* Remove copyright and reference to Ghost (sorry!).
* Removed social media icons.
* Removed author name, bio, location and website.

### Styling and layout (not covered above)
* Slightly off-centre (margin-left: 10%).
* Disabled animation of homepage header.
* Disabled (most) unused CSS rules.
* Post content links are styled blue.
* Minified `screen.css` to `screen-min.css` using [clean-css](https://github.com/GoalSmashers/clean-css).

### Assets
* Removed `/js` folder for `fitvid.js` and `index.js`.
* Removed `/fonts` folder as icons are not used.

## Copyright & License

Copyright (c) 2013-2014 Ghost Foundation - Released under the MIT License.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
