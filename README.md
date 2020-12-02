# FFmpeg Docker image

[![Docker Stars](https://img.shields.io/docker/stars/livesporttv/ffmpeg.svg?style=plastic)](https://registry.hub.docker.com/v2/repositories/livesporttv/ffmpeg/stars/count/)

This project prepares a minimalist Docker image with FFmpeg. It compiles FFmpeg from sources
following instructions from the [Compilation Guide](https://trac.ffmpeg.org/wiki/CompilationGuide).

You can install the latest build of this image by running `docker pull livesporttv/ffmpeg`.

This image can be used as a base for an encoding farm.

## Builds

You can use `livesporttv/ffmpeg` or `livesporttv/ffmpeg:4.3` to get the latest build based on ubuntu.

Format is `ffmpeg:MAJOR.MINOR-VARIANT` with MAJOR.MINOR in :

- 4.3
- snapshot

and VARIANT in :

- nvidia
- ubuntu

Please use [Github issues](https://github.com/livesporttv/ffmpeg/issues/new) to report any bug or missing feature.

## Keep up to date

See Dockerfile-env to update a version

- [FFMPEG_VERSION](http://ffmpeg.org/releases/): [GNU Lesser General Public License (LGPL) version 2.1](https://ffmpeg.org/legal.html)
- [OGG_VERSION](https://xiph.org/downloads/): [BSD-style license](https://git.xiph.org/?p=mirrors/ogg.git;a=blob_plain;f=COPYING;hb=HEAD)
- [OPENCOREAMR_VERSION](https://sourceforge.net/projects/opencore-amr/files/opencore-amr/): [Apache License](https://sourceforge.net/p/opencore-amr/code/ci/master/tree/LICENSE)
- [VORBIS_VERSION](https://xiph.org/downloads/): [BSD-style license](https://git.xiph.org/?p=mirrors/vorbis.git;a=blob_plain;f=COPYING;hb=HEAD)
- [THEORA_VERSION](https://xiph.org/downloads/): [BSD-style license](https://git.xiph.org/?p=mirrors/theora.git;a=blob_plain;f=COPYING;hb=HEAD)
- [LAME_VERSION](http://lame.sourceforge.net/download.php): [GNU Lesser General Public License (LGPL) version 2.1](http://lame.cvs.sourceforge.net/viewvc/lame/lame/LICENSE?revision=1.9)
- [OPUS_VERSION](https://www.opus-codec.org/downloads/): [BSD-style license](https://www.opus-codec.org/license/)
- [VPX_VERSION](https://github.com/webmproject/libvpx/releases): [BSD-style license](https://github.com/webmproject/libvpx/blob/master/LICENSE)
- [WEBP_VERSION](https://storage.googleapis.com/downloads.webmproject.org/releases/webp/index.html): [BSD-style license](https://github.com/webmproject/libvpx/blob/master/LICENSE)
- [XVID_VERSION](https://labs.xvid.com/source/): [GNU General Public Licence (GPL) version 2](http://websvn.xvid.org/cvs/viewvc.cgi/trunk/xvidcore/LICENSE?revision=851)
- [FDKAAC_VERSION](https://github.com/mstorsjo/fdk-aac/releases): [Liberal but not a license of patented technologies](https://github.com/mstorsjo/fdk-aac/blob/master/NOTICE)
- [FREETYPE_VERSION](http://download.savannah.gnu.org/releases/freetype/): [GNU General Public License (GPL) version 2](https://www.freetype.org/license.html)
- [LIBVIDSTAB_VERSION](https://github.com/georgmartius/vid.stab/releases): [GNU General Public License (GPL) version 2](https://github.com/georgmartius/vid.stab/blob/master/LICENSE)
- [LIBFRIDIBI_VERSION](https://www.fribidi.org/): [GNU General Public License (GPL) version 2](https://cgit.freedesktop.org/fribidi/fribidi/plain/COPYING)
- [X264_VERSION](http://www.videolan.org/developers/x264.html): [GNU General Public License (GPL) version 2](https://git.videolan.org/?p=x264.git;a=blob_plain;f=COPYING;hb=HEAD)
- [X265_VERSION](https://bitbucket.org/multicoreware/x265/downloads/): [GNU General Public License (GPL) version 2](https://bitbucket.org/multicoreware/x265/raw/f8ae7afc1f61ed0db3b2f23f5d581706fe6ed677/COPYING)
- [LIBZMQ_VERSION](https://github.com/zeromq/libzmq/releases/): [GNU Lesser General Public License (LGPL) version 3.0](https://github.com/zeromq/libzmq/blob/v4.3.2/COPYING.LESSER)
- [LIBSRT_VERSION](https://github.com/Haivision/srt/releases/): [MPL-2.0](https://github.com/Haivision/srt/blob/master/LICENSE)
- [LIBPNG_VERSION](https://sourceforge.net/projects/libpng/files/): [zlib/libpng License](https://sourceforge.net/p/libpng/code/ci/master/tree/LICENSE)
- [LIBARIBB24_VERSION](https://github.com/nkoriyama/ar
