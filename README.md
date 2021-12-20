
README
======
Everything over at https://github.com/OpenMPT/openmpt applies to this

Fork Difference
======================

This fork adds to the Tracker the ability to do command line conversion of 1 file. Ie:
OpenMPT fileA.xm -convert fileB.s3m

This will open OpenModPlugTracker and convert to file to target file type (support file types are same as openmpt save formats: xm, it, s3m, mod).
Then it will close the program.

I needed this to compose music for the Virtual Boy via VirtualBeat by enthusi.

I'm sure there are better ways to do this, but this is the way I did it.
Maybe writing a whole new command line program which reuses some of the code from the tracker which handles file open and file save would be enough.

But I took the shortest path for me. I tried starting with libopenmpt only but there's just not enough information to do everything I want there.

License
-------

The OpenMPT/libopenmpt project is distributed under the *BSD-3-Clause* License.
See [LICENSE](LICENSE) for the full license text.

Files below the `include/` (external projects) and `contrib/` (related assets
not directly considered integral part of the project) folders may be subject to
other licenses. See the respective subfolders for license information. These
folders are not distributed in all source packages, and in particular they are
not distributed in the Autotools packages.
