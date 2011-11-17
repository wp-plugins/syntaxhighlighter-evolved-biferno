=== SyntaxHighlighter Evolved Biferno ===
Contributors: sandrobilbeisi
Donate link: http://www.viper007bond.com/wordpress-plugins/syntaxhighlighter/donate/
Tags: syntax, highlighter, biferno, code, CSS, html, bfr, sourcecode
Requires at least: 2.7
Tested up to: 3.2.1
Stable tag: 1.0.1

Adds support for the Biferno language to the SyntaxHighlighter Evolved plugin using the [sourcecode language="biferno"] tag.
== Description ==

<b>SyntaxHighlighter Evolved Biferno</b> is a plugin for self-hosted WordPress that adds support to Alex Mills' (Viper007) [SyntaxHighlighter Evolved](http://wordpress.org/extend/plugins/syntaxhighlighter/) plugin for the Biferno language .

It provides a brush designed to work with the SyntaxHighlighter Evolved WordPress plugin .

= Features: =

 - Biferno opening and closing tags are captured
 - Variables within double-quoted strings are captured
 - Numerical values are captured
 - a large superset of Biferno's function names are recognized
 - Custom function names are captured



= Notes: =

- To be able to use this plugin, you will need the SyntaxHighlighter Evolved plugin installed.

- this plugin follows the programming conventions outlined by [Alex Mills](http://www.viper007bond.com/) (Viper007) for extending  his plugin: [Adding A New Brush (Language)](http://www.viper007bond.com/wordpress-plugins/syntaxhighlighter/adding-a-new-brush-language/)

- uses my [Biferno JavaScript brush for SyntaxHighlighter](http://www.sandrobilbeisi.org/wp/works/web-development/biferno-javascript-brush-for-syntaxhighlighter-shbrush-js/).

- this plugin is based on similar work by apollox2: [Scott Selikoff](http://www.selikoff.net/) [SyntaxHighlighter Evolved AppleScript](http://wordpress.org/extend/plugins/syntaxhighlighter-evolved-applescript/)

- [SyntaxHighlighter Evolved](http://wordpress.org/extend/plugins/syntaxhighlighter/) Wordpress plugin by Alex Mills (Viper007) is based on the [SyntaxHighlighter JavaScript package by Alex Gorbatchev](http://alexgorbatchev.com/SyntaxHighlighter/).


== Installation ==

###Prerequisite###

In order to use SyntaxHighlighter Evolved Biferno, you must first install [SyntaxHighlighter Evolved](http://wordpress.org/extend/plugins/syntaxhighlighter/).

###Installation###

Extract all files from the ZIP file, making sure to keep the file/folder structure intact, and then upload it to /wp-content/plugins/.

###Plugin Activation###

Go to the admin area of your WordPress install and click on the "Plugins" menu. Click on "Activate" for the "SyntaxHighlighter Evolved: Biferno" plugin.

###Plugin Usage###

Just wrap your code in `[sourcecode language="biferno"]`your code here `[/sourcecode]`
or
wrap your code in `[biferno]`, such as `[biferno]` code here `[/biferno]` .

The shortcodes accept a wide variety of parameters. For details, see the bottom of the SyntaxHighlighter Evolved's settings page.

== Frequently Asked Questions ==

= The code is just being displayed raw. It isn't being converted into a code box or anything. What's wrong?  =

Make sure your theme's `footer.php` file has `<?php wp_footer(); ?>` somewhere inside of it, otherwise the plugin won't be able to do it's thing.

> **INFO:** When you find a that a keyword or a other special word of Biferno is not highlighted. Please write entry into the forum of this plugin. -> <a href="http://wordpress.org/tags/syntaxhighlighter-evolved-biferno?forum_id=10" title="Wordpress Support Forum">Support Forum</a>

== Screenshots ==

1. This is a sample image of the plugin in action as applied to Biferno code.

== Upgrade Notice ==

= 1.0.1 = This is the first peer-reviewed and published version.

== Changelog ==
= 1.0.1 =
* Initial release