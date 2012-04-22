How to build platform

1. Get android open source.
    : version info - Android icecreamsandwich 4.0.3
    ( Download site : http://source.android.com )

2. Overwrite modules that you want to build.
- \external\libjpega : Write "libjpega \" into "build\core\user_tags.mk" so that add this module.
- \external\libexifa : Write "libexifa \" into "build\core\user_tags.mk" so that add this module.

3. Copy the files to original Gingerbread source tree (overwrite) and then make

4. make update-api

5. make