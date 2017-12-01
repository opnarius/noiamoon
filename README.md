# Noia Moon
![Preview](http://i66.tinypic.com/2d457n.png)

Fork of the theme [Noia Fox](https://addons.mozilla.org/en-US/firefox/addon/noia-fox/) by David Vincent for Pale Moon. Icons by Carlitus.

## Building
Simply download the contents of the "src" folder  and pack the contents of both the "options" and "theme" folders into a .zip file each. Then, rename the files to .xpi. Pack both of these XPI files with the install.rdf file in the "src" folder into another .xpi. Then, drag into the browser. You can install these separately if you wish, however it is strongly advised to install together.
### Building using npm scripts
This fork provides npm scripts to help building this extension. 
```bash
npm run release
```
Will complile the Options and Theme extension into a single installable package. 
>Note current scripts utilize winrar cli in path.

## Download
You can grab the latest release either from the Releases section.

## Other fixes

youtude user agent string: `Mozilla/5.0 (Windows NT 6.1; WOW64; rv:42.0) Gecko/20100101 Firefox/42.0 PaleMoon/27.0.0`
general.useragent.override.servethehome.com: `Mozilla/5.0 (Windows NT 6.1; WOW64; rv:52.9) Gecko/20100101 Firefox/52.9 (Pale Moon)`