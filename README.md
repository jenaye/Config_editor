# Config_editor

 <i class="icon-cog"></i> **Settings**

 > **Sublime text 3**

### Install package control

```
import urllib.request,os,hashlib; h = '2915d1851351e5ee549c20394736b442' + '8bc59f460fa1548d1514676163dafc88'; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); by = urllib.request.urlopen( 'http://packagecontrol.io/' + pf.replace(' ', '%20')).read(); dh = hashlib.sha256(by).hexdigest(); print('Error validating download (got %s instead of %s), please try manual install' % (dh, h)) if dh != h else open(os.path.join( ipp, pf), 'wb' ).write(by)

```

### how it work ? 

Ctrl + Shift + P  =>  just write " Install "

 > **List of packages**

| Package 
| :------- | 
| Material theme |
| Nettus & Fetch |
| PlainTasks |


 * PlainTasks :  Preferences > Packages Settings > PlainTasks > User settings, add this code


```
{
    "date_format": "%d/%m/%Y à %H:%M",
    "color_scheme": "Packages/PlainTasks/tasks-eighties-dark.hidden-tmTheme",
    "font_size": 15

}

```




* Material theme : Preferences > Color Scheme > Material theme > Darker


* Nettus & Fetch : Ctrl + Shift + p

| Actions
| :------- | 
| Fetch File |
| Fetch manage |
| Fetch Package |