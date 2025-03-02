=== Share Drafts Publicly ===
Contributors: travislopes, pereirinha
Tags: admin, post, draft, share, public
Requires at least: 3.0
Tested up to: 4.8.1
Stable tag: 4.2.2

Provide a secret link to non-logged in users to view post drafts.

== Description ==
Need to show a post to someone but they don't have a WordPress user account? Share Drafts Publicly allows you to generate a private URL for non-users to view post drafts with a simple click of a button.

== Installation ==
= Requirements =
* WordPress version 3.0 and later (tested at 3.4.2)

= Installation =
1. Unpack the download package.
1. Upload all files to the `/wp-content/plugins/` directory, with folder
1. Activate the plugin through the 'Plugins' menu in WordPress

== Screenshots ==

1. Make a draft public by clicking the "Make Draft Public" button in the "Share Drafts Publicly" meta box.
2. Once a draft is shareable, you can copy the link or make the post private again.

== Changelog ==
= v1.1.5 =
* Added security enhancements.
= v1.1.4 =
* Added security enhancements.
= v1.1.3 =
* Fixed PHP error when determining if draft should be shown.
= v1.1.2 =
* Fixed PHP notice when getting draft URL or draft status.
* Fixed WordPress coding standards issues.
= v1.1.1 =
* Added "sdp_allowed_post_status" filter for setting which post statuses will present the "Share Drafts Publicly" metabox.
= v1.1 =
* Moved public draft controls to separate meta box.
= v1.0.1 =
* Fixed bug where secret key changes on saving a new draft
= v1.0.0 =
* Initial release