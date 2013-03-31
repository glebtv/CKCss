## CKCsss

This is an update of the CKCss plugin to work with CKEditor 4

This plugin adds full-featured inline CSS editing (similar to TinyMCE's "Edit CSS Style" button) to CKEditor.

## Usage
        
        config.extraPlugins = "...,colordialog,CKCss";
        config.toolbar = 'CMS';
        config.toolbar_CMS =
            [
                [..., 'CKCss']
            ];

You might need to add a locale file for your language

Note: you can enter most values directly in select boxes when "Type In" mode is selected.
Note: CKEditor 3 should also be fully working, just use language files from lang-ckeditor3

## Credits

Original plugin: http://code.google.com/p/ckcss/

Update of original plugin: http://extensions.joomla.org/extensions/extension-specific/jck-editor-extensions/15373

## License

Original plugin was GNU GPL v3
