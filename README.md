# Purpose #
This project contains some scripts that are attemptimg to make building and testing [SEAndroid][seandroid] as painless as possible.

# Goal #
I want these scripts to be able to cover the entire build process from 

1. Checking out the source
  * And any required SDKs/build tools
  * Including specifying branches
1. Checking for OS specific dependencies
  * Potentially making metapackages (RPMs, DEBs, etc)
1. Applying patches
  * Both branch and OS specific
1. Building the project
  * What good is all this source if we can't do anything with it?

# Relevant Links #

* [SEAndroid][seandroid]
* [AOSP Home](http://source.android.com/)
* [eLinux wiki](http://elinux.org/Android_Build_System)
* [Aleks Maus' Blog](http://aleksmaus.blogspot.com/2012/05/bulding-aosp-on-ubuntu-1204.html)
* [Al Sutton's Google+ Post](https://plus.google.com/113331808607528811927/posts/gDuDeGfVWQP)

# TODO #
* Add function to renice build and all children [ref](http://www.askdavetaylor.com/how_do_i_find_all_child_processes_in_unix.html)

[seandroid]: http://selinuxproject.org/page/SEAndroido

