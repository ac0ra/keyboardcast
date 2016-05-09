# keyboardcast

Just providing source download since original download page is not available (at least at the moment).

--------------------------

[https://launchpad.net/keyboardcast/]

[http://blogs.gnome.org/desrt/2005/12/04/keyboardcast/]

The purpose of keyboardcast is to allow you to send keystrokes to multiple
X windows at once. This allows you, for example, to control a number of
terminals connected to different but similar hosts for purposes of mass-
administration.

You can also select non-terminals. If you come up with a reasonable use
for this ability I'd be interested in hearing about it.

The program can select windows to send to either by matching their titles
(using a substring) or by clicking on them (in a method similar to GIMP's
screenshot feature).

The program also features the ability to spawn off multiple instances of
gnome-terminal executing a single command on multiple arguments (for example
executing 'ssh' on several hosts). The gnome-terminals are invoked with
the profile 'keyboardcast' if it exists (so, for example, your font size
can be smaller).
