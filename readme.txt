=== Plugin Name ===
Contributors: ollieread
Tags: magic quotes, removal
Requires at least: 3.0
Tested up to: 3.1

This plugin reverses the add_magic_quotes() core WordPress function.

== Description ==

WP-NMMQ or WordPress No more magic quotes is a small and simple plugin that reverses the 
add_magic_quotes() code within the WordPress core that automatically escapes $_POST, 
$_GET, $_COOKIE and $_SERVER without any regard for the magic_quotes setting within php.ini.

== Installation ==

1. Extract the archive wherever you want
2. Move the `WP-NMMQ.php` plugin file to `/wp-content/plugins/`
3. Upload and enabled via the admin area

== Frequently Asked Questions ==

= What exactly does this plugin enable me to do? =

It enables you to create WordPress plugins that handle data passed via $_POST, $_GET, $_COOKIE or _$SERVER 
without having to write your own hack to prevent WordPress escaping it.

= Will this plugin benefit me? =

This plugin will only really benefit you, if you are an individual planning on developing a WordPress plugin that
uses one of the predefined data variables as listed above.