# Purpose #
This project contains some scripts that are attemptimg to make building and testing [SEAndroid][seandroid] as painless as possible.

# Our presentation #
The presentation Burns and I put together for our class.
This covers a little bit about SELinux, SEAndroid, and what we did.

[Hosted on OpenShift](http://isa673-fotios.rhcloud.com)

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


[seandroid]: http://selinuxproject.org/page/SEAndroido

