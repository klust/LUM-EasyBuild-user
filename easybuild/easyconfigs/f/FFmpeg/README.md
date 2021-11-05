# FFmpeg instructions

  * [FFmpeg home page](https://ffmpeg.org/)

  * [FFmpeg internal git](https://git.ffmpeg.org/gitweb/ffmpeg.git)


## EasyBuild

  * [FFmpeg support in the EasyBuilders repository](https://github.com/easybuilders/easybuild-easyconfigs/tree/develop/easybuild/easyconfigs/f/FFmpeg)

  * [FFmpeg support in the CSCS repository](https://github.com/eth-cscs/production/tree/master/easybuild/easyconfigs/f/FFmpeg)

Note: It is not clear is NASM is really a dependency. From the documentation it looks
like it is only needed at build time so it appears to be wrongly marked as a dependency
in EasyBuild.

### 4.3.3 for CPE 21.08

  * We started from the EasyBuilders ones as those seem to be a lot more complete
    at least in the list of dependencies. It may be that this only influences
    the executables and not the libraries though.


