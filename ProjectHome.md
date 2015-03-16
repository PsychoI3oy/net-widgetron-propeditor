Rooted Android phone owners sometimes have to edit build.prop (or build.boardname.prop) files to tweak settings like hsdpa, model name displayed, or other things. The problem is that this has to either be done on a computer with file pushing back and forth or via cli on the phone. Furthermore, these files are overwritten whenever a new Android update is flashed.

PropEditor allows you to edit the build.prop files on the phone, with a GUI that shows you a list of all the properties, and suggests modifications for given properties (to save you mistyping complicated and critical information). Furthermore, PropEditor allows you to merge two .prop files, so you can save your common edits on your sdcard and overwrite these settings in a newly flashed system build.prop.

![http://blargification.com/pe/editor.png](http://blargification.com/pe/editor.png) ![http://blargification.com/pe/suggest.png](http://blargification.com/pe/suggest.png)


Version 0.3 is still considered Alpha quality **AND IS EVEN MORE DANGEROUS** due to direct editing on /system. No guarantees are made for anything. Use at your own risk. PLEASE visually inspect files after editing to make sure the edits worked. There's backup buttons. Use them.

Source is hosted on github, see link in sidebar.

See README for updates in 0.3