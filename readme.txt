=== Fake Login Area ===
Contributors: dmchale
Tags: login, users, login area, user login
Requires at least: 2.6
Tested up to: 4.7
Stable tag: 1.05
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Allows you to display a user login form to nowhere.

== Description ==

Do you want your organization to appear bigger, or more important/legitimate/established than you are right now?
The presence of a user login area on your website will help you achieve that effect for your site visitors.

After installing this plugin, simply add the class "flaform" to the desired link. When the user clicks the link, a
modal window will appear with a user/password prompt to log in. Of course, the form does nothing and will always claim
to "fail" the login, but it still makes it look like you have more to offer!

Huge props to [SweetAlert](http://t4t5.github.io/sweetalert/), the awesome popup window that I am using with this
plugin.

== Installation ==

1. Upload the `fake-login-area` directory to the `/wp-content/plugins/` directory via FTP
1. Alternatively, upload the `fake-login-area_v#.#.zip` file to the 'Plugins->Add New' page in your WordPress admin
area
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Add the class "flaform" to your desired link. For example, you may have a CMS Page called "log in" or a link on your
homepage/sidebar, and create a link with the markup such as &lt;a href="#" class="flaform"&gt;Log In Now&lt;/a&gt;

== Frequently Asked Questions ==

= How do I get the form to appear? =
You just need to write a TINY amount of HTML to make use of this plugin. Add the class "flaform" to your desired link.
For example, you may have a CMS Page called "log in"  or a link on your homepage/sidebar and create a link with the
markup such as &lt;a href="#" class="flaform"&gt;Log In Now&lt;/a&gt;

= A login form that doesn't do anything? Seriously? =
Believe it or not, this plugin came about after a client legitimately asked for one of these. After discussing with
others, I decided this was something that other people may want as well. And it turns out, I was right :)

= Can I customize the form? =
Soon! Early versions of this plugin just want to put the functionality in your hands, but I plan to allow for all sorts
of customizations of the form including colors, all of the text, number of fields, field labels, and more.

== Screenshots ==

1. The login form itself
2. The "error" message displayed to the user

== Changelog ==

= 1.05 =
* Updated CSS to ensure that input[type=text] boxes stay hidden even when being forced to display:block by theme styles (discovered via twenty seventeen)
* Updated SweetAlert js and css supporting files to latest versions (as of 12/08/2016)
* Tested plugin through WP 4.7

= 1.01 =
* Updated for WordPress version tag
* Updated SweetAlert js and css supporting files to latest versions

= 1.0 =
* Initial Release

== Upgrade Notice ==

= 1.05 =
* Minor style update and latest version of sweetalert resources

= 1.01 =
* Updated for WordPress version tag
* Updated SweetAlert js and css supporting files to latest versions

= 1.0 =
* Initial Release