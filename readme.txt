=== Prevent Password Reset ===
Contributors: greenshady
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=3687060
Tags: admin, password
Requires at least: 3.3
Tested up to: 3.3
Stable tag: 0.1

Prevents password reset for select users via the WordPress "lost password" form.

== Description ==

Prevents password reset for select users via the WordPress "lost password" form. This plugin adds a checkbox to each user's profile in the admin. If selected, it prevents the user's password from being reset.  If a user selects to prevent their password from being reset, no one can try to reset the password.  It stops it completely. 

Things to keep in mind:

* If you lose your password, you won't be able to reset it either unless you remove the plugin via FTP, go into the database, or have an administrator on the site change your password.
* This plugin does not disable the ability to edit/change a password from the user profile page. It merely blocks password resetting from the "lost password" form.

== Installation ==

1. Upload `prevent-password-reset` to the `/wp-content/plugins/` directory.
1. Activate the plugin through the 'Plugins' menu in WordPress.
1. Go to your user profile in the admin to select whether to prevent password resetting.

== Frequently Asked Questions ==

= Why was this plugin created? =

I needed a way to disable password resets for specific administrators on my site but leave this functionality open for the other 1,000s of users.  So, I chose to make this an option on a per-user basis.

= How do I use it? =

Once installed, a checkbox gets added to the "Personal Options" section of each user's profile page in the WordPress admin.  Anyone who can edit the user may check this box to disable password resets for that individual user.

= I forgot my password. What should I do? =

The easiest way to do this is to log into your hosting account via FTP.  Proceed to your plugins directory and delete the `prevent-password-reset` folder.  This should allow you to reset passwords for any user account via the "lost password" form.

If you don't have this type of access, you need to talk to a site administrator who does to have them update your password.

== Screenshots ==

1. Disabled password reset
2. Password reset checkbox on user profile page

== Changelog ==

**Version 0.1**

* Plugin launch.  Everything's new!