SublimeText3 - Options
====
1.Install Package Control in Console
```
import urllib.request,os,hashlib; h = '2915d1851351e5ee549c20394736b442' + '8bc59f460fa1548d1514676163dafc88'; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); by = urllib.request.urlopen( 'http://packagecontrol.io/' + pf.replace(' ', '%20')).read(); dh = hashlib.sha256(by).hexdigest(); print('Error validating download (got %s instead of %s), please try manual install' % (dh, h)) if dh != h else open(os.path.join( ipp, pf), 'wb' ).write(by)
```
2.Rename to Users\\[username]\AppData\Roaming\Sublime Text 3\Packages\User 
    
3.Done

Include package: 
* Alignment
* BracketHighlighter
* ChineseLocalization
* DocBlockr
* Emmet
* JsFormat
* Markdown Preview
* SideBarEnhancements
* SublimeLinter
* SublimeLinter-jshint

[PackageControl](https://packagecontrol.io/)

