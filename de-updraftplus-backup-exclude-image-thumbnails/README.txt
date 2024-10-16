=== Exclude Image Thumbnails From UpdraftPlus Backups ===
Contributors: davidbaumwald
Tags: updraftplus, updraft, backup, exclude, image, thumbnail, image size
Requires at least: 3.5
Tested up to: 6.6
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

An UpdraftPlus extension that excludes image size thumbnails, generated by WordPress, from Updraft backups.

== Description ==

A small plugin to exclude WordPress generated image thumbnails from Updraft backups, saving space.  The original, full-sized image is included in backups, so if a restoration from backup is needed, WP CLI or a plugin can be used to regenerate thumbnails using the original, full-size images.

Features:

*   Works for all image types and includes both native and custom image sizes added by themes and plugins.

== Installation ==

This section describes how to install the plugin and get it working.

1. Ensure UpdraftPlus Backup/Restore is installed and activated
1. Upload the plugin to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' screen in WordPress

== Changelog ==

= 1.0.4 =
* Updated assets.

= 1.0.3 =
* IMPROVED - Support WebP and AVIF fieltypes, props @josklever.

= 1.0.2 =
* IMPROVED - Regex update to prevent files with dimensions at the end of the file name from being filtered.

= 1.0.1 =
* IMPROVED - Regex filtering.
* FIXED - README content.

= 1.0.0 =
* Initial release.
