# malaysia-state-flag-icon-css
> Forked from [`lipis/flag-icon-css`](https://github.com/lipis/flag-icon-css)

A collection of Malaysian state flags in SVG — plus the CSS for easier integration.
See the [demo](http://lipis.github.io/flag-icon-css/).

Install
-------

```bash
yarn add github:jwarby/malaysia-state-flag-icon-css
```

## Usage

For using the flags inline with text add the classes `.malaysia-state-flag-icon` and
`.malaysia-state-flag-icon-xxx` (where `xxx` is the
[abbreviation](https://en.wikipedia.org/wiki/States_and_federal_territories_of_Malaysia)
of a state's name) to an empty `<span>`. Example:

```html
<span class="malaysia-state-flag-icon malaysia-state-flag-icon-mlk"></span>
```

You could also apply this to any element, but in that case you'll have to use the
`flag-icon-background` instead of `flag-icon` and you're set. This will add the
correct background with the following CSS properties:

```css
background-size: contain;
background-position: 50%;
background-repeat: no-repeat;
```

Which means that the flag is just going to appear in the middle of an element, so
you will have to set manually the correct size of 1 by 2 ratio.

### List of codes

- `jhr`: Johor
- `kdh`: Kedah
- `ktn`: Kelantan
- `mlk`: Melaka
- `nsn`: Negeri Sembilan
- `phg`: Pahang
- `png`: Penang
- `prk`: Perak
- `pls`: Perlis
- `sbh`: Sabah
- `swk`: Sarawak
- `sgr`: Selangor
- `trg`: Terengganu
- `kul`: Kuala Lumpur
- `lbn`: Labuan
- `pjy`: Putrajaya
- `ft`: Federal territories

## Development

Run the `npm install` to install the dependencies after cloning the project and
you'll be able to:

To watch for changes and live reload if served

```bash
$ grunt
```

To build `*.less` files

```bash
$ grunt build
```

To serve it on `localhost:8000`

```bash
$ grunt connect
```

## Credits

- Thanks to [lipis](https://github.com/lipis) for the original [`flag-icon-css`](https://github.com/lipis/flag-icon-css) from which
  this project is derived
- Thanks to the authors of the SVG state flags:
  - Johor: <a href="http://creativecommons.org/licenses/by-sa/3.0/" title="Creative Commons Attribution-Share Alike 3.0">CC BY-SA 3.0</a>, <a href="https://commons.wikimedia.org/w/index.php?curid=596053">Link</a>
  - Kedah: By <a href="https://en.wikipedia.org/wiki/User:Bukhrin" class="extiw" title="wikipedia:User:Bukhrin">Bukhrin</a> at <a href="https://en.wikipedia.org/wiki/" class="extiw" title="wikipedia:">English Wikipedia</a> - Transferred from <span class="plainlinks"><a class="external text" href="//en.wikipedia.org">en.wikipedia</a></span> to Commons., Public Domain, <a href="https://commons.wikimedia.org/w/index.php?curid=3827325">Link</a>
  - Kelantan: By <a href="//commons.wikimedia.org/wiki/User:Mysid" title="User:Mysid">Mysid</a>, <a href="http://creativecommons.org/licenses/by-sa/3.0/" title="Creative Commons Attribution-Share Alike 3.0">CC BY-SA 3.0</a>, <a href="https://commons.wikimedia.org/w/index.php?curid=1069049">Link</a>
  - Melaka: By User <a href="https://en.wikipedia.org/wiki/User:Mysid" class="extiw" title="en:User:Mysid">Mysid</a> on <a class="external text" href="http://en.wikipedia.org">en.wikipedia</a> - <a href="https://en.wikipedia.org/wiki/Flag_of_Malacca.svg" class="extiw" title="w:Flag of Malacca.svg">w:Flag of Malacca.svg</a>, Public Domain, <a href="https://commons.wikimedia.org/w/index.php?curid=1037511">Link</a>
  - Negeri Sembilan: By <a href="//commons.wikimedia.org/wiki/User:Himasaram" title="User:Himasaram">Himasaram</a> - <a href="//commons.wikimedia.org/wiki/File:Inkscape_Logo.svg" title="File:Inkscape Logo.svg"></a>This <a href="https://en.wikipedia.org/wiki/Vector_images" class="extiw" title="w:Vector images">vector image</a> was created with <a href="//commons.wikimedia.org/wiki/Help:Inkscape" title="Help:Inkscape">Inkscape</a>.Specification at <a rel="nofollow" class="external text" href="http://www.crwflags.com/fotw/flags/my-neger.html">FOTW</a>, Public Domain, <a href="https://commons.wikimedia.org/w/index.php?curid=1066812">Link</a>
  - Pahang: By No machine-readable author provided. <a href="//commons.wikimedia.org/wiki/User:Urmas" title="User:Urmas">Urmas</a> assumed (based on copyright claims). - No machine-readable source provided. Own work assumed (based on copyright claims)., Public Domain, <a href="https://commons.wikimedia.org/w/index.php?curid=565445">Link</a>
  - Penang: By Original designer of the flag is unknown. - Own made. The image of the penang tree are retrieved from <a rel="nofollow" class="external free" href="http://mymalaysiainfo.com/generalinfo/malaysian-flag/penang-flag/pulaupinang.jpg">http://mymalaysiainfo.com/generalinfo/malaysian-flag/penang-flag/pulaupinang.jpg</a> The Older vision is E-mailed to uploader by author of xrmap., Public Domain, <a href="https://commons.wikimedia.org/w/index.php?curid=651484">Link</a>
  - Perak: By No machine-readable author provided. <a href="//commons.wikimedia.org/wiki/User:Urmas" title="User:Urmas">Urmas</a> assumed (based on copyright claims). - No machine-readable source provided. Own work assumed (based on copyright claims)., Public Domain, <a href="https://commons.wikimedia.org/w/index.php?curid=565424">Link</a>
  - Perlis: By No machine-readable author provided. <a href="//commons.wikimedia.org/wiki/User:Urmas" title="User:Urmas">Urmas</a> assumed (based on copyright claims). - No machine-readable source provided. Own work assumed (based on copyright claims)., Public Domain, <a href="https://commons.wikimedia.org/w/index.php?curid=565447">Link</a>
  - Sabah: By User <a href="https://en.wikipedia.org/wiki/User:Mysid" class="extiw" title="en:User:Mysid">Mysid</a> on <a class="external text" href="http://en.wikipedia.org">en.wikipedia</a> - Originally from <a class="external text" href="http://en.wikipedia.org">en.wikipedia</a>; description page is (was) <a href="https://en.wikipedia.org/wiki/Flag_of_Sabah.svg" class="extiw" title="w:Flag of Sabah.svg">here</a>, Public Domain, <a href="https://commons.wikimedia.org/w/index.php?curid=1037512">Link</a>
  - Sarawak: By <a href="https://en.wikipedia.org/wiki/User:Matthew_A._Lockhart" class="extiw" title="en:User:Matthew A. Lockhart">Matthew A. Lockhart</a> at the <a href="https://en.wikipedia.org/wiki/" class="extiw" title="w:">English language Wikipedia</a>, <a href="http://creativecommons.org/licenses/by-sa/3.0/" title="Creative Commons Attribution-Share Alike 3.0">CC BY-SA 3.0</a>, <a href="https://commons.wikimedia.org/w/index.php?curid=1069069">Link</a>
  - Selangor: By <a href="https://en.wikipedia.org/wiki/User:Mysid" class="extiw" title="en:User:Mysid">Mysid</a> at the <a href="https://en.wikipedia.org/wiki/" class="extiw" title="w:">English language Wikipedia</a>, <a href="http://creativecommons.org/licenses/by-sa/3.0/" title="Creative Commons Attribution-Share Alike 3.0">CC BY-SA 3.0</a>, <a href="https://commons.wikimedia.org/w/index.php?curid=1069135">Link</a>)
  - Terengganu: By <a href="//commons.wikimedia.org/wiki/User:Mysid" title="User:Mysid">Mysid</a>, <a href="http://creativecommons.org/licenses/by-sa/3.0/" title="Creative Commons Attribution-Share Alike 3.0">CC BY-SA 3.0</a>, <a href="https://commons.wikimedia.org/w/index.php?curid=1069289">Link</a>
  - Kuala Lumpur Federal Territory: By No machine-readable author provided. Zscout370 assumed (based on copyright claims). - No machine-readable source provided. Own work assumed (based on copyright claims)., Public Domain, https://commons.wikimedia.org/w/index.php?curid=508742
  - Labuan Federal Territory: By Stefan Fussan - Own work, Public Domain, https://commons.wikimedia.org/w/index.php?curid=2051226
  - Putrajaya Federal Territory: By Bearsmalaysia, Ranking Update, SiBr4 and NikNaksThis vector image includes elements that have been taken or adapted from this:  Coat of arms of Malaysia.svg.This vector image includes elements that have been taken or adapted from this:  Coat of arms of Penang.svg.This vector image includes elements that have been taken or adapted from this:  Coat of arms of Sabah.svg.This vector image includes elements that have been taken or adapted from this:  Coat of arms of Sarawak.svg. - Unknown, coat of arms first version adopted 1952, modified 1963, 1965, 1982 and 1988, Public Domain, https://commons.wikimedia.org/w/index.php?curid=25780223
  - Federal Territories: By Syed - Own work, Public Domain, https://commons.wikimedia.org/w/index.php?curid=18902560
