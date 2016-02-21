# Decisionary's Drupal Dev Lib

This is a development too lmeant to be used while build Drupal sites.  Currently it is targeted against Drupal 7, though
we will be updating it to Drupal 8 quite soon.

This library is currently under rapid and active development, and should not be used for any project, at this time.  We
will update it when we feel it is ready for basic use.

## Hooks

The first tool developed for this library is a 'hooks' toolset.  This toolset permits a developer to use the 'add_hook'
command to create a fragment hookfile that may then be edited to add the required hook code.  This command will create a
'hooks' directory if it does not already exist, and a file named [theme]_[hook].php.  The contents of that file will be
a basic PHP file with a function named [theme]_[hook].  This will allow developers to easily see what hooks are being
overridden in a theme, and to quickly find and edit the desired hook.

Using the 'combine_hooks' function will create a template.php file with all of the overridden hook definitions in it,
suitable for using in your drupal theme.
