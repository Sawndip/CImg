![alt tag](http://cimg.eu/img/CImgLogo2.jpg)

The <font color="#000066"><b>CImg Library</b></font> is a <b>small</b>, <b>open source</b>, and modern C++ toolkit</b> for <b>image processing</b>, designed with these properties in mind:

- <font color="#000066"><b>CImg</b></font> defines <i>classes</i> and <i>methods</i> to manage images in your own C++ code. You can use <font color="#000066"><b>CImg</b></font> to load/save various file formats, access pixel values, display/transform/filter images, draw primitives (text, faces, curves, 3d objects, ...), compute statistics, manage user interactions on images, and so on...

- <font color="#000066"><b>CImg</b></font> defines a single image class able to represent datasets having up to <i>4-dimensions</i> (from 1d scalar signals to 3d hyperspectral volumetric images), with <i>template pixel types</i> (<tt style="font-family:monospace;">bool,char,int,float,...</tt>). It also handles image <i>collections</i> and <i>sequences</i>.

- <font color="#000066"><b>CImg</b></font> is <i>self-contained</i>, <i>thread-safe</i> and <i>highly portable</i>. It fully works on <i>different operating systems</i> (<tt style="font-family:monospace;">Unix,Windows,MacOS X,*BSD,...</tt>) and is compatible with <i>various C++ compilers</i> (<tt style="font-family:monospace;">Visual C++,g++,clang++,icc,...</tt>).

- <font color="#000066"><b>CImg</b></font> is <i>lightweight</i>. It is made of a single header file <a href="https://raw.githubusercontent.com/dtschump/CImg/master/CImg.h"><tt style="font-family:monospace;">CImg.h</tt></a> that must be included in your C++ source. It defines only <i>four</i> different classes, encapsulated in the namespace <tt style="font-family:monospace;">cimg_library</tt>. It can be compiled using a minimal set of standard C++ and system libraries only. <i>No need for exotic or complex dependencies</i>.

- Although not mandatory, <font color="#000066"><b>CImg</b></font> can use functionalities of external tools/libraries such as <a href="http://libboard.sourceforge.net/">Board</a>, <a href="http://ffmpeg.mplayerhq.hu/">FFMPEG</a>, <a href="http://www.fftw.org/">FFTW3</a>, <a href="http://www.graphicsmagick.org/">GraphicsMagick</a>, <a href="http://www.imagemagick.org/">ImageMagick</a>, <a href="http://www.netlib.org/lapack/">Lapack</a>, <a href="http://curl.haxx.se/libcurl/">libcurl</a>, <a href="http://www.ijg.org/">libjpeg</a>, <a href="http://www.libpng.org/pub/png/libpng.html">libpng</a>, <a href="http://www.libtiff.org/">libtiff</a>, <a href="http://www.imagemagick.org/Magick++/">Magick++</a>, <a href="http://www.openexr.com/">OpenEXR</a>, <a href="http://http://opencv.willowgarage.com/wiki/">OpenCV</a>, <a href="http://www.openmp.org/">OpenMP</a> or <a href="http://xmedcon.sourceforge.net/">XMedCon</a>. Moreover, a simple <i>plug-in</i> mechanism allows any user to directly enhance the library capabilities according to his needs.

- <font color="#000066"><b>CImg</b></font> is a <i>free, open-source library</i> distributed under the <a href="http://www.cecill.info/licences/Licence_CeCILL-C_V1-en.txt"><i>CeCILL-C</i></a> (close to the GNU LGPL) or <a href="http://www.cecill.info/licences/Licence_CeCILL_V2-en.txt"><i>CeCILL</i></a> (compatible with the GNU GPL) licenses. It can be used in commercial applications.

<blockquote>
  <font color="#000066"><b>CImg</b></font> stands for <font color="#000066"><b>Cool Image</b></font> : It is <i>easy to use</i>, <i>efficient</i> and is intended to be a very pleasant toolbox to design image processing algorithms in C++. Due to its generic conception, it can cover a wide range of image processing applications.
</blockquote>
