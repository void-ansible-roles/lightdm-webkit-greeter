lightdm-webkit-greeter
======================


What is does this role do?
--------------------------


Meta
----

Files Managed:
  * /etc/lightdm/lightdm-webkit-greeter.conf
  * /usr/share/lightdm/lightdm.conf.d/90-lightdm-webkit.conf
  * /usr/local/bin/fixScreens
  * /usr/local/bin/lightdm-setup
  * /usr/local/bin/lightdm-cleanup

Defaults Provided:
  * LWG_theme_name: simple

Variables Required:
  * None

Optional Variables:
  * LWG_theme_name: What theme should be used.  Name should match the folder name of the theme stored in /usr/local/lightdm-webkit/themes/

Files Required:
  * None

Optional Files:
  * None

Conflicting Roles:
  * None

Depends On:
  * [lightdm](https://github.com/void-ansible-roles/lightdm)
