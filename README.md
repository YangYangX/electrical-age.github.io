# Official Electrical-Age website [![Build Status](https://travis-ci.org/Electrical-Age/electrical-age.github.io.svg)](https://travis-ci.org/Electrical-Age/electrical-age.github.io)

This is the source code of the official [Electrical-Age/ElectricalAge](https://github.com/Electrical-Age/ElectricalAge) website available online at https://electrical-age.net.

The code source of the mod is available in the [Electrical-Age/ElectricalAge](https://github.com/Electrical-Age/ElectricalAge) repository.

## Jekyll

The website is based on [Jekyll](https://jekyllrb.com/). Before getting started, you'll need to install:

1. [Ruby](https://www.ruby-lang.org/)
2. [Bundler](http://bundler.io/)

Then, run the following command to install Jekyll and the required gems:

```sh
$ ./script/install.sh
```

Or install them manually:

```sh
$ gem update
$ gem install jekyll
$ gem install rmagick -- '--with-opt-dir="[path to ImageMagick]"'
$ gem install jekyll-responsive_image
$ jekyll serve
```

Finally, run the `./script/server.sh` script from the root folder to build and serve Jekyll locally. Navigate to [http://localhost:4000](http://localhost:4000) to see the website.

## License

The source code of this mod is licensed under the LGPL V3.0 licence. See http://www.gnu.org/copyleft/lesser.html for more informations.

All graphics and 3D models are licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported License. To view a copy of this license, visit http://creativecommons.org/licenses/by-nc-sa/3.0/.