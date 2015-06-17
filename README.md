# Sublime Text Goodies

## Batch Install Packages

From [https://github.com/mrmartineau/SublimeTextSetupWiki/issues/3](https://github.com/mrmartineau/SublimeTextSetupWiki/issues/3):

>To install Package Control, http://sublime.wbond.net/Package%20Control.sublime-package needs to be placed inside of the Installed Packages/ folder. The next time Sublime starts, it will install the package.
>
>To batch install other packages, a Package Control.sublime-settings file needs to be placed into the Packages/User/ folder. Inside of the settings file should be a JSON object with the key "installed_packages" that references a list of package names. When Package Control starts, if any of those packages are not present, the will be automatically downloaded and installed.

Could easily simplify this process more by turning the steps above into a shell script or something else (e.g.  [https://gist.github.com/vishaltelangre/5075346](https://gist.github.com/vishaltelangre/5075346))
