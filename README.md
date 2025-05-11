# Moved to Codeberg: https://codeberg.org/floe/mobile-information-systems

## _Mobile Information Systems_ lecture materials

## Preface

This repository contains lecture materials (mostly slide sets) for a graduate course in mobile information systems. This course was initially held at [Bauhaus-Universität Weimar](https://www.uni-weimar.de/) in the summer semester 2015 for M.Sc. students in the [Computer Science and Media](http://www.uni-weimar.de/en/media/studies/computer-science-and-media-hci/medieninformatik-computer-science-and-media-msc/) degree. Prerequisites are a bachelor's degree in computer science and good programming skills (theoretical as well as practical) in Java.

_Comments, feedback and suggestions for improvement (including pull requests) are very welcome._

Some material was contributed by Prof. Dr. Matthias Kranz (University of Passau), Prof. Dr. Andreas Butz & Dr. Julie Wagner (Ludwig-Maximilians-Universität Munich) - thanks again!

## License

Original copyright © 2015 by [Florian Echtler](http://www.uni-weimar.de/en/media/chairs/mobile-media/). All material is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/) ![CC-BY-SA-NC](https://i.creativecommons.org/l/by-nc-sa/4.0/80x15.png).

As a very brief summary, this means that you can freely use these materials as long as you:

* provide attribution to the original author(s)
* share your modifications under the same or a similar license
* only use them for non-commercial purposes (such as teaching a university course)

Where possible, I have tagged material from external sources with CC (also under a compatible CC license), PD (public domain material) or FU (material which I believe to be included as "fair use").

## Contents

The course currently spans 10 weekly sessions with the following topics:

* Introduction & Basics
* Big Issues
* Networks & Location
* I/O on Small Screens Part 1 & 2
* Usage Context
* Privacy & Security
* UbiComp & IoT
* Mixed Reality
* Case Studies

There's also two extra lectures which are very topic-specific and might not work for some audiences:

* Android Internals
* Mobile Algorithms

The course is usually accompanied by an Android-based exercise class every two weeks. As the exercise materials are part of the graded course assignments, I'm currently not including them in this public release.

A video recording of the entire course (except lectures 10 and 12) is available on [Youtube](https://www.youtube.com/watch?v=8EmbrZJwMOI&list=PLjEglKdMOevWv4zPW0diw7iJFdT7s4sTP), also with CC license.

## git and ODT

The files in this repository are in OpenDocument format. If you add the following lines to your `~/.gitconfig` file and install the `odt2txt` utility, you can use the regular `git diff` command to compare versions etc. (see also [here](http://www-verimag.imag.fr/~moy/opendocument/) for more details).

    [diff "odf"]
    	textconv = odt2txt
