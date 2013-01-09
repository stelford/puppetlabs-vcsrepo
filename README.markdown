vcsrepo
=======

Note
----

This fork provides the patch from xgoat already rolled in,
along with the changes to make it ruby 1.8.7 compliant. If
this doesn't mean anything to you, then this is probably 
the wrong repo for you .. or .. in the words of Obi Wan Kenobi;

This is not the repo you are looking for

(I think he said that)

Purpose
-------

This provides a single type, `vcsrepo`.

This type can be used to describe:

* A working copy checked out from a (remote or local) source, at an
  arbitrary revision
* A "blank" working copy not associated with a source (when it makes
  sense for the VCS being used)
* A "blank" central repository (when the distinction makes sense for the VCS
  being used)

Supported Version Control Systems
---------------------------------

This module supports a wide range of VCS types, each represented by a
separate provider.

For information on how to use this module with a specific VCS, see
`README.<VCS>.markdown`.

License
-------

See LICENSE.
