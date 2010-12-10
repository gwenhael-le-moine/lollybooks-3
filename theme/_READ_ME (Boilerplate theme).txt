
Welcome to Boilerplate Starkers.

This theme might look like a little bit of a quagmire at first, blush because it is a merger of two great themes with a very minor bit by me, but stay with me, it'll all make sense in a bit, I promise.

And please let me know if you have any questions/suggestions/thoughts,
Atg
http://aarontgrogg.com/
aarontgrogg@gmail.com

-----------------------------------------------------------

CHANGE LOG:


v.2.1 2010-11-14:

Per WP, changed screenshot.png to reflect visual representation of site, not HTML4 Boilerplate logo.

Added additional classes (ie, lte7, lte8, lte9, where appropriate) to IE Conditional Comments in wrap <html> block.

Removed extraneous (explanatory) comments from HTML, hopefully you'll get it, if not, refer to HTML5 Boilerplate documentation (https://github.com/paulirish/html5-boilerplate/wiki).

Expanded Admin Page content, adding text and links to help users understand each option more clearly.

Removed the following from header.php and added as optional items on the Admin page:
- <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
- <meta name="viewport" content="width=device-width, initial-scale=1.0">
- <link rel="shortcut icon" href="/favicon.ico">
- <link rel="apple-touch-icon" href="/apple-touch-icon.png">

Added an option to the Admin page to include an IE-only CSS.

A few people recommended changing third-party links (Modernizr, jQuery, etc.) to Google repository.
I went back-and-forth on this, whether it made more sense to link to Google's repository (possible caching benefits, definite CDN benefits),
or whether it made more sense to give the developer the ability to control their own assets and serve from local files.
In the end, I went with local versions, mostly for version-control, but also because I figure if Google goes down, it could hurt your site;
if your site is down, whether JS is available isn't exactly your biggest problem...
In some future version I'd like to make both options available via the Admin page...
It would be fairly easy to change these paths if you wanted, in /wp-content/themes/boilerplate/boilerplate-admin/admin-menu.php, under "Create functions to add above elements to pages"

A few recommendations gratefully accepted from Micah (http://www.twolanedesign.com/):
- If Modernizr is unchecked, IEShiv will be added (inside an IE conditional comment).
- Add Async Google Analytics option to Admin Page.
  * Appears WP doesn't like GA, so this has been removed, but check here for instructions () on how to add it back in once you've downloaded Boilerplate...
- Removing WP version number via functions.php (http://digwp.com/2009/07/remove-wordpress-version-number/)
- Also recommended these two links which do contain some great scripts, but kind of go against the idea of Starkers (that less-is-more).
  You can easily add anything you like to the functions.php:
  http://digwp.com/2010/03/wordpress-functions-php-template-custom-functions/
  http://digwp.com/2010/04/wordpress-custom-functions-php-template-part-2/

Grabbed updated assets (css, js, etc.) from github per:
- http://github.com/paulirish/html5-boilerplate/compare/v0.9...v0.9.1
- http://github.com/paulirish/html5-boilerplate/compare/v0.9.1...v0.9.5





-----------------------------------------------------------

v.2.0.1 2010-10-06:
Boilerplate starts with the Starkers theme (http://starkerstheme.com/)...
  mixes in HTML5 Boilerplate (http://html5boilerplate.com/)...
    then makes a couple minor modifications...
	1) moved IE conditionals from <boby> to <html>, to better synch with Modernizr...
	2) above also allowed me to remove the <!--[if IE]><![endif]--> recommended by www.phpied.com/conditional-comments-block-downloads/...
	3) moved extraneous items (like Modernizr, jQuery, Belated PNG, etc.) to Admin panel (not the last item in the Settings drop-down)...
	The only extraneous items left in the mark-up are the two favicon references in header.php; read about it there.

* The directory "- MOVE TO ROOT" is filled with HTML5 Boilerplate goodness that 
  should be copied FROM that directory and pasted TO your blog's root directory.
* The .htaccess in that directory is filled with things which I honestly do not understand...
  I had to comment-out several items in order to get my WP installation to work, so, play if you like.

Be sure to read these "read me" type files as well:
	- _READ_ME.txt and _LICENSE.txt are from Starkers Theme
	- README.markdown is from HTML5 Boilerplate

-----------------------------------------------------------

v.1.0 2010-10-01:
Was pure crap, please ignore...