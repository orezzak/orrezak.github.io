## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/orezzak/orrezak.github.io/edit/main/README.md) to maintain and preview the content for your website in Markdown files.

You can use the [HTML](https://github.com/orezzak/orrezak.github.io/blob/main/Ridgeline%20chart-PEC2.html) to maintain and preview the content for your website in Markdown files.



Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).



### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/orezzak/orrezak.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.


<html>
<head><meta charset="utf-8" />

<title>Ridgeline chart-PEC2</title>

<script src="https://cdnjs.cloudflare.com/ajax/libs/require.js/2.1.10/require.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/2.0.3/jquery.min.js"></script>



<style type="text/css">
    /*!
*
* Twitter Bootstrap
*
*/
/*!
 * Bootstrap v3.3.7 (http://getbootstrap.com)
 * Copyright 2011-2016 Twitter, Inc.
 * Licensed under MIT (https://github.com/twbs/bootstrap/blob/master/LICENSE)
 */
/*! normalize.css v3.0.3 | MIT License | github.com/necolas/normalize.css */
html {
  font-family: sans-serif;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
}
body {
  margin: 0;
}
article,
aside,
details,
figcaption,
figure,
footer,
header,
hgroup,
main,
menu,
nav,
section,
summary {
  display: block;
}
audio,
canvas,
progress,
video {
  display: inline-block;
  vertical-align: baseline;
}
audio:not([controls]) {
  display: none;
  height: 0;
}
[hidden],
template {
  display: none;
}
a {
  background-color: transparent;
}
a:active,
a:hover {
  outline: 0;
}
abbr[title] {
  border-bottom: 1px dotted;
}
b,
strong {
  font-weight: bold;
}
dfn {
  font-style: italic;
}
h1 {
  font-size: 2em;
  margin: 0.67em 0;
}
mark {
  background: #ff0;
  color: #000;
}
small {
  font-size: 80%;
}
sub,
sup {
  font-size: 75%;
  line-height: 0;
  position: relative;
  vertical-align: baseline;
}
sup {
  top: -0.5em;
}
sub {
  bottom: -0.25em;
}
img {
  border: 0;
}
svg:not(:root) {
  overflow: hidden;
}
figure {
  margin: 1em 40px;
}
hr {
  box-sizing: content-box;
  height: 0;
}
pre {
  overflow: auto;
}
code,
kbd,
pre,
samp {
  font-family: monospace, monospace;
  font-size: 1em;
}
button,
input,
optgroup,
select,
textarea {
  color: inherit;
  font: inherit;
  margin: 0;
}
button {
  overflow: visible;
}
button,
select {
  text-transform: none;
}
button,
html input[type="button"],
input[type="reset"],
input[type="submit"] {
  -webkit-appearance: button;
  cursor: pointer;
}
button[disabled],
html input[disabled] {
  cursor: default;
}
button::-moz-focus-inner,
input::-moz-focus-inner {
  border: 0;
  padding: 0;
}
input {
  line-height: normal;
}
input[type="checkbox"],
input[type="radio"] {
  box-sizing: border-box;
  padding: 0;
}
input[type="number"]::-webkit-inner-spin-button,
input[type="number"]::-webkit-outer-spin-button {
  height: auto;
}
input[type="search"] {
  -webkit-appearance: textfield;
  box-sizing: content-box;
}
input[type="search"]::-webkit-search-cancel-button,
input[type="search"]::-webkit-search-decoration {
  -webkit-appearance: none;
}
fieldset {
  border: 1px solid #c0c0c0;
  margin: 0 2px;
  padding: 0.35em 0.625em 0.75em;
}
legend {
  border: 0;
  padding: 0;
}
textarea {
  overflow: auto;
}
optgroup {
  font-weight: bold;
}
table {
  border-collapse: collapse;
  border-spacing: 0;
}
td,
th {
  padding: 0;
}
/*! Source: https://github.com/h5bp/html5-boilerplate/blob/master/src/css/main.css */
@media print {
  *,
  *:before,
  *:after {
    background: transparent !important;
    box-shadow: none !important;
    text-shadow: none !important;
  }
  a,
  a:visited {
    text-decoration: underline;
  }
  a[href]:after {
    content: " (" attr(href) ")";
  }
  abbr[title]:after {
    content: " (" attr(title) ")";
  }
  a[href^="#"]:after,
  a[href^="javascript:"]:after {
    content: "";
  }
  pre,
  blockquote {
    border: 1px solid #999;
    page-break-inside: avoid;
  }
  thead {
    display: table-header-group;
  }
  tr,
  img {
    page-break-inside: avoid;
  }
  img {
    max-width: 100% !important;
  }
  p,
  h2,
  h3 {
    orphans: 3;
    widows: 3;
  }
  h2,
  h3 {
    page-break-after: avoid;
  }
  .navbar {
    display: none;
  }
  .btn > .caret,
  .dropup > .btn > .caret {
    border-top-color: #000 !important;
  }
  .label {
    border: 1px solid #000;
  }
  .table {
    border-collapse: collapse !important;
  }
  .table td,
  .table th {
    background-color: #fff !important;
  }
  .table-bordered th,
  .table-bordered td {
    border: 1px solid #ddd !important;
  }
}
@font-face {
  font-family: 'Glyphicons Halflings';
  src: url('../components/bootstrap/fonts/glyphicons-halflings-regular.eot');
  src: url('../components/bootstrap/fonts/glyphicons-halflings-regular.eot?#iefix') format('embedded-opentype'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.woff2') format('woff2'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.woff') format('woff'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.ttf') format('truetype'), url('../components/bootstrap/fonts/glyphicons-halflings-regular.svg#glyphicons_halflingsregular') format('svg');
}
.glyphicon {
  position: relative;
  top: 1px;
  display: inline-block;
  font-family: 'Glyphicons Halflings';
  font-style: normal;
  font-weight: normal;
  line-height: 1;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
.glyphicon-asterisk:before {
  content: "\002a";
}
.glyphicon-plus:before {
  content: "\002b";
}
.glyphicon-euro:before,
.glyphicon-eur:before {
  content: "\20ac";
}
.glyphicon-minus:before {
  content: "\2212";
}
.glyphicon-cloud:before {
  content: "\2601";
}
.glyphicon-envelope:before {
  content: "\2709";
}
.glyphicon-pencil:before {
  content: "\270f";
}
.glyphicon-glass:before {
  content: "\e001";
}
.glyphicon-music:before {
  content: "\e002";
}
.glyphicon-search:before {
  content: "\e003";
}
.glyphicon-heart:before {
  content: "\e005";
}
.glyphicon-star:before {
  content: "\e006";
}
.glyphicon-star-empty:before {
  content: "\e007";
}
.glyphicon-user:before {
  content: "\e008";
}
.glyphicon-film:before {
  content: "\e009";
}
.glyphicon-th-large:before {
  content: "\e010";
}
.glyphicon-th:before {
  content: "\e011";
}
.glyphicon-th-list:before {
  content: "\e012";
}
.glyphicon-ok:before {
  content: "\e013";
}
.glyphicon-remove:before {
  content: "\e014";
}
.glyphicon-zoom-in:before {
  content: "\e015";
}
.glyphicon-zoom-out:before {
  content: "\e016";
}
.glyphicon-off:before {
  content: "\e017";
}
.glyphicon-signal:before {
  content: "\e018";
}
.glyphicon-cog:before {
  content: "\e019";
}
.glyphicon-trash:before {
  content: "\e020";
}
.glyphicon-home:before {
  content: "\e021";
}
.glyphicon-file:before {
  content: "\e022";
}
.glyphicon-time:before {
  content: "\e023";
}
.glyphicon-road:before {
  content: "\e024";
}
.glyphicon-download-alt:before {
  content: "\e025";
}
.glyphicon-download:before {
  content: "\e026";
}
.glyphicon-upload:before {
  content: "\e027";
}
.glyphicon-inbox:before {
  content: "\e028";
}
.glyphicon-play-circle:before {
  content: "\e029";
}
.glyphicon-repeat:before {
  content: "\e030";
}
.glyphicon-refresh:before {
  content: "\e031";
}
.glyphicon-list-alt:before {
  content: "\e032";
}
.glyphicon-lock:before {
  content: "\e033";
}
.glyphicon-flag:before {
  content: "\e034";
}
.glyphicon-headphones:before {
  content: "\e035";
}
.glyphicon-volume-off:before {
  content: "\e036";
}
.glyphicon-volume-down:before {
  content: "\e037";
}
.glyphicon-volume-up:before {
  content: "\e038";
}
.glyphicon-qrcode:before {
  content: "\e039";
}
.glyphicon-barcode:before {
  content: "\e040";
}
.glyphicon-tag:before {
  content: "\e041";
}
.glyphicon-tags:before {
  content: "\e042";
}
.glyphicon-book:before {
  content: "\e043";
}
.glyphicon-bookmark:before {
  content: "\e044";
}
.glyphicon-print:before {
  content: "\e045";
}
.glyphicon-camera:before {
  content: "\e046";
}
.glyphicon-font:before {
  content: "\e047";
}
.glyphicon-bold:before {
  content: "\e048";
}
.glyphicon-italic:before {
  content: "\e049";
}
.glyphicon-text-height:before {
  content: "\e050";
}
.glyphicon-text-width:before {
  content: "\e051";
}
.glyphicon-align-left:before {
  content: "\e052";
}
.glyphicon-align-center:before {
  content: "\e053";
}
.glyphicon-align-right:before {
  content: "\e054";
}
.glyphicon-align-justify:before {
  content: "\e055";
}
.glyphicon-list:before {
  content: "\e056";
}
.glyphicon-indent-left:before {
  content: "\e057";
}
.glyphicon-indent-right:before {
  content: "\e058";
}
.glyphicon-facetime-video:before {
  content: "\e059";
}
.glyphicon-picture:before {
  content: "\e060";
}
.glyphicon-map-marker:before {
  content: "\e062";
}
.glyphicon-adjust:before {
  content: "\e063";
}
.glyphicon-tint:before {
  content: "\e064";
}
.glyphicon-edit:before {
  content: "\e065";
}
.glyphicon-share:before {
  content: "\e066";
}
.glyphicon-check:before {
  content: "\e067";
}
.glyphicon-move:before {
  content: "\e068";
}
.glyphicon-step-backward:before {
  content: "\e069";
}
.glyphicon-fast-backward:before {
  content: "\e070";
}
.glyphicon-backward:before {
  content: "\e071";
}
.glyphicon-play:before {
  content: "\e072";
}
.glyphicon-pause:before {
  content: "\e073";
}
.glyphicon-stop:before {
  content: "\e074";
}
.glyphicon-forward:before {
  content: "\e075";
}
.glyphicon-fast-forward:before {
  content: "\e076";
}
.glyphicon-step-forward:before {
  content: "\e077";
}
.glyphicon-eject:before {
  content: "\e078";
}
.glyphicon-chevron-left:before {
  content: "\e079";
}
.glyphicon-chevron-right:before {
  content: "\e080";
}
.glyphicon-plus-sign:before {
  content: "\e081";
}
.glyphicon-minus-sign:before {
  content: "\e082";
}
.glyphicon-remove-sign:before {
  content: "\e083";
}
.glyphicon-ok-sign:before {
  content: "\e084";
}
.glyphicon-question-sign:before {
  content: "\e085";
}
.glyphicon-info-sign:before {
  content: "\e086";
}
.glyphicon-screenshot:before {
  content: "\e087";
}
.glyphicon-remove-circle:before {
  content: "\e088";
}
.glyphicon-ok-circle:before {
  content: "\e089";
}
.glyphicon-ban-circle:before {
  content: "\e090";
}
.glyphicon-arrow-left:before {
  content: "\e091";
}
.glyphicon-arrow-right:before {
  content: "\e092";
}
.glyphicon-arrow-up:before {
  content: "\e093";
}
.glyphicon-arrow-down:before {
  content: "\e094";
}
.glyphicon-share-alt:before {
  content: "\e095";
}
.glyphicon-resize-full:before {
  content: "\e096";
}
.glyphicon-resize-small:before {
  content: "\e097";
}
.glyphicon-exclamation-sign:before {
  content: "\e101";
}
.glyphicon-gift:before {
  content: "\e102";
}
.glyphicon-leaf:before {
  content: "\e103";
}
.glyphicon-fire:before {
  content: "\e104";
}
.glyphicon-eye-open:before {
  content: "\e105";
}
.glyphicon-eye-close:before {
  content: "\e106";
}
.glyphicon-warning-sign:before {
  content: "\e107";
}
.glyphicon-plane:before {
  content: "\e108";
}
.glyphicon-calendar:before {
  content: "\e109";
}
.glyphicon-random:before {
  content: "\e110";
}
.glyphicon-comment:before {
  content: "\e111";
}
.glyphicon-magnet:before {
  content: "\e112";
}
.glyphicon-chevron-up:before {
  content: "\e113";
}
.glyphicon-chevron-down:before {
  content: "\e114";
}
.glyphicon-retweet:before {
  content: "\e115";
}
.glyphicon-shopping-cart:before {
  content: "\e116";
}
.glyphicon-folder-close:before {
  content: "\e117";
}
.glyphicon-folder-open:before {
  content: "\e118";
}
.glyphicon-resize-vertical:before {
  content: "\e119";
}
.glyphicon-resize-horizontal:before {
  content: "\e120";
}
.glyphicon-hdd:before {
  content: "\e121";
}
.glyphicon-bullhorn:before {
  content: "\e122";
}
.glyphicon-bell:before {
  content: "\e123";
}
.glyphicon-certificate:before {
  content: "\e124";
}
.glyphicon-thumbs-up:before {
  content: "\e125";
}
.glyphicon-thumbs-down:before {
  content: "\e126";
}
.glyphicon-hand-right:before {
  content: "\e127";
}
.glyphicon-hand-left:before {
  content: "\e128";
}
.glyphicon-hand-up:before {
  content: "\e129";
}
.glyphicon-hand-down:before {
  content: "\e130";
}
.glyphicon-circle-arrow-right:before {
  content: "\e131";
}
.glyphicon-circle-arrow-left:before {
  content: "\e132";
}
.glyphicon-circle-arrow-up:before {
  content: "\e133";
}
.glyphicon-circle-arrow-down:before {
  content: "\e134";
}
.glyphicon-globe:before {
  content: "\e135";
}
.glyphicon-wrench:before {
  content: "\e136";
}
.glyphicon-tasks:before {
  content: "\e137";
}
.glyphicon-filter:before {
  content: "\e138";
}
.glyphicon-briefcase:before {
  content: "\e139";
}
.glyphicon-fullscreen:before {
  content: "\e140";
}
.glyphicon-dashboard:before {
  content: "\e141";
}
.glyphicon-paperclip:before {
  content: "\e142";
}
.glyphicon-heart-empty:before {
  content: "\e143";
}
.glyphicon-link:before {
  content: "\e144";
}
.glyphicon-phone:before {
  content: "\e145";
}
.glyphicon-pushpin:before {
  content: "\e146";
}
.glyphicon-usd:before {
  content: "\e148";
}
.glyphicon-gbp:before {
  content: "\e149";
}
.glyphicon-sort:before {
  content: "\e150";
}
.glyphicon-sort-by-alphabet:before {
  content: "\e151";
}
.glyphicon-sort-by-alphabet-alt:before {
  content: "\e152";
}
.glyphicon-sort-by-order:before {
  content: "\e153";
}
.glyphicon-sort-by-order-alt:before {
  content: "\e154";
}
.glyphicon-sort-by-attributes:before {
  content: "\e155";
}
.glyphicon-sort-by-attributes-alt:before {
  content: "\e156";
}
.glyphicon-unchecked:before {
  content: "\e157";
}
.glyphicon-expand:before {
  content: "\e158";
}
.glyphicon-collapse-down:before {
  content: "\e159";
}
.glyphicon-collapse-up:before {
  content: "\e160";
}
.glyphicon-log-in:before {
  content: "\e161";
}
.glyphicon-flash:before {
  content: "\e162";
}
.glyphicon-log-out:before {
  content: "\e163";
}
.glyphicon-new-window:before {
  content: "\e164";
}
.glyphicon-record:before {
  content: "\e165";
}
.glyphicon-save:before {
  content: "\e166";
}
.glyphicon-open:before {
  content: "\e167";
}
.glyphicon-saved:before {
  content: "\e168";
}
.glyphicon-import:before {
  content: "\e169";
}
.glyphicon-export:before {
  content: "\e170";
}
.glyphicon-send:before {
  content: "\e171";
}
.glyphicon-floppy-disk:before {
  content: "\e172";
}
.glyphicon-floppy-saved:before {
  content: "\e173";
}
.glyphicon-floppy-remove:before {
  content: "\e174";
}
.glyphicon-floppy-save:before {
  content: "\e175";
}
.glyphicon-floppy-open:before {
  content: "\e176";
}
.glyphicon-credit-card:before {
  content: "\e177";
}
.glyphicon-transfer:before {
  content: "\e178";
}
.glyphicon-cutlery:before {
  content: "\e179";
}
.glyphicon-header:before {
  content: "\e180";
}
.glyphicon-compressed:before {
  content: "\e181";
}
.glyphicon-earphone:before {
  content: "\e182";
}
.glyphicon-phone-alt:before {
  content: "\e183";
}
.glyphicon-tower:before {
  content: "\e184";
}
.glyphicon-stats:before {
  content: "\e185";
}
.glyphicon-sd-video:before {
  content: "\e186";
}
.glyphicon-hd-video:before {
  content: "\e187";
}
.glyphicon-subtitles:before {
  content: "\e188";
}
.glyphicon-sound-stereo:before {
  content: "\e189";
}
.glyphicon-sound-dolby:before {
  content: "\e190";
}
.glyphicon-sound-5-1:before {
  content: "\e191";
}
.glyphicon-sound-6-1:before {
  content: "\e192";
}
.glyphicon-sound-7-1:before {
  content: "\e193";
}
.glyphicon-copyright-mark:before {
  content: "\e194";
}
.glyphicon-registration-mark:before {
  content: "\e195";
}
.glyphicon-cloud-download:before {
  content: "\e197";
}
.glyphicon-cloud-upload:before {
  content: "\e198";
}
.glyphicon-tree-conifer:before {
  content: "\e199";
}
.glyphicon-tree-deciduous:before {
  content: "\e200";
}
.glyphicon-cd:before {
  content: "\e201";
}
.glyphicon-save-file:before {
  content: "\e202";
}
.glyphicon-open-file:before {
  content: "\e203";
}
.glyphicon-level-up:before {
  content: "\e204";
}
.glyphicon-copy:before {
  content: "\e205";
}
.glyphicon-paste:before {
  content: "\e206";
}
.glyphicon-alert:before {
  content: "\e209";
}
.glyphicon-equalizer:before {
  content: "\e210";
}
.glyphicon-king:before {
  content: "\e211";
}
.glyphicon-queen:before {
  content: "\e212";
}
.glyphicon-pawn:before {
  content: "\e213";
}
.glyphicon-bishop:before {
  content: "\e214";
}
.glyphicon-knight:before {
  content: "\e215";
}
.glyphicon-baby-formula:before {
  content: "\e216";
}
.glyphicon-tent:before {
  content: "\26fa";
}
.glyphicon-blackboard:before {
  content: "\e218";
}
.glyphicon-bed:before {
  content: "\e219";
}
.glyphicon-apple:before {
  content: "\f8ff";
}
.glyphicon-erase:before {
  content: "\e221";
}
.glyphicon-hourglass:before {
  content: "\231b";
}
.glyphicon-lamp:before {
  content: "\e223";
}
.glyphicon-duplicate:before {
  content: "\e224";
}
.glyphicon-piggy-bank:before {
  content: "\e225";
}
.glyphicon-scissors:before {
  content: "\e226";
}
.glyphicon-bitcoin:before {
  content: "\e227";
}
.glyphicon-btc:before {
  content: "\e227";
}
.glyphicon-xbt:before {
  content: "\e227";
}
.glyphicon-yen:before {
  content: "\00a5";
}
.glyphicon-jpy:before {
  content: "\00a5";
}
.glyphicon-ruble:before {
  content: "\20bd";
}
.glyphicon-rub:before {
  content: "\20bd";
}
.glyphicon-scale:before {
  content: "\e230";
}
.glyphicon-ice-lolly:before {
  content: "\e231";
}
.glyphicon-ice-lolly-tasted:before {
  content: "\e232";
}
.glyphicon-education:before {
  content: "\e233";
}
.glyphicon-option-horizontal:before {
  content: "\e234";
}
.glyphicon-option-vertical:before {
  content: "\e235";
}
.glyphicon-menu-hamburger:before {
  content: "\e236";
}
.glyphicon-modal-window:before {
  content: "\e237";
}
.glyphicon-oil:before {
  content: "\e238";
}
.glyphicon-grain:before {
  content: "\e239";
}
.glyphicon-sunglasses:before {
  content: "\e240";
}
.glyphicon-text-size:before {
  content: "\e241";
}
.glyphicon-text-color:before {
  content: "\e242";
}
.glyphicon-text-background:before {
  content: "\e243";
}
.glyphicon-object-align-top:before {
  content: "\e244";
}
.glyphicon-object-align-bottom:before {
  content: "\e245";
}
.glyphicon-object-align-horizontal:before {
  content: "\e246";
}
.glyphicon-object-align-left:before {
  content: "\e247";
}
.glyphicon-object-align-vertical:before {
  content: "\e248";
}
.glyphicon-object-align-right:before {
  content: "\e249";
}
.glyphicon-triangle-right:before {
  content: "\e250";
}
.glyphicon-triangle-left:before {
  content: "\e251";
}
.glyphicon-triangle-bottom:before {
  content: "\e252";
}
.glyphicon-triangle-top:before {
  content: "\e253";
}
.glyphicon-console:before {
  content: "\e254";
}
.glyphicon-superscript:before {
  content: "\e255";
}
.glyphicon-subscript:before {
  content: "\e256";
}
.glyphicon-menu-left:before {
  content: "\e257";
}
.glyphicon-menu-right:before {
  content: "\e258";
}
.glyphicon-menu-down:before {
  content: "\e259";
}
.glyphicon-menu-up:before {
  content: "\e260";
}
* {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
*:before,
*:after {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
html {
  font-size: 10px;
  -webkit-tap-highlight-color: rgba(0, 0, 0, 0);
}
body {
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-size: 13px;
  line-height: 1.42857143;
  color: #000;
  background-color: #fff;
}
input,
button,
select,
textarea {
  font-family: inherit;
  font-size: inherit;
  line-height: inherit;
}
a {
  color: #337ab7;
  text-decoration: none;
}
a:hover,
a:focus {
  color: #23527c;
  text-decoration: underline;
}
a:focus {
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
figure {
  margin: 0;
}
img {
  vertical-align: middle;
}
.img-responsive,
.thumbnail > img,
.thumbnail a > img,
.carousel-inner > .item > img,
.carousel-inner > .item > a > img {
  display: block;
  max-width: 100%;
  height: auto;
}
.img-rounded {
  border-radius: 3px;
}
.img-thumbnail {
  padding: 4px;
  line-height: 1.42857143;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 2px;
  -webkit-transition: all 0.2s ease-in-out;
  -o-transition: all 0.2s ease-in-out;
  transition: all 0.2s ease-in-out;
  display: inline-block;
  max-width: 100%;
  height: auto;
}
.img-circle {
  border-radius: 50%;
}
hr {
  margin-top: 18px;
  margin-bottom: 18px;
  border: 0;
  border-top: 1px solid #eeeeee;
}
.sr-only {
  position: absolute;
  width: 1px;
  height: 1px;
  margin: -1px;
  padding: 0;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
.sr-only-focusable:active,
.sr-only-focusable:focus {
  position: static;
  width: auto;
  height: auto;
  margin: 0;
  overflow: visible;
  clip: auto;
}
[role="button"] {
  cursor: pointer;
}
h1,
h2,
h3,
h4,
h5,
h6,
.h1,
.h2,
.h3,
.h4,
.h5,
.h6 {
  font-family: inherit;
  font-weight: 500;
  line-height: 1.1;
  color: inherit;
}
h1 small,
h2 small,
h3 small,
h4 small,
h5 small,
h6 small,
.h1 small,
.h2 small,
.h3 small,
.h4 small,
.h5 small,
.h6 small,
h1 .small,
h2 .small,
h3 .small,
h4 .small,
h5 .small,
h6 .small,
.h1 .small,
.h2 .small,
.h3 .small,
.h4 .small,
.h5 .small,
.h6 .small {
  font-weight: normal;
  line-height: 1;
  color: #777777;
}
h1,
.h1,
h2,
.h2,
h3,
.h3 {
  margin-top: 18px;
  margin-bottom: 9px;
}
h1 small,
.h1 small,
h2 small,
.h2 small,
h3 small,
.h3 small,
h1 .small,
.h1 .small,
h2 .small,
.h2 .small,
h3 .small,
.h3 .small {
  font-size: 65%;
}
h4,
.h4,
h5,
.h5,
h6,
.h6 {
  margin-top: 9px;
  margin-bottom: 9px;
}
h4 small,
.h4 small,
h5 small,
.h5 small,
h6 small,
.h6 small,
h4 .small,
.h4 .small,
h5 .small,
.h5 .small,
h6 .small,
.h6 .small {
  font-size: 75%;
}
h1,
.h1 {
  font-size: 33px;
}
h2,
.h2 {
  font-size: 27px;
}
h3,
.h3 {
  font-size: 23px;
}
h4,
.h4 {
  font-size: 17px;
}
h5,
.h5 {
  font-size: 13px;
}
h6,
.h6 {
  font-size: 12px;
}
p {
  margin: 0 0 9px;
}
.lead {
  margin-bottom: 18px;
  font-size: 14px;
  font-weight: 300;
  line-height: 1.4;
}
@media (min-width: 768px) {
  .lead {
    font-size: 19.5px;
  }
}
small,
.small {
  font-size: 92%;
}
mark,
.mark {
  background-color: #fcf8e3;
  padding: .2em;
}
.text-left {
  text-align: left;
}
.text-right {
  text-align: right;
}
.text-center {
  text-align: center;
}
.text-justify {
  text-align: justify;
}
.text-nowrap {
  white-space: nowrap;
}
.text-lowercase {
  text-transform: lowercase;
}
.text-uppercase {
  text-transform: uppercase;
}
.text-capitalize {
  text-transform: capitalize;
}
.text-muted {
  color: #777777;
}
.text-primary {
  color: #337ab7;
}
a.text-primary:hover,
a.text-primary:focus {
  color: #286090;
}
.text-success {
  color: #3c763d;
}
a.text-success:hover,
a.text-success:focus {
  color: #2b542c;
}
.text-info {
  color: #31708f;
}
a.text-info:hover,
a.text-info:focus {
  color: #245269;
}
.text-warning {
  color: #8a6d3b;
}
a.text-warning:hover,
a.text-warning:focus {
  color: #66512c;
}
.text-danger {
  color: #a94442;
}
a.text-danger:hover,
a.text-danger:focus {
  color: #843534;
}
.bg-primary {
  color: #fff;
  background-color: #337ab7;
}
a.bg-primary:hover,
a.bg-primary:focus {
  background-color: #286090;
}
.bg-success {
  background-color: #dff0d8;
}
a.bg-success:hover,
a.bg-success:focus {
  background-color: #c1e2b3;
}
.bg-info {
  background-color: #d9edf7;
}
a.bg-info:hover,
a.bg-info:focus {
  background-color: #afd9ee;
}
.bg-warning {
  background-color: #fcf8e3;
}
a.bg-warning:hover,
a.bg-warning:focus {
  background-color: #f7ecb5;
}
.bg-danger {
  background-color: #f2dede;
}
a.bg-danger:hover,
a.bg-danger:focus {
  background-color: #e4b9b9;
}
.page-header {
  padding-bottom: 8px;
  margin: 36px 0 18px;
  border-bottom: 1px solid #eeeeee;
}
ul,
ol {
  margin-top: 0;
  margin-bottom: 9px;
}
ul ul,
ol ul,
ul ol,
ol ol {
  margin-bottom: 0;
}
.list-unstyled {
  padding-left: 0;
  list-style: none;
}
.list-inline {
  padding-left: 0;
  list-style: none;
  margin-left: -5px;
}
.list-inline > li {
  display: inline-block;
  padding-left: 5px;
  padding-right: 5px;
}
dl {
  margin-top: 0;
  margin-bottom: 18px;
}
dt,
dd {
  line-height: 1.42857143;
}
dt {
  font-weight: bold;
}
dd {
  margin-left: 0;
}
@media (min-width: 541px) {
  .dl-horizontal dt {
    float: left;
    width: 160px;
    clear: left;
    text-align: right;
    overflow: hidden;
    text-overflow: ellipsis;
    white-space: nowrap;
  }
  .dl-horizontal dd {
    margin-left: 180px;
  }
}
abbr[title],
abbr[data-original-title] {
  cursor: help;
  border-bottom: 1px dotted #777777;
}
.initialism {
  font-size: 90%;
  text-transform: uppercase;
}
blockquote {
  padding: 9px 18px;
  margin: 0 0 18px;
  font-size: inherit;
  border-left: 5px solid #eeeeee;
}
blockquote p:last-child,
blockquote ul:last-child,
blockquote ol:last-child {
  margin-bottom: 0;
}
blockquote footer,
blockquote small,
blockquote .small {
  display: block;
  font-size: 80%;
  line-height: 1.42857143;
  color: #777777;
}
blockquote footer:before,
blockquote small:before,
blockquote .small:before {
  content: '\2014 \00A0';
}
.blockquote-reverse,
blockquote.pull-right {
  padding-right: 15px;
  padding-left: 0;
  border-right: 5px solid #eeeeee;
  border-left: 0;
  text-align: right;
}
.blockquote-reverse footer:before,
blockquote.pull-right footer:before,
.blockquote-reverse small:before,
blockquote.pull-right small:before,
.blockquote-reverse .small:before,
blockquote.pull-right .small:before {
  content: '';
}
.blockquote-reverse footer:after,
blockquote.pull-right footer:after,
.blockquote-reverse small:after,
blockquote.pull-right small:after,
.blockquote-reverse .small:after,
blockquote.pull-right .small:after {
  content: '\00A0 \2014';
}
address {
  margin-bottom: 18px;
  font-style: normal;
  line-height: 1.42857143;
}
code,
kbd,
pre,
samp {
  font-family: monospace;
}
code {
  padding: 2px 4px;
  font-size: 90%;
  color: #c7254e;
  background-color: #f9f2f4;
  border-radius: 2px;
}
kbd {
  padding: 2px 4px;
  font-size: 90%;
  color: #888;
  background-color: transparent;
  border-radius: 1px;
  box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.25);
}
kbd kbd {
  padding: 0;
  font-size: 100%;
  font-weight: bold;
  box-shadow: none;
}
pre {
  display: block;
  padding: 8.5px;
  margin: 0 0 9px;
  font-size: 12px;
  line-height: 1.42857143;
  word-break: break-all;
  word-wrap: break-word;
  color: #333333;
  background-color: #f5f5f5;
  border: 1px solid #ccc;
  border-radius: 2px;
}
pre code {
  padding: 0;
  font-size: inherit;
  color: inherit;
  white-space: pre-wrap;
  background-color: transparent;
  border-radius: 0;
}
.pre-scrollable {
  max-height: 340px;
  overflow-y: scroll;
}
.container {
  margin-right: auto;
  margin-left: auto;
  padding-left: 0px;
  padding-right: 0px;
}
@media (min-width: 768px) {
  .container {
    width: 768px;
  }
}
@media (min-width: 992px) {
  .container {
    width: 940px;
  }
}
@media (min-width: 1200px) {
  .container {
    width: 1140px;
  }
}
.container-fluid {
  margin-right: auto;
  margin-left: auto;
  padding-left: 0px;
  padding-right: 0px;
}
.row {
  margin-left: 0px;
  margin-right: 0px;
}
.col-xs-1, .col-sm-1, .col-md-1, .col-lg-1, .col-xs-2, .col-sm-2, .col-md-2, .col-lg-2, .col-xs-3, .col-sm-3, .col-md-3, .col-lg-3, .col-xs-4, .col-sm-4, .col-md-4, .col-lg-4, .col-xs-5, .col-sm-5, .col-md-5, .col-lg-5, .col-xs-6, .col-sm-6, .col-md-6, .col-lg-6, .col-xs-7, .col-sm-7, .col-md-7, .col-lg-7, .col-xs-8, .col-sm-8, .col-md-8, .col-lg-8, .col-xs-9, .col-sm-9, .col-md-9, .col-lg-9, .col-xs-10, .col-sm-10, .col-md-10, .col-lg-10, .col-xs-11, .col-sm-11, .col-md-11, .col-lg-11, .col-xs-12, .col-sm-12, .col-md-12, .col-lg-12 {
  position: relative;
  min-height: 1px;
  padding-left: 0px;
  padding-right: 0px;
}
.col-xs-1, .col-xs-2, .col-xs-3, .col-xs-4, .col-xs-5, .col-xs-6, .col-xs-7, .col-xs-8, .col-xs-9, .col-xs-10, .col-xs-11, .col-xs-12 {
  float: left;
}
.col-xs-12 {
  width: 100%;
}
.col-xs-11 {
  width: 91.66666667%;
}
.col-xs-10 {
  width: 83.33333333%;
}
.col-xs-9 {
  width: 75%;
}
.col-xs-8 {
  width: 66.66666667%;
}
.col-xs-7 {
  width: 58.33333333%;
}
.col-xs-6 {
  width: 50%;
}
.col-xs-5 {
  width: 41.66666667%;
}
.col-xs-4 {
  width: 33.33333333%;
}
.col-xs-3 {
  width: 25%;
}
.col-xs-2 {
  width: 16.66666667%;
}
.col-xs-1 {
  width: 8.33333333%;
}
.col-xs-pull-12 {
  right: 100%;
}
.col-xs-pull-11 {
  right: 91.66666667%;
}
.col-xs-pull-10 {
  right: 83.33333333%;
}
.col-xs-pull-9 {
  right: 75%;
}
.col-xs-pull-8 {
  right: 66.66666667%;
}
.col-xs-pull-7 {
  right: 58.33333333%;
}
.col-xs-pull-6 {
  right: 50%;
}
.col-xs-pull-5 {
  right: 41.66666667%;
}
.col-xs-pull-4 {
  right: 33.33333333%;
}
.col-xs-pull-3 {
  right: 25%;
}
.col-xs-pull-2 {
  right: 16.66666667%;
}
.col-xs-pull-1 {
  right: 8.33333333%;
}
.col-xs-pull-0 {
  right: auto;
}
.col-xs-push-12 {
  left: 100%;
}
.col-xs-push-11 {
  left: 91.66666667%;
}
.col-xs-push-10 {
  left: 83.33333333%;
}
.col-xs-push-9 {
  left: 75%;
}
.col-xs-push-8 {
  left: 66.66666667%;
}
.col-xs-push-7 {
  left: 58.33333333%;
}
.col-xs-push-6 {
  left: 50%;
}
.col-xs-push-5 {
  left: 41.66666667%;
}
.col-xs-push-4 {
  left: 33.33333333%;
}
.col-xs-push-3 {
  left: 25%;
}
.col-xs-push-2 {
  left: 16.66666667%;
}
.col-xs-push-1 {
  left: 8.33333333%;
}
.col-xs-push-0 {
  left: auto;
}
.col-xs-offset-12 {
  margin-left: 100%;
}
.col-xs-offset-11 {
  margin-left: 91.66666667%;
}
.col-xs-offset-10 {
  margin-left: 83.33333333%;
}
.col-xs-offset-9 {
  margin-left: 75%;
}
.col-xs-offset-8 {
  margin-left: 66.66666667%;
}
.col-xs-offset-7 {
  margin-left: 58.33333333%;
}
.col-xs-offset-6 {
  margin-left: 50%;
}
.col-xs-offset-5 {
  margin-left: 41.66666667%;
}
.col-xs-offset-4 {
  margin-left: 33.33333333%;
}
.col-xs-offset-3 {
  margin-left: 25%;
}
.col-xs-offset-2 {
  margin-left: 16.66666667%;
}
.col-xs-offset-1 {
  margin-left: 8.33333333%;
}
.col-xs-offset-0 {
  margin-left: 0%;
}
@media (min-width: 768px) {
  .col-sm-1, .col-sm-2, .col-sm-3, .col-sm-4, .col-sm-5, .col-sm-6, .col-sm-7, .col-sm-8, .col-sm-9, .col-sm-10, .col-sm-11, .col-sm-12 {
    float: left;
  }
  .col-sm-12 {
    width: 100%;
  }
  .col-sm-11 {
    width: 91.66666667%;
  }
  .col-sm-10 {
    width: 83.33333333%;
  }
  .col-sm-9 {
    width: 75%;
  }
  .col-sm-8 {
    width: 66.66666667%;
  }
  .col-sm-7 {
    width: 58.33333333%;
  }
  .col-sm-6 {
    width: 50%;
  }
  .col-sm-5 {
    width: 41.66666667%;
  }
  .col-sm-4 {
    width: 33.33333333%;
  }
  .col-sm-3 {
    width: 25%;
  }
  .col-sm-2 {
    width: 16.66666667%;
  }
  .col-sm-1 {
    width: 8.33333333%;
  }
  .col-sm-pull-12 {
    right: 100%;
  }
  .col-sm-pull-11 {
    right: 91.66666667%;
  }
  .col-sm-pull-10 {
    right: 83.33333333%;
  }
  .col-sm-pull-9 {
    right: 75%;
  }
  .col-sm-pull-8 {
    right: 66.66666667%;
  }
  .col-sm-pull-7 {
    right: 58.33333333%;
  }
  .col-sm-pull-6 {
    right: 50%;
  }
  .col-sm-pull-5 {
    right: 41.66666667%;
  }
  .col-sm-pull-4 {
    right: 33.33333333%;
  }
  .col-sm-pull-3 {
    right: 25%;
  }
  .col-sm-pull-2 {
    right: 16.66666667%;
  }
  .col-sm-pull-1 {
    right: 8.33333333%;
  }
  .col-sm-pull-0 {
    right: auto;
  }
  .col-sm-push-12 {
    left: 100%;
  }
  .col-sm-push-11 {
    left: 91.66666667%;
  }
  .col-sm-push-10 {
    left: 83.33333333%;
  }
  .col-sm-push-9 {
    left: 75%;
  }
  .col-sm-push-8 {
    left: 66.66666667%;
  }
  .col-sm-push-7 {
    left: 58.33333333%;
  }
  .col-sm-push-6 {
    left: 50%;
  }
  .col-sm-push-5 {
    left: 41.66666667%;
  }
  .col-sm-push-4 {
    left: 33.33333333%;
  }
  .col-sm-push-3 {
    left: 25%;
  }
  .col-sm-push-2 {
    left: 16.66666667%;
  }
  .col-sm-push-1 {
    left: 8.33333333%;
  }
  .col-sm-push-0 {
    left: auto;
  }
  .col-sm-offset-12 {
    margin-left: 100%;
  }
  .col-sm-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-sm-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-sm-offset-9 {
    margin-left: 75%;
  }
  .col-sm-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-sm-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-sm-offset-6 {
    margin-left: 50%;
  }
  .col-sm-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-sm-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-sm-offset-3 {
    margin-left: 25%;
  }
  .col-sm-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-sm-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-sm-offset-0 {
    margin-left: 0%;
  }
}
@media (min-width: 992px) {
  .col-md-1, .col-md-2, .col-md-3, .col-md-4, .col-md-5, .col-md-6, .col-md-7, .col-md-8, .col-md-9, .col-md-10, .col-md-11, .col-md-12 {
    float: left;
  }
  .col-md-12 {
    width: 100%;
  }
  .col-md-11 {
    width: 91.66666667%;
  }
  .col-md-10 {
    width: 83.33333333%;
  }
  .col-md-9 {
    width: 75%;
  }
  .col-md-8 {
    width: 66.66666667%;
  }
  .col-md-7 {
    width: 58.33333333%;
  }
  .col-md-6 {
    width: 50%;
  }
  .col-md-5 {
    width: 41.66666667%;
  }
  .col-md-4 {
    width: 33.33333333%;
  }
  .col-md-3 {
    width: 25%;
  }
  .col-md-2 {
    width: 16.66666667%;
  }
  .col-md-1 {
    width: 8.33333333%;
  }
  .col-md-pull-12 {
    right: 100%;
  }
  .col-md-pull-11 {
    right: 91.66666667%;
  }
  .col-md-pull-10 {
    right: 83.33333333%;
  }
  .col-md-pull-9 {
    right: 75%;
  }
  .col-md-pull-8 {
    right: 66.66666667%;
  }
  .col-md-pull-7 {
    right: 58.33333333%;
  }
  .col-md-pull-6 {
    right: 50%;
  }
  .col-md-pull-5 {
    right: 41.66666667%;
  }
  .col-md-pull-4 {
    right: 33.33333333%;
  }
  .col-md-pull-3 {
    right: 25%;
  }
  .col-md-pull-2 {
    right: 16.66666667%;
  }
  .col-md-pull-1 {
    right: 8.33333333%;
  }
  .col-md-pull-0 {
    right: auto;
  }
  .col-md-push-12 {
    left: 100%;
  }
  .col-md-push-11 {
    left: 91.66666667%;
  }
  .col-md-push-10 {
    left: 83.33333333%;
  }
  .col-md-push-9 {
    left: 75%;
  }
  .col-md-push-8 {
    left: 66.66666667%;
  }
  .col-md-push-7 {
    left: 58.33333333%;
  }
  .col-md-push-6 {
    left: 50%;
  }
  .col-md-push-5 {
    left: 41.66666667%;
  }
  .col-md-push-4 {
    left: 33.33333333%;
  }
  .col-md-push-3 {
    left: 25%;
  }
  .col-md-push-2 {
    left: 16.66666667%;
  }
  .col-md-push-1 {
    left: 8.33333333%;
  }
  .col-md-push-0 {
    left: auto;
  }
  .col-md-offset-12 {
    margin-left: 100%;
  }
  .col-md-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-md-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-md-offset-9 {
    margin-left: 75%;
  }
  .col-md-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-md-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-md-offset-6 {
    margin-left: 50%;
  }
  .col-md-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-md-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-md-offset-3 {
    margin-left: 25%;
  }
  .col-md-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-md-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-md-offset-0 {
    margin-left: 0%;
  }
}
@media (min-width: 1200px) {
  .col-lg-1, .col-lg-2, .col-lg-3, .col-lg-4, .col-lg-5, .col-lg-6, .col-lg-7, .col-lg-8, .col-lg-9, .col-lg-10, .col-lg-11, .col-lg-12 {
    float: left;
  }
  .col-lg-12 {
    width: 100%;
  }
  .col-lg-11 {
    width: 91.66666667%;
  }
  .col-lg-10 {
    width: 83.33333333%;
  }
  .col-lg-9 {
    width: 75%;
  }
  .col-lg-8 {
    width: 66.66666667%;
  }
  .col-lg-7 {
    width: 58.33333333%;
  }
  .col-lg-6 {
    width: 50%;
  }
  .col-lg-5 {
    width: 41.66666667%;
  }
  .col-lg-4 {
    width: 33.33333333%;
  }
  .col-lg-3 {
    width: 25%;
  }
  .col-lg-2 {
    width: 16.66666667%;
  }
  .col-lg-1 {
    width: 8.33333333%;
  }
  .col-lg-pull-12 {
    right: 100%;
  }
  .col-lg-pull-11 {
    right: 91.66666667%;
  }
  .col-lg-pull-10 {
    right: 83.33333333%;
  }
  .col-lg-pull-9 {
    right: 75%;
  }
  .col-lg-pull-8 {
    right: 66.66666667%;
  }
  .col-lg-pull-7 {
    right: 58.33333333%;
  }
  .col-lg-pull-6 {
    right: 50%;
  }
  .col-lg-pull-5 {
    right: 41.66666667%;
  }
  .col-lg-pull-4 {
    right: 33.33333333%;
  }
  .col-lg-pull-3 {
    right: 25%;
  }
  .col-lg-pull-2 {
    right: 16.66666667%;
  }
  .col-lg-pull-1 {
    right: 8.33333333%;
  }
  .col-lg-pull-0 {
    right: auto;
  }
  .col-lg-push-12 {
    left: 100%;
  }
  .col-lg-push-11 {
    left: 91.66666667%;
  }
  .col-lg-push-10 {
    left: 83.33333333%;
  }
  .col-lg-push-9 {
    left: 75%;
  }
  .col-lg-push-8 {
    left: 66.66666667%;
  }
  .col-lg-push-7 {
    left: 58.33333333%;
  }
  .col-lg-push-6 {
    left: 50%;
  }
  .col-lg-push-5 {
    left: 41.66666667%;
  }
  .col-lg-push-4 {
    left: 33.33333333%;
  }
  .col-lg-push-3 {
    left: 25%;
  }
  .col-lg-push-2 {
    left: 16.66666667%;
  }
  .col-lg-push-1 {
    left: 8.33333333%;
  }
  .col-lg-push-0 {
    left: auto;
  }
  .col-lg-offset-12 {
    margin-left: 100%;
  }
  .col-lg-offset-11 {
    margin-left: 91.66666667%;
  }
  .col-lg-offset-10 {
    margin-left: 83.33333333%;
  }
  .col-lg-offset-9 {
    margin-left: 75%;
  }
  .col-lg-offset-8 {
    margin-left: 66.66666667%;
  }
  .col-lg-offset-7 {
    margin-left: 58.33333333%;
  }
  .col-lg-offset-6 {
    margin-left: 50%;
  }
  .col-lg-offset-5 {
    margin-left: 41.66666667%;
  }
  .col-lg-offset-4 {
    margin-left: 33.33333333%;
  }
  .col-lg-offset-3 {
    margin-left: 25%;
  }
  .col-lg-offset-2 {
    margin-left: 16.66666667%;
  }
  .col-lg-offset-1 {
    margin-left: 8.33333333%;
  }
  .col-lg-offset-0 {
    margin-left: 0%;
  }
}
table {
  background-color: transparent;
}
caption {
  padding-top: 8px;
  padding-bottom: 8px;
  color: #777777;
  text-align: left;
}
th {
  text-align: left;
}
.table {
  width: 100%;
  max-width: 100%;
  margin-bottom: 18px;
}
.table > thead > tr > th,
.table > tbody > tr > th,
.table > tfoot > tr > th,
.table > thead > tr > td,
.table > tbody > tr > td,
.table > tfoot > tr > td {
  padding: 8px;
  line-height: 1.42857143;
  vertical-align: top;
  border-top: 1px solid #ddd;
}
.table > thead > tr > th {
  vertical-align: bottom;
  border-bottom: 2px solid #ddd;
}
.table > caption + thead > tr:first-child > th,
.table > colgroup + thead > tr:first-child > th,
.table > thead:first-child > tr:first-child > th,
.table > caption + thead > tr:first-child > td,
.table > colgroup + thead > tr:first-child > td,
.table > thead:first-child > tr:first-child > td {
  border-top: 0;
}
.table > tbody + tbody {
  border-top: 2px solid #ddd;
}
.table .table {
  background-color: #fff;
}
.table-condensed > thead > tr > th,
.table-condensed > tbody > tr > th,
.table-condensed > tfoot > tr > th,
.table-condensed > thead > tr > td,
.table-condensed > tbody > tr > td,
.table-condensed > tfoot > tr > td {
  padding: 5px;
}
.table-bordered {
  border: 1px solid #ddd;
}
.table-bordered > thead > tr > th,
.table-bordered > tbody > tr > th,
.table-bordered > tfoot > tr > th,
.table-bordered > thead > tr > td,
.table-bordered > tbody > tr > td,
.table-bordered > tfoot > tr > td {
  border: 1px solid #ddd;
}
.table-bordered > thead > tr > th,
.table-bordered > thead > tr > td {
  border-bottom-width: 2px;
}
.table-striped > tbody > tr:nth-of-type(odd) {
  background-color: #f9f9f9;
}
.table-hover > tbody > tr:hover {
  background-color: #f5f5f5;
}
table col[class*="col-"] {
  position: static;
  float: none;
  display: table-column;
}
table td[class*="col-"],
table th[class*="col-"] {
  position: static;
  float: none;
  display: table-cell;
}
.table > thead > tr > td.active,
.table > tbody > tr > td.active,
.table > tfoot > tr > td.active,
.table > thead > tr > th.active,
.table > tbody > tr > th.active,
.table > tfoot > tr > th.active,
.table > thead > tr.active > td,
.table > tbody > tr.active > td,
.table > tfoot > tr.active > td,
.table > thead > tr.active > th,
.table > tbody > tr.active > th,
.table > tfoot > tr.active > th {
  background-color: #f5f5f5;
}
.table-hover > tbody > tr > td.active:hover,
.table-hover > tbody > tr > th.active:hover,
.table-hover > tbody > tr.active:hover > td,
.table-hover > tbody > tr:hover > .active,
.table-hover > tbody > tr.active:hover > th {
  background-color: #e8e8e8;
}
.table > thead > tr > td.success,
.table > tbody > tr > td.success,
.table > tfoot > tr > td.success,
.table > thead > tr > th.success,
.table > tbody > tr > th.success,
.table > tfoot > tr > th.success,
.table > thead > tr.success > td,
.table > tbody > tr.success > td,
.table > tfoot > tr.success > td,
.table > thead > tr.success > th,
.table > tbody > tr.success > th,
.table > tfoot > tr.success > th {
  background-color: #dff0d8;
}
.table-hover > tbody > tr > td.success:hover,
.table-hover > tbody > tr > th.success:hover,
.table-hover > tbody > tr.success:hover > td,
.table-hover > tbody > tr:hover > .success,
.table-hover > tbody > tr.success:hover > th {
  background-color: #d0e9c6;
}
.table > thead > tr > td.info,
.table > tbody > tr > td.info,
.table > tfoot > tr > td.info,
.table > thead > tr > th.info,
.table > tbody > tr > th.info,
.table > tfoot > tr > th.info,
.table > thead > tr.info > td,
.table > tbody > tr.info > td,
.table > tfoot > tr.info > td,
.table > thead > tr.info > th,
.table > tbody > tr.info > th,
.table > tfoot > tr.info > th {
  background-color: #d9edf7;
}
.table-hover > tbody > tr > td.info:hover,
.table-hover > tbody > tr > th.info:hover,
.table-hover > tbody > tr.info:hover > td,
.table-hover > tbody > tr:hover > .info,
.table-hover > tbody > tr.info:hover > th {
  background-color: #c4e3f3;
}
.table > thead > tr > td.warning,
.table > tbody > tr > td.warning,
.table > tfoot > tr > td.warning,
.table > thead > tr > th.warning,
.table > tbody > tr > th.warning,
.table > tfoot > tr > th.warning,
.table > thead > tr.warning > td,
.table > tbody > tr.warning > td,
.table > tfoot > tr.warning > td,
.table > thead > tr.warning > th,
.table > tbody > tr.warning > th,
.table > tfoot > tr.warning > th {
  background-color: #fcf8e3;
}
.table-hover > tbody > tr > td.warning:hover,
.table-hover > tbody > tr > th.warning:hover,
.table-hover > tbody > tr.warning:hover > td,
.table-hover > tbody > tr:hover > .warning,
.table-hover > tbody > tr.warning:hover > th {
  background-color: #faf2cc;
}
.table > thead > tr > td.danger,
.table > tbody > tr > td.danger,
.table > tfoot > tr > td.danger,
.table > thead > tr > th.danger,
.table > tbody > tr > th.danger,
.table > tfoot > tr > th.danger,
.table > thead > tr.danger > td,
.table > tbody > tr.danger > td,
.table > tfoot > tr.danger > td,
.table > thead > tr.danger > th,
.table > tbody > tr.danger > th,
.table > tfoot > tr.danger > th {
  background-color: #f2dede;
}
.table-hover > tbody > tr > td.danger:hover,
.table-hover > tbody > tr > th.danger:hover,
.table-hover > tbody > tr.danger:hover > td,
.table-hover > tbody > tr:hover > .danger,
.table-hover > tbody > tr.danger:hover > th {
  background-color: #ebcccc;
}
.table-responsive {
  overflow-x: auto;
  min-height: 0.01%;
}
@media screen and (max-width: 767px) {
  .table-responsive {
    width: 100%;
    margin-bottom: 13.5px;
    overflow-y: hidden;
    -ms-overflow-style: -ms-autohiding-scrollbar;
    border: 1px solid #ddd;
  }
  .table-responsive > .table {
    margin-bottom: 0;
  }
  .table-responsive > .table > thead > tr > th,
  .table-responsive > .table > tbody > tr > th,
  .table-responsive > .table > tfoot > tr > th,
  .table-responsive > .table > thead > tr > td,
  .table-responsive > .table > tbody > tr > td,
  .table-responsive > .table > tfoot > tr > td {
    white-space: nowrap;
  }
  .table-responsive > .table-bordered {
    border: 0;
  }
  .table-responsive > .table-bordered > thead > tr > th:first-child,
  .table-responsive > .table-bordered > tbody > tr > th:first-child,
  .table-responsive > .table-bordered > tfoot > tr > th:first-child,
  .table-responsive > .table-bordered > thead > tr > td:first-child,
  .table-responsive > .table-bordered > tbody > tr > td:first-child,
  .table-responsive > .table-bordered > tfoot > tr > td:first-child {
    border-left: 0;
  }
  .table-responsive > .table-bordered > thead > tr > th:last-child,
  .table-responsive > .table-bordered > tbody > tr > th:last-child,
  .table-responsive > .table-bordered > tfoot > tr > th:last-child,
  .table-responsive > .table-bordered > thead > tr > td:last-child,
  .table-responsive > .table-bordered > tbody > tr > td:last-child,
  .table-responsive > .table-bordered > tfoot > tr > td:last-child {
    border-right: 0;
  }
  .table-responsive > .table-bordered > tbody > tr:last-child > th,
  .table-responsive > .table-bordered > tfoot > tr:last-child > th,
  .table-responsive > .table-bordered > tbody > tr:last-child > td,
  .table-responsive > .table-bordered > tfoot > tr:last-child > td {
    border-bottom: 0;
  }
}
fieldset {
  padding: 0;
  margin: 0;
  border: 0;
  min-width: 0;
}
legend {
  display: block;
  width: 100%;
  padding: 0;
  margin-bottom: 18px;
  font-size: 19.5px;
  line-height: inherit;
  color: #333333;
  border: 0;
  border-bottom: 1px solid #e5e5e5;
}
label {
  display: inline-block;
  max-width: 100%;
  margin-bottom: 5px;
  font-weight: bold;
}
input[type="search"] {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
input[type="radio"],
input[type="checkbox"] {
  margin: 4px 0 0;
  margin-top: 1px \9;
  line-height: normal;
}
input[type="file"] {
  display: block;
}
input[type="range"] {
  display: block;
  width: 100%;
}
select[multiple],
select[size] {
  height: auto;
}
input[type="file"]:focus,
input[type="radio"]:focus,
input[type="checkbox"]:focus {
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
output {
  display: block;
  padding-top: 7px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
}
.form-control {
  display: block;
  width: 100%;
  height: 32px;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
  background-color: #fff;
  background-image: none;
  border: 1px solid #ccc;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
}
.form-control:focus {
  border-color: #66afe9;
  outline: 0;
  -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
  box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
}
.form-control::-moz-placeholder {
  color: #999;
  opacity: 1;
}
.form-control:-ms-input-placeholder {
  color: #999;
}
.form-control::-webkit-input-placeholder {
  color: #999;
}
.form-control::-ms-expand {
  border: 0;
  background-color: transparent;
}
.form-control[disabled],
.form-control[readonly],
fieldset[disabled] .form-control {
  background-color: #eeeeee;
  opacity: 1;
}
.form-control[disabled],
fieldset[disabled] .form-control {
  cursor: not-allowed;
}
textarea.form-control {
  height: auto;
}
input[type="search"] {
  -webkit-appearance: none;
}
@media screen and (-webkit-min-device-pixel-ratio: 0) {
  input[type="date"].form-control,
  input[type="time"].form-control,
  input[type="datetime-local"].form-control,
  input[type="month"].form-control {
    line-height: 32px;
  }
  input[type="date"].input-sm,
  input[type="time"].input-sm,
  input[type="datetime-local"].input-sm,
  input[type="month"].input-sm,
  .input-group-sm input[type="date"],
  .input-group-sm input[type="time"],
  .input-group-sm input[type="datetime-local"],
  .input-group-sm input[type="month"] {
    line-height: 30px;
  }
  input[type="date"].input-lg,
  input[type="time"].input-lg,
  input[type="datetime-local"].input-lg,
  input[type="month"].input-lg,
  .input-group-lg input[type="date"],
  .input-group-lg input[type="time"],
  .input-group-lg input[type="datetime-local"],
  .input-group-lg input[type="month"] {
    line-height: 45px;
  }
}
.form-group {
  margin-bottom: 15px;
}
.radio,
.checkbox {
  position: relative;
  display: block;
  margin-top: 10px;
  margin-bottom: 10px;
}
.radio label,
.checkbox label {
  min-height: 18px;
  padding-left: 20px;
  margin-bottom: 0;
  font-weight: normal;
  cursor: pointer;
}
.radio input[type="radio"],
.radio-inline input[type="radio"],
.checkbox input[type="checkbox"],
.checkbox-inline input[type="checkbox"] {
  position: absolute;
  margin-left: -20px;
  margin-top: 4px \9;
}
.radio + .radio,
.checkbox + .checkbox {
  margin-top: -5px;
}
.radio-inline,
.checkbox-inline {
  position: relative;
  display: inline-block;
  padding-left: 20px;
  margin-bottom: 0;
  vertical-align: middle;
  font-weight: normal;
  cursor: pointer;
}
.radio-inline + .radio-inline,
.checkbox-inline + .checkbox-inline {
  margin-top: 0;
  margin-left: 10px;
}
input[type="radio"][disabled],
input[type="checkbox"][disabled],
input[type="radio"].disabled,
input[type="checkbox"].disabled,
fieldset[disabled] input[type="radio"],
fieldset[disabled] input[type="checkbox"] {
  cursor: not-allowed;
}
.radio-inline.disabled,
.checkbox-inline.disabled,
fieldset[disabled] .radio-inline,
fieldset[disabled] .checkbox-inline {
  cursor: not-allowed;
}
.radio.disabled label,
.checkbox.disabled label,
fieldset[disabled] .radio label,
fieldset[disabled] .checkbox label {
  cursor: not-allowed;
}
.form-control-static {
  padding-top: 7px;
  padding-bottom: 7px;
  margin-bottom: 0;
  min-height: 31px;
}
.form-control-static.input-lg,
.form-control-static.input-sm {
  padding-left: 0;
  padding-right: 0;
}
.input-sm {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
select.input-sm {
  height: 30px;
  line-height: 30px;
}
textarea.input-sm,
select[multiple].input-sm {
  height: auto;
}
.form-group-sm .form-control {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.form-group-sm select.form-control {
  height: 30px;
  line-height: 30px;
}
.form-group-sm textarea.form-control,
.form-group-sm select[multiple].form-control {
  height: auto;
}
.form-group-sm .form-control-static {
  height: 30px;
  min-height: 30px;
  padding: 6px 10px;
  font-size: 12px;
  line-height: 1.5;
}
.input-lg {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
select.input-lg {
  height: 45px;
  line-height: 45px;
}
textarea.input-lg,
select[multiple].input-lg {
  height: auto;
}
.form-group-lg .form-control {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
.form-group-lg select.form-control {
  height: 45px;
  line-height: 45px;
}
.form-group-lg textarea.form-control,
.form-group-lg select[multiple].form-control {
  height: auto;
}
.form-group-lg .form-control-static {
  height: 45px;
  min-height: 35px;
  padding: 11px 16px;
  font-size: 17px;
  line-height: 1.3333333;
}
.has-feedback {
  position: relative;
}
.has-feedback .form-control {
  padding-right: 40px;
}
.form-control-feedback {
  position: absolute;
  top: 0;
  right: 0;
  z-index: 2;
  display: block;
  width: 32px;
  height: 32px;
  line-height: 32px;
  text-align: center;
  pointer-events: none;
}
.input-lg + .form-control-feedback,
.input-group-lg + .form-control-feedback,
.form-group-lg .form-control + .form-control-feedback {
  width: 45px;
  height: 45px;
  line-height: 45px;
}
.input-sm + .form-control-feedback,
.input-group-sm + .form-control-feedback,
.form-group-sm .form-control + .form-control-feedback {
  width: 30px;
  height: 30px;
  line-height: 30px;
}
.has-success .help-block,
.has-success .control-label,
.has-success .radio,
.has-success .checkbox,
.has-success .radio-inline,
.has-success .checkbox-inline,
.has-success.radio label,
.has-success.checkbox label,
.has-success.radio-inline label,
.has-success.checkbox-inline label {
  color: #3c763d;
}
.has-success .form-control {
  border-color: #3c763d;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-success .form-control:focus {
  border-color: #2b542c;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #67b168;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #67b168;
}
.has-success .input-group-addon {
  color: #3c763d;
  border-color: #3c763d;
  background-color: #dff0d8;
}
.has-success .form-control-feedback {
  color: #3c763d;
}
.has-warning .help-block,
.has-warning .control-label,
.has-warning .radio,
.has-warning .checkbox,
.has-warning .radio-inline,
.has-warning .checkbox-inline,
.has-warning.radio label,
.has-warning.checkbox label,
.has-warning.radio-inline label,
.has-warning.checkbox-inline label {
  color: #8a6d3b;
}
.has-warning .form-control {
  border-color: #8a6d3b;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-warning .form-control:focus {
  border-color: #66512c;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #c0a16b;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #c0a16b;
}
.has-warning .input-group-addon {
  color: #8a6d3b;
  border-color: #8a6d3b;
  background-color: #fcf8e3;
}
.has-warning .form-control-feedback {
  color: #8a6d3b;
}
.has-error .help-block,
.has-error .control-label,
.has-error .radio,
.has-error .checkbox,
.has-error .radio-inline,
.has-error .checkbox-inline,
.has-error.radio label,
.has-error.checkbox label,
.has-error.radio-inline label,
.has-error.checkbox-inline label {
  color: #a94442;
}
.has-error .form-control {
  border-color: #a94442;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
}
.has-error .form-control:focus {
  border-color: #843534;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #ce8483;
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075), 0 0 6px #ce8483;
}
.has-error .input-group-addon {
  color: #a94442;
  border-color: #a94442;
  background-color: #f2dede;
}
.has-error .form-control-feedback {
  color: #a94442;
}
.has-feedback label ~ .form-control-feedback {
  top: 23px;
}
.has-feedback label.sr-only ~ .form-control-feedback {
  top: 0;
}
.help-block {
  display: block;
  margin-top: 5px;
  margin-bottom: 10px;
  color: #404040;
}
@media (min-width: 768px) {
  .form-inline .form-group {
    display: inline-block;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .form-control {
    display: inline-block;
    width: auto;
    vertical-align: middle;
  }
  .form-inline .form-control-static {
    display: inline-block;
  }
  .form-inline .input-group {
    display: inline-table;
    vertical-align: middle;
  }
  .form-inline .input-group .input-group-addon,
  .form-inline .input-group .input-group-btn,
  .form-inline .input-group .form-control {
    width: auto;
  }
  .form-inline .input-group > .form-control {
    width: 100%;
  }
  .form-inline .control-label {
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .radio,
  .form-inline .checkbox {
    display: inline-block;
    margin-top: 0;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .form-inline .radio label,
  .form-inline .checkbox label {
    padding-left: 0;
  }
  .form-inline .radio input[type="radio"],
  .form-inline .checkbox input[type="checkbox"] {
    position: relative;
    margin-left: 0;
  }
  .form-inline .has-feedback .form-control-feedback {
    top: 0;
  }
}
.form-horizontal .radio,
.form-horizontal .checkbox,
.form-horizontal .radio-inline,
.form-horizontal .checkbox-inline {
  margin-top: 0;
  margin-bottom: 0;
  padding-top: 7px;
}
.form-horizontal .radio,
.form-horizontal .checkbox {
  min-height: 25px;
}
.form-horizontal .form-group {
  margin-left: 0px;
  margin-right: 0px;
}
@media (min-width: 768px) {
  .form-horizontal .control-label {
    text-align: right;
    margin-bottom: 0;
    padding-top: 7px;
  }
}
.form-horizontal .has-feedback .form-control-feedback {
  right: 0px;
}
@media (min-width: 768px) {
  .form-horizontal .form-group-lg .control-label {
    padding-top: 11px;
    font-size: 17px;
  }
}
@media (min-width: 768px) {
  .form-horizontal .form-group-sm .control-label {
    padding-top: 6px;
    font-size: 12px;
  }
}
.btn {
  display: inline-block;
  margin-bottom: 0;
  font-weight: normal;
  text-align: center;
  vertical-align: middle;
  touch-action: manipulation;
  cursor: pointer;
  background-image: none;
  border: 1px solid transparent;
  white-space: nowrap;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  border-radius: 2px;
  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
}
.btn:focus,
.btn:active:focus,
.btn.active:focus,
.btn.focus,
.btn:active.focus,
.btn.active.focus {
  outline: 5px auto -webkit-focus-ring-color;
  outline-offset: -2px;
}
.btn:hover,
.btn:focus,
.btn.focus {
  color: #333;
  text-decoration: none;
}
.btn:active,
.btn.active {
  outline: 0;
  background-image: none;
  -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
  box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
}
.btn.disabled,
.btn[disabled],
fieldset[disabled] .btn {
  cursor: not-allowed;
  opacity: 0.65;
  filter: alpha(opacity=65);
  -webkit-box-shadow: none;
  box-shadow: none;
}
a.btn.disabled,
fieldset[disabled] a.btn {
  pointer-events: none;
}
.btn-default {
  color: #333;
  background-color: #fff;
  border-color: #ccc;
}
.btn-default:focus,
.btn-default.focus {
  color: #333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
.btn-default:hover {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.btn-default:active,
.btn-default.active,
.open > .dropdown-toggle.btn-default {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.btn-default:active:hover,
.btn-default.active:hover,
.open > .dropdown-toggle.btn-default:hover,
.btn-default:active:focus,
.btn-default.active:focus,
.open > .dropdown-toggle.btn-default:focus,
.btn-default:active.focus,
.btn-default.active.focus,
.open > .dropdown-toggle.btn-default.focus {
  color: #333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
.btn-default:active,
.btn-default.active,
.open > .dropdown-toggle.btn-default {
  background-image: none;
}
.btn-default.disabled:hover,
.btn-default[disabled]:hover,
fieldset[disabled] .btn-default:hover,
.btn-default.disabled:focus,
.btn-default[disabled]:focus,
fieldset[disabled] .btn-default:focus,
.btn-default.disabled.focus,
.btn-default[disabled].focus,
fieldset[disabled] .btn-default.focus {
  background-color: #fff;
  border-color: #ccc;
}
.btn-default .badge {
  color: #fff;
  background-color: #333;
}
.btn-primary {
  color: #fff;
  background-color: #337ab7;
  border-color: #2e6da4;
}
.btn-primary:focus,
.btn-primary.focus {
  color: #fff;
  background-color: #286090;
  border-color: #122b40;
}
.btn-primary:hover {
  color: #fff;
  background-color: #286090;
  border-color: #204d74;
}
.btn-primary:active,
.btn-primary.active,
.open > .dropdown-toggle.btn-primary {
  color: #fff;
  background-color: #286090;
  border-color: #204d74;
}
.btn-primary:active:hover,
.btn-primary.active:hover,
.open > .dropdown-toggle.btn-primary:hover,
.btn-primary:active:focus,
.btn-primary.active:focus,
.open > .dropdown-toggle.btn-primary:focus,
.btn-primary:active.focus,
.btn-primary.active.focus,
.open > .dropdown-toggle.btn-primary.focus {
  color: #fff;
  background-color: #204d74;
  border-color: #122b40;
}
.btn-primary:active,
.btn-primary.active,
.open > .dropdown-toggle.btn-primary {
  background-image: none;
}
.btn-primary.disabled:hover,
.btn-primary[disabled]:hover,
fieldset[disabled] .btn-primary:hover,
.btn-primary.disabled:focus,
.btn-primary[disabled]:focus,
fieldset[disabled] .btn-primary:focus,
.btn-primary.disabled.focus,
.btn-primary[disabled].focus,
fieldset[disabled] .btn-primary.focus {
  background-color: #337ab7;
  border-color: #2e6da4;
}
.btn-primary .badge {
  color: #337ab7;
  background-color: #fff;
}
.btn-success {
  color: #fff;
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.btn-success:focus,
.btn-success.focus {
  color: #fff;
  background-color: #449d44;
  border-color: #255625;
}
.btn-success:hover {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.btn-success:active,
.btn-success.active,
.open > .dropdown-toggle.btn-success {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.btn-success:active:hover,
.btn-success.active:hover,
.open > .dropdown-toggle.btn-success:hover,
.btn-success:active:focus,
.btn-success.active:focus,
.open > .dropdown-toggle.btn-success:focus,
.btn-success:active.focus,
.btn-success.active.focus,
.open > .dropdown-toggle.btn-success.focus {
  color: #fff;
  background-color: #398439;
  border-color: #255625;
}
.btn-success:active,
.btn-success.active,
.open > .dropdown-toggle.btn-success {
  background-image: none;
}
.btn-success.disabled:hover,
.btn-success[disabled]:hover,
fieldset[disabled] .btn-success:hover,
.btn-success.disabled:focus,
.btn-success[disabled]:focus,
fieldset[disabled] .btn-success:focus,
.btn-success.disabled.focus,
.btn-success[disabled].focus,
fieldset[disabled] .btn-success.focus {
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.btn-success .badge {
  color: #5cb85c;
  background-color: #fff;
}
.btn-info {
  color: #fff;
  background-color: #5bc0de;
  border-color: #46b8da;
}
.btn-info:focus,
.btn-info.focus {
  color: #fff;
  background-color: #31b0d5;
  border-color: #1b6d85;
}
.btn-info:hover {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.btn-info:active,
.btn-info.active,
.open > .dropdown-toggle.btn-info {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.btn-info:active:hover,
.btn-info.active:hover,
.open > .dropdown-toggle.btn-info:hover,
.btn-info:active:focus,
.btn-info.active:focus,
.open > .dropdown-toggle.btn-info:focus,
.btn-info:active.focus,
.btn-info.active.focus,
.open > .dropdown-toggle.btn-info.focus {
  color: #fff;
  background-color: #269abc;
  border-color: #1b6d85;
}
.btn-info:active,
.btn-info.active,
.open > .dropdown-toggle.btn-info {
  background-image: none;
}
.btn-info.disabled:hover,
.btn-info[disabled]:hover,
fieldset[disabled] .btn-info:hover,
.btn-info.disabled:focus,
.btn-info[disabled]:focus,
fieldset[disabled] .btn-info:focus,
.btn-info.disabled.focus,
.btn-info[disabled].focus,
fieldset[disabled] .btn-info.focus {
  background-color: #5bc0de;
  border-color: #46b8da;
}
.btn-info .badge {
  color: #5bc0de;
  background-color: #fff;
}
.btn-warning {
  color: #fff;
  background-color: #f0ad4e;
  border-color: #eea236;
}
.btn-warning:focus,
.btn-warning.focus {
  color: #fff;
  background-color: #ec971f;
  border-color: #985f0d;
}
.btn-warning:hover {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.btn-warning:active,
.btn-warning.active,
.open > .dropdown-toggle.btn-warning {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.btn-warning:active:hover,
.btn-warning.active:hover,
.open > .dropdown-toggle.btn-warning:hover,
.btn-warning:active:focus,
.btn-warning.active:focus,
.open > .dropdown-toggle.btn-warning:focus,
.btn-warning:active.focus,
.btn-warning.active.focus,
.open > .dropdown-toggle.btn-warning.focus {
  color: #fff;
  background-color: #d58512;
  border-color: #985f0d;
}
.btn-warning:active,
.btn-warning.active,
.open > .dropdown-toggle.btn-warning {
  background-image: none;
}
.btn-warning.disabled:hover,
.btn-warning[disabled]:hover,
fieldset[disabled] .btn-warning:hover,
.btn-warning.disabled:focus,
.btn-warning[disabled]:focus,
fieldset[disabled] .btn-warning:focus,
.btn-warning.disabled.focus,
.btn-warning[disabled].focus,
fieldset[disabled] .btn-warning.focus {
  background-color: #f0ad4e;
  border-color: #eea236;
}
.btn-warning .badge {
  color: #f0ad4e;
  background-color: #fff;
}
.btn-danger {
  color: #fff;
  background-color: #d9534f;
  border-color: #d43f3a;
}
.btn-danger:focus,
.btn-danger.focus {
  color: #fff;
  background-color: #c9302c;
  border-color: #761c19;
}
.btn-danger:hover {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.btn-danger:active,
.btn-danger.active,
.open > .dropdown-toggle.btn-danger {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.btn-danger:active:hover,
.btn-danger.active:hover,
.open > .dropdown-toggle.btn-danger:hover,
.btn-danger:active:focus,
.btn-danger.active:focus,
.open > .dropdown-toggle.btn-danger:focus,
.btn-danger:active.focus,
.btn-danger.active.focus,
.open > .dropdown-toggle.btn-danger.focus {
  color: #fff;
  background-color: #ac2925;
  border-color: #761c19;
}
.btn-danger:active,
.btn-danger.active,
.open > .dropdown-toggle.btn-danger {
  background-image: none;
}
.btn-danger.disabled:hover,
.btn-danger[disabled]:hover,
fieldset[disabled] .btn-danger:hover,
.btn-danger.disabled:focus,
.btn-danger[disabled]:focus,
fieldset[disabled] .btn-danger:focus,
.btn-danger.disabled.focus,
.btn-danger[disabled].focus,
fieldset[disabled] .btn-danger.focus {
  background-color: #d9534f;
  border-color: #d43f3a;
}
.btn-danger .badge {
  color: #d9534f;
  background-color: #fff;
}
.btn-link {
  color: #337ab7;
  font-weight: normal;
  border-radius: 0;
}
.btn-link,
.btn-link:active,
.btn-link.active,
.btn-link[disabled],
fieldset[disabled] .btn-link {
  background-color: transparent;
  -webkit-box-shadow: none;
  box-shadow: none;
}
.btn-link,
.btn-link:hover,
.btn-link:focus,
.btn-link:active {
  border-color: transparent;
}
.btn-link:hover,
.btn-link:focus {
  color: #23527c;
  text-decoration: underline;
  background-color: transparent;
}
.btn-link[disabled]:hover,
fieldset[disabled] .btn-link:hover,
.btn-link[disabled]:focus,
fieldset[disabled] .btn-link:focus {
  color: #777777;
  text-decoration: none;
}
.btn-lg,
.btn-group-lg > .btn {
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
.btn-sm,
.btn-group-sm > .btn {
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.btn-xs,
.btn-group-xs > .btn {
  padding: 1px 5px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
.btn-block {
  display: block;
  width: 100%;
}
.btn-block + .btn-block {
  margin-top: 5px;
}
input[type="submit"].btn-block,
input[type="reset"].btn-block,
input[type="button"].btn-block {
  width: 100%;
}
.fade {
  opacity: 0;
  -webkit-transition: opacity 0.15s linear;
  -o-transition: opacity 0.15s linear;
  transition: opacity 0.15s linear;
}
.fade.in {
  opacity: 1;
}
.collapse {
  display: none;
}
.collapse.in {
  display: block;
}
tr.collapse.in {
  display: table-row;
}
tbody.collapse.in {
  display: table-row-group;
}
.collapsing {
  position: relative;
  height: 0;
  overflow: hidden;
  -webkit-transition-property: height, visibility;
  transition-property: height, visibility;
  -webkit-transition-duration: 0.35s;
  transition-duration: 0.35s;
  -webkit-transition-timing-function: ease;
  transition-timing-function: ease;
}
.caret {
  display: inline-block;
  width: 0;
  height: 0;
  margin-left: 2px;
  vertical-align: middle;
  border-top: 4px dashed;
  border-top: 4px solid \9;
  border-right: 4px solid transparent;
  border-left: 4px solid transparent;
}
.dropup,
.dropdown {
  position: relative;
}
.dropdown-toggle:focus {
  outline: 0;
}
.dropdown-menu {
  position: absolute;
  top: 100%;
  left: 0;
  z-index: 1000;
  display: none;
  float: left;
  min-width: 160px;
  padding: 5px 0;
  margin: 2px 0 0;
  list-style: none;
  font-size: 13px;
  text-align: left;
  background-color: #fff;
  border: 1px solid #ccc;
  border: 1px solid rgba(0, 0, 0, 0.15);
  border-radius: 2px;
  -webkit-box-shadow: 0 6px 12px rgba(0, 0, 0, 0.175);
  box-shadow: 0 6px 12px rgba(0, 0, 0, 0.175);
  background-clip: padding-box;
}
.dropdown-menu.pull-right {
  right: 0;
  left: auto;
}
.dropdown-menu .divider {
  height: 1px;
  margin: 8px 0;
  overflow: hidden;
  background-color: #e5e5e5;
}
.dropdown-menu > li > a {
  display: block;
  padding: 3px 20px;
  clear: both;
  font-weight: normal;
  line-height: 1.42857143;
  color: #333333;
  white-space: nowrap;
}
.dropdown-menu > li > a:hover,
.dropdown-menu > li > a:focus {
  text-decoration: none;
  color: #262626;
  background-color: #f5f5f5;
}
.dropdown-menu > .active > a,
.dropdown-menu > .active > a:hover,
.dropdown-menu > .active > a:focus {
  color: #fff;
  text-decoration: none;
  outline: 0;
  background-color: #337ab7;
}
.dropdown-menu > .disabled > a,
.dropdown-menu > .disabled > a:hover,
.dropdown-menu > .disabled > a:focus {
  color: #777777;
}
.dropdown-menu > .disabled > a:hover,
.dropdown-menu > .disabled > a:focus {
  text-decoration: none;
  background-color: transparent;
  background-image: none;
  filter: progid:DXImageTransform.Microsoft.gradient(enabled = false);
  cursor: not-allowed;
}
.open > .dropdown-menu {
  display: block;
}
.open > a {
  outline: 0;
}
.dropdown-menu-right {
  left: auto;
  right: 0;
}
.dropdown-menu-left {
  left: 0;
  right: auto;
}
.dropdown-header {
  display: block;
  padding: 3px 20px;
  font-size: 12px;
  line-height: 1.42857143;
  color: #777777;
  white-space: nowrap;
}
.dropdown-backdrop {
  position: fixed;
  left: 0;
  right: 0;
  bottom: 0;
  top: 0;
  z-index: 990;
}
.pull-right > .dropdown-menu {
  right: 0;
  left: auto;
}
.dropup .caret,
.navbar-fixed-bottom .dropdown .caret {
  border-top: 0;
  border-bottom: 4px dashed;
  border-bottom: 4px solid \9;
  content: "";
}
.dropup .dropdown-menu,
.navbar-fixed-bottom .dropdown .dropdown-menu {
  top: auto;
  bottom: 100%;
  margin-bottom: 2px;
}
@media (min-width: 541px) {
  .navbar-right .dropdown-menu {
    left: auto;
    right: 0;
  }
  .navbar-right .dropdown-menu-left {
    left: 0;
    right: auto;
  }
}
.btn-group,
.btn-group-vertical {
  position: relative;
  display: inline-block;
  vertical-align: middle;
}
.btn-group > .btn,
.btn-group-vertical > .btn {
  position: relative;
  float: left;
}
.btn-group > .btn:hover,
.btn-group-vertical > .btn:hover,
.btn-group > .btn:focus,
.btn-group-vertical > .btn:focus,
.btn-group > .btn:active,
.btn-group-vertical > .btn:active,
.btn-group > .btn.active,
.btn-group-vertical > .btn.active {
  z-index: 2;
}
.btn-group .btn + .btn,
.btn-group .btn + .btn-group,
.btn-group .btn-group + .btn,
.btn-group .btn-group + .btn-group {
  margin-left: -1px;
}
.btn-toolbar {
  margin-left: -5px;
}
.btn-toolbar .btn,
.btn-toolbar .btn-group,
.btn-toolbar .input-group {
  float: left;
}
.btn-toolbar > .btn,
.btn-toolbar > .btn-group,
.btn-toolbar > .input-group {
  margin-left: 5px;
}
.btn-group > .btn:not(:first-child):not(:last-child):not(.dropdown-toggle) {
  border-radius: 0;
}
.btn-group > .btn:first-child {
  margin-left: 0;
}
.btn-group > .btn:first-child:not(:last-child):not(.dropdown-toggle) {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.btn-group > .btn:last-child:not(:first-child),
.btn-group > .dropdown-toggle:not(:first-child) {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.btn-group > .btn-group {
  float: left;
}
.btn-group > .btn-group:not(:first-child):not(:last-child) > .btn {
  border-radius: 0;
}
.btn-group > .btn-group:first-child:not(:last-child) > .btn:last-child,
.btn-group > .btn-group:first-child:not(:last-child) > .dropdown-toggle {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.btn-group > .btn-group:last-child:not(:first-child) > .btn:first-child {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.btn-group .dropdown-toggle:active,
.btn-group.open .dropdown-toggle {
  outline: 0;
}
.btn-group > .btn + .dropdown-toggle {
  padding-left: 8px;
  padding-right: 8px;
}
.btn-group > .btn-lg + .dropdown-toggle {
  padding-left: 12px;
  padding-right: 12px;
}
.btn-group.open .dropdown-toggle {
  -webkit-box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
  box-shadow: inset 0 3px 5px rgba(0, 0, 0, 0.125);
}
.btn-group.open .dropdown-toggle.btn-link {
  -webkit-box-shadow: none;
  box-shadow: none;
}
.btn .caret {
  margin-left: 0;
}
.btn-lg .caret {
  border-width: 5px 5px 0;
  border-bottom-width: 0;
}
.dropup .btn-lg .caret {
  border-width: 0 5px 5px;
}
.btn-group-vertical > .btn,
.btn-group-vertical > .btn-group,
.btn-group-vertical > .btn-group > .btn {
  display: block;
  float: none;
  width: 100%;
  max-width: 100%;
}
.btn-group-vertical > .btn-group > .btn {
  float: none;
}
.btn-group-vertical > .btn + .btn,
.btn-group-vertical > .btn + .btn-group,
.btn-group-vertical > .btn-group + .btn,
.btn-group-vertical > .btn-group + .btn-group {
  margin-top: -1px;
  margin-left: 0;
}
.btn-group-vertical > .btn:not(:first-child):not(:last-child) {
  border-radius: 0;
}
.btn-group-vertical > .btn:first-child:not(:last-child) {
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.btn-group-vertical > .btn:last-child:not(:first-child) {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
  border-bottom-right-radius: 2px;
  border-bottom-left-radius: 2px;
}
.btn-group-vertical > .btn-group:not(:first-child):not(:last-child) > .btn {
  border-radius: 0;
}
.btn-group-vertical > .btn-group:first-child:not(:last-child) > .btn:last-child,
.btn-group-vertical > .btn-group:first-child:not(:last-child) > .dropdown-toggle {
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.btn-group-vertical > .btn-group:last-child:not(:first-child) > .btn:first-child {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.btn-group-justified {
  display: table;
  width: 100%;
  table-layout: fixed;
  border-collapse: separate;
}
.btn-group-justified > .btn,
.btn-group-justified > .btn-group {
  float: none;
  display: table-cell;
  width: 1%;
}
.btn-group-justified > .btn-group .btn {
  width: 100%;
}
.btn-group-justified > .btn-group .dropdown-menu {
  left: auto;
}
[data-toggle="buttons"] > .btn input[type="radio"],
[data-toggle="buttons"] > .btn-group > .btn input[type="radio"],
[data-toggle="buttons"] > .btn input[type="checkbox"],
[data-toggle="buttons"] > .btn-group > .btn input[type="checkbox"] {
  position: absolute;
  clip: rect(0, 0, 0, 0);
  pointer-events: none;
}
.input-group {
  position: relative;
  display: table;
  border-collapse: separate;
}
.input-group[class*="col-"] {
  float: none;
  padding-left: 0;
  padding-right: 0;
}
.input-group .form-control {
  position: relative;
  z-index: 2;
  float: left;
  width: 100%;
  margin-bottom: 0;
}
.input-group .form-control:focus {
  z-index: 3;
}
.input-group-lg > .form-control,
.input-group-lg > .input-group-addon,
.input-group-lg > .input-group-btn > .btn {
  height: 45px;
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
  border-radius: 3px;
}
select.input-group-lg > .form-control,
select.input-group-lg > .input-group-addon,
select.input-group-lg > .input-group-btn > .btn {
  height: 45px;
  line-height: 45px;
}
textarea.input-group-lg > .form-control,
textarea.input-group-lg > .input-group-addon,
textarea.input-group-lg > .input-group-btn > .btn,
select[multiple].input-group-lg > .form-control,
select[multiple].input-group-lg > .input-group-addon,
select[multiple].input-group-lg > .input-group-btn > .btn {
  height: auto;
}
.input-group-sm > .form-control,
.input-group-sm > .input-group-addon,
.input-group-sm > .input-group-btn > .btn {
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
}
select.input-group-sm > .form-control,
select.input-group-sm > .input-group-addon,
select.input-group-sm > .input-group-btn > .btn {
  height: 30px;
  line-height: 30px;
}
textarea.input-group-sm > .form-control,
textarea.input-group-sm > .input-group-addon,
textarea.input-group-sm > .input-group-btn > .btn,
select[multiple].input-group-sm > .form-control,
select[multiple].input-group-sm > .input-group-addon,
select[multiple].input-group-sm > .input-group-btn > .btn {
  height: auto;
}
.input-group-addon,
.input-group-btn,
.input-group .form-control {
  display: table-cell;
}
.input-group-addon:not(:first-child):not(:last-child),
.input-group-btn:not(:first-child):not(:last-child),
.input-group .form-control:not(:first-child):not(:last-child) {
  border-radius: 0;
}
.input-group-addon,
.input-group-btn {
  width: 1%;
  white-space: nowrap;
  vertical-align: middle;
}
.input-group-addon {
  padding: 6px 12px;
  font-size: 13px;
  font-weight: normal;
  line-height: 1;
  color: #555555;
  text-align: center;
  background-color: #eeeeee;
  border: 1px solid #ccc;
  border-radius: 2px;
}
.input-group-addon.input-sm {
  padding: 5px 10px;
  font-size: 12px;
  border-radius: 1px;
}
.input-group-addon.input-lg {
  padding: 10px 16px;
  font-size: 17px;
  border-radius: 3px;
}
.input-group-addon input[type="radio"],
.input-group-addon input[type="checkbox"] {
  margin-top: 0;
}
.input-group .form-control:first-child,
.input-group-addon:first-child,
.input-group-btn:first-child > .btn,
.input-group-btn:first-child > .btn-group > .btn,
.input-group-btn:first-child > .dropdown-toggle,
.input-group-btn:last-child > .btn:not(:last-child):not(.dropdown-toggle),
.input-group-btn:last-child > .btn-group:not(:last-child) > .btn {
  border-bottom-right-radius: 0;
  border-top-right-radius: 0;
}
.input-group-addon:first-child {
  border-right: 0;
}
.input-group .form-control:last-child,
.input-group-addon:last-child,
.input-group-btn:last-child > .btn,
.input-group-btn:last-child > .btn-group > .btn,
.input-group-btn:last-child > .dropdown-toggle,
.input-group-btn:first-child > .btn:not(:first-child),
.input-group-btn:first-child > .btn-group:not(:first-child) > .btn {
  border-bottom-left-radius: 0;
  border-top-left-radius: 0;
}
.input-group-addon:last-child {
  border-left: 0;
}
.input-group-btn {
  position: relative;
  font-size: 0;
  white-space: nowrap;
}
.input-group-btn > .btn {
  position: relative;
}
.input-group-btn > .btn + .btn {
  margin-left: -1px;
}
.input-group-btn > .btn:hover,
.input-group-btn > .btn:focus,
.input-group-btn > .btn:active {
  z-index: 2;
}
.input-group-btn:first-child > .btn,
.input-group-btn:first-child > .btn-group {
  margin-right: -1px;
}
.input-group-btn:last-child > .btn,
.input-group-btn:last-child > .btn-group {
  z-index: 2;
  margin-left: -1px;
}
.nav {
  margin-bottom: 0;
  padding-left: 0;
  list-style: none;
}
.nav > li {
  position: relative;
  display: block;
}
.nav > li > a {
  position: relative;
  display: block;
  padding: 10px 15px;
}
.nav > li > a:hover,
.nav > li > a:focus {
  text-decoration: none;
  background-color: #eeeeee;
}
.nav > li.disabled > a {
  color: #777777;
}
.nav > li.disabled > a:hover,
.nav > li.disabled > a:focus {
  color: #777777;
  text-decoration: none;
  background-color: transparent;
  cursor: not-allowed;
}
.nav .open > a,
.nav .open > a:hover,
.nav .open > a:focus {
  background-color: #eeeeee;
  border-color: #337ab7;
}
.nav .nav-divider {
  height: 1px;
  margin: 8px 0;
  overflow: hidden;
  background-color: #e5e5e5;
}
.nav > li > a > img {
  max-width: none;
}
.nav-tabs {
  border-bottom: 1px solid #ddd;
}
.nav-tabs > li {
  float: left;
  margin-bottom: -1px;
}
.nav-tabs > li > a {
  margin-right: 2px;
  line-height: 1.42857143;
  border: 1px solid transparent;
  border-radius: 2px 2px 0 0;
}
.nav-tabs > li > a:hover {
  border-color: #eeeeee #eeeeee #ddd;
}
.nav-tabs > li.active > a,
.nav-tabs > li.active > a:hover,
.nav-tabs > li.active > a:focus {
  color: #555555;
  background-color: #fff;
  border: 1px solid #ddd;
  border-bottom-color: transparent;
  cursor: default;
}
.nav-tabs.nav-justified {
  width: 100%;
  border-bottom: 0;
}
.nav-tabs.nav-justified > li {
  float: none;
}
.nav-tabs.nav-justified > li > a {
  text-align: center;
  margin-bottom: 5px;
}
.nav-tabs.nav-justified > .dropdown .dropdown-menu {
  top: auto;
  left: auto;
}
@media (min-width: 768px) {
  .nav-tabs.nav-justified > li {
    display: table-cell;
    width: 1%;
  }
  .nav-tabs.nav-justified > li > a {
    margin-bottom: 0;
  }
}
.nav-tabs.nav-justified > li > a {
  margin-right: 0;
  border-radius: 2px;
}
.nav-tabs.nav-justified > .active > a,
.nav-tabs.nav-justified > .active > a:hover,
.nav-tabs.nav-justified > .active > a:focus {
  border: 1px solid #ddd;
}
@media (min-width: 768px) {
  .nav-tabs.nav-justified > li > a {
    border-bottom: 1px solid #ddd;
    border-radius: 2px 2px 0 0;
  }
  .nav-tabs.nav-justified > .active > a,
  .nav-tabs.nav-justified > .active > a:hover,
  .nav-tabs.nav-justified > .active > a:focus {
    border-bottom-color: #fff;
  }
}
.nav-pills > li {
  float: left;
}
.nav-pills > li > a {
  border-radius: 2px;
}
.nav-pills > li + li {
  margin-left: 2px;
}
.nav-pills > li.active > a,
.nav-pills > li.active > a:hover,
.nav-pills > li.active > a:focus {
  color: #fff;
  background-color: #337ab7;
}
.nav-stacked > li {
  float: none;
}
.nav-stacked > li + li {
  margin-top: 2px;
  margin-left: 0;
}
.nav-justified {
  width: 100%;
}
.nav-justified > li {
  float: none;
}
.nav-justified > li > a {
  text-align: center;
  margin-bottom: 5px;
}
.nav-justified > .dropdown .dropdown-menu {
  top: auto;
  left: auto;
}
@media (min-width: 768px) {
  .nav-justified > li {
    display: table-cell;
    width: 1%;
  }
  .nav-justified > li > a {
    margin-bottom: 0;
  }
}
.nav-tabs-justified {
  border-bottom: 0;
}
.nav-tabs-justified > li > a {
  margin-right: 0;
  border-radius: 2px;
}
.nav-tabs-justified > .active > a,
.nav-tabs-justified > .active > a:hover,
.nav-tabs-justified > .active > a:focus {
  border: 1px solid #ddd;
}
@media (min-width: 768px) {
  .nav-tabs-justified > li > a {
    border-bottom: 1px solid #ddd;
    border-radius: 2px 2px 0 0;
  }
  .nav-tabs-justified > .active > a,
  .nav-tabs-justified > .active > a:hover,
  .nav-tabs-justified > .active > a:focus {
    border-bottom-color: #fff;
  }
}
.tab-content > .tab-pane {
  display: none;
}
.tab-content > .active {
  display: block;
}
.nav-tabs .dropdown-menu {
  margin-top: -1px;
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.navbar {
  position: relative;
  min-height: 30px;
  margin-bottom: 18px;
  border: 1px solid transparent;
}
@media (min-width: 541px) {
  .navbar {
    border-radius: 2px;
  }
}
@media (min-width: 541px) {
  .navbar-header {
    float: left;
  }
}
.navbar-collapse {
  overflow-x: visible;
  padding-right: 0px;
  padding-left: 0px;
  border-top: 1px solid transparent;
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1);
  -webkit-overflow-scrolling: touch;
}
.navbar-collapse.in {
  overflow-y: auto;
}
@media (min-width: 541px) {
  .navbar-collapse {
    width: auto;
    border-top: 0;
    box-shadow: none;
  }
  .navbar-collapse.collapse {
    display: block !important;
    height: auto !important;
    padding-bottom: 0;
    overflow: visible !important;
  }
  .navbar-collapse.in {
    overflow-y: visible;
  }
  .navbar-fixed-top .navbar-collapse,
  .navbar-static-top .navbar-collapse,
  .navbar-fixed-bottom .navbar-collapse {
    padding-left: 0;
    padding-right: 0;
  }
}
.navbar-fixed-top .navbar-collapse,
.navbar-fixed-bottom .navbar-collapse {
  max-height: 340px;
}
@media (max-device-width: 540px) and (orientation: landscape) {
  .navbar-fixed-top .navbar-collapse,
  .navbar-fixed-bottom .navbar-collapse {
    max-height: 200px;
  }
}
.container > .navbar-header,
.container-fluid > .navbar-header,
.container > .navbar-collapse,
.container-fluid > .navbar-collapse {
  margin-right: 0px;
  margin-left: 0px;
}
@media (min-width: 541px) {
  .container > .navbar-header,
  .container-fluid > .navbar-header,
  .container > .navbar-collapse,
  .container-fluid > .navbar-collapse {
    margin-right: 0;
    margin-left: 0;
  }
}
.navbar-static-top {
  z-index: 1000;
  border-width: 0 0 1px;
}
@media (min-width: 541px) {
  .navbar-static-top {
    border-radius: 0;
  }
}
.navbar-fixed-top,
.navbar-fixed-bottom {
  position: fixed;
  right: 0;
  left: 0;
  z-index: 1030;
}
@media (min-width: 541px) {
  .navbar-fixed-top,
  .navbar-fixed-bottom {
    border-radius: 0;
  }
}
.navbar-fixed-top {
  top: 0;
  border-width: 0 0 1px;
}
.navbar-fixed-bottom {
  bottom: 0;
  margin-bottom: 0;
  border-width: 1px 0 0;
}
.navbar-brand {
  float: left;
  padding: 6px 0px;
  font-size: 17px;
  line-height: 18px;
  height: 30px;
}
.navbar-brand:hover,
.navbar-brand:focus {
  text-decoration: none;
}
.navbar-brand > img {
  display: block;
}
@media (min-width: 541px) {
  .navbar > .container .navbar-brand,
  .navbar > .container-fluid .navbar-brand {
    margin-left: 0px;
  }
}
.navbar-toggle {
  position: relative;
  float: right;
  margin-right: 0px;
  padding: 9px 10px;
  margin-top: -2px;
  margin-bottom: -2px;
  background-color: transparent;
  background-image: none;
  border: 1px solid transparent;
  border-radius: 2px;
}
.navbar-toggle:focus {
  outline: 0;
}
.navbar-toggle .icon-bar {
  display: block;
  width: 22px;
  height: 2px;
  border-radius: 1px;
}
.navbar-toggle .icon-bar + .icon-bar {
  margin-top: 4px;
}
@media (min-width: 541px) {
  .navbar-toggle {
    display: none;
  }
}
.navbar-nav {
  margin: 3px 0px;
}
.navbar-nav > li > a {
  padding-top: 10px;
  padding-bottom: 10px;
  line-height: 18px;
}
@media (max-width: 540px) {
  .navbar-nav .open .dropdown-menu {
    position: static;
    float: none;
    width: auto;
    margin-top: 0;
    background-color: transparent;
    border: 0;
    box-shadow: none;
  }
  .navbar-nav .open .dropdown-menu > li > a,
  .navbar-nav .open .dropdown-menu .dropdown-header {
    padding: 5px 15px 5px 25px;
  }
  .navbar-nav .open .dropdown-menu > li > a {
    line-height: 18px;
  }
  .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-nav .open .dropdown-menu > li > a:focus {
    background-image: none;
  }
}
@media (min-width: 541px) {
  .navbar-nav {
    float: left;
    margin: 0;
  }
  .navbar-nav > li {
    float: left;
  }
  .navbar-nav > li > a {
    padding-top: 6px;
    padding-bottom: 6px;
  }
}
.navbar-form {
  margin-left: 0px;
  margin-right: 0px;
  padding: 10px 0px;
  border-top: 1px solid transparent;
  border-bottom: 1px solid transparent;
  -webkit-box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.1);
  box-shadow: inset 0 1px 0 rgba(255, 255, 255, 0.1), 0 1px 0 rgba(255, 255, 255, 0.1);
  margin-top: -1px;
  margin-bottom: -1px;
}
@media (min-width: 768px) {
  .navbar-form .form-group {
    display: inline-block;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .form-control {
    display: inline-block;
    width: auto;
    vertical-align: middle;
  }
  .navbar-form .form-control-static {
    display: inline-block;
  }
  .navbar-form .input-group {
    display: inline-table;
    vertical-align: middle;
  }
  .navbar-form .input-group .input-group-addon,
  .navbar-form .input-group .input-group-btn,
  .navbar-form .input-group .form-control {
    width: auto;
  }
  .navbar-form .input-group > .form-control {
    width: 100%;
  }
  .navbar-form .control-label {
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .radio,
  .navbar-form .checkbox {
    display: inline-block;
    margin-top: 0;
    margin-bottom: 0;
    vertical-align: middle;
  }
  .navbar-form .radio label,
  .navbar-form .checkbox label {
    padding-left: 0;
  }
  .navbar-form .radio input[type="radio"],
  .navbar-form .checkbox input[type="checkbox"] {
    position: relative;
    margin-left: 0;
  }
  .navbar-form .has-feedback .form-control-feedback {
    top: 0;
  }
}
@media (max-width: 540px) {
  .navbar-form .form-group {
    margin-bottom: 5px;
  }
  .navbar-form .form-group:last-child {
    margin-bottom: 0;
  }
}
@media (min-width: 541px) {
  .navbar-form {
    width: auto;
    border: 0;
    margin-left: 0;
    margin-right: 0;
    padding-top: 0;
    padding-bottom: 0;
    -webkit-box-shadow: none;
    box-shadow: none;
  }
}
.navbar-nav > li > .dropdown-menu {
  margin-top: 0;
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.navbar-fixed-bottom .navbar-nav > li > .dropdown-menu {
  margin-bottom: 0;
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
  border-bottom-right-radius: 0;
  border-bottom-left-radius: 0;
}
.navbar-btn {
  margin-top: -1px;
  margin-bottom: -1px;
}
.navbar-btn.btn-sm {
  margin-top: 0px;
  margin-bottom: 0px;
}
.navbar-btn.btn-xs {
  margin-top: 4px;
  margin-bottom: 4px;
}
.navbar-text {
  margin-top: 6px;
  margin-bottom: 6px;
}
@media (min-width: 541px) {
  .navbar-text {
    float: left;
    margin-left: 0px;
    margin-right: 0px;
  }
}
@media (min-width: 541px) {
  .navbar-left {
    float: left !important;
    float: left;
  }
  .navbar-right {
    float: right !important;
    float: right;
    margin-right: 0px;
  }
  .navbar-right ~ .navbar-right {
    margin-right: 0;
  }
}
.navbar-default {
  background-color: #f8f8f8;
  border-color: #e7e7e7;
}
.navbar-default .navbar-brand {
  color: #777;
}
.navbar-default .navbar-brand:hover,
.navbar-default .navbar-brand:focus {
  color: #5e5e5e;
  background-color: transparent;
}
.navbar-default .navbar-text {
  color: #777;
}
.navbar-default .navbar-nav > li > a {
  color: #777;
}
.navbar-default .navbar-nav > li > a:hover,
.navbar-default .navbar-nav > li > a:focus {
  color: #333;
  background-color: transparent;
}
.navbar-default .navbar-nav > .active > a,
.navbar-default .navbar-nav > .active > a:hover,
.navbar-default .navbar-nav > .active > a:focus {
  color: #555;
  background-color: #e7e7e7;
}
.navbar-default .navbar-nav > .disabled > a,
.navbar-default .navbar-nav > .disabled > a:hover,
.navbar-default .navbar-nav > .disabled > a:focus {
  color: #ccc;
  background-color: transparent;
}
.navbar-default .navbar-toggle {
  border-color: #ddd;
}
.navbar-default .navbar-toggle:hover,
.navbar-default .navbar-toggle:focus {
  background-color: #ddd;
}
.navbar-default .navbar-toggle .icon-bar {
  background-color: #888;
}
.navbar-default .navbar-collapse,
.navbar-default .navbar-form {
  border-color: #e7e7e7;
}
.navbar-default .navbar-nav > .open > a,
.navbar-default .navbar-nav > .open > a:hover,
.navbar-default .navbar-nav > .open > a:focus {
  background-color: #e7e7e7;
  color: #555;
}
@media (max-width: 540px) {
  .navbar-default .navbar-nav .open .dropdown-menu > li > a {
    color: #777;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > li > a:focus {
    color: #333;
    background-color: transparent;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a,
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > .active > a:focus {
    color: #555;
    background-color: #e7e7e7;
  }
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a,
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a:hover,
  .navbar-default .navbar-nav .open .dropdown-menu > .disabled > a:focus {
    color: #ccc;
    background-color: transparent;
  }
}
.navbar-default .navbar-link {
  color: #777;
}
.navbar-default .navbar-link:hover {
  color: #333;
}
.navbar-default .btn-link {
  color: #777;
}
.navbar-default .btn-link:hover,
.navbar-default .btn-link:focus {
  color: #333;
}
.navbar-default .btn-link[disabled]:hover,
fieldset[disabled] .navbar-default .btn-link:hover,
.navbar-default .btn-link[disabled]:focus,
fieldset[disabled] .navbar-default .btn-link:focus {
  color: #ccc;
}
.navbar-inverse {
  background-color: #222;
  border-color: #080808;
}
.navbar-inverse .navbar-brand {
  color: #9d9d9d;
}
.navbar-inverse .navbar-brand:hover,
.navbar-inverse .navbar-brand:focus {
  color: #fff;
  background-color: transparent;
}
.navbar-inverse .navbar-text {
  color: #9d9d9d;
}
.navbar-inverse .navbar-nav > li > a {
  color: #9d9d9d;
}
.navbar-inverse .navbar-nav > li > a:hover,
.navbar-inverse .navbar-nav > li > a:focus {
  color: #fff;
  background-color: transparent;
}
.navbar-inverse .navbar-nav > .active > a,
.navbar-inverse .navbar-nav > .active > a:hover,
.navbar-inverse .navbar-nav > .active > a:focus {
  color: #fff;
  background-color: #080808;
}
.navbar-inverse .navbar-nav > .disabled > a,
.navbar-inverse .navbar-nav > .disabled > a:hover,
.navbar-inverse .navbar-nav > .disabled > a:focus {
  color: #444;
  background-color: transparent;
}
.navbar-inverse .navbar-toggle {
  border-color: #333;
}
.navbar-inverse .navbar-toggle:hover,
.navbar-inverse .navbar-toggle:focus {
  background-color: #333;
}
.navbar-inverse .navbar-toggle .icon-bar {
  background-color: #fff;
}
.navbar-inverse .navbar-collapse,
.navbar-inverse .navbar-form {
  border-color: #101010;
}
.navbar-inverse .navbar-nav > .open > a,
.navbar-inverse .navbar-nav > .open > a:hover,
.navbar-inverse .navbar-nav > .open > a:focus {
  background-color: #080808;
  color: #fff;
}
@media (max-width: 540px) {
  .navbar-inverse .navbar-nav .open .dropdown-menu > .dropdown-header {
    border-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu .divider {
    background-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a {
    color: #9d9d9d;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > li > a:focus {
    color: #fff;
    background-color: transparent;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .active > a:focus {
    color: #fff;
    background-color: #080808;
  }
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a:hover,
  .navbar-inverse .navbar-nav .open .dropdown-menu > .disabled > a:focus {
    color: #444;
    background-color: transparent;
  }
}
.navbar-inverse .navbar-link {
  color: #9d9d9d;
}
.navbar-inverse .navbar-link:hover {
  color: #fff;
}
.navbar-inverse .btn-link {
  color: #9d9d9d;
}
.navbar-inverse .btn-link:hover,
.navbar-inverse .btn-link:focus {
  color: #fff;
}
.navbar-inverse .btn-link[disabled]:hover,
fieldset[disabled] .navbar-inverse .btn-link:hover,
.navbar-inverse .btn-link[disabled]:focus,
fieldset[disabled] .navbar-inverse .btn-link:focus {
  color: #444;
}
.breadcrumb {
  padding: 8px 15px;
  margin-bottom: 18px;
  list-style: none;
  background-color: #f5f5f5;
  border-radius: 2px;
}
.breadcrumb > li {
  display: inline-block;
}
.breadcrumb > li + li:before {
  content: "/\00a0";
  padding: 0 5px;
  color: #5e5e5e;
}
.breadcrumb > .active {
  color: #777777;
}
.pagination {
  display: inline-block;
  padding-left: 0;
  margin: 18px 0;
  border-radius: 2px;
}
.pagination > li {
  display: inline;
}
.pagination > li > a,
.pagination > li > span {
  position: relative;
  float: left;
  padding: 6px 12px;
  line-height: 1.42857143;
  text-decoration: none;
  color: #337ab7;
  background-color: #fff;
  border: 1px solid #ddd;
  margin-left: -1px;
}
.pagination > li:first-child > a,
.pagination > li:first-child > span {
  margin-left: 0;
  border-bottom-left-radius: 2px;
  border-top-left-radius: 2px;
}
.pagination > li:last-child > a,
.pagination > li:last-child > span {
  border-bottom-right-radius: 2px;
  border-top-right-radius: 2px;
}
.pagination > li > a:hover,
.pagination > li > span:hover,
.pagination > li > a:focus,
.pagination > li > span:focus {
  z-index: 2;
  color: #23527c;
  background-color: #eeeeee;
  border-color: #ddd;
}
.pagination > .active > a,
.pagination > .active > span,
.pagination > .active > a:hover,
.pagination > .active > span:hover,
.pagination > .active > a:focus,
.pagination > .active > span:focus {
  z-index: 3;
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7;
  cursor: default;
}
.pagination > .disabled > span,
.pagination > .disabled > span:hover,
.pagination > .disabled > span:focus,
.pagination > .disabled > a,
.pagination > .disabled > a:hover,
.pagination > .disabled > a:focus {
  color: #777777;
  background-color: #fff;
  border-color: #ddd;
  cursor: not-allowed;
}
.pagination-lg > li > a,
.pagination-lg > li > span {
  padding: 10px 16px;
  font-size: 17px;
  line-height: 1.3333333;
}
.pagination-lg > li:first-child > a,
.pagination-lg > li:first-child > span {
  border-bottom-left-radius: 3px;
  border-top-left-radius: 3px;
}
.pagination-lg > li:last-child > a,
.pagination-lg > li:last-child > span {
  border-bottom-right-radius: 3px;
  border-top-right-radius: 3px;
}
.pagination-sm > li > a,
.pagination-sm > li > span {
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
}
.pagination-sm > li:first-child > a,
.pagination-sm > li:first-child > span {
  border-bottom-left-radius: 1px;
  border-top-left-radius: 1px;
}
.pagination-sm > li:last-child > a,
.pagination-sm > li:last-child > span {
  border-bottom-right-radius: 1px;
  border-top-right-radius: 1px;
}
.pager {
  padding-left: 0;
  margin: 18px 0;
  list-style: none;
  text-align: center;
}
.pager li {
  display: inline;
}
.pager li > a,
.pager li > span {
  display: inline-block;
  padding: 5px 14px;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 15px;
}
.pager li > a:hover,
.pager li > a:focus {
  text-decoration: none;
  background-color: #eeeeee;
}
.pager .next > a,
.pager .next > span {
  float: right;
}
.pager .previous > a,
.pager .previous > span {
  float: left;
}
.pager .disabled > a,
.pager .disabled > a:hover,
.pager .disabled > a:focus,
.pager .disabled > span {
  color: #777777;
  background-color: #fff;
  cursor: not-allowed;
}
.label {
  display: inline;
  padding: .2em .6em .3em;
  font-size: 75%;
  font-weight: bold;
  line-height: 1;
  color: #fff;
  text-align: center;
  white-space: nowrap;
  vertical-align: baseline;
  border-radius: .25em;
}
a.label:hover,
a.label:focus {
  color: #fff;
  text-decoration: none;
  cursor: pointer;
}
.label:empty {
  display: none;
}
.btn .label {
  position: relative;
  top: -1px;
}
.label-default {
  background-color: #777777;
}
.label-default[href]:hover,
.label-default[href]:focus {
  background-color: #5e5e5e;
}
.label-primary {
  background-color: #337ab7;
}
.label-primary[href]:hover,
.label-primary[href]:focus {
  background-color: #286090;
}
.label-success {
  background-color: #5cb85c;
}
.label-success[href]:hover,
.label-success[href]:focus {
  background-color: #449d44;
}
.label-info {
  background-color: #5bc0de;
}
.label-info[href]:hover,
.label-info[href]:focus {
  background-color: #31b0d5;
}
.label-warning {
  background-color: #f0ad4e;
}
.label-warning[href]:hover,
.label-warning[href]:focus {
  background-color: #ec971f;
}
.label-danger {
  background-color: #d9534f;
}
.label-danger[href]:hover,
.label-danger[href]:focus {
  background-color: #c9302c;
}
.badge {
  display: inline-block;
  min-width: 10px;
  padding: 3px 7px;
  font-size: 12px;
  font-weight: bold;
  color: #fff;
  line-height: 1;
  vertical-align: middle;
  white-space: nowrap;
  text-align: center;
  background-color: #777777;
  border-radius: 10px;
}
.badge:empty {
  display: none;
}
.btn .badge {
  position: relative;
  top: -1px;
}
.btn-xs .badge,
.btn-group-xs > .btn .badge {
  top: 0;
  padding: 1px 5px;
}
a.badge:hover,
a.badge:focus {
  color: #fff;
  text-decoration: none;
  cursor: pointer;
}
.list-group-item.active > .badge,
.nav-pills > .active > a > .badge {
  color: #337ab7;
  background-color: #fff;
}
.list-group-item > .badge {
  float: right;
}
.list-group-item > .badge + .badge {
  margin-right: 5px;
}
.nav-pills > li > a > .badge {
  margin-left: 3px;
}
.jumbotron {
  padding-top: 30px;
  padding-bottom: 30px;
  margin-bottom: 30px;
  color: inherit;
  background-color: #eeeeee;
}
.jumbotron h1,
.jumbotron .h1 {
  color: inherit;
}
.jumbotron p {
  margin-bottom: 15px;
  font-size: 20px;
  font-weight: 200;
}
.jumbotron > hr {
  border-top-color: #d5d5d5;
}
.container .jumbotron,
.container-fluid .jumbotron {
  border-radius: 3px;
  padding-left: 0px;
  padding-right: 0px;
}
.jumbotron .container {
  max-width: 100%;
}
@media screen and (min-width: 768px) {
  .jumbotron {
    padding-top: 48px;
    padding-bottom: 48px;
  }
  .container .jumbotron,
  .container-fluid .jumbotron {
    padding-left: 60px;
    padding-right: 60px;
  }
  .jumbotron h1,
  .jumbotron .h1 {
    font-size: 59px;
  }
}
.thumbnail {
  display: block;
  padding: 4px;
  margin-bottom: 18px;
  line-height: 1.42857143;
  background-color: #fff;
  border: 1px solid #ddd;
  border-radius: 2px;
  -webkit-transition: border 0.2s ease-in-out;
  -o-transition: border 0.2s ease-in-out;
  transition: border 0.2s ease-in-out;
}
.thumbnail > img,
.thumbnail a > img {
  margin-left: auto;
  margin-right: auto;
}
a.thumbnail:hover,
a.thumbnail:focus,
a.thumbnail.active {
  border-color: #337ab7;
}
.thumbnail .caption {
  padding: 9px;
  color: #000;
}
.alert {
  padding: 15px;
  margin-bottom: 18px;
  border: 1px solid transparent;
  border-radius: 2px;
}
.alert h4 {
  margin-top: 0;
  color: inherit;
}
.alert .alert-link {
  font-weight: bold;
}
.alert > p,
.alert > ul {
  margin-bottom: 0;
}
.alert > p + p {
  margin-top: 5px;
}
.alert-dismissable,
.alert-dismissible {
  padding-right: 35px;
}
.alert-dismissable .close,
.alert-dismissible .close {
  position: relative;
  top: -2px;
  right: -21px;
  color: inherit;
}
.alert-success {
  background-color: #dff0d8;
  border-color: #d6e9c6;
  color: #3c763d;
}
.alert-success hr {
  border-top-color: #c9e2b3;
}
.alert-success .alert-link {
  color: #2b542c;
}
.alert-info {
  background-color: #d9edf7;
  border-color: #bce8f1;
  color: #31708f;
}
.alert-info hr {
  border-top-color: #a6e1ec;
}
.alert-info .alert-link {
  color: #245269;
}
.alert-warning {
  background-color: #fcf8e3;
  border-color: #faebcc;
  color: #8a6d3b;
}
.alert-warning hr {
  border-top-color: #f7e1b5;
}
.alert-warning .alert-link {
  color: #66512c;
}
.alert-danger {
  background-color: #f2dede;
  border-color: #ebccd1;
  color: #a94442;
}
.alert-danger hr {
  border-top-color: #e4b9c0;
}
.alert-danger .alert-link {
  color: #843534;
}
@-webkit-keyframes progress-bar-stripes {
  from {
    background-position: 40px 0;
  }
  to {
    background-position: 0 0;
  }
}
@keyframes progress-bar-stripes {
  from {
    background-position: 40px 0;
  }
  to {
    background-position: 0 0;
  }
}
.progress {
  overflow: hidden;
  height: 18px;
  margin-bottom: 18px;
  background-color: #f5f5f5;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1);
  box-shadow: inset 0 1px 2px rgba(0, 0, 0, 0.1);
}
.progress-bar {
  float: left;
  width: 0%;
  height: 100%;
  font-size: 12px;
  line-height: 18px;
  color: #fff;
  text-align: center;
  background-color: #337ab7;
  -webkit-box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.15);
  box-shadow: inset 0 -1px 0 rgba(0, 0, 0, 0.15);
  -webkit-transition: width 0.6s ease;
  -o-transition: width 0.6s ease;
  transition: width 0.6s ease;
}
.progress-striped .progress-bar,
.progress-bar-striped {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-size: 40px 40px;
}
.progress.active .progress-bar,
.progress-bar.active {
  -webkit-animation: progress-bar-stripes 2s linear infinite;
  -o-animation: progress-bar-stripes 2s linear infinite;
  animation: progress-bar-stripes 2s linear infinite;
}
.progress-bar-success {
  background-color: #5cb85c;
}
.progress-striped .progress-bar-success {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-info {
  background-color: #5bc0de;
}
.progress-striped .progress-bar-info {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-warning {
  background-color: #f0ad4e;
}
.progress-striped .progress-bar-warning {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.progress-bar-danger {
  background-color: #d9534f;
}
.progress-striped .progress-bar-danger {
  background-image: -webkit-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: -o-linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
  background-image: linear-gradient(45deg, rgba(255, 255, 255, 0.15) 25%, transparent 25%, transparent 50%, rgba(255, 255, 255, 0.15) 50%, rgba(255, 255, 255, 0.15) 75%, transparent 75%, transparent);
}
.media {
  margin-top: 15px;
}
.media:first-child {
  margin-top: 0;
}
.media,
.media-body {
  zoom: 1;
  overflow: hidden;
}
.media-body {
  width: 10000px;
}
.media-object {
  display: block;
}
.media-object.img-thumbnail {
  max-width: none;
}
.media-right,
.media > .pull-right {
  padding-left: 10px;
}
.media-left,
.media > .pull-left {
  padding-right: 10px;
}
.media-left,
.media-right,
.media-body {
  display: table-cell;
  vertical-align: top;
}
.media-middle {
  vertical-align: middle;
}
.media-bottom {
  vertical-align: bottom;
}
.media-heading {
  margin-top: 0;
  margin-bottom: 5px;
}
.media-list {
  padding-left: 0;
  list-style: none;
}
.list-group {
  margin-bottom: 20px;
  padding-left: 0;
}
.list-group-item {
  position: relative;
  display: block;
  padding: 10px 15px;
  margin-bottom: -1px;
  background-color: #fff;
  border: 1px solid #ddd;
}
.list-group-item:first-child {
  border-top-right-radius: 2px;
  border-top-left-radius: 2px;
}
.list-group-item:last-child {
  margin-bottom: 0;
  border-bottom-right-radius: 2px;
  border-bottom-left-radius: 2px;
}
a.list-group-item,
button.list-group-item {
  color: #555;
}
a.list-group-item .list-group-item-heading,
button.list-group-item .list-group-item-heading {
  color: #333;
}
a.list-group-item:hover,
button.list-group-item:hover,
a.list-group-item:focus,
button.list-group-item:focus {
  text-decoration: none;
  color: #555;
  background-color: #f5f5f5;
}
button.list-group-item {
  width: 100%;
  text-align: left;
}
.list-group-item.disabled,
.list-group-item.disabled:hover,
.list-group-item.disabled:focus {
  background-color: #eeeeee;
  color: #777777;
  cursor: not-allowed;
}
.list-group-item.disabled .list-group-item-heading,
.list-group-item.disabled:hover .list-group-item-heading,
.list-group-item.disabled:focus .list-group-item-heading {
  color: inherit;
}
.list-group-item.disabled .list-group-item-text,
.list-group-item.disabled:hover .list-group-item-text,
.list-group-item.disabled:focus .list-group-item-text {
  color: #777777;
}
.list-group-item.active,
.list-group-item.active:hover,
.list-group-item.active:focus {
  z-index: 2;
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7;
}
.list-group-item.active .list-group-item-heading,
.list-group-item.active:hover .list-group-item-heading,
.list-group-item.active:focus .list-group-item-heading,
.list-group-item.active .list-group-item-heading > small,
.list-group-item.active:hover .list-group-item-heading > small,
.list-group-item.active:focus .list-group-item-heading > small,
.list-group-item.active .list-group-item-heading > .small,
.list-group-item.active:hover .list-group-item-heading > .small,
.list-group-item.active:focus .list-group-item-heading > .small {
  color: inherit;
}
.list-group-item.active .list-group-item-text,
.list-group-item.active:hover .list-group-item-text,
.list-group-item.active:focus .list-group-item-text {
  color: #c7ddef;
}
.list-group-item-success {
  color: #3c763d;
  background-color: #dff0d8;
}
a.list-group-item-success,
button.list-group-item-success {
  color: #3c763d;
}
a.list-group-item-success .list-group-item-heading,
button.list-group-item-success .list-group-item-heading {
  color: inherit;
}
a.list-group-item-success:hover,
button.list-group-item-success:hover,
a.list-group-item-success:focus,
button.list-group-item-success:focus {
  color: #3c763d;
  background-color: #d0e9c6;
}
a.list-group-item-success.active,
button.list-group-item-success.active,
a.list-group-item-success.active:hover,
button.list-group-item-success.active:hover,
a.list-group-item-success.active:focus,
button.list-group-item-success.active:focus {
  color: #fff;
  background-color: #3c763d;
  border-color: #3c763d;
}
.list-group-item-info {
  color: #31708f;
  background-color: #d9edf7;
}
a.list-group-item-info,
button.list-group-item-info {
  color: #31708f;
}
a.list-group-item-info .list-group-item-heading,
button.list-group-item-info .list-group-item-heading {
  color: inherit;
}
a.list-group-item-info:hover,
button.list-group-item-info:hover,
a.list-group-item-info:focus,
button.list-group-item-info:focus {
  color: #31708f;
  background-color: #c4e3f3;
}
a.list-group-item-info.active,
button.list-group-item-info.active,
a.list-group-item-info.active:hover,
button.list-group-item-info.active:hover,
a.list-group-item-info.active:focus,
button.list-group-item-info.active:focus {
  color: #fff;
  background-color: #31708f;
  border-color: #31708f;
}
.list-group-item-warning {
  color: #8a6d3b;
  background-color: #fcf8e3;
}
a.list-group-item-warning,
button.list-group-item-warning {
  color: #8a6d3b;
}
a.list-group-item-warning .list-group-item-heading,
button.list-group-item-warning .list-group-item-heading {
  color: inherit;
}
a.list-group-item-warning:hover,
button.list-group-item-warning:hover,
a.list-group-item-warning:focus,
button.list-group-item-warning:focus {
  color: #8a6d3b;
  background-color: #faf2cc;
}
a.list-group-item-warning.active,
button.list-group-item-warning.active,
a.list-group-item-warning.active:hover,
button.list-group-item-warning.active:hover,
a.list-group-item-warning.active:focus,
button.list-group-item-warning.active:focus {
  color: #fff;
  background-color: #8a6d3b;
  border-color: #8a6d3b;
}
.list-group-item-danger {
  color: #a94442;
  background-color: #f2dede;
}
a.list-group-item-danger,
button.list-group-item-danger {
  color: #a94442;
}
a.list-group-item-danger .list-group-item-heading,
button.list-group-item-danger .list-group-item-heading {
  color: inherit;
}
a.list-group-item-danger:hover,
button.list-group-item-danger:hover,
a.list-group-item-danger:focus,
button.list-group-item-danger:focus {
  color: #a94442;
  background-color: #ebcccc;
}
a.list-group-item-danger.active,
button.list-group-item-danger.active,
a.list-group-item-danger.active:hover,
button.list-group-item-danger.active:hover,
a.list-group-item-danger.active:focus,
button.list-group-item-danger.active:focus {
  color: #fff;
  background-color: #a94442;
  border-color: #a94442;
}
.list-group-item-heading {
  margin-top: 0;
  margin-bottom: 5px;
}
.list-group-item-text {
  margin-bottom: 0;
  line-height: 1.3;
}
.panel {
  margin-bottom: 18px;
  background-color: #fff;
  border: 1px solid transparent;
  border-radius: 2px;
  -webkit-box-shadow: 0 1px 1px rgba(0, 0, 0, 0.05);
  box-shadow: 0 1px 1px rgba(0, 0, 0, 0.05);
}
.panel-body {
  padding: 15px;
}
.panel-heading {
  padding: 10px 15px;
  border-bottom: 1px solid transparent;
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel-heading > .dropdown .dropdown-toggle {
  color: inherit;
}
.panel-title {
  margin-top: 0;
  margin-bottom: 0;
  font-size: 15px;
  color: inherit;
}
.panel-title > a,
.panel-title > small,
.panel-title > .small,
.panel-title > small > a,
.panel-title > .small > a {
  color: inherit;
}
.panel-footer {
  padding: 10px 15px;
  background-color: #f5f5f5;
  border-top: 1px solid #ddd;
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .list-group,
.panel > .panel-collapse > .list-group {
  margin-bottom: 0;
}
.panel > .list-group .list-group-item,
.panel > .panel-collapse > .list-group .list-group-item {
  border-width: 1px 0;
  border-radius: 0;
}
.panel > .list-group:first-child .list-group-item:first-child,
.panel > .panel-collapse > .list-group:first-child .list-group-item:first-child {
  border-top: 0;
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel > .list-group:last-child .list-group-item:last-child,
.panel > .panel-collapse > .list-group:last-child .list-group-item:last-child {
  border-bottom: 0;
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .panel-heading + .panel-collapse > .list-group .list-group-item:first-child {
  border-top-right-radius: 0;
  border-top-left-radius: 0;
}
.panel-heading + .list-group .list-group-item:first-child {
  border-top-width: 0;
}
.list-group + .panel-footer {
  border-top-width: 0;
}
.panel > .table,
.panel > .table-responsive > .table,
.panel > .panel-collapse > .table {
  margin-bottom: 0;
}
.panel > .table caption,
.panel > .table-responsive > .table caption,
.panel > .panel-collapse > .table caption {
  padding-left: 15px;
  padding-right: 15px;
}
.panel > .table:first-child,
.panel > .table-responsive:first-child > .table:first-child {
  border-top-right-radius: 1px;
  border-top-left-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child {
  border-top-left-radius: 1px;
  border-top-right-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child td:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child td:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child td:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child td:first-child,
.panel > .table:first-child > thead:first-child > tr:first-child th:first-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child th:first-child,
.panel > .table:first-child > tbody:first-child > tr:first-child th:first-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child th:first-child {
  border-top-left-radius: 1px;
}
.panel > .table:first-child > thead:first-child > tr:first-child td:last-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child td:last-child,
.panel > .table:first-child > tbody:first-child > tr:first-child td:last-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child td:last-child,
.panel > .table:first-child > thead:first-child > tr:first-child th:last-child,
.panel > .table-responsive:first-child > .table:first-child > thead:first-child > tr:first-child th:last-child,
.panel > .table:first-child > tbody:first-child > tr:first-child th:last-child,
.panel > .table-responsive:first-child > .table:first-child > tbody:first-child > tr:first-child th:last-child {
  border-top-right-radius: 1px;
}
.panel > .table:last-child,
.panel > .table-responsive:last-child > .table:last-child {
  border-bottom-right-radius: 1px;
  border-bottom-left-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child {
  border-bottom-left-radius: 1px;
  border-bottom-right-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child td:first-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child td:first-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child td:first-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child td:first-child,
.panel > .table:last-child > tbody:last-child > tr:last-child th:first-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child th:first-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child th:first-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child th:first-child {
  border-bottom-left-radius: 1px;
}
.panel > .table:last-child > tbody:last-child > tr:last-child td:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child td:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child td:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child td:last-child,
.panel > .table:last-child > tbody:last-child > tr:last-child th:last-child,
.panel > .table-responsive:last-child > .table:last-child > tbody:last-child > tr:last-child th:last-child,
.panel > .table:last-child > tfoot:last-child > tr:last-child th:last-child,
.panel > .table-responsive:last-child > .table:last-child > tfoot:last-child > tr:last-child th:last-child {
  border-bottom-right-radius: 1px;
}
.panel > .panel-body + .table,
.panel > .panel-body + .table-responsive,
.panel > .table + .panel-body,
.panel > .table-responsive + .panel-body {
  border-top: 1px solid #ddd;
}
.panel > .table > tbody:first-child > tr:first-child th,
.panel > .table > tbody:first-child > tr:first-child td {
  border-top: 0;
}
.panel > .table-bordered,
.panel > .table-responsive > .table-bordered {
  border: 0;
}
.panel > .table-bordered > thead > tr > th:first-child,
.panel > .table-responsive > .table-bordered > thead > tr > th:first-child,
.panel > .table-bordered > tbody > tr > th:first-child,
.panel > .table-responsive > .table-bordered > tbody > tr > th:first-child,
.panel > .table-bordered > tfoot > tr > th:first-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > th:first-child,
.panel > .table-bordered > thead > tr > td:first-child,
.panel > .table-responsive > .table-bordered > thead > tr > td:first-child,
.panel > .table-bordered > tbody > tr > td:first-child,
.panel > .table-responsive > .table-bordered > tbody > tr > td:first-child,
.panel > .table-bordered > tfoot > tr > td:first-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > td:first-child {
  border-left: 0;
}
.panel > .table-bordered > thead > tr > th:last-child,
.panel > .table-responsive > .table-bordered > thead > tr > th:last-child,
.panel > .table-bordered > tbody > tr > th:last-child,
.panel > .table-responsive > .table-bordered > tbody > tr > th:last-child,
.panel > .table-bordered > tfoot > tr > th:last-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > th:last-child,
.panel > .table-bordered > thead > tr > td:last-child,
.panel > .table-responsive > .table-bordered > thead > tr > td:last-child,
.panel > .table-bordered > tbody > tr > td:last-child,
.panel > .table-responsive > .table-bordered > tbody > tr > td:last-child,
.panel > .table-bordered > tfoot > tr > td:last-child,
.panel > .table-responsive > .table-bordered > tfoot > tr > td:last-child {
  border-right: 0;
}
.panel > .table-bordered > thead > tr:first-child > td,
.panel > .table-responsive > .table-bordered > thead > tr:first-child > td,
.panel > .table-bordered > tbody > tr:first-child > td,
.panel > .table-responsive > .table-bordered > tbody > tr:first-child > td,
.panel > .table-bordered > thead > tr:first-child > th,
.panel > .table-responsive > .table-bordered > thead > tr:first-child > th,
.panel > .table-bordered > tbody > tr:first-child > th,
.panel > .table-responsive > .table-bordered > tbody > tr:first-child > th {
  border-bottom: 0;
}
.panel > .table-bordered > tbody > tr:last-child > td,
.panel > .table-responsive > .table-bordered > tbody > tr:last-child > td,
.panel > .table-bordered > tfoot > tr:last-child > td,
.panel > .table-responsive > .table-bordered > tfoot > tr:last-child > td,
.panel > .table-bordered > tbody > tr:last-child > th,
.panel > .table-responsive > .table-bordered > tbody > tr:last-child > th,
.panel > .table-bordered > tfoot > tr:last-child > th,
.panel > .table-responsive > .table-bordered > tfoot > tr:last-child > th {
  border-bottom: 0;
}
.panel > .table-responsive {
  border: 0;
  margin-bottom: 0;
}
.panel-group {
  margin-bottom: 18px;
}
.panel-group .panel {
  margin-bottom: 0;
  border-radius: 2px;
}
.panel-group .panel + .panel {
  margin-top: 5px;
}
.panel-group .panel-heading {
  border-bottom: 0;
}
.panel-group .panel-heading + .panel-collapse > .panel-body,
.panel-group .panel-heading + .panel-collapse > .list-group {
  border-top: 1px solid #ddd;
}
.panel-group .panel-footer {
  border-top: 0;
}
.panel-group .panel-footer + .panel-collapse .panel-body {
  border-bottom: 1px solid #ddd;
}
.panel-default {
  border-color: #ddd;
}
.panel-default > .panel-heading {
  color: #333333;
  background-color: #f5f5f5;
  border-color: #ddd;
}
.panel-default > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #ddd;
}
.panel-default > .panel-heading .badge {
  color: #f5f5f5;
  background-color: #333333;
}
.panel-default > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #ddd;
}
.panel-primary {
  border-color: #337ab7;
}
.panel-primary > .panel-heading {
  color: #fff;
  background-color: #337ab7;
  border-color: #337ab7;
}
.panel-primary > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #337ab7;
}
.panel-primary > .panel-heading .badge {
  color: #337ab7;
  background-color: #fff;
}
.panel-primary > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #337ab7;
}
.panel-success {
  border-color: #d6e9c6;
}
.panel-success > .panel-heading {
  color: #3c763d;
  background-color: #dff0d8;
  border-color: #d6e9c6;
}
.panel-success > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #d6e9c6;
}
.panel-success > .panel-heading .badge {
  color: #dff0d8;
  background-color: #3c763d;
}
.panel-success > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #d6e9c6;
}
.panel-info {
  border-color: #bce8f1;
}
.panel-info > .panel-heading {
  color: #31708f;
  background-color: #d9edf7;
  border-color: #bce8f1;
}
.panel-info > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #bce8f1;
}
.panel-info > .panel-heading .badge {
  color: #d9edf7;
  background-color: #31708f;
}
.panel-info > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #bce8f1;
}
.panel-warning {
  border-color: #faebcc;
}
.panel-warning > .panel-heading {
  color: #8a6d3b;
  background-color: #fcf8e3;
  border-color: #faebcc;
}
.panel-warning > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #faebcc;
}
.panel-warning > .panel-heading .badge {
  color: #fcf8e3;
  background-color: #8a6d3b;
}
.panel-warning > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #faebcc;
}
.panel-danger {
  border-color: #ebccd1;
}
.panel-danger > .panel-heading {
  color: #a94442;
  background-color: #f2dede;
  border-color: #ebccd1;
}
.panel-danger > .panel-heading + .panel-collapse > .panel-body {
  border-top-color: #ebccd1;
}
.panel-danger > .panel-heading .badge {
  color: #f2dede;
  background-color: #a94442;
}
.panel-danger > .panel-footer + .panel-collapse > .panel-body {
  border-bottom-color: #ebccd1;
}
.embed-responsive {
  position: relative;
  display: block;
  height: 0;
  padding: 0;
  overflow: hidden;
}
.embed-responsive .embed-responsive-item,
.embed-responsive iframe,
.embed-responsive embed,
.embed-responsive object,
.embed-responsive video {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  height: 100%;
  width: 100%;
  border: 0;
}
.embed-responsive-16by9 {
  padding-bottom: 56.25%;
}
.embed-responsive-4by3 {
  padding-bottom: 75%;
}
.well {
  min-height: 20px;
  padding: 19px;
  margin-bottom: 20px;
  background-color: #f5f5f5;
  border: 1px solid #e3e3e3;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.05);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.05);
}
.well blockquote {
  border-color: #ddd;
  border-color: rgba(0, 0, 0, 0.15);
}
.well-lg {
  padding: 24px;
  border-radius: 3px;
}
.well-sm {
  padding: 9px;
  border-radius: 1px;
}
.close {
  float: right;
  font-size: 19.5px;
  font-weight: bold;
  line-height: 1;
  color: #000;
  text-shadow: 0 1px 0 #fff;
  opacity: 0.2;
  filter: alpha(opacity=20);
}
.close:hover,
.close:focus {
  color: #000;
  text-decoration: none;
  cursor: pointer;
  opacity: 0.5;
  filter: alpha(opacity=50);
}
button.close {
  padding: 0;
  cursor: pointer;
  background: transparent;
  border: 0;
  -webkit-appearance: none;
}
.modal-open {
  overflow: hidden;
}
.modal {
  display: none;
  overflow: hidden;
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1050;
  -webkit-overflow-scrolling: touch;
  outline: 0;
}
.modal.fade .modal-dialog {
  -webkit-transform: translate(0, -25%);
  -ms-transform: translate(0, -25%);
  -o-transform: translate(0, -25%);
  transform: translate(0, -25%);
  -webkit-transition: -webkit-transform 0.3s ease-out;
  -moz-transition: -moz-transform 0.3s ease-out;
  -o-transition: -o-transform 0.3s ease-out;
  transition: transform 0.3s ease-out;
}
.modal.in .modal-dialog {
  -webkit-transform: translate(0, 0);
  -ms-transform: translate(0, 0);
  -o-transform: translate(0, 0);
  transform: translate(0, 0);
}
.modal-open .modal {
  overflow-x: hidden;
  overflow-y: auto;
}
.modal-dialog {
  position: relative;
  width: auto;
  margin: 10px;
}
.modal-content {
  position: relative;
  background-color: #fff;
  border: 1px solid #999;
  border: 1px solid rgba(0, 0, 0, 0.2);
  border-radius: 3px;
  -webkit-box-shadow: 0 3px 9px rgba(0, 0, 0, 0.5);
  box-shadow: 0 3px 9px rgba(0, 0, 0, 0.5);
  background-clip: padding-box;
  outline: 0;
}
.modal-backdrop {
  position: fixed;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
  z-index: 1040;
  background-color: #000;
}
.modal-backdrop.fade {
  opacity: 0;
  filter: alpha(opacity=0);
}
.modal-backdrop.in {
  opacity: 0.5;
  filter: alpha(opacity=50);
}
.modal-header {
  padding: 15px;
  border-bottom: 1px solid #e5e5e5;
}
.modal-header .close {
  margin-top: -2px;
}
.modal-title {
  margin: 0;
  line-height: 1.42857143;
}
.modal-body {
  position: relative;
  padding: 15px;
}
.modal-footer {
  padding: 15px;
  text-align: right;
  border-top: 1px solid #e5e5e5;
}
.modal-footer .btn + .btn {
  margin-left: 5px;
  margin-bottom: 0;
}
.modal-footer .btn-group .btn + .btn {
  margin-left: -1px;
}
.modal-footer .btn-block + .btn-block {
  margin-left: 0;
}
.modal-scrollbar-measure {
  position: absolute;
  top: -9999px;
  width: 50px;
  height: 50px;
  overflow: scroll;
}
@media (min-width: 768px) {
  .modal-dialog {
    width: 600px;
    margin: 30px auto;
  }
  .modal-content {
    -webkit-box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
  }
  .modal-sm {
    width: 300px;
  }
}
@media (min-width: 992px) {
  .modal-lg {
    width: 900px;
  }
}
.tooltip {
  position: absolute;
  z-index: 1070;
  display: block;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-style: normal;
  font-weight: normal;
  letter-spacing: normal;
  line-break: auto;
  line-height: 1.42857143;
  text-align: left;
  text-align: start;
  text-decoration: none;
  text-shadow: none;
  text-transform: none;
  white-space: normal;
  word-break: normal;
  word-spacing: normal;
  word-wrap: normal;
  font-size: 12px;
  opacity: 0;
  filter: alpha(opacity=0);
}
.tooltip.in {
  opacity: 0.9;
  filter: alpha(opacity=90);
}
.tooltip.top {
  margin-top: -3px;
  padding: 5px 0;
}
.tooltip.right {
  margin-left: 3px;
  padding: 0 5px;
}
.tooltip.bottom {
  margin-top: 3px;
  padding: 5px 0;
}
.tooltip.left {
  margin-left: -3px;
  padding: 0 5px;
}
.tooltip-inner {
  max-width: 200px;
  padding: 3px 8px;
  color: #fff;
  text-align: center;
  background-color: #000;
  border-radius: 2px;
}
.tooltip-arrow {
  position: absolute;
  width: 0;
  height: 0;
  border-color: transparent;
  border-style: solid;
}
.tooltip.top .tooltip-arrow {
  bottom: 0;
  left: 50%;
  margin-left: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}
.tooltip.top-left .tooltip-arrow {
  bottom: 0;
  right: 5px;
  margin-bottom: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}
.tooltip.top-right .tooltip-arrow {
  bottom: 0;
  left: 5px;
  margin-bottom: -5px;
  border-width: 5px 5px 0;
  border-top-color: #000;
}
.tooltip.right .tooltip-arrow {
  top: 50%;
  left: 0;
  margin-top: -5px;
  border-width: 5px 5px 5px 0;
  border-right-color: #000;
}
.tooltip.left .tooltip-arrow {
  top: 50%;
  right: 0;
  margin-top: -5px;
  border-width: 5px 0 5px 5px;
  border-left-color: #000;
}
.tooltip.bottom .tooltip-arrow {
  top: 0;
  left: 50%;
  margin-left: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}
.tooltip.bottom-left .tooltip-arrow {
  top: 0;
  right: 5px;
  margin-top: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}
.tooltip.bottom-right .tooltip-arrow {
  top: 0;
  left: 5px;
  margin-top: -5px;
  border-width: 0 5px 5px;
  border-bottom-color: #000;
}
.popover {
  position: absolute;
  top: 0;
  left: 0;
  z-index: 1060;
  display: none;
  max-width: 276px;
  padding: 1px;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
  font-style: normal;
  font-weight: normal;
  letter-spacing: normal;
  line-break: auto;
  line-height: 1.42857143;
  text-align: left;
  text-align: start;
  text-decoration: none;
  text-shadow: none;
  text-transform: none;
  white-space: normal;
  word-break: normal;
  word-spacing: normal;
  word-wrap: normal;
  font-size: 13px;
  background-color: #fff;
  background-clip: padding-box;
  border: 1px solid #ccc;
  border: 1px solid rgba(0, 0, 0, 0.2);
  border-radius: 3px;
  -webkit-box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
  box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
}
.popover.top {
  margin-top: -10px;
}
.popover.right {
  margin-left: 10px;
}
.popover.bottom {
  margin-top: 10px;
}
.popover.left {
  margin-left: -10px;
}
.popover-title {
  margin: 0;
  padding: 8px 14px;
  font-size: 13px;
  background-color: #f7f7f7;
  border-bottom: 1px solid #ebebeb;
  border-radius: 2px 2px 0 0;
}
.popover-content {
  padding: 9px 14px;
}
.popover > .arrow,
.popover > .arrow:after {
  position: absolute;
  display: block;
  width: 0;
  height: 0;
  border-color: transparent;
  border-style: solid;
}
.popover > .arrow {
  border-width: 11px;
}
.popover > .arrow:after {
  border-width: 10px;
  content: "";
}
.popover.top > .arrow {
  left: 50%;
  margin-left: -11px;
  border-bottom-width: 0;
  border-top-color: #999999;
  border-top-color: rgba(0, 0, 0, 0.25);
  bottom: -11px;
}
.popover.top > .arrow:after {
  content: " ";
  bottom: 1px;
  margin-left: -10px;
  border-bottom-width: 0;
  border-top-color: #fff;
}
.popover.right > .arrow {
  top: 50%;
  left: -11px;
  margin-top: -11px;
  border-left-width: 0;
  border-right-color: #999999;
  border-right-color: rgba(0, 0, 0, 0.25);
}
.popover.right > .arrow:after {
  content: " ";
  left: 1px;
  bottom: -10px;
  border-left-width: 0;
  border-right-color: #fff;
}
.popover.bottom > .arrow {
  left: 50%;
  margin-left: -11px;
  border-top-width: 0;
  border-bottom-color: #999999;
  border-bottom-color: rgba(0, 0, 0, 0.25);
  top: -11px;
}
.popover.bottom > .arrow:after {
  content: " ";
  top: 1px;
  margin-left: -10px;
  border-top-width: 0;
  border-bottom-color: #fff;
}
.popover.left > .arrow {
  top: 50%;
  right: -11px;
  margin-top: -11px;
  border-right-width: 0;
  border-left-color: #999999;
  border-left-color: rgba(0, 0, 0, 0.25);
}
.popover.left > .arrow:after {
  content: " ";
  right: 1px;
  border-right-width: 0;
  border-left-color: #fff;
  bottom: -10px;
}
.carousel {
  position: relative;
}
.carousel-inner {
  position: relative;
  overflow: hidden;
  width: 100%;
}
.carousel-inner > .item {
  display: none;
  position: relative;
  -webkit-transition: 0.6s ease-in-out left;
  -o-transition: 0.6s ease-in-out left;
  transition: 0.6s ease-in-out left;
}
.carousel-inner > .item > img,
.carousel-inner > .item > a > img {
  line-height: 1;
}
@media all and (transform-3d), (-webkit-transform-3d) {
  .carousel-inner > .item {
    -webkit-transition: -webkit-transform 0.6s ease-in-out;
    -moz-transition: -moz-transform 0.6s ease-in-out;
    -o-transition: -o-transform 0.6s ease-in-out;
    transition: transform 0.6s ease-in-out;
    -webkit-backface-visibility: hidden;
    -moz-backface-visibility: hidden;
    backface-visibility: hidden;
    -webkit-perspective: 1000px;
    -moz-perspective: 1000px;
    perspective: 1000px;
  }
  .carousel-inner > .item.next,
  .carousel-inner > .item.active.right {
    -webkit-transform: translate3d(100%, 0, 0);
    transform: translate3d(100%, 0, 0);
    left: 0;
  }
  .carousel-inner > .item.prev,
  .carousel-inner > .item.active.left {
    -webkit-transform: translate3d(-100%, 0, 0);
    transform: translate3d(-100%, 0, 0);
    left: 0;
  }
  .carousel-inner > .item.next.left,
  .carousel-inner > .item.prev.right,
  .carousel-inner > .item.active {
    -webkit-transform: translate3d(0, 0, 0);
    transform: translate3d(0, 0, 0);
    left: 0;
  }
}
.carousel-inner > .active,
.carousel-inner > .next,
.carousel-inner > .prev {
  display: block;
}
.carousel-inner > .active {
  left: 0;
}
.carousel-inner > .next,
.carousel-inner > .prev {
  position: absolute;
  top: 0;
  width: 100%;
}
.carousel-inner > .next {
  left: 100%;
}
.carousel-inner > .prev {
  left: -100%;
}
.carousel-inner > .next.left,
.carousel-inner > .prev.right {
  left: 0;
}
.carousel-inner > .active.left {
  left: -100%;
}
.carousel-inner > .active.right {
  left: 100%;
}
.carousel-control {
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  width: 15%;
  opacity: 0.5;
  filter: alpha(opacity=50);
  font-size: 20px;
  color: #fff;
  text-align: center;
  text-shadow: 0 1px 2px rgba(0, 0, 0, 0.6);
  background-color: rgba(0, 0, 0, 0);
}
.carousel-control.left {
  background-image: -webkit-linear-gradient(left, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-image: -o-linear-gradient(left, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-image: linear-gradient(to right, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.0001) 100%);
  background-repeat: repeat-x;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#80000000', endColorstr='#00000000', GradientType=1);
}
.carousel-control.right {
  left: auto;
  right: 0;
  background-image: -webkit-linear-gradient(left, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-image: -o-linear-gradient(left, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-image: linear-gradient(to right, rgba(0, 0, 0, 0.0001) 0%, rgba(0, 0, 0, 0.5) 100%);
  background-repeat: repeat-x;
  filter: progid:DXImageTransform.Microsoft.gradient(startColorstr='#00000000', endColorstr='#80000000', GradientType=1);
}
.carousel-control:hover,
.carousel-control:focus {
  outline: 0;
  color: #fff;
  text-decoration: none;
  opacity: 0.9;
  filter: alpha(opacity=90);
}
.carousel-control .icon-prev,
.carousel-control .icon-next,
.carousel-control .glyphicon-chevron-left,
.carousel-control .glyphicon-chevron-right {
  position: absolute;
  top: 50%;
  margin-top: -10px;
  z-index: 5;
  display: inline-block;
}
.carousel-control .icon-prev,
.carousel-control .glyphicon-chevron-left {
  left: 50%;
  margin-left: -10px;
}
.carousel-control .icon-next,
.carousel-control .glyphicon-chevron-right {
  right: 50%;
  margin-right: -10px;
}
.carousel-control .icon-prev,
.carousel-control .icon-next {
  width: 20px;
  height: 20px;
  line-height: 1;
  font-family: serif;
}
.carousel-control .icon-prev:before {
  content: '\2039';
}
.carousel-control .icon-next:before {
  content: '\203a';
}
.carousel-indicators {
  position: absolute;
  bottom: 10px;
  left: 50%;
  z-index: 15;
  width: 60%;
  margin-left: -30%;
  padding-left: 0;
  list-style: none;
  text-align: center;
}
.carousel-indicators li {
  display: inline-block;
  width: 10px;
  height: 10px;
  margin: 1px;
  text-indent: -999px;
  border: 1px solid #fff;
  border-radius: 10px;
  cursor: pointer;
  background-color: #000 \9;
  background-color: rgba(0, 0, 0, 0);
}
.carousel-indicators .active {
  margin: 0;
  width: 12px;
  height: 12px;
  background-color: #fff;
}
.carousel-caption {
  position: absolute;
  left: 15%;
  right: 15%;
  bottom: 20px;
  z-index: 10;
  padding-top: 20px;
  padding-bottom: 20px;
  color: #fff;
  text-align: center;
  text-shadow: 0 1px 2px rgba(0, 0, 0, 0.6);
}
.carousel-caption .btn {
  text-shadow: none;
}
@media screen and (min-width: 768px) {
  .carousel-control .glyphicon-chevron-left,
  .carousel-control .glyphicon-chevron-right,
  .carousel-control .icon-prev,
  .carousel-control .icon-next {
    width: 30px;
    height: 30px;
    margin-top: -10px;
    font-size: 30px;
  }
  .carousel-control .glyphicon-chevron-left,
  .carousel-control .icon-prev {
    margin-left: -10px;
  }
  .carousel-control .glyphicon-chevron-right,
  .carousel-control .icon-next {
    margin-right: -10px;
  }
  .carousel-caption {
    left: 20%;
    right: 20%;
    padding-bottom: 30px;
  }
  .carousel-indicators {
    bottom: 20px;
  }
}
.clearfix:before,
.clearfix:after,
.dl-horizontal dd:before,
.dl-horizontal dd:after,
.container:before,
.container:after,
.container-fluid:before,
.container-fluid:after,
.row:before,
.row:after,
.form-horizontal .form-group:before,
.form-horizontal .form-group:after,
.btn-toolbar:before,
.btn-toolbar:after,
.btn-group-vertical > .btn-group:before,
.btn-group-vertical > .btn-group:after,
.nav:before,
.nav:after,
.navbar:before,
.navbar:after,
.navbar-header:before,
.navbar-header:after,
.navbar-collapse:before,
.navbar-collapse:after,
.pager:before,
.pager:after,
.panel-body:before,
.panel-body:after,
.modal-header:before,
.modal-header:after,
.modal-footer:before,
.modal-footer:after,
.item_buttons:before,
.item_buttons:after {
  content: " ";
  display: table;
}
.clearfix:after,
.dl-horizontal dd:after,
.container:after,
.container-fluid:after,
.row:after,
.form-horizontal .form-group:after,
.btn-toolbar:after,
.btn-group-vertical > .btn-group:after,
.nav:after,
.navbar:after,
.navbar-header:after,
.navbar-collapse:after,
.pager:after,
.panel-body:after,
.modal-header:after,
.modal-footer:after,
.item_buttons:after {
  clear: both;
}
.center-block {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
.pull-right {
  float: right !important;
}
.pull-left {
  float: left !important;
}
.hide {
  display: none !important;
}
.show {
  display: block !important;
}
.invisible {
  visibility: hidden;
}
.text-hide {
  font: 0/0 a;
  color: transparent;
  text-shadow: none;
  background-color: transparent;
  border: 0;
}
.hidden {
  display: none !important;
}
.affix {
  position: fixed;
}
@-ms-viewport {
  width: device-width;
}
.visible-xs,
.visible-sm,
.visible-md,
.visible-lg {
  display: none !important;
}
.visible-xs-block,
.visible-xs-inline,
.visible-xs-inline-block,
.visible-sm-block,
.visible-sm-inline,
.visible-sm-inline-block,
.visible-md-block,
.visible-md-inline,
.visible-md-inline-block,
.visible-lg-block,
.visible-lg-inline,
.visible-lg-inline-block {
  display: none !important;
}
@media (max-width: 767px) {
  .visible-xs {
    display: block !important;
  }
  table.visible-xs {
    display: table !important;
  }
  tr.visible-xs {
    display: table-row !important;
  }
  th.visible-xs,
  td.visible-xs {
    display: table-cell !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-block {
    display: block !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-inline {
    display: inline !important;
  }
}
@media (max-width: 767px) {
  .visible-xs-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm {
    display: block !important;
  }
  table.visible-sm {
    display: table !important;
  }
  tr.visible-sm {
    display: table-row !important;
  }
  th.visible-sm,
  td.visible-sm {
    display: table-cell !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-block {
    display: block !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-inline {
    display: inline !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .visible-sm-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md {
    display: block !important;
  }
  table.visible-md {
    display: table !important;
  }
  tr.visible-md {
    display: table-row !important;
  }
  th.visible-md,
  td.visible-md {
    display: table-cell !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-block {
    display: block !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-inline {
    display: inline !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .visible-md-inline-block {
    display: inline-block !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg {
    display: block !important;
  }
  table.visible-lg {
    display: table !important;
  }
  tr.visible-lg {
    display: table-row !important;
  }
  th.visible-lg,
  td.visible-lg {
    display: table-cell !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-block {
    display: block !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-inline {
    display: inline !important;
  }
}
@media (min-width: 1200px) {
  .visible-lg-inline-block {
    display: inline-block !important;
  }
}
@media (max-width: 767px) {
  .hidden-xs {
    display: none !important;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  .hidden-sm {
    display: none !important;
  }
}
@media (min-width: 992px) and (max-width: 1199px) {
  .hidden-md {
    display: none !important;
  }
}
@media (min-width: 1200px) {
  .hidden-lg {
    display: none !important;
  }
}
.visible-print {
  display: none !important;
}
@media print {
  .visible-print {
    display: block !important;
  }
  table.visible-print {
    display: table !important;
  }
  tr.visible-print {
    display: table-row !important;
  }
  th.visible-print,
  td.visible-print {
    display: table-cell !important;
  }
}
.visible-print-block {
  display: none !important;
}
@media print {
  .visible-print-block {
    display: block !important;
  }
}
.visible-print-inline {
  display: none !important;
}
@media print {
  .visible-print-inline {
    display: inline !important;
  }
}
.visible-print-inline-block {
  display: none !important;
}
@media print {
  .visible-print-inline-block {
    display: inline-block !important;
  }
}
@media print {
  .hidden-print {
    display: none !important;
  }
}
/*!
*
* Font Awesome
*
*/
/*!
 *  Font Awesome 4.7.0 by @davegandy - http://fontawesome.io - @fontawesome
 *  License - http://fontawesome.io/license (Font: SIL OFL 1.1, CSS: MIT License)
 */
/* FONT PATH
 * -------------------------- */
@font-face {
  font-family: 'FontAwesome';
  src: url('../components/font-awesome/fonts/fontawesome-webfont.eot?v=4.7.0');
  src: url('../components/font-awesome/fonts/fontawesome-webfont.eot?#iefix&v=4.7.0') format('embedded-opentype'), url('../components/font-awesome/fonts/fontawesome-webfont.woff2?v=4.7.0') format('woff2'), url('../components/font-awesome/fonts/fontawesome-webfont.woff?v=4.7.0') format('woff'), url('../components/font-awesome/fonts/fontawesome-webfont.ttf?v=4.7.0') format('truetype'), url('../components/font-awesome/fonts/fontawesome-webfont.svg?v=4.7.0#fontawesomeregular') format('svg');
  font-weight: normal;
  font-style: normal;
}
.fa {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
/* makes the font 33% larger relative to the icon container */
.fa-lg {
  font-size: 1.33333333em;
  line-height: 0.75em;
  vertical-align: -15%;
}
.fa-2x {
  font-size: 2em;
}
.fa-3x {
  font-size: 3em;
}
.fa-4x {
  font-size: 4em;
}
.fa-5x {
  font-size: 5em;
}
.fa-fw {
  width: 1.28571429em;
  text-align: center;
}
.fa-ul {
  padding-left: 0;
  margin-left: 2.14285714em;
  list-style-type: none;
}
.fa-ul > li {
  position: relative;
}
.fa-li {
  position: absolute;
  left: -2.14285714em;
  width: 2.14285714em;
  top: 0.14285714em;
  text-align: center;
}
.fa-li.fa-lg {
  left: -1.85714286em;
}
.fa-border {
  padding: .2em .25em .15em;
  border: solid 0.08em #eee;
  border-radius: .1em;
}
.fa-pull-left {
  float: left;
}
.fa-pull-right {
  float: right;
}
.fa.fa-pull-left {
  margin-right: .3em;
}
.fa.fa-pull-right {
  margin-left: .3em;
}
/* Deprecated as of 4.4.0 */
.pull-right {
  float: right;
}
.pull-left {
  float: left;
}
.fa.pull-left {
  margin-right: .3em;
}
.fa.pull-right {
  margin-left: .3em;
}
.fa-spin {
  -webkit-animation: fa-spin 2s infinite linear;
  animation: fa-spin 2s infinite linear;
}
.fa-pulse {
  -webkit-animation: fa-spin 1s infinite steps(8);
  animation: fa-spin 1s infinite steps(8);
}
@-webkit-keyframes fa-spin {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(359deg);
    transform: rotate(359deg);
  }
}
@keyframes fa-spin {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(359deg);
    transform: rotate(359deg);
  }
}
.fa-rotate-90 {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=1)";
  -webkit-transform: rotate(90deg);
  -ms-transform: rotate(90deg);
  transform: rotate(90deg);
}
.fa-rotate-180 {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=2)";
  -webkit-transform: rotate(180deg);
  -ms-transform: rotate(180deg);
  transform: rotate(180deg);
}
.fa-rotate-270 {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=3)";
  -webkit-transform: rotate(270deg);
  -ms-transform: rotate(270deg);
  transform: rotate(270deg);
}
.fa-flip-horizontal {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=0, mirror=1)";
  -webkit-transform: scale(-1, 1);
  -ms-transform: scale(-1, 1);
  transform: scale(-1, 1);
}
.fa-flip-vertical {
  -ms-filter: "progid:DXImageTransform.Microsoft.BasicImage(rotation=2, mirror=1)";
  -webkit-transform: scale(1, -1);
  -ms-transform: scale(1, -1);
  transform: scale(1, -1);
}
:root .fa-rotate-90,
:root .fa-rotate-180,
:root .fa-rotate-270,
:root .fa-flip-horizontal,
:root .fa-flip-vertical {
  filter: none;
}
.fa-stack {
  position: relative;
  display: inline-block;
  width: 2em;
  height: 2em;
  line-height: 2em;
  vertical-align: middle;
}
.fa-stack-1x,
.fa-stack-2x {
  position: absolute;
  left: 0;
  width: 100%;
  text-align: center;
}
.fa-stack-1x {
  line-height: inherit;
}
.fa-stack-2x {
  font-size: 2em;
}
.fa-inverse {
  color: #fff;
}
/* Font Awesome uses the Unicode Private Use Area (PUA) to ensure screen
   readers do not read off random characters that represent icons */
.fa-glass:before {
  content: "\f000";
}
.fa-music:before {
  content: "\f001";
}
.fa-search:before {
  content: "\f002";
}
.fa-envelope-o:before {
  content: "\f003";
}
.fa-heart:before {
  content: "\f004";
}
.fa-star:before {
  content: "\f005";
}
.fa-star-o:before {
  content: "\f006";
}
.fa-user:before {
  content: "\f007";
}
.fa-film:before {
  content: "\f008";
}
.fa-th-large:before {
  content: "\f009";
}
.fa-th:before {
  content: "\f00a";
}
.fa-th-list:before {
  content: "\f00b";
}
.fa-check:before {
  content: "\f00c";
}
.fa-remove:before,
.fa-close:before,
.fa-times:before {
  content: "\f00d";
}
.fa-search-plus:before {
  content: "\f00e";
}
.fa-search-minus:before {
  content: "\f010";
}
.fa-power-off:before {
  content: "\f011";
}
.fa-signal:before {
  content: "\f012";
}
.fa-gear:before,
.fa-cog:before {
  content: "\f013";
}
.fa-trash-o:before {
  content: "\f014";
}
.fa-home:before {
  content: "\f015";
}
.fa-file-o:before {
  content: "\f016";
}
.fa-clock-o:before {
  content: "\f017";
}
.fa-road:before {
  content: "\f018";
}
.fa-download:before {
  content: "\f019";
}
.fa-arrow-circle-o-down:before {
  content: "\f01a";
}
.fa-arrow-circle-o-up:before {
  content: "\f01b";
}
.fa-inbox:before {
  content: "\f01c";
}
.fa-play-circle-o:before {
  content: "\f01d";
}
.fa-rotate-right:before,
.fa-repeat:before {
  content: "\f01e";
}
.fa-refresh:before {
  content: "\f021";
}
.fa-list-alt:before {
  content: "\f022";
}
.fa-lock:before {
  content: "\f023";
}
.fa-flag:before {
  content: "\f024";
}
.fa-headphones:before {
  content: "\f025";
}
.fa-volume-off:before {
  content: "\f026";
}
.fa-volume-down:before {
  content: "\f027";
}
.fa-volume-up:before {
  content: "\f028";
}
.fa-qrcode:before {
  content: "\f029";
}
.fa-barcode:before {
  content: "\f02a";
}
.fa-tag:before {
  content: "\f02b";
}
.fa-tags:before {
  content: "\f02c";
}
.fa-book:before {
  content: "\f02d";
}
.fa-bookmark:before {
  content: "\f02e";
}
.fa-print:before {
  content: "\f02f";
}
.fa-camera:before {
  content: "\f030";
}
.fa-font:before {
  content: "\f031";
}
.fa-bold:before {
  content: "\f032";
}
.fa-italic:before {
  content: "\f033";
}
.fa-text-height:before {
  content: "\f034";
}
.fa-text-width:before {
  content: "\f035";
}
.fa-align-left:before {
  content: "\f036";
}
.fa-align-center:before {
  content: "\f037";
}
.fa-align-right:before {
  content: "\f038";
}
.fa-align-justify:before {
  content: "\f039";
}
.fa-list:before {
  content: "\f03a";
}
.fa-dedent:before,
.fa-outdent:before {
  content: "\f03b";
}
.fa-indent:before {
  content: "\f03c";
}
.fa-video-camera:before {
  content: "\f03d";
}
.fa-photo:before,
.fa-image:before,
.fa-picture-o:before {
  content: "\f03e";
}
.fa-pencil:before {
  content: "\f040";
}
.fa-map-marker:before {
  content: "\f041";
}
.fa-adjust:before {
  content: "\f042";
}
.fa-tint:before {
  content: "\f043";
}
.fa-edit:before,
.fa-pencil-square-o:before {
  content: "\f044";
}
.fa-share-square-o:before {
  content: "\f045";
}
.fa-check-square-o:before {
  content: "\f046";
}
.fa-arrows:before {
  content: "\f047";
}
.fa-step-backward:before {
  content: "\f048";
}
.fa-fast-backward:before {
  content: "\f049";
}
.fa-backward:before {
  content: "\f04a";
}
.fa-play:before {
  content: "\f04b";
}
.fa-pause:before {
  content: "\f04c";
}
.fa-stop:before {
  content: "\f04d";
}
.fa-forward:before {
  content: "\f04e";
}
.fa-fast-forward:before {
  content: "\f050";
}
.fa-step-forward:before {
  content: "\f051";
}
.fa-eject:before {
  content: "\f052";
}
.fa-chevron-left:before {
  content: "\f053";
}
.fa-chevron-right:before {
  content: "\f054";
}
.fa-plus-circle:before {
  content: "\f055";
}
.fa-minus-circle:before {
  content: "\f056";
}
.fa-times-circle:before {
  content: "\f057";
}
.fa-check-circle:before {
  content: "\f058";
}
.fa-question-circle:before {
  content: "\f059";
}
.fa-info-circle:before {
  content: "\f05a";
}
.fa-crosshairs:before {
  content: "\f05b";
}
.fa-times-circle-o:before {
  content: "\f05c";
}
.fa-check-circle-o:before {
  content: "\f05d";
}
.fa-ban:before {
  content: "\f05e";
}
.fa-arrow-left:before {
  content: "\f060";
}
.fa-arrow-right:before {
  content: "\f061";
}
.fa-arrow-up:before {
  content: "\f062";
}
.fa-arrow-down:before {
  content: "\f063";
}
.fa-mail-forward:before,
.fa-share:before {
  content: "\f064";
}
.fa-expand:before {
  content: "\f065";
}
.fa-compress:before {
  content: "\f066";
}
.fa-plus:before {
  content: "\f067";
}
.fa-minus:before {
  content: "\f068";
}
.fa-asterisk:before {
  content: "\f069";
}
.fa-exclamation-circle:before {
  content: "\f06a";
}
.fa-gift:before {
  content: "\f06b";
}
.fa-leaf:before {
  content: "\f06c";
}
.fa-fire:before {
  content: "\f06d";
}
.fa-eye:before {
  content: "\f06e";
}
.fa-eye-slash:before {
  content: "\f070";
}
.fa-warning:before,
.fa-exclamation-triangle:before {
  content: "\f071";
}
.fa-plane:before {
  content: "\f072";
}
.fa-calendar:before {
  content: "\f073";
}
.fa-random:before {
  content: "\f074";
}
.fa-comment:before {
  content: "\f075";
}
.fa-magnet:before {
  content: "\f076";
}
.fa-chevron-up:before {
  content: "\f077";
}
.fa-chevron-down:before {
  content: "\f078";
}
.fa-retweet:before {
  content: "\f079";
}
.fa-shopping-cart:before {
  content: "\f07a";
}
.fa-folder:before {
  content: "\f07b";
}
.fa-folder-open:before {
  content: "\f07c";
}
.fa-arrows-v:before {
  content: "\f07d";
}
.fa-arrows-h:before {
  content: "\f07e";
}
.fa-bar-chart-o:before,
.fa-bar-chart:before {
  content: "\f080";
}
.fa-twitter-square:before {
  content: "\f081";
}
.fa-facebook-square:before {
  content: "\f082";
}
.fa-camera-retro:before {
  content: "\f083";
}
.fa-key:before {
  content: "\f084";
}
.fa-gears:before,
.fa-cogs:before {
  content: "\f085";
}
.fa-comments:before {
  content: "\f086";
}
.fa-thumbs-o-up:before {
  content: "\f087";
}
.fa-thumbs-o-down:before {
  content: "\f088";
}
.fa-star-half:before {
  content: "\f089";
}
.fa-heart-o:before {
  content: "\f08a";
}
.fa-sign-out:before {
  content: "\f08b";
}
.fa-linkedin-square:before {
  content: "\f08c";
}
.fa-thumb-tack:before {
  content: "\f08d";
}
.fa-external-link:before {
  content: "\f08e";
}
.fa-sign-in:before {
  content: "\f090";
}
.fa-trophy:before {
  content: "\f091";
}
.fa-github-square:before {
  content: "\f092";
}
.fa-upload:before {
  content: "\f093";
}
.fa-lemon-o:before {
  content: "\f094";
}
.fa-phone:before {
  content: "\f095";
}
.fa-square-o:before {
  content: "\f096";
}
.fa-bookmark-o:before {
  content: "\f097";
}
.fa-phone-square:before {
  content: "\f098";
}
.fa-twitter:before {
  content: "\f099";
}
.fa-facebook-f:before,
.fa-facebook:before {
  content: "\f09a";
}
.fa-github:before {
  content: "\f09b";
}
.fa-unlock:before {
  content: "\f09c";
}
.fa-credit-card:before {
  content: "\f09d";
}
.fa-feed:before,
.fa-rss:before {
  content: "\f09e";
}
.fa-hdd-o:before {
  content: "\f0a0";
}
.fa-bullhorn:before {
  content: "\f0a1";
}
.fa-bell:before {
  content: "\f0f3";
}
.fa-certificate:before {
  content: "\f0a3";
}
.fa-hand-o-right:before {
  content: "\f0a4";
}
.fa-hand-o-left:before {
  content: "\f0a5";
}
.fa-hand-o-up:before {
  content: "\f0a6";
}
.fa-hand-o-down:before {
  content: "\f0a7";
}
.fa-arrow-circle-left:before {
  content: "\f0a8";
}
.fa-arrow-circle-right:before {
  content: "\f0a9";
}
.fa-arrow-circle-up:before {
  content: "\f0aa";
}
.fa-arrow-circle-down:before {
  content: "\f0ab";
}
.fa-globe:before {
  content: "\f0ac";
}
.fa-wrench:before {
  content: "\f0ad";
}
.fa-tasks:before {
  content: "\f0ae";
}
.fa-filter:before {
  content: "\f0b0";
}
.fa-briefcase:before {
  content: "\f0b1";
}
.fa-arrows-alt:before {
  content: "\f0b2";
}
.fa-group:before,
.fa-users:before {
  content: "\f0c0";
}
.fa-chain:before,
.fa-link:before {
  content: "\f0c1";
}
.fa-cloud:before {
  content: "\f0c2";
}
.fa-flask:before {
  content: "\f0c3";
}
.fa-cut:before,
.fa-scissors:before {
  content: "\f0c4";
}
.fa-copy:before,
.fa-files-o:before {
  content: "\f0c5";
}
.fa-paperclip:before {
  content: "\f0c6";
}
.fa-save:before,
.fa-floppy-o:before {
  content: "\f0c7";
}
.fa-square:before {
  content: "\f0c8";
}
.fa-navicon:before,
.fa-reorder:before,
.fa-bars:before {
  content: "\f0c9";
}
.fa-list-ul:before {
  content: "\f0ca";
}
.fa-list-ol:before {
  content: "\f0cb";
}
.fa-strikethrough:before {
  content: "\f0cc";
}
.fa-underline:before {
  content: "\f0cd";
}
.fa-table:before {
  content: "\f0ce";
}
.fa-magic:before {
  content: "\f0d0";
}
.fa-truck:before {
  content: "\f0d1";
}
.fa-pinterest:before {
  content: "\f0d2";
}
.fa-pinterest-square:before {
  content: "\f0d3";
}
.fa-google-plus-square:before {
  content: "\f0d4";
}
.fa-google-plus:before {
  content: "\f0d5";
}
.fa-money:before {
  content: "\f0d6";
}
.fa-caret-down:before {
  content: "\f0d7";
}
.fa-caret-up:before {
  content: "\f0d8";
}
.fa-caret-left:before {
  content: "\f0d9";
}
.fa-caret-right:before {
  content: "\f0da";
}
.fa-columns:before {
  content: "\f0db";
}
.fa-unsorted:before,
.fa-sort:before {
  content: "\f0dc";
}
.fa-sort-down:before,
.fa-sort-desc:before {
  content: "\f0dd";
}
.fa-sort-up:before,
.fa-sort-asc:before {
  content: "\f0de";
}
.fa-envelope:before {
  content: "\f0e0";
}
.fa-linkedin:before {
  content: "\f0e1";
}
.fa-rotate-left:before,
.fa-undo:before {
  content: "\f0e2";
}
.fa-legal:before,
.fa-gavel:before {
  content: "\f0e3";
}
.fa-dashboard:before,
.fa-tachometer:before {
  content: "\f0e4";
}
.fa-comment-o:before {
  content: "\f0e5";
}
.fa-comments-o:before {
  content: "\f0e6";
}
.fa-flash:before,
.fa-bolt:before {
  content: "\f0e7";
}
.fa-sitemap:before {
  content: "\f0e8";
}
.fa-umbrella:before {
  content: "\f0e9";
}
.fa-paste:before,
.fa-clipboard:before {
  content: "\f0ea";
}
.fa-lightbulb-o:before {
  content: "\f0eb";
}
.fa-exchange:before {
  content: "\f0ec";
}
.fa-cloud-download:before {
  content: "\f0ed";
}
.fa-cloud-upload:before {
  content: "\f0ee";
}
.fa-user-md:before {
  content: "\f0f0";
}
.fa-stethoscope:before {
  content: "\f0f1";
}
.fa-suitcase:before {
  content: "\f0f2";
}
.fa-bell-o:before {
  content: "\f0a2";
}
.fa-coffee:before {
  content: "\f0f4";
}
.fa-cutlery:before {
  content: "\f0f5";
}
.fa-file-text-o:before {
  content: "\f0f6";
}
.fa-building-o:before {
  content: "\f0f7";
}
.fa-hospital-o:before {
  content: "\f0f8";
}
.fa-ambulance:before {
  content: "\f0f9";
}
.fa-medkit:before {
  content: "\f0fa";
}
.fa-fighter-jet:before {
  content: "\f0fb";
}
.fa-beer:before {
  content: "\f0fc";
}
.fa-h-square:before {
  content: "\f0fd";
}
.fa-plus-square:before {
  content: "\f0fe";
}
.fa-angle-double-left:before {
  content: "\f100";
}
.fa-angle-double-right:before {
  content: "\f101";
}
.fa-angle-double-up:before {
  content: "\f102";
}
.fa-angle-double-down:before {
  content: "\f103";
}
.fa-angle-left:before {
  content: "\f104";
}
.fa-angle-right:before {
  content: "\f105";
}
.fa-angle-up:before {
  content: "\f106";
}
.fa-angle-down:before {
  content: "\f107";
}
.fa-desktop:before {
  content: "\f108";
}
.fa-laptop:before {
  content: "\f109";
}
.fa-tablet:before {
  content: "\f10a";
}
.fa-mobile-phone:before,
.fa-mobile:before {
  content: "\f10b";
}
.fa-circle-o:before {
  content: "\f10c";
}
.fa-quote-left:before {
  content: "\f10d";
}
.fa-quote-right:before {
  content: "\f10e";
}
.fa-spinner:before {
  content: "\f110";
}
.fa-circle:before {
  content: "\f111";
}
.fa-mail-reply:before,
.fa-reply:before {
  content: "\f112";
}
.fa-github-alt:before {
  content: "\f113";
}
.fa-folder-o:before {
  content: "\f114";
}
.fa-folder-open-o:before {
  content: "\f115";
}
.fa-smile-o:before {
  content: "\f118";
}
.fa-frown-o:before {
  content: "\f119";
}
.fa-meh-o:before {
  content: "\f11a";
}
.fa-gamepad:before {
  content: "\f11b";
}
.fa-keyboard-o:before {
  content: "\f11c";
}
.fa-flag-o:before {
  content: "\f11d";
}
.fa-flag-checkered:before {
  content: "\f11e";
}
.fa-terminal:before {
  content: "\f120";
}
.fa-code:before {
  content: "\f121";
}
.fa-mail-reply-all:before,
.fa-reply-all:before {
  content: "\f122";
}
.fa-star-half-empty:before,
.fa-star-half-full:before,
.fa-star-half-o:before {
  content: "\f123";
}
.fa-location-arrow:before {
  content: "\f124";
}
.fa-crop:before {
  content: "\f125";
}
.fa-code-fork:before {
  content: "\f126";
}
.fa-unlink:before,
.fa-chain-broken:before {
  content: "\f127";
}
.fa-question:before {
  content: "\f128";
}
.fa-info:before {
  content: "\f129";
}
.fa-exclamation:before {
  content: "\f12a";
}
.fa-superscript:before {
  content: "\f12b";
}
.fa-subscript:before {
  content: "\f12c";
}
.fa-eraser:before {
  content: "\f12d";
}
.fa-puzzle-piece:before {
  content: "\f12e";
}
.fa-microphone:before {
  content: "\f130";
}
.fa-microphone-slash:before {
  content: "\f131";
}
.fa-shield:before {
  content: "\f132";
}
.fa-calendar-o:before {
  content: "\f133";
}
.fa-fire-extinguisher:before {
  content: "\f134";
}
.fa-rocket:before {
  content: "\f135";
}
.fa-maxcdn:before {
  content: "\f136";
}
.fa-chevron-circle-left:before {
  content: "\f137";
}
.fa-chevron-circle-right:before {
  content: "\f138";
}
.fa-chevron-circle-up:before {
  content: "\f139";
}
.fa-chevron-circle-down:before {
  content: "\f13a";
}
.fa-html5:before {
  content: "\f13b";
}
.fa-css3:before {
  content: "\f13c";
}
.fa-anchor:before {
  content: "\f13d";
}
.fa-unlock-alt:before {
  content: "\f13e";
}
.fa-bullseye:before {
  content: "\f140";
}
.fa-ellipsis-h:before {
  content: "\f141";
}
.fa-ellipsis-v:before {
  content: "\f142";
}
.fa-rss-square:before {
  content: "\f143";
}
.fa-play-circle:before {
  content: "\f144";
}
.fa-ticket:before {
  content: "\f145";
}
.fa-minus-square:before {
  content: "\f146";
}
.fa-minus-square-o:before {
  content: "\f147";
}
.fa-level-up:before {
  content: "\f148";
}
.fa-level-down:before {
  content: "\f149";
}
.fa-check-square:before {
  content: "\f14a";
}
.fa-pencil-square:before {
  content: "\f14b";
}
.fa-external-link-square:before {
  content: "\f14c";
}
.fa-share-square:before {
  content: "\f14d";
}
.fa-compass:before {
  content: "\f14e";
}
.fa-toggle-down:before,
.fa-caret-square-o-down:before {
  content: "\f150";
}
.fa-toggle-up:before,
.fa-caret-square-o-up:before {
  content: "\f151";
}
.fa-toggle-right:before,
.fa-caret-square-o-right:before {
  content: "\f152";
}
.fa-euro:before,
.fa-eur:before {
  content: "\f153";
}
.fa-gbp:before {
  content: "\f154";
}
.fa-dollar:before,
.fa-usd:before {
  content: "\f155";
}
.fa-rupee:before,
.fa-inr:before {
  content: "\f156";
}
.fa-cny:before,
.fa-rmb:before,
.fa-yen:before,
.fa-jpy:before {
  content: "\f157";
}
.fa-ruble:before,
.fa-rouble:before,
.fa-rub:before {
  content: "\f158";
}
.fa-won:before,
.fa-krw:before {
  content: "\f159";
}
.fa-bitcoin:before,
.fa-btc:before {
  content: "\f15a";
}
.fa-file:before {
  content: "\f15b";
}
.fa-file-text:before {
  content: "\f15c";
}
.fa-sort-alpha-asc:before {
  content: "\f15d";
}
.fa-sort-alpha-desc:before {
  content: "\f15e";
}
.fa-sort-amount-asc:before {
  content: "\f160";
}
.fa-sort-amount-desc:before {
  content: "\f161";
}
.fa-sort-numeric-asc:before {
  content: "\f162";
}
.fa-sort-numeric-desc:before {
  content: "\f163";
}
.fa-thumbs-up:before {
  content: "\f164";
}
.fa-thumbs-down:before {
  content: "\f165";
}
.fa-youtube-square:before {
  content: "\f166";
}
.fa-youtube:before {
  content: "\f167";
}
.fa-xing:before {
  content: "\f168";
}
.fa-xing-square:before {
  content: "\f169";
}
.fa-youtube-play:before {
  content: "\f16a";
}
.fa-dropbox:before {
  content: "\f16b";
}
.fa-stack-overflow:before {
  content: "\f16c";
}
.fa-instagram:before {
  content: "\f16d";
}
.fa-flickr:before {
  content: "\f16e";
}
.fa-adn:before {
  content: "\f170";
}
.fa-bitbucket:before {
  content: "\f171";
}
.fa-bitbucket-square:before {
  content: "\f172";
}
.fa-tumblr:before {
  content: "\f173";
}
.fa-tumblr-square:before {
  content: "\f174";
}
.fa-long-arrow-down:before {
  content: "\f175";
}
.fa-long-arrow-up:before {
  content: "\f176";
}
.fa-long-arrow-left:before {
  content: "\f177";
}
.fa-long-arrow-right:before {
  content: "\f178";
}
.fa-apple:before {
  content: "\f179";
}
.fa-windows:before {
  content: "\f17a";
}
.fa-android:before {
  content: "\f17b";
}
.fa-linux:before {
  content: "\f17c";
}
.fa-dribbble:before {
  content: "\f17d";
}
.fa-skype:before {
  content: "\f17e";
}
.fa-foursquare:before {
  content: "\f180";
}
.fa-trello:before {
  content: "\f181";
}
.fa-female:before {
  content: "\f182";
}
.fa-male:before {
  content: "\f183";
}
.fa-gittip:before,
.fa-gratipay:before {
  content: "\f184";
}
.fa-sun-o:before {
  content: "\f185";
}
.fa-moon-o:before {
  content: "\f186";
}
.fa-archive:before {
  content: "\f187";
}
.fa-bug:before {
  content: "\f188";
}
.fa-vk:before {
  content: "\f189";
}
.fa-weibo:before {
  content: "\f18a";
}
.fa-renren:before {
  content: "\f18b";
}
.fa-pagelines:before {
  content: "\f18c";
}
.fa-stack-exchange:before {
  content: "\f18d";
}
.fa-arrow-circle-o-right:before {
  content: "\f18e";
}
.fa-arrow-circle-o-left:before {
  content: "\f190";
}
.fa-toggle-left:before,
.fa-caret-square-o-left:before {
  content: "\f191";
}
.fa-dot-circle-o:before {
  content: "\f192";
}
.fa-wheelchair:before {
  content: "\f193";
}
.fa-vimeo-square:before {
  content: "\f194";
}
.fa-turkish-lira:before,
.fa-try:before {
  content: "\f195";
}
.fa-plus-square-o:before {
  content: "\f196";
}
.fa-space-shuttle:before {
  content: "\f197";
}
.fa-slack:before {
  content: "\f198";
}
.fa-envelope-square:before {
  content: "\f199";
}
.fa-wordpress:before {
  content: "\f19a";
}
.fa-openid:before {
  content: "\f19b";
}
.fa-institution:before,
.fa-bank:before,
.fa-university:before {
  content: "\f19c";
}
.fa-mortar-board:before,
.fa-graduation-cap:before {
  content: "\f19d";
}
.fa-yahoo:before {
  content: "\f19e";
}
.fa-google:before {
  content: "\f1a0";
}
.fa-reddit:before {
  content: "\f1a1";
}
.fa-reddit-square:before {
  content: "\f1a2";
}
.fa-stumbleupon-circle:before {
  content: "\f1a3";
}
.fa-stumbleupon:before {
  content: "\f1a4";
}
.fa-delicious:before {
  content: "\f1a5";
}
.fa-digg:before {
  content: "\f1a6";
}
.fa-pied-piper-pp:before {
  content: "\f1a7";
}
.fa-pied-piper-alt:before {
  content: "\f1a8";
}
.fa-drupal:before {
  content: "\f1a9";
}
.fa-joomla:before {
  content: "\f1aa";
}
.fa-language:before {
  content: "\f1ab";
}
.fa-fax:before {
  content: "\f1ac";
}
.fa-building:before {
  content: "\f1ad";
}
.fa-child:before {
  content: "\f1ae";
}
.fa-paw:before {
  content: "\f1b0";
}
.fa-spoon:before {
  content: "\f1b1";
}
.fa-cube:before {
  content: "\f1b2";
}
.fa-cubes:before {
  content: "\f1b3";
}
.fa-behance:before {
  content: "\f1b4";
}
.fa-behance-square:before {
  content: "\f1b5";
}
.fa-steam:before {
  content: "\f1b6";
}
.fa-steam-square:before {
  content: "\f1b7";
}
.fa-recycle:before {
  content: "\f1b8";
}
.fa-automobile:before,
.fa-car:before {
  content: "\f1b9";
}
.fa-cab:before,
.fa-taxi:before {
  content: "\f1ba";
}
.fa-tree:before {
  content: "\f1bb";
}
.fa-spotify:before {
  content: "\f1bc";
}
.fa-deviantart:before {
  content: "\f1bd";
}
.fa-soundcloud:before {
  content: "\f1be";
}
.fa-database:before {
  content: "\f1c0";
}
.fa-file-pdf-o:before {
  content: "\f1c1";
}
.fa-file-word-o:before {
  content: "\f1c2";
}
.fa-file-excel-o:before {
  content: "\f1c3";
}
.fa-file-powerpoint-o:before {
  content: "\f1c4";
}
.fa-file-photo-o:before,
.fa-file-picture-o:before,
.fa-file-image-o:before {
  content: "\f1c5";
}
.fa-file-zip-o:before,
.fa-file-archive-o:before {
  content: "\f1c6";
}
.fa-file-sound-o:before,
.fa-file-audio-o:before {
  content: "\f1c7";
}
.fa-file-movie-o:before,
.fa-file-video-o:before {
  content: "\f1c8";
}
.fa-file-code-o:before {
  content: "\f1c9";
}
.fa-vine:before {
  content: "\f1ca";
}
.fa-codepen:before {
  content: "\f1cb";
}
.fa-jsfiddle:before {
  content: "\f1cc";
}
.fa-life-bouy:before,
.fa-life-buoy:before,
.fa-life-saver:before,
.fa-support:before,
.fa-life-ring:before {
  content: "\f1cd";
}
.fa-circle-o-notch:before {
  content: "\f1ce";
}
.fa-ra:before,
.fa-resistance:before,
.fa-rebel:before {
  content: "\f1d0";
}
.fa-ge:before,
.fa-empire:before {
  content: "\f1d1";
}
.fa-git-square:before {
  content: "\f1d2";
}
.fa-git:before {
  content: "\f1d3";
}
.fa-y-combinator-square:before,
.fa-yc-square:before,
.fa-hacker-news:before {
  content: "\f1d4";
}
.fa-tencent-weibo:before {
  content: "\f1d5";
}
.fa-qq:before {
  content: "\f1d6";
}
.fa-wechat:before,
.fa-weixin:before {
  content: "\f1d7";
}
.fa-send:before,
.fa-paper-plane:before {
  content: "\f1d8";
}
.fa-send-o:before,
.fa-paper-plane-o:before {
  content: "\f1d9";
}
.fa-history:before {
  content: "\f1da";
}
.fa-circle-thin:before {
  content: "\f1db";
}
.fa-header:before {
  content: "\f1dc";
}
.fa-paragraph:before {
  content: "\f1dd";
}
.fa-sliders:before {
  content: "\f1de";
}
.fa-share-alt:before {
  content: "\f1e0";
}
.fa-share-alt-square:before {
  content: "\f1e1";
}
.fa-bomb:before {
  content: "\f1e2";
}
.fa-soccer-ball-o:before,
.fa-futbol-o:before {
  content: "\f1e3";
}
.fa-tty:before {
  content: "\f1e4";
}
.fa-binoculars:before {
  content: "\f1e5";
}
.fa-plug:before {
  content: "\f1e6";
}
.fa-slideshare:before {
  content: "\f1e7";
}
.fa-twitch:before {
  content: "\f1e8";
}
.fa-yelp:before {
  content: "\f1e9";
}
.fa-newspaper-o:before {
  content: "\f1ea";
}
.fa-wifi:before {
  content: "\f1eb";
}
.fa-calculator:before {
  content: "\f1ec";
}
.fa-paypal:before {
  content: "\f1ed";
}
.fa-google-wallet:before {
  content: "\f1ee";
}
.fa-cc-visa:before {
  content: "\f1f0";
}
.fa-cc-mastercard:before {
  content: "\f1f1";
}
.fa-cc-discover:before {
  content: "\f1f2";
}
.fa-cc-amex:before {
  content: "\f1f3";
}
.fa-cc-paypal:before {
  content: "\f1f4";
}
.fa-cc-stripe:before {
  content: "\f1f5";
}
.fa-bell-slash:before {
  content: "\f1f6";
}
.fa-bell-slash-o:before {
  content: "\f1f7";
}
.fa-trash:before {
  content: "\f1f8";
}
.fa-copyright:before {
  content: "\f1f9";
}
.fa-at:before {
  content: "\f1fa";
}
.fa-eyedropper:before {
  content: "\f1fb";
}
.fa-paint-brush:before {
  content: "\f1fc";
}
.fa-birthday-cake:before {
  content: "\f1fd";
}
.fa-area-chart:before {
  content: "\f1fe";
}
.fa-pie-chart:before {
  content: "\f200";
}
.fa-line-chart:before {
  content: "\f201";
}
.fa-lastfm:before {
  content: "\f202";
}
.fa-lastfm-square:before {
  content: "\f203";
}
.fa-toggle-off:before {
  content: "\f204";
}
.fa-toggle-on:before {
  content: "\f205";
}
.fa-bicycle:before {
  content: "\f206";
}
.fa-bus:before {
  content: "\f207";
}
.fa-ioxhost:before {
  content: "\f208";
}
.fa-angellist:before {
  content: "\f209";
}
.fa-cc:before {
  content: "\f20a";
}
.fa-shekel:before,
.fa-sheqel:before,
.fa-ils:before {
  content: "\f20b";
}
.fa-meanpath:before {
  content: "\f20c";
}
.fa-buysellads:before {
  content: "\f20d";
}
.fa-connectdevelop:before {
  content: "\f20e";
}
.fa-dashcube:before {
  content: "\f210";
}
.fa-forumbee:before {
  content: "\f211";
}
.fa-leanpub:before {
  content: "\f212";
}
.fa-sellsy:before {
  content: "\f213";
}
.fa-shirtsinbulk:before {
  content: "\f214";
}
.fa-simplybuilt:before {
  content: "\f215";
}
.fa-skyatlas:before {
  content: "\f216";
}
.fa-cart-plus:before {
  content: "\f217";
}
.fa-cart-arrow-down:before {
  content: "\f218";
}
.fa-diamond:before {
  content: "\f219";
}
.fa-ship:before {
  content: "\f21a";
}
.fa-user-secret:before {
  content: "\f21b";
}
.fa-motorcycle:before {
  content: "\f21c";
}
.fa-street-view:before {
  content: "\f21d";
}
.fa-heartbeat:before {
  content: "\f21e";
}
.fa-venus:before {
  content: "\f221";
}
.fa-mars:before {
  content: "\f222";
}
.fa-mercury:before {
  content: "\f223";
}
.fa-intersex:before,
.fa-transgender:before {
  content: "\f224";
}
.fa-transgender-alt:before {
  content: "\f225";
}
.fa-venus-double:before {
  content: "\f226";
}
.fa-mars-double:before {
  content: "\f227";
}
.fa-venus-mars:before {
  content: "\f228";
}
.fa-mars-stroke:before {
  content: "\f229";
}
.fa-mars-stroke-v:before {
  content: "\f22a";
}
.fa-mars-stroke-h:before {
  content: "\f22b";
}
.fa-neuter:before {
  content: "\f22c";
}
.fa-genderless:before {
  content: "\f22d";
}
.fa-facebook-official:before {
  content: "\f230";
}
.fa-pinterest-p:before {
  content: "\f231";
}
.fa-whatsapp:before {
  content: "\f232";
}
.fa-server:before {
  content: "\f233";
}
.fa-user-plus:before {
  content: "\f234";
}
.fa-user-times:before {
  content: "\f235";
}
.fa-hotel:before,
.fa-bed:before {
  content: "\f236";
}
.fa-viacoin:before {
  content: "\f237";
}
.fa-train:before {
  content: "\f238";
}
.fa-subway:before {
  content: "\f239";
}
.fa-medium:before {
  content: "\f23a";
}
.fa-yc:before,
.fa-y-combinator:before {
  content: "\f23b";
}
.fa-optin-monster:before {
  content: "\f23c";
}
.fa-opencart:before {
  content: "\f23d";
}
.fa-expeditedssl:before {
  content: "\f23e";
}
.fa-battery-4:before,
.fa-battery:before,
.fa-battery-full:before {
  content: "\f240";
}
.fa-battery-3:before,
.fa-battery-three-quarters:before {
  content: "\f241";
}
.fa-battery-2:before,
.fa-battery-half:before {
  content: "\f242";
}
.fa-battery-1:before,
.fa-battery-quarter:before {
  content: "\f243";
}
.fa-battery-0:before,
.fa-battery-empty:before {
  content: "\f244";
}
.fa-mouse-pointer:before {
  content: "\f245";
}
.fa-i-cursor:before {
  content: "\f246";
}
.fa-object-group:before {
  content: "\f247";
}
.fa-object-ungroup:before {
  content: "\f248";
}
.fa-sticky-note:before {
  content: "\f249";
}
.fa-sticky-note-o:before {
  content: "\f24a";
}
.fa-cc-jcb:before {
  content: "\f24b";
}
.fa-cc-diners-club:before {
  content: "\f24c";
}
.fa-clone:before {
  content: "\f24d";
}
.fa-balance-scale:before {
  content: "\f24e";
}
.fa-hourglass-o:before {
  content: "\f250";
}
.fa-hourglass-1:before,
.fa-hourglass-start:before {
  content: "\f251";
}
.fa-hourglass-2:before,
.fa-hourglass-half:before {
  content: "\f252";
}
.fa-hourglass-3:before,
.fa-hourglass-end:before {
  content: "\f253";
}
.fa-hourglass:before {
  content: "\f254";
}
.fa-hand-grab-o:before,
.fa-hand-rock-o:before {
  content: "\f255";
}
.fa-hand-stop-o:before,
.fa-hand-paper-o:before {
  content: "\f256";
}
.fa-hand-scissors-o:before {
  content: "\f257";
}
.fa-hand-lizard-o:before {
  content: "\f258";
}
.fa-hand-spock-o:before {
  content: "\f259";
}
.fa-hand-pointer-o:before {
  content: "\f25a";
}
.fa-hand-peace-o:before {
  content: "\f25b";
}
.fa-trademark:before {
  content: "\f25c";
}
.fa-registered:before {
  content: "\f25d";
}
.fa-creative-commons:before {
  content: "\f25e";
}
.fa-gg:before {
  content: "\f260";
}
.fa-gg-circle:before {
  content: "\f261";
}
.fa-tripadvisor:before {
  content: "\f262";
}
.fa-odnoklassniki:before {
  content: "\f263";
}
.fa-odnoklassniki-square:before {
  content: "\f264";
}
.fa-get-pocket:before {
  content: "\f265";
}
.fa-wikipedia-w:before {
  content: "\f266";
}
.fa-safari:before {
  content: "\f267";
}
.fa-chrome:before {
  content: "\f268";
}
.fa-firefox:before {
  content: "\f269";
}
.fa-opera:before {
  content: "\f26a";
}
.fa-internet-explorer:before {
  content: "\f26b";
}
.fa-tv:before,
.fa-television:before {
  content: "\f26c";
}
.fa-contao:before {
  content: "\f26d";
}
.fa-500px:before {
  content: "\f26e";
}
.fa-amazon:before {
  content: "\f270";
}
.fa-calendar-plus-o:before {
  content: "\f271";
}
.fa-calendar-minus-o:before {
  content: "\f272";
}
.fa-calendar-times-o:before {
  content: "\f273";
}
.fa-calendar-check-o:before {
  content: "\f274";
}
.fa-industry:before {
  content: "\f275";
}
.fa-map-pin:before {
  content: "\f276";
}
.fa-map-signs:before {
  content: "\f277";
}
.fa-map-o:before {
  content: "\f278";
}
.fa-map:before {
  content: "\f279";
}
.fa-commenting:before {
  content: "\f27a";
}
.fa-commenting-o:before {
  content: "\f27b";
}
.fa-houzz:before {
  content: "\f27c";
}
.fa-vimeo:before {
  content: "\f27d";
}
.fa-black-tie:before {
  content: "\f27e";
}
.fa-fonticons:before {
  content: "\f280";
}
.fa-reddit-alien:before {
  content: "\f281";
}
.fa-edge:before {
  content: "\f282";
}
.fa-credit-card-alt:before {
  content: "\f283";
}
.fa-codiepie:before {
  content: "\f284";
}
.fa-modx:before {
  content: "\f285";
}
.fa-fort-awesome:before {
  content: "\f286";
}
.fa-usb:before {
  content: "\f287";
}
.fa-product-hunt:before {
  content: "\f288";
}
.fa-mixcloud:before {
  content: "\f289";
}
.fa-scribd:before {
  content: "\f28a";
}
.fa-pause-circle:before {
  content: "\f28b";
}
.fa-pause-circle-o:before {
  content: "\f28c";
}
.fa-stop-circle:before {
  content: "\f28d";
}
.fa-stop-circle-o:before {
  content: "\f28e";
}
.fa-shopping-bag:before {
  content: "\f290";
}
.fa-shopping-basket:before {
  content: "\f291";
}
.fa-hashtag:before {
  content: "\f292";
}
.fa-bluetooth:before {
  content: "\f293";
}
.fa-bluetooth-b:before {
  content: "\f294";
}
.fa-percent:before {
  content: "\f295";
}
.fa-gitlab:before {
  content: "\f296";
}
.fa-wpbeginner:before {
  content: "\f297";
}
.fa-wpforms:before {
  content: "\f298";
}
.fa-envira:before {
  content: "\f299";
}
.fa-universal-access:before {
  content: "\f29a";
}
.fa-wheelchair-alt:before {
  content: "\f29b";
}
.fa-question-circle-o:before {
  content: "\f29c";
}
.fa-blind:before {
  content: "\f29d";
}
.fa-audio-description:before {
  content: "\f29e";
}
.fa-volume-control-phone:before {
  content: "\f2a0";
}
.fa-braille:before {
  content: "\f2a1";
}
.fa-assistive-listening-systems:before {
  content: "\f2a2";
}
.fa-asl-interpreting:before,
.fa-american-sign-language-interpreting:before {
  content: "\f2a3";
}
.fa-deafness:before,
.fa-hard-of-hearing:before,
.fa-deaf:before {
  content: "\f2a4";
}
.fa-glide:before {
  content: "\f2a5";
}
.fa-glide-g:before {
  content: "\f2a6";
}
.fa-signing:before,
.fa-sign-language:before {
  content: "\f2a7";
}
.fa-low-vision:before {
  content: "\f2a8";
}
.fa-viadeo:before {
  content: "\f2a9";
}
.fa-viadeo-square:before {
  content: "\f2aa";
}
.fa-snapchat:before {
  content: "\f2ab";
}
.fa-snapchat-ghost:before {
  content: "\f2ac";
}
.fa-snapchat-square:before {
  content: "\f2ad";
}
.fa-pied-piper:before {
  content: "\f2ae";
}
.fa-first-order:before {
  content: "\f2b0";
}
.fa-yoast:before {
  content: "\f2b1";
}
.fa-themeisle:before {
  content: "\f2b2";
}
.fa-google-plus-circle:before,
.fa-google-plus-official:before {
  content: "\f2b3";
}
.fa-fa:before,
.fa-font-awesome:before {
  content: "\f2b4";
}
.fa-handshake-o:before {
  content: "\f2b5";
}
.fa-envelope-open:before {
  content: "\f2b6";
}
.fa-envelope-open-o:before {
  content: "\f2b7";
}
.fa-linode:before {
  content: "\f2b8";
}
.fa-address-book:before {
  content: "\f2b9";
}
.fa-address-book-o:before {
  content: "\f2ba";
}
.fa-vcard:before,
.fa-address-card:before {
  content: "\f2bb";
}
.fa-vcard-o:before,
.fa-address-card-o:before {
  content: "\f2bc";
}
.fa-user-circle:before {
  content: "\f2bd";
}
.fa-user-circle-o:before {
  content: "\f2be";
}
.fa-user-o:before {
  content: "\f2c0";
}
.fa-id-badge:before {
  content: "\f2c1";
}
.fa-drivers-license:before,
.fa-id-card:before {
  content: "\f2c2";
}
.fa-drivers-license-o:before,
.fa-id-card-o:before {
  content: "\f2c3";
}
.fa-quora:before {
  content: "\f2c4";
}
.fa-free-code-camp:before {
  content: "\f2c5";
}
.fa-telegram:before {
  content: "\f2c6";
}
.fa-thermometer-4:before,
.fa-thermometer:before,
.fa-thermometer-full:before {
  content: "\f2c7";
}
.fa-thermometer-3:before,
.fa-thermometer-three-quarters:before {
  content: "\f2c8";
}
.fa-thermometer-2:before,
.fa-thermometer-half:before {
  content: "\f2c9";
}
.fa-thermometer-1:before,
.fa-thermometer-quarter:before {
  content: "\f2ca";
}
.fa-thermometer-0:before,
.fa-thermometer-empty:before {
  content: "\f2cb";
}
.fa-shower:before {
  content: "\f2cc";
}
.fa-bathtub:before,
.fa-s15:before,
.fa-bath:before {
  content: "\f2cd";
}
.fa-podcast:before {
  content: "\f2ce";
}
.fa-window-maximize:before {
  content: "\f2d0";
}
.fa-window-minimize:before {
  content: "\f2d1";
}
.fa-window-restore:before {
  content: "\f2d2";
}
.fa-times-rectangle:before,
.fa-window-close:before {
  content: "\f2d3";
}
.fa-times-rectangle-o:before,
.fa-window-close-o:before {
  content: "\f2d4";
}
.fa-bandcamp:before {
  content: "\f2d5";
}
.fa-grav:before {
  content: "\f2d6";
}
.fa-etsy:before {
  content: "\f2d7";
}
.fa-imdb:before {
  content: "\f2d8";
}
.fa-ravelry:before {
  content: "\f2d9";
}
.fa-eercast:before {
  content: "\f2da";
}
.fa-microchip:before {
  content: "\f2db";
}
.fa-snowflake-o:before {
  content: "\f2dc";
}
.fa-superpowers:before {
  content: "\f2dd";
}
.fa-wpexplorer:before {
  content: "\f2de";
}
.fa-meetup:before {
  content: "\f2e0";
}
.sr-only {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
.sr-only-focusable:active,
.sr-only-focusable:focus {
  position: static;
  width: auto;
  height: auto;
  margin: 0;
  overflow: visible;
  clip: auto;
}
.sr-only-focusable:active,
.sr-only-focusable:focus {
  position: static;
  width: auto;
  height: auto;
  margin: 0;
  overflow: visible;
  clip: auto;
}
/*!
*
* IPython base
*
*/
.modal.fade .modal-dialog {
  -webkit-transform: translate(0, 0);
  -ms-transform: translate(0, 0);
  -o-transform: translate(0, 0);
  transform: translate(0, 0);
}
code {
  color: #000;
}
pre {
  font-size: inherit;
  line-height: inherit;
}
label {
  font-weight: normal;
}
/* Make the page background atleast 100% the height of the view port */
/* Make the page itself atleast 70% the height of the view port */
.border-box-sizing {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
.corner-all {
  border-radius: 2px;
}
.no-padding {
  padding: 0px;
}
/* Flexible box model classes */
/* Taken from Alex Russell http://infrequently.org/2009/08/css-3-progress/ */
/* This file is a compatability layer.  It allows the usage of flexible box 
model layouts accross multiple browsers, including older browsers.  The newest,
universal implementation of the flexible box model is used when available (see
`Modern browsers` comments below).  Browsers that are known to implement this 
new spec completely include:

    Firefox 28.0+
    Chrome 29.0+
    Internet Explorer 11+ 
    Opera 17.0+

Browsers not listed, including Safari, are supported via the styling under the
`Old browsers` comments below.
*/
.hbox {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
.hbox > * {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
}
.vbox {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
.vbox > * {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
}
.hbox.reverse,
.vbox.reverse,
.reverse {
  /* Old browsers */
  -webkit-box-direction: reverse;
  -moz-box-direction: reverse;
  box-direction: reverse;
  /* Modern browsers */
  flex-direction: row-reverse;
}
.hbox.box-flex0,
.vbox.box-flex0,
.box-flex0 {
  /* Old browsers */
  -webkit-box-flex: 0;
  -moz-box-flex: 0;
  box-flex: 0;
  /* Modern browsers */
  flex: none;
  width: auto;
}
.hbox.box-flex1,
.vbox.box-flex1,
.box-flex1 {
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
.hbox.box-flex,
.vbox.box-flex,
.box-flex {
  /* Old browsers */
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
.hbox.box-flex2,
.vbox.box-flex2,
.box-flex2 {
  /* Old browsers */
  -webkit-box-flex: 2;
  -moz-box-flex: 2;
  box-flex: 2;
  /* Modern browsers */
  flex: 2;
}
.box-group1 {
  /*  Deprecated */
  -webkit-box-flex-group: 1;
  -moz-box-flex-group: 1;
  box-flex-group: 1;
}
.box-group2 {
  /* Deprecated */
  -webkit-box-flex-group: 2;
  -moz-box-flex-group: 2;
  box-flex-group: 2;
}
.hbox.start,
.vbox.start,
.start {
  /* Old browsers */
  -webkit-box-pack: start;
  -moz-box-pack: start;
  box-pack: start;
  /* Modern browsers */
  justify-content: flex-start;
}
.hbox.end,
.vbox.end,
.end {
  /* Old browsers */
  -webkit-box-pack: end;
  -moz-box-pack: end;
  box-pack: end;
  /* Modern browsers */
  justify-content: flex-end;
}
.hbox.center,
.vbox.center,
.center {
  /* Old browsers */
  -webkit-box-pack: center;
  -moz-box-pack: center;
  box-pack: center;
  /* Modern browsers */
  justify-content: center;
}
.hbox.baseline,
.vbox.baseline,
.baseline {
  /* Old browsers */
  -webkit-box-pack: baseline;
  -moz-box-pack: baseline;
  box-pack: baseline;
  /* Modern browsers */
  justify-content: baseline;
}
.hbox.stretch,
.vbox.stretch,
.stretch {
  /* Old browsers */
  -webkit-box-pack: stretch;
  -moz-box-pack: stretch;
  box-pack: stretch;
  /* Modern browsers */
  justify-content: stretch;
}
.hbox.align-start,
.vbox.align-start,
.align-start {
  /* Old browsers */
  -webkit-box-align: start;
  -moz-box-align: start;
  box-align: start;
  /* Modern browsers */
  align-items: flex-start;
}
.hbox.align-end,
.vbox.align-end,
.align-end {
  /* Old browsers */
  -webkit-box-align: end;
  -moz-box-align: end;
  box-align: end;
  /* Modern browsers */
  align-items: flex-end;
}
.hbox.align-center,
.vbox.align-center,
.align-center {
  /* Old browsers */
  -webkit-box-align: center;
  -moz-box-align: center;
  box-align: center;
  /* Modern browsers */
  align-items: center;
}
.hbox.align-baseline,
.vbox.align-baseline,
.align-baseline {
  /* Old browsers */
  -webkit-box-align: baseline;
  -moz-box-align: baseline;
  box-align: baseline;
  /* Modern browsers */
  align-items: baseline;
}
.hbox.align-stretch,
.vbox.align-stretch,
.align-stretch {
  /* Old browsers */
  -webkit-box-align: stretch;
  -moz-box-align: stretch;
  box-align: stretch;
  /* Modern browsers */
  align-items: stretch;
}
div.error {
  margin: 2em;
  text-align: center;
}
div.error > h1 {
  font-size: 500%;
  line-height: normal;
}
div.error > p {
  font-size: 200%;
  line-height: normal;
}
div.traceback-wrapper {
  text-align: left;
  max-width: 800px;
  margin: auto;
}
div.traceback-wrapper pre.traceback {
  max-height: 600px;
  overflow: auto;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
body {
  background-color: #fff;
  /* This makes sure that the body covers the entire window and needs to
       be in a different element than the display: box in wrapper below */
  position: absolute;
  left: 0px;
  right: 0px;
  top: 0px;
  bottom: 0px;
  overflow: visible;
}
body > #header {
  /* Initially hidden to prevent FLOUC */
  display: none;
  background-color: #fff;
  /* Display over codemirror */
  position: relative;
  z-index: 100;
}
body > #header #header-container {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  padding: 5px;
  padding-bottom: 5px;
  padding-top: 5px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
body > #header .header-bar {
  width: 100%;
  height: 1px;
  background: #e7e7e7;
  margin-bottom: -1px;
}
@media print {
  body > #header {
    display: none !important;
  }
}
#header-spacer {
  width: 100%;
  visibility: hidden;
}
@media print {
  #header-spacer {
    display: none;
  }
}
#ipython_notebook {
  padding-left: 0px;
  padding-top: 1px;
  padding-bottom: 1px;
}
[dir="rtl"] #ipython_notebook {
  margin-right: 10px;
  margin-left: 0;
}
[dir="rtl"] #ipython_notebook.pull-left {
  float: right !important;
  float: right;
}
.flex-spacer {
  flex: 1;
}
#noscript {
  width: auto;
  padding-top: 16px;
  padding-bottom: 16px;
  text-align: center;
  font-size: 22px;
  color: red;
  font-weight: bold;
}
#ipython_notebook img {
  height: 28px;
}
#site {
  width: 100%;
  display: none;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  overflow: auto;
}
@media print {
  #site {
    height: auto !important;
  }
}
/* Smaller buttons */
.ui-button .ui-button-text {
  padding: 0.2em 0.8em;
  font-size: 77%;
}
input.ui-button {
  padding: 0.3em 0.9em;
}
span#kernel_logo_widget {
  margin: 0 10px;
}
span#login_widget {
  float: right;
}
[dir="rtl"] span#login_widget {
  float: left;
}
span#login_widget > .button,
#logout {
  color: #333;
  background-color: #fff;
  border-color: #ccc;
}
span#login_widget > .button:focus,
#logout:focus,
span#login_widget > .button.focus,
#logout.focus {
  color: #333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
span#login_widget > .button:hover,
#logout:hover {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
span#login_widget > .button:active,
#logout:active,
span#login_widget > .button.active,
#logout.active,
.open > .dropdown-togglespan#login_widget > .button,
.open > .dropdown-toggle#logout {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
span#login_widget > .button:active:hover,
#logout:active:hover,
span#login_widget > .button.active:hover,
#logout.active:hover,
.open > .dropdown-togglespan#login_widget > .button:hover,
.open > .dropdown-toggle#logout:hover,
span#login_widget > .button:active:focus,
#logout:active:focus,
span#login_widget > .button.active:focus,
#logout.active:focus,
.open > .dropdown-togglespan#login_widget > .button:focus,
.open > .dropdown-toggle#logout:focus,
span#login_widget > .button:active.focus,
#logout:active.focus,
span#login_widget > .button.active.focus,
#logout.active.focus,
.open > .dropdown-togglespan#login_widget > .button.focus,
.open > .dropdown-toggle#logout.focus {
  color: #333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
span#login_widget > .button:active,
#logout:active,
span#login_widget > .button.active,
#logout.active,
.open > .dropdown-togglespan#login_widget > .button,
.open > .dropdown-toggle#logout {
  background-image: none;
}
span#login_widget > .button.disabled:hover,
#logout.disabled:hover,
span#login_widget > .button[disabled]:hover,
#logout[disabled]:hover,
fieldset[disabled] span#login_widget > .button:hover,
fieldset[disabled] #logout:hover,
span#login_widget > .button.disabled:focus,
#logout.disabled:focus,
span#login_widget > .button[disabled]:focus,
#logout[disabled]:focus,
fieldset[disabled] span#login_widget > .button:focus,
fieldset[disabled] #logout:focus,
span#login_widget > .button.disabled.focus,
#logout.disabled.focus,
span#login_widget > .button[disabled].focus,
#logout[disabled].focus,
fieldset[disabled] span#login_widget > .button.focus,
fieldset[disabled] #logout.focus {
  background-color: #fff;
  border-color: #ccc;
}
span#login_widget > .button .badge,
#logout .badge {
  color: #fff;
  background-color: #333;
}
.nav-header {
  text-transform: none;
}
#header > span {
  margin-top: 10px;
}
.modal_stretch .modal-dialog {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  min-height: 80vh;
}
.modal_stretch .modal-dialog .modal-body {
  max-height: calc(100vh - 200px);
  overflow: auto;
  flex: 1;
}
.modal-header {
  cursor: move;
}
@media (min-width: 768px) {
  .modal .modal-dialog {
    width: 700px;
  }
}
@media (min-width: 768px) {
  select.form-control {
    margin-left: 12px;
    margin-right: 12px;
  }
}
/*!
*
* IPython auth
*
*/
.center-nav {
  display: inline-block;
  margin-bottom: -4px;
}
[dir="rtl"] .center-nav form.pull-left {
  float: right !important;
  float: right;
}
[dir="rtl"] .center-nav .navbar-text {
  float: right;
}
[dir="rtl"] .navbar-inner {
  text-align: right;
}
[dir="rtl"] div.text-left {
  text-align: right;
}
/*!
*
* IPython tree view
*
*/
/* We need an invisible input field on top of the sentense*/
/* "Drag file onto the list ..." */
.alternate_upload {
  background-color: none;
  display: inline;
}
.alternate_upload.form {
  padding: 0;
  margin: 0;
}
.alternate_upload input.fileinput {
  position: absolute;
  display: block;
  width: 100%;
  height: 100%;
  overflow: hidden;
  cursor: pointer;
  opacity: 0;
  z-index: 2;
}
.alternate_upload .btn-xs > input.fileinput {
  margin: -1px -5px;
}
.alternate_upload .btn-upload {
  position: relative;
  height: 22px;
}
::-webkit-file-upload-button {
  cursor: pointer;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
ul#tabs {
  margin-bottom: 4px;
}
ul#tabs a {
  padding-top: 6px;
  padding-bottom: 4px;
}
[dir="rtl"] ul#tabs.nav-tabs > li {
  float: right;
}
[dir="rtl"] ul#tabs.nav.nav-tabs {
  padding-right: 0;
}
ul.breadcrumb a:focus,
ul.breadcrumb a:hover {
  text-decoration: none;
}
ul.breadcrumb i.icon-home {
  font-size: 16px;
  margin-right: 4px;
}
ul.breadcrumb span {
  color: #5e5e5e;
}
.list_toolbar {
  padding: 4px 0 4px 0;
  vertical-align: middle;
}
.list_toolbar .tree-buttons {
  padding-top: 1px;
}
[dir="rtl"] .list_toolbar .tree-buttons .pull-right {
  float: left !important;
  float: left;
}
[dir="rtl"] .list_toolbar .col-sm-4,
[dir="rtl"] .list_toolbar .col-sm-8 {
  float: right;
}
.dynamic-buttons {
  padding-top: 3px;
  display: inline-block;
}
.list_toolbar [class*="span"] {
  min-height: 24px;
}
.list_header {
  font-weight: bold;
  background-color: #EEE;
}
.list_placeholder {
  font-weight: bold;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
}
.list_container {
  margin-top: 4px;
  margin-bottom: 20px;
  border: 1px solid #ddd;
  border-radius: 2px;
}
.list_container > div {
  border-bottom: 1px solid #ddd;
}
.list_container > div:hover .list-item {
  background-color: red;
}
.list_container > div:last-child {
  border: none;
}
.list_item:hover .list_item {
  background-color: #ddd;
}
.list_item a {
  text-decoration: none;
}
.list_item:hover {
  background-color: #fafafa;
}
.list_header > div,
.list_item > div {
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
  line-height: 22px;
}
.list_header > div input,
.list_item > div input {
  margin-right: 7px;
  margin-left: 14px;
  vertical-align: text-bottom;
  line-height: 22px;
  position: relative;
  top: -1px;
}
.list_header > div .item_link,
.list_item > div .item_link {
  margin-left: -1px;
  vertical-align: baseline;
  line-height: 22px;
}
[dir="rtl"] .list_item > div input {
  margin-right: 0;
}
.new-file input[type=checkbox] {
  visibility: hidden;
}
.item_name {
  line-height: 22px;
  height: 24px;
}
.item_icon {
  font-size: 14px;
  color: #5e5e5e;
  margin-right: 7px;
  margin-left: 7px;
  line-height: 22px;
  vertical-align: baseline;
}
.item_modified {
  margin-right: 7px;
  margin-left: 7px;
}
[dir="rtl"] .item_modified.pull-right {
  float: left !important;
  float: left;
}
.item_buttons {
  line-height: 1em;
  margin-left: -5px;
}
.item_buttons .btn,
.item_buttons .btn-group,
.item_buttons .input-group {
  float: left;
}
.item_buttons > .btn,
.item_buttons > .btn-group,
.item_buttons > .input-group {
  margin-left: 5px;
}
.item_buttons .btn {
  min-width: 13ex;
}
.item_buttons .running-indicator {
  padding-top: 4px;
  color: #5cb85c;
}
.item_buttons .kernel-name {
  padding-top: 4px;
  color: #5bc0de;
  margin-right: 7px;
  float: left;
}
[dir="rtl"] .item_buttons.pull-right {
  float: left !important;
  float: left;
}
[dir="rtl"] .item_buttons .kernel-name {
  margin-left: 7px;
  float: right;
}
.toolbar_info {
  height: 24px;
  line-height: 24px;
}
.list_item input:not([type=checkbox]) {
  padding-top: 3px;
  padding-bottom: 3px;
  height: 22px;
  line-height: 14px;
  margin: 0px;
}
.highlight_text {
  color: blue;
}
#project_name {
  display: inline-block;
  padding-left: 7px;
  margin-left: -2px;
}
#project_name > .breadcrumb {
  padding: 0px;
  margin-bottom: 0px;
  background-color: transparent;
  font-weight: bold;
}
.sort_button {
  display: inline-block;
  padding-left: 7px;
}
[dir="rtl"] .sort_button.pull-right {
  float: left !important;
  float: left;
}
#tree-selector {
  padding-right: 0px;
}
#button-select-all {
  min-width: 50px;
}
[dir="rtl"] #button-select-all.btn {
  float: right ;
}
#select-all {
  margin-left: 7px;
  margin-right: 2px;
  margin-top: 2px;
  height: 16px;
}
[dir="rtl"] #select-all.pull-left {
  float: right !important;
  float: right;
}
.menu_icon {
  margin-right: 2px;
}
.tab-content .row {
  margin-left: 0px;
  margin-right: 0px;
}
.folder_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f114";
}
.folder_icon:before.fa-pull-left {
  margin-right: .3em;
}
.folder_icon:before.fa-pull-right {
  margin-left: .3em;
}
.folder_icon:before.pull-left {
  margin-right: .3em;
}
.folder_icon:before.pull-right {
  margin-left: .3em;
}
.notebook_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f02d";
  position: relative;
  top: -1px;
}
.notebook_icon:before.fa-pull-left {
  margin-right: .3em;
}
.notebook_icon:before.fa-pull-right {
  margin-left: .3em;
}
.notebook_icon:before.pull-left {
  margin-right: .3em;
}
.notebook_icon:before.pull-right {
  margin-left: .3em;
}
.running_notebook_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f02d";
  position: relative;
  top: -1px;
  color: #5cb85c;
}
.running_notebook_icon:before.fa-pull-left {
  margin-right: .3em;
}
.running_notebook_icon:before.fa-pull-right {
  margin-left: .3em;
}
.running_notebook_icon:before.pull-left {
  margin-right: .3em;
}
.running_notebook_icon:before.pull-right {
  margin-left: .3em;
}
.file_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f016";
  position: relative;
  top: -2px;
}
.file_icon:before.fa-pull-left {
  margin-right: .3em;
}
.file_icon:before.fa-pull-right {
  margin-left: .3em;
}
.file_icon:before.pull-left {
  margin-right: .3em;
}
.file_icon:before.pull-right {
  margin-left: .3em;
}
#notebook_toolbar .pull-right {
  padding-top: 0px;
  margin-right: -1px;
}
ul#new-menu {
  left: auto;
  right: 0;
}
#new-menu .dropdown-header {
  font-size: 10px;
  border-bottom: 1px solid #e5e5e5;
  padding: 0 0 3px;
  margin: -3px 20px 0;
}
.kernel-menu-icon {
  padding-right: 12px;
  width: 24px;
  content: "\f096";
}
.kernel-menu-icon:before {
  content: "\f096";
}
.kernel-menu-icon-current:before {
  content: "\f00c";
}
#tab_content {
  padding-top: 20px;
}
#running .panel-group .panel {
  margin-top: 3px;
  margin-bottom: 1em;
}
#running .panel-group .panel .panel-heading {
  background-color: #EEE;
  padding-top: 4px;
  padding-bottom: 4px;
  padding-left: 7px;
  padding-right: 7px;
  line-height: 22px;
}
#running .panel-group .panel .panel-heading a:focus,
#running .panel-group .panel .panel-heading a:hover {
  text-decoration: none;
}
#running .panel-group .panel .panel-body {
  padding: 0px;
}
#running .panel-group .panel .panel-body .list_container {
  margin-top: 0px;
  margin-bottom: 0px;
  border: 0px;
  border-radius: 0px;
}
#running .panel-group .panel .panel-body .list_container .list_item {
  border-bottom: 1px solid #ddd;
}
#running .panel-group .panel .panel-body .list_container .list_item:last-child {
  border-bottom: 0px;
}
.delete-button {
  display: none;
}
.duplicate-button {
  display: none;
}
.rename-button {
  display: none;
}
.move-button {
  display: none;
}
.download-button {
  display: none;
}
.shutdown-button {
  display: none;
}
.dynamic-instructions {
  display: inline-block;
  padding-top: 4px;
}
/*!
*
* IPython text editor webapp
*
*/
.selected-keymap i.fa {
  padding: 0px 5px;
}
.selected-keymap i.fa:before {
  content: "\f00c";
}
#mode-menu {
  overflow: auto;
  max-height: 20em;
}
.edit_app #header {
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
.edit_app #menubar .navbar {
  /* Use a negative 1 bottom margin, so the border overlaps the border of the
    header */
  margin-bottom: -1px;
}
.dirty-indicator {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator.fa-pull-right {
  margin-left: .3em;
}
.dirty-indicator.pull-left {
  margin-right: .3em;
}
.dirty-indicator.pull-right {
  margin-left: .3em;
}
.dirty-indicator-dirty {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator-dirty.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator-dirty.fa-pull-right {
  margin-left: .3em;
}
.dirty-indicator-dirty.pull-left {
  margin-right: .3em;
}
.dirty-indicator-dirty.pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  width: 20px;
}
.dirty-indicator-clean.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean.fa-pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean.pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean.pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f00c";
}
.dirty-indicator-clean:before.fa-pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean:before.fa-pull-right {
  margin-left: .3em;
}
.dirty-indicator-clean:before.pull-left {
  margin-right: .3em;
}
.dirty-indicator-clean:before.pull-right {
  margin-left: .3em;
}
#filename {
  font-size: 16pt;
  display: table;
  padding: 0px 5px;
}
#current-mode {
  padding-left: 5px;
  padding-right: 5px;
}
#texteditor-backdrop {
  padding-top: 20px;
  padding-bottom: 20px;
}
@media not print {
  #texteditor-backdrop {
    background-color: #EEE;
  }
}
@media print {
  #texteditor-backdrop #texteditor-container .CodeMirror-gutter,
  #texteditor-backdrop #texteditor-container .CodeMirror-gutters {
    background-color: #fff;
  }
}
@media not print {
  #texteditor-backdrop #texteditor-container .CodeMirror-gutter,
  #texteditor-backdrop #texteditor-container .CodeMirror-gutters {
    background-color: #fff;
  }
}
@media not print {
  #texteditor-backdrop #texteditor-container {
    padding: 0px;
    background-color: #fff;
    -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
    box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  }
}
.CodeMirror-dialog {
  background-color: #fff;
}
/*!
*
* IPython notebook
*
*/
/* CSS font colors for translated ANSI escape sequences */
/* The color values are a mix of
   http://www.xcolors.net/dl/baskerville-ivorylight and
   http://www.xcolors.net/dl/euphrasia */
.ansi-black-fg {
  color: #3E424D;
}
.ansi-black-bg {
  background-color: #3E424D;
}
.ansi-black-intense-fg {
  color: #282C36;
}
.ansi-black-intense-bg {
  background-color: #282C36;
}
.ansi-red-fg {
  color: #E75C58;
}
.ansi-red-bg {
  background-color: #E75C58;
}
.ansi-red-intense-fg {
  color: #B22B31;
}
.ansi-red-intense-bg {
  background-color: #B22B31;
}
.ansi-green-fg {
  color: #00A250;
}
.ansi-green-bg {
  background-color: #00A250;
}
.ansi-green-intense-fg {
  color: #007427;
}
.ansi-green-intense-bg {
  background-color: #007427;
}
.ansi-yellow-fg {
  color: #DDB62B;
}
.ansi-yellow-bg {
  background-color: #DDB62B;
}
.ansi-yellow-intense-fg {
  color: #B27D12;
}
.ansi-yellow-intense-bg {
  background-color: #B27D12;
}
.ansi-blue-fg {
  color: #208FFB;
}
.ansi-blue-bg {
  background-color: #208FFB;
}
.ansi-blue-intense-fg {
  color: #0065CA;
}
.ansi-blue-intense-bg {
  background-color: #0065CA;
}
.ansi-magenta-fg {
  color: #D160C4;
}
.ansi-magenta-bg {
  background-color: #D160C4;
}
.ansi-magenta-intense-fg {
  color: #A03196;
}
.ansi-magenta-intense-bg {
  background-color: #A03196;
}
.ansi-cyan-fg {
  color: #60C6C8;
}
.ansi-cyan-bg {
  background-color: #60C6C8;
}
.ansi-cyan-intense-fg {
  color: #258F8F;
}
.ansi-cyan-intense-bg {
  background-color: #258F8F;
}
.ansi-white-fg {
  color: #C5C1B4;
}
.ansi-white-bg {
  background-color: #C5C1B4;
}
.ansi-white-intense-fg {
  color: #A1A6B2;
}
.ansi-white-intense-bg {
  background-color: #A1A6B2;
}
.ansi-default-inverse-fg {
  color: #FFFFFF;
}
.ansi-default-inverse-bg {
  background-color: #000000;
}
.ansi-bold {
  font-weight: bold;
}
.ansi-underline {
  text-decoration: underline;
}
/* The following styles are deprecated an will be removed in a future version */
.ansibold {
  font-weight: bold;
}
.ansi-inverse {
  outline: 0.5px dotted;
}
/* use dark versions for foreground, to improve visibility */
.ansiblack {
  color: black;
}
.ansired {
  color: darkred;
}
.ansigreen {
  color: darkgreen;
}
.ansiyellow {
  color: #c4a000;
}
.ansiblue {
  color: darkblue;
}
.ansipurple {
  color: darkviolet;
}
.ansicyan {
  color: steelblue;
}
.ansigray {
  color: gray;
}
/* and light for background, for the same reason */
.ansibgblack {
  background-color: black;
}
.ansibgred {
  background-color: red;
}
.ansibggreen {
  background-color: green;
}
.ansibgyellow {
  background-color: yellow;
}
.ansibgblue {
  background-color: blue;
}
.ansibgpurple {
  background-color: magenta;
}
.ansibgcyan {
  background-color: cyan;
}
.ansibggray {
  background-color: gray;
}
div.cell {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  border-radius: 2px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  border-width: 1px;
  border-style: solid;
  border-color: transparent;
  width: 100%;
  padding: 5px;
  /* This acts as a spacer between cells, that is outside the border */
  margin: 0px;
  outline: none;
  position: relative;
  overflow: visible;
}
div.cell:before {
  position: absolute;
  display: block;
  top: -1px;
  left: -1px;
  width: 5px;
  height: calc(100% +  2px);
  content: '';
  background: transparent;
}
div.cell.jupyter-soft-selected {
  border-left-color: #E3F2FD;
  border-left-width: 1px;
  padding-left: 5px;
  border-right-color: #E3F2FD;
  border-right-width: 1px;
  background: #E3F2FD;
}
@media print {
  div.cell.jupyter-soft-selected {
    border-color: transparent;
  }
}
div.cell.selected,
div.cell.selected.jupyter-soft-selected {
  border-color: #ababab;
}
div.cell.selected:before,
div.cell.selected.jupyter-soft-selected:before {
  position: absolute;
  display: block;
  top: -1px;
  left: -1px;
  width: 5px;
  height: calc(100% +  2px);
  content: '';
  background: #42A5F5;
}
@media print {
  div.cell.selected,
  div.cell.selected.jupyter-soft-selected {
    border-color: transparent;
  }
}
.edit_mode div.cell.selected {
  border-color: #66BB6A;
}
.edit_mode div.cell.selected:before {
  position: absolute;
  display: block;
  top: -1px;
  left: -1px;
  width: 5px;
  height: calc(100% +  2px);
  content: '';
  background: #66BB6A;
}
@media print {
  .edit_mode div.cell.selected {
    border-color: transparent;
  }
}
.prompt {
  /* This needs to be wide enough for 3 digit prompt numbers: In[100]: */
  min-width: 14ex;
  /* This padding is tuned to match the padding on the CodeMirror editor. */
  padding: 0.4em;
  margin: 0px;
  font-family: monospace;
  text-align: right;
  /* This has to match that of the the CodeMirror class line-height below */
  line-height: 1.21429em;
  /* Don't highlight prompt number selection */
  -webkit-touch-callout: none;
  -webkit-user-select: none;
  -khtml-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  /* Use default cursor */
  cursor: default;
}
@media (max-width: 540px) {
  .prompt {
    text-align: left;
  }
}
div.inner_cell {
  min-width: 0;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
/* input_area and input_prompt must match in top border and margin for alignment */
div.input_area {
  border: 1px solid #cfcfcf;
  border-radius: 2px;
  background: #f7f7f7;
  line-height: 1.21429em;
}
/* This is needed so that empty prompt areas can collapse to zero height when there
   is no content in the output_subarea and the prompt. The main purpose of this is
   to make sure that empty JavaScript output_subareas have no height. */
div.prompt:empty {
  padding-top: 0;
  padding-bottom: 0;
}
div.unrecognized_cell {
  padding: 5px 5px 5px 0px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
div.unrecognized_cell .inner_cell {
  border-radius: 2px;
  padding: 5px;
  font-weight: bold;
  color: red;
  border: 1px solid #cfcfcf;
  background: #eaeaea;
}
div.unrecognized_cell .inner_cell a {
  color: inherit;
  text-decoration: none;
}
div.unrecognized_cell .inner_cell a:hover {
  color: inherit;
  text-decoration: none;
}
@media (max-width: 540px) {
  div.unrecognized_cell > div.prompt {
    display: none;
  }
}
div.code_cell {
  /* avoid page breaking on code cells when printing */
}
@media print {
  div.code_cell {
    page-break-inside: avoid;
  }
}
/* any special styling for code cells that are currently running goes here */
div.input {
  page-break-inside: avoid;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
@media (max-width: 540px) {
  div.input {
    /* Old browsers */
    display: -webkit-box;
    -webkit-box-orient: vertical;
    -webkit-box-align: stretch;
    display: -moz-box;
    -moz-box-orient: vertical;
    -moz-box-align: stretch;
    display: box;
    box-orient: vertical;
    box-align: stretch;
    /* Modern browsers */
    display: flex;
    flex-direction: column;
    align-items: stretch;
  }
}
/* input_area and input_prompt must match in top border and margin for alignment */
div.input_prompt {
  color: #303F9F;
  border-top: 1px solid transparent;
}
div.input_area > div.highlight {
  margin: 0.4em;
  border: none;
  padding: 0px;
  background-color: transparent;
}
div.input_area > div.highlight > pre {
  margin: 0px;
  border: none;
  padding: 0px;
  background-color: transparent;
}
/* The following gets added to the <head> if it is detected that the user has a
 * monospace font with inconsistent normal/bold/italic height.  See
 * notebookmain.js.  Such fonts will have keywords vertically offset with
 * respect to the rest of the text.  The user should select a better font.
 * See: https://github.com/ipython/ipython/issues/1503
 *
 * .CodeMirror span {
 *      vertical-align: bottom;
 * }
 */
.CodeMirror {
  line-height: 1.21429em;
  /* Changed from 1em to our global default */
  font-size: 14px;
  height: auto;
  /* Changed to auto to autogrow */
  background: none;
  /* Changed from white to allow our bg to show through */
}
.CodeMirror-scroll {
  /*  The CodeMirror docs are a bit fuzzy on if overflow-y should be hidden or visible.*/
  /*  We have found that if it is visible, vertical scrollbars appear with font size changes.*/
  overflow-y: hidden;
  overflow-x: auto;
}
.CodeMirror-lines {
  /* In CM2, this used to be 0.4em, but in CM3 it went to 4px. We need the em value because */
  /* we have set a different line-height and want this to scale with that. */
  /* Note that this should set vertical padding only, since CodeMirror assumes
       that horizontal padding will be set on CodeMirror pre */
  padding: 0.4em 0;
}
.CodeMirror-linenumber {
  padding: 0 8px 0 4px;
}
.CodeMirror-gutters {
  border-bottom-left-radius: 2px;
  border-top-left-radius: 2px;
}
.CodeMirror pre {
  /* In CM3 this went to 4px from 0 in CM2. This sets horizontal padding only,
    use .CodeMirror-lines for vertical */
  padding: 0 0.4em;
  border: 0;
  border-radius: 0;
}
.CodeMirror-cursor {
  border-left: 1.4px solid black;
}
@media screen and (min-width: 2138px) and (max-width: 4319px) {
  .CodeMirror-cursor {
    border-left: 2px solid black;
  }
}
@media screen and (min-width: 4320px) {
  .CodeMirror-cursor {
    border-left: 4px solid black;
  }
}
/*

Original style from softwaremaniacs.org (c) Ivan Sagalaev <Maniac@SoftwareManiacs.Org>
Adapted from GitHub theme

*/
.highlight-base {
  color: #000;
}
.highlight-variable {
  color: #000;
}
.highlight-variable-2 {
  color: #1a1a1a;
}
.highlight-variable-3 {
  color: #333333;
}
.highlight-string {
  color: #BA2121;
}
.highlight-comment {
  color: #408080;
  font-style: italic;
}
.highlight-number {
  color: #080;
}
.highlight-atom {
  color: #88F;
}
.highlight-keyword {
  color: #008000;
  font-weight: bold;
}
.highlight-builtin {
  color: #008000;
}
.highlight-error {
  color: #f00;
}
.highlight-operator {
  color: #AA22FF;
  font-weight: bold;
}
.highlight-meta {
  color: #AA22FF;
}
/* previously not defined, copying from default codemirror */
.highlight-def {
  color: #00f;
}
.highlight-string-2 {
  color: #f50;
}
.highlight-qualifier {
  color: #555;
}
.highlight-bracket {
  color: #997;
}
.highlight-tag {
  color: #170;
}
.highlight-attribute {
  color: #00c;
}
.highlight-header {
  color: blue;
}
.highlight-quote {
  color: #090;
}
.highlight-link {
  color: #00c;
}
/* apply the same style to codemirror */
.cm-s-ipython span.cm-keyword {
  color: #008000;
  font-weight: bold;
}
.cm-s-ipython span.cm-atom {
  color: #88F;
}
.cm-s-ipython span.cm-number {
  color: #080;
}
.cm-s-ipython span.cm-def {
  color: #00f;
}
.cm-s-ipython span.cm-variable {
  color: #000;
}
.cm-s-ipython span.cm-operator {
  color: #AA22FF;
  font-weight: bold;
}
.cm-s-ipython span.cm-variable-2 {
  color: #1a1a1a;
}
.cm-s-ipython span.cm-variable-3 {
  color: #333333;
}
.cm-s-ipython span.cm-comment {
  color: #408080;
  font-style: italic;
}
.cm-s-ipython span.cm-string {
  color: #BA2121;
}
.cm-s-ipython span.cm-string-2 {
  color: #f50;
}
.cm-s-ipython span.cm-meta {
  color: #AA22FF;
}
.cm-s-ipython span.cm-qualifier {
  color: #555;
}
.cm-s-ipython span.cm-builtin {
  color: #008000;
}
.cm-s-ipython span.cm-bracket {
  color: #997;
}
.cm-s-ipython span.cm-tag {
  color: #170;
}
.cm-s-ipython span.cm-attribute {
  color: #00c;
}
.cm-s-ipython span.cm-header {
  color: blue;
}
.cm-s-ipython span.cm-quote {
  color: #090;
}
.cm-s-ipython span.cm-link {
  color: #00c;
}
.cm-s-ipython span.cm-error {
  color: #f00;
}
.cm-s-ipython span.cm-tab {
  background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAMCAYAAAAkuj5RAAAAAXNSR0IArs4c6QAAAGFJREFUSMft1LsRQFAQheHPowAKoACx3IgEKtaEHujDjORSgWTH/ZOdnZOcM/sgk/kFFWY0qV8foQwS4MKBCS3qR6ixBJvElOobYAtivseIE120FaowJPN75GMu8j/LfMwNjh4HUpwg4LUAAAAASUVORK5CYII=);
  background-position: right;
  background-repeat: no-repeat;
}
div.output_wrapper {
  /* this position must be relative to enable descendents to be absolute within it */
  position: relative;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
  z-index: 1;
}
/* class for the output area when it should be height-limited */
div.output_scroll {
  /* ideally, this would be max-height, but FF barfs all over that */
  height: 24em;
  /* FF needs this *and the wrapper* to specify full width, or it will shrinkwrap */
  width: 100%;
  overflow: auto;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 2px 8px rgba(0, 0, 0, 0.8);
  box-shadow: inset 0 2px 8px rgba(0, 0, 0, 0.8);
  display: block;
}
/* output div while it is collapsed */
div.output_collapsed {
  margin: 0px;
  padding: 0px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
div.out_prompt_overlay {
  height: 100%;
  padding: 0px 0.4em;
  position: absolute;
  border-radius: 2px;
}
div.out_prompt_overlay:hover {
  /* use inner shadow to get border that is computed the same on WebKit/FF */
  -webkit-box-shadow: inset 0 0 1px #000;
  box-shadow: inset 0 0 1px #000;
  background: rgba(240, 240, 240, 0.5);
}
div.output_prompt {
  color: #D84315;
}
/* This class is the outer container of all output sections. */
div.output_area {
  padding: 0px;
  page-break-inside: avoid;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
div.output_area .MathJax_Display {
  text-align: left !important;
}
div.output_area .rendered_html table {
  margin-left: 0;
  margin-right: 0;
}
div.output_area .rendered_html img {
  margin-left: 0;
  margin-right: 0;
}
div.output_area img,
div.output_area svg {
  max-width: 100%;
  height: auto;
}
div.output_area img.unconfined,
div.output_area svg.unconfined {
  max-width: none;
}
div.output_area .mglyph > img {
  max-width: none;
}
/* This is needed to protect the pre formating from global settings such
   as that of bootstrap */
.output {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: vertical;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: vertical;
  -moz-box-align: stretch;
  display: box;
  box-orient: vertical;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: column;
  align-items: stretch;
}
@media (max-width: 540px) {
  div.output_area {
    /* Old browsers */
    display: -webkit-box;
    -webkit-box-orient: vertical;
    -webkit-box-align: stretch;
    display: -moz-box;
    -moz-box-orient: vertical;
    -moz-box-align: stretch;
    display: box;
    box-orient: vertical;
    box-align: stretch;
    /* Modern browsers */
    display: flex;
    flex-direction: column;
    align-items: stretch;
  }
}
div.output_area pre {
  margin: 0;
  padding: 1px 0 1px 0;
  border: 0;
  vertical-align: baseline;
  color: black;
  background-color: transparent;
  border-radius: 0;
}
/* This class is for the output subarea inside the output_area and after
   the prompt div. */
div.output_subarea {
  overflow-x: auto;
  padding: 0.4em;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
  max-width: calc(100% - 14ex);
}
div.output_scroll div.output_subarea {
  overflow-x: visible;
}
/* The rest of the output_* classes are for special styling of the different
   output types */
/* all text output has this class: */
div.output_text {
  text-align: left;
  color: #000;
  /* This has to match that of the the CodeMirror class line-height below */
  line-height: 1.21429em;
}
/* stdout/stderr are 'text' as well as 'stream', but execute_result/error are *not* streams */
div.output_stderr {
  background: #fdd;
  /* very light red background for stderr */
}
div.output_latex {
  text-align: left;
}
/* Empty output_javascript divs should have no height */
div.output_javascript:empty {
  padding: 0;
}
.js-error {
  color: darkred;
}
/* raw_input styles */
div.raw_input_container {
  line-height: 1.21429em;
  padding-top: 5px;
}
pre.raw_input_prompt {
  /* nothing needed here. */
}
input.raw_input {
  font-family: monospace;
  font-size: inherit;
  color: inherit;
  width: auto;
  /* make sure input baseline aligns with prompt */
  vertical-align: baseline;
  /* padding + margin = 0.5em between prompt and cursor */
  padding: 0em 0.25em;
  margin: 0em 0.25em;
}
input.raw_input:focus {
  box-shadow: none;
}
p.p-space {
  margin-bottom: 10px;
}
div.output_unrecognized {
  padding: 5px;
  font-weight: bold;
  color: red;
}
div.output_unrecognized a {
  color: inherit;
  text-decoration: none;
}
div.output_unrecognized a:hover {
  color: inherit;
  text-decoration: none;
}
.rendered_html {
  color: #000;
  /* any extras will just be numbers: */
}
.rendered_html em {
  font-style: italic;
}
.rendered_html strong {
  font-weight: bold;
}
.rendered_html u {
  text-decoration: underline;
}
.rendered_html :link {
  text-decoration: underline;
}
.rendered_html :visited {
  text-decoration: underline;
}
.rendered_html h1 {
  font-size: 185.7%;
  margin: 1.08em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h2 {
  font-size: 157.1%;
  margin: 1.27em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h3 {
  font-size: 128.6%;
  margin: 1.55em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h4 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
}
.rendered_html h5 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
  font-style: italic;
}
.rendered_html h6 {
  font-size: 100%;
  margin: 2em 0 0 0;
  font-weight: bold;
  line-height: 1.0;
  font-style: italic;
}
.rendered_html h1:first-child {
  margin-top: 0.538em;
}
.rendered_html h2:first-child {
  margin-top: 0.636em;
}
.rendered_html h3:first-child {
  margin-top: 0.777em;
}
.rendered_html h4:first-child {
  margin-top: 1em;
}
.rendered_html h5:first-child {
  margin-top: 1em;
}
.rendered_html h6:first-child {
  margin-top: 1em;
}
.rendered_html ul:not(.list-inline),
.rendered_html ol:not(.list-inline) {
  padding-left: 2em;
}
.rendered_html ul {
  list-style: disc;
}
.rendered_html ul ul {
  list-style: square;
  margin-top: 0;
}
.rendered_html ul ul ul {
  list-style: circle;
}
.rendered_html ol {
  list-style: decimal;
}
.rendered_html ol ol {
  list-style: upper-alpha;
  margin-top: 0;
}
.rendered_html ol ol ol {
  list-style: lower-alpha;
}
.rendered_html ol ol ol ol {
  list-style: lower-roman;
}
.rendered_html ol ol ol ol ol {
  list-style: decimal;
}
.rendered_html * + ul {
  margin-top: 1em;
}
.rendered_html * + ol {
  margin-top: 1em;
}
.rendered_html hr {
  color: black;
  background-color: black;
}
.rendered_html pre {
  margin: 1em 2em;
  padding: 0px;
  background-color: #fff;
}
.rendered_html code {
  background-color: #eff0f1;
}
.rendered_html p code {
  padding: 1px 5px;
}
.rendered_html pre code {
  background-color: #fff;
}
.rendered_html pre,
.rendered_html code {
  border: 0;
  color: #000;
  font-size: 100%;
}
.rendered_html blockquote {
  margin: 1em 2em;
}
.rendered_html table {
  margin-left: auto;
  margin-right: auto;
  border: none;
  border-collapse: collapse;
  border-spacing: 0;
  color: black;
  font-size: 12px;
  table-layout: fixed;
}
.rendered_html thead {
  border-bottom: 1px solid black;
  vertical-align: bottom;
}
.rendered_html tr,
.rendered_html th,
.rendered_html td {
  text-align: right;
  vertical-align: middle;
  padding: 0.5em 0.5em;
  line-height: normal;
  white-space: normal;
  max-width: none;
  border: none;
}
.rendered_html th {
  font-weight: bold;
}
.rendered_html tbody tr:nth-child(odd) {
  background: #f5f5f5;
}
.rendered_html tbody tr:hover {
  background: rgba(66, 165, 245, 0.2);
}
.rendered_html * + table {
  margin-top: 1em;
}
.rendered_html p {
  text-align: left;
}
.rendered_html * + p {
  margin-top: 1em;
}
.rendered_html img {
  display: block;
  margin-left: auto;
  margin-right: auto;
}
.rendered_html * + img {
  margin-top: 1em;
}
.rendered_html img,
.rendered_html svg {
  max-width: 100%;
  height: auto;
}
.rendered_html img.unconfined,
.rendered_html svg.unconfined {
  max-width: none;
}
.rendered_html .alert {
  margin-bottom: initial;
}
.rendered_html * + .alert {
  margin-top: 1em;
}
[dir="rtl"] .rendered_html p {
  text-align: right;
}
div.text_cell {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
}
@media (max-width: 540px) {
  div.text_cell > div.prompt {
    display: none;
  }
}
div.text_cell_render {
  /*font-family: "Helvetica Neue", Arial, Helvetica, Geneva, sans-serif;*/
  outline: none;
  resize: none;
  width: inherit;
  border-style: none;
  padding: 0.5em 0.5em 0.5em 0.4em;
  color: #000;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
a.anchor-link:link {
  text-decoration: none;
  padding: 0px 20px;
  visibility: hidden;
}
h1:hover .anchor-link,
h2:hover .anchor-link,
h3:hover .anchor-link,
h4:hover .anchor-link,
h5:hover .anchor-link,
h6:hover .anchor-link {
  visibility: visible;
}
.text_cell.rendered .input_area {
  display: none;
}
.text_cell.rendered .rendered_html {
  overflow-x: auto;
  overflow-y: hidden;
}
.text_cell.rendered .rendered_html tr,
.text_cell.rendered .rendered_html th,
.text_cell.rendered .rendered_html td {
  max-width: none;
}
.text_cell.unrendered .text_cell_render {
  display: none;
}
.text_cell .dropzone .input_area {
  border: 2px dashed #bababa;
  margin: -1px;
}
.cm-header-1,
.cm-header-2,
.cm-header-3,
.cm-header-4,
.cm-header-5,
.cm-header-6 {
  font-weight: bold;
  font-family: "Helvetica Neue", Helvetica, Arial, sans-serif;
}
.cm-header-1 {
  font-size: 185.7%;
}
.cm-header-2 {
  font-size: 157.1%;
}
.cm-header-3 {
  font-size: 128.6%;
}
.cm-header-4 {
  font-size: 110%;
}
.cm-header-5 {
  font-size: 100%;
  font-style: italic;
}
.cm-header-6 {
  font-size: 100%;
  font-style: italic;
}
/*!
*
* IPython notebook webapp
*
*/
@media (max-width: 767px) {
  .notebook_app {
    padding-left: 0px;
    padding-right: 0px;
  }
}
#ipython-main-app {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  height: 100%;
}
div#notebook_panel {
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  height: 100%;
}
div#notebook {
  font-size: 14px;
  line-height: 20px;
  overflow-y: hidden;
  overflow-x: auto;
  width: 100%;
  /* This spaces the page away from the edge of the notebook area */
  padding-top: 20px;
  margin: 0px;
  outline: none;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  min-height: 100%;
}
@media not print {
  #notebook-container {
    padding: 15px;
    background-color: #fff;
    min-height: 0;
    -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
    box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  }
}
@media print {
  #notebook-container {
    width: 100%;
  }
}
div.ui-widget-content {
  border: 1px solid #ababab;
  outline: none;
}
pre.dialog {
  background-color: #f7f7f7;
  border: 1px solid #ddd;
  border-radius: 2px;
  padding: 0.4em;
  padding-left: 2em;
}
p.dialog {
  padding: 0.2em;
}
/* Word-wrap output correctly.  This is the CSS3 spelling, though Firefox seems
   to not honor it correctly.  Webkit browsers (Chrome, rekonq, Safari) do.
 */
pre,
code,
kbd,
samp {
  white-space: pre-wrap;
}
#fonttest {
  font-family: monospace;
}
p {
  margin-bottom: 0;
}
.end_space {
  min-height: 100px;
  transition: height .2s ease;
}
.notebook_app > #header {
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
@media not print {
  .notebook_app {
    background-color: #EEE;
  }
}
kbd {
  border-style: solid;
  border-width: 1px;
  box-shadow: none;
  margin: 2px;
  padding-left: 2px;
  padding-right: 2px;
  padding-top: 1px;
  padding-bottom: 1px;
}
.jupyter-keybindings {
  padding: 1px;
  line-height: 24px;
  border-bottom: 1px solid gray;
}
.jupyter-keybindings input {
  margin: 0;
  padding: 0;
  border: none;
}
.jupyter-keybindings i {
  padding: 6px;
}
.well code {
  background-color: #ffffff;
  border-color: #ababab;
  border-width: 1px;
  border-style: solid;
  padding: 2px;
  padding-top: 1px;
  padding-bottom: 1px;
}
/* CSS for the cell toolbar */
.celltoolbar {
  border: thin solid #CFCFCF;
  border-bottom: none;
  background: #EEE;
  border-radius: 2px 2px 0px 0px;
  width: 100%;
  height: 29px;
  padding-right: 4px;
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
  /* Old browsers */
  -webkit-box-pack: end;
  -moz-box-pack: end;
  box-pack: end;
  /* Modern browsers */
  justify-content: flex-end;
  display: -webkit-flex;
}
@media print {
  .celltoolbar {
    display: none;
  }
}
.ctb_hideshow {
  display: none;
  vertical-align: bottom;
}
/* ctb_show is added to the ctb_hideshow div to show the cell toolbar.
   Cell toolbars are only shown when the ctb_global_show class is also set.
*/
.ctb_global_show .ctb_show.ctb_hideshow {
  display: block;
}
.ctb_global_show .ctb_show + .input_area,
.ctb_global_show .ctb_show + div.text_cell_input,
.ctb_global_show .ctb_show ~ div.text_cell_render {
  border-top-right-radius: 0px;
  border-top-left-radius: 0px;
}
.ctb_global_show .ctb_show ~ div.text_cell_render {
  border: 1px solid #cfcfcf;
}
.celltoolbar {
  font-size: 87%;
  padding-top: 3px;
}
.celltoolbar select {
  display: block;
  width: 100%;
  height: 32px;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
  background-color: #fff;
  background-image: none;
  border: 1px solid #ccc;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
  width: inherit;
  font-size: inherit;
  height: 22px;
  padding: 0px;
  display: inline-block;
}
.celltoolbar select:focus {
  border-color: #66afe9;
  outline: 0;
  -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
  box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
}
.celltoolbar select::-moz-placeholder {
  color: #999;
  opacity: 1;
}
.celltoolbar select:-ms-input-placeholder {
  color: #999;
}
.celltoolbar select::-webkit-input-placeholder {
  color: #999;
}
.celltoolbar select::-ms-expand {
  border: 0;
  background-color: transparent;
}
.celltoolbar select[disabled],
.celltoolbar select[readonly],
fieldset[disabled] .celltoolbar select {
  background-color: #eeeeee;
  opacity: 1;
}
.celltoolbar select[disabled],
fieldset[disabled] .celltoolbar select {
  cursor: not-allowed;
}
textarea.celltoolbar select {
  height: auto;
}
select.celltoolbar select {
  height: 30px;
  line-height: 30px;
}
textarea.celltoolbar select,
select[multiple].celltoolbar select {
  height: auto;
}
.celltoolbar label {
  margin-left: 5px;
  margin-right: 5px;
}
.tags_button_container {
  width: 100%;
  display: flex;
}
.tag-container {
  display: flex;
  flex-direction: row;
  flex-grow: 1;
  overflow: hidden;
  position: relative;
}
.tag-container > * {
  margin: 0 4px;
}
.remove-tag-btn {
  margin-left: 4px;
}
.tags-input {
  display: flex;
}
.cell-tag:last-child:after {
  content: "";
  position: absolute;
  right: 0;
  width: 40px;
  height: 100%;
  /* Fade to background color of cell toolbar */
  background: linear-gradient(to right, rgba(0, 0, 0, 0), #EEE);
}
.tags-input > * {
  margin-left: 4px;
}
.cell-tag,
.tags-input input,
.tags-input button {
  display: block;
  width: 100%;
  height: 32px;
  padding: 6px 12px;
  font-size: 13px;
  line-height: 1.42857143;
  color: #555555;
  background-color: #fff;
  background-image: none;
  border: 1px solid #ccc;
  border-radius: 2px;
  -webkit-box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  box-shadow: inset 0 1px 1px rgba(0, 0, 0, 0.075);
  -webkit-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  -o-transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  transition: border-color ease-in-out .15s, box-shadow ease-in-out .15s;
  height: 30px;
  padding: 5px 10px;
  font-size: 12px;
  line-height: 1.5;
  border-radius: 1px;
  box-shadow: none;
  width: inherit;
  font-size: inherit;
  height: 22px;
  line-height: 22px;
  padding: 0px 4px;
  display: inline-block;
}
.cell-tag:focus,
.tags-input input:focus,
.tags-input button:focus {
  border-color: #66afe9;
  outline: 0;
  -webkit-box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
  box-shadow: inset 0 1px 1px rgba(0,0,0,.075), 0 0 8px rgba(102, 175, 233, 0.6);
}
.cell-tag::-moz-placeholder,
.tags-input input::-moz-placeholder,
.tags-input button::-moz-placeholder {
  color: #999;
  opacity: 1;
}
.cell-tag:-ms-input-placeholder,
.tags-input input:-ms-input-placeholder,
.tags-input button:-ms-input-placeholder {
  color: #999;
}
.cell-tag::-webkit-input-placeholder,
.tags-input input::-webkit-input-placeholder,
.tags-input button::-webkit-input-placeholder {
  color: #999;
}
.cell-tag::-ms-expand,
.tags-input input::-ms-expand,
.tags-input button::-ms-expand {
  border: 0;
  background-color: transparent;
}
.cell-tag[disabled],
.tags-input input[disabled],
.tags-input button[disabled],
.cell-tag[readonly],
.tags-input input[readonly],
.tags-input button[readonly],
fieldset[disabled] .cell-tag,
fieldset[disabled] .tags-input input,
fieldset[disabled] .tags-input button {
  background-color: #eeeeee;
  opacity: 1;
}
.cell-tag[disabled],
.tags-input input[disabled],
.tags-input button[disabled],
fieldset[disabled] .cell-tag,
fieldset[disabled] .tags-input input,
fieldset[disabled] .tags-input button {
  cursor: not-allowed;
}
textarea.cell-tag,
textarea.tags-input input,
textarea.tags-input button {
  height: auto;
}
select.cell-tag,
select.tags-input input,
select.tags-input button {
  height: 30px;
  line-height: 30px;
}
textarea.cell-tag,
textarea.tags-input input,
textarea.tags-input button,
select[multiple].cell-tag,
select[multiple].tags-input input,
select[multiple].tags-input button {
  height: auto;
}
.cell-tag,
.tags-input button {
  padding: 0px 4px;
}
.cell-tag {
  background-color: #fff;
  white-space: nowrap;
}
.tags-input input[type=text]:focus {
  outline: none;
  box-shadow: none;
  border-color: #ccc;
}
.completions {
  position: absolute;
  z-index: 110;
  overflow: hidden;
  border: 1px solid #ababab;
  border-radius: 2px;
  -webkit-box-shadow: 0px 6px 10px -1px #adadad;
  box-shadow: 0px 6px 10px -1px #adadad;
  line-height: 1;
}
.completions select {
  background: white;
  outline: none;
  border: none;
  padding: 0px;
  margin: 0px;
  overflow: auto;
  font-family: monospace;
  font-size: 110%;
  color: #000;
  width: auto;
}
.completions select option.context {
  color: #286090;
}
#kernel_logo_widget .current_kernel_logo {
  display: none;
  margin-top: -1px;
  margin-bottom: -1px;
  width: 32px;
  height: 32px;
}
[dir="rtl"] #kernel_logo_widget {
  float: left !important;
  float: left;
}
.modal .modal-body .move-path {
  display: flex;
  flex-direction: row;
  justify-content: space;
  align-items: center;
}
.modal .modal-body .move-path .server-root {
  padding-right: 20px;
}
.modal .modal-body .move-path .path-input {
  flex: 1;
}
#menubar {
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  margin-top: 1px;
}
#menubar .navbar {
  border-top: 1px;
  border-radius: 0px 0px 2px 2px;
  margin-bottom: 0px;
}
#menubar .navbar-toggle {
  float: left;
  padding-top: 7px;
  padding-bottom: 7px;
  border: none;
}
#menubar .navbar-collapse {
  clear: left;
}
[dir="rtl"] #menubar .navbar-toggle {
  float: right;
}
[dir="rtl"] #menubar .navbar-collapse {
  clear: right;
}
[dir="rtl"] #menubar .navbar-nav {
  float: right;
}
[dir="rtl"] #menubar .nav {
  padding-right: 0px;
}
[dir="rtl"] #menubar .navbar-nav > li {
  float: right;
}
[dir="rtl"] #menubar .navbar-right {
  float: left !important;
}
[dir="rtl"] ul.dropdown-menu {
  text-align: right;
  left: auto;
}
[dir="rtl"] ul#new-menu.dropdown-menu {
  right: auto;
  left: 0;
}
.nav-wrapper {
  border-bottom: 1px solid #e7e7e7;
}
i.menu-icon {
  padding-top: 4px;
}
[dir="rtl"] i.menu-icon.pull-right {
  float: left !important;
  float: left;
}
ul#help_menu li a {
  overflow: hidden;
  padding-right: 2.2em;
}
ul#help_menu li a i {
  margin-right: -1.2em;
}
[dir="rtl"] ul#help_menu li a {
  padding-left: 2.2em;
}
[dir="rtl"] ul#help_menu li a i {
  margin-right: 0;
  margin-left: -1.2em;
}
[dir="rtl"] ul#help_menu li a i.pull-right {
  float: left !important;
  float: left;
}
.dropdown-submenu {
  position: relative;
}
.dropdown-submenu > .dropdown-menu {
  top: 0;
  left: 100%;
  margin-top: -6px;
  margin-left: -1px;
}
[dir="rtl"] .dropdown-submenu > .dropdown-menu {
  right: 100%;
  margin-right: -1px;
}
.dropdown-submenu:hover > .dropdown-menu {
  display: block;
}
.dropdown-submenu > a:after {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  display: block;
  content: "\f0da";
  float: right;
  color: #333333;
  margin-top: 2px;
  margin-right: -10px;
}
.dropdown-submenu > a:after.fa-pull-left {
  margin-right: .3em;
}
.dropdown-submenu > a:after.fa-pull-right {
  margin-left: .3em;
}
.dropdown-submenu > a:after.pull-left {
  margin-right: .3em;
}
.dropdown-submenu > a:after.pull-right {
  margin-left: .3em;
}
[dir="rtl"] .dropdown-submenu > a:after {
  float: left;
  content: "\f0d9";
  margin-right: 0;
  margin-left: -10px;
}
.dropdown-submenu:hover > a:after {
  color: #262626;
}
.dropdown-submenu.pull-left {
  float: none;
}
.dropdown-submenu.pull-left > .dropdown-menu {
  left: -100%;
  margin-left: 10px;
}
#notification_area {
  float: right !important;
  float: right;
  z-index: 10;
}
[dir="rtl"] #notification_area {
  float: left !important;
  float: left;
}
.indicator_area {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
}
[dir="rtl"] .indicator_area {
  float: left !important;
  float: left;
}
#kernel_indicator {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
  border-left: 1px solid;
}
#kernel_indicator .kernel_indicator_name {
  padding-left: 5px;
  padding-right: 5px;
}
[dir="rtl"] #kernel_indicator {
  float: left !important;
  float: left;
  border-left: 0;
  border-right: 1px solid;
}
#modal_indicator {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
}
[dir="rtl"] #modal_indicator {
  float: left !important;
  float: left;
}
#readonly-indicator {
  float: right !important;
  float: right;
  color: #777;
  margin-left: 5px;
  margin-right: 5px;
  width: 11px;
  z-index: 10;
  text-align: center;
  width: auto;
  margin-top: 2px;
  margin-bottom: 0px;
  margin-left: 0px;
  margin-right: 0px;
  display: none;
}
.modal_indicator:before {
  width: 1.28571429em;
  text-align: center;
}
.edit_mode .modal_indicator:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f040";
}
.edit_mode .modal_indicator:before.fa-pull-left {
  margin-right: .3em;
}
.edit_mode .modal_indicator:before.fa-pull-right {
  margin-left: .3em;
}
.edit_mode .modal_indicator:before.pull-left {
  margin-right: .3em;
}
.edit_mode .modal_indicator:before.pull-right {
  margin-left: .3em;
}
.command_mode .modal_indicator:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: ' ';
}
.command_mode .modal_indicator:before.fa-pull-left {
  margin-right: .3em;
}
.command_mode .modal_indicator:before.fa-pull-right {
  margin-left: .3em;
}
.command_mode .modal_indicator:before.pull-left {
  margin-right: .3em;
}
.command_mode .modal_indicator:before.pull-right {
  margin-left: .3em;
}
.kernel_idle_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f10c";
}
.kernel_idle_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_idle_icon:before.fa-pull-right {
  margin-left: .3em;
}
.kernel_idle_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_idle_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_busy_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f111";
}
.kernel_busy_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_busy_icon:before.fa-pull-right {
  margin-left: .3em;
}
.kernel_busy_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_busy_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_dead_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f1e2";
}
.kernel_dead_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_dead_icon:before.fa-pull-right {
  margin-left: .3em;
}
.kernel_dead_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_dead_icon:before.pull-right {
  margin-left: .3em;
}
.kernel_disconnected_icon:before {
  display: inline-block;
  font: normal normal normal 14px/1 FontAwesome;
  font-size: inherit;
  text-rendering: auto;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  content: "\f127";
}
.kernel_disconnected_icon:before.fa-pull-left {
  margin-right: .3em;
}
.kernel_disconnected_icon:before.fa-pull-right {
  margin-left: .3em;
}
.kernel_disconnected_icon:before.pull-left {
  margin-right: .3em;
}
.kernel_disconnected_icon:before.pull-right {
  margin-left: .3em;
}
.notification_widget {
  color: #777;
  z-index: 10;
  background: rgba(240, 240, 240, 0.5);
  margin-right: 4px;
  color: #333;
  background-color: #fff;
  border-color: #ccc;
}
.notification_widget:focus,
.notification_widget.focus {
  color: #333;
  background-color: #e6e6e6;
  border-color: #8c8c8c;
}
.notification_widget:hover {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.notification_widget:active,
.notification_widget.active,
.open > .dropdown-toggle.notification_widget {
  color: #333;
  background-color: #e6e6e6;
  border-color: #adadad;
}
.notification_widget:active:hover,
.notification_widget.active:hover,
.open > .dropdown-toggle.notification_widget:hover,
.notification_widget:active:focus,
.notification_widget.active:focus,
.open > .dropdown-toggle.notification_widget:focus,
.notification_widget:active.focus,
.notification_widget.active.focus,
.open > .dropdown-toggle.notification_widget.focus {
  color: #333;
  background-color: #d4d4d4;
  border-color: #8c8c8c;
}
.notification_widget:active,
.notification_widget.active,
.open > .dropdown-toggle.notification_widget {
  background-image: none;
}
.notification_widget.disabled:hover,
.notification_widget[disabled]:hover,
fieldset[disabled] .notification_widget:hover,
.notification_widget.disabled:focus,
.notification_widget[disabled]:focus,
fieldset[disabled] .notification_widget:focus,
.notification_widget.disabled.focus,
.notification_widget[disabled].focus,
fieldset[disabled] .notification_widget.focus {
  background-color: #fff;
  border-color: #ccc;
}
.notification_widget .badge {
  color: #fff;
  background-color: #333;
}
.notification_widget.warning {
  color: #fff;
  background-color: #f0ad4e;
  border-color: #eea236;
}
.notification_widget.warning:focus,
.notification_widget.warning.focus {
  color: #fff;
  background-color: #ec971f;
  border-color: #985f0d;
}
.notification_widget.warning:hover {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.notification_widget.warning:active,
.notification_widget.warning.active,
.open > .dropdown-toggle.notification_widget.warning {
  color: #fff;
  background-color: #ec971f;
  border-color: #d58512;
}
.notification_widget.warning:active:hover,
.notification_widget.warning.active:hover,
.open > .dropdown-toggle.notification_widget.warning:hover,
.notification_widget.warning:active:focus,
.notification_widget.warning.active:focus,
.open > .dropdown-toggle.notification_widget.warning:focus,
.notification_widget.warning:active.focus,
.notification_widget.warning.active.focus,
.open > .dropdown-toggle.notification_widget.warning.focus {
  color: #fff;
  background-color: #d58512;
  border-color: #985f0d;
}
.notification_widget.warning:active,
.notification_widget.warning.active,
.open > .dropdown-toggle.notification_widget.warning {
  background-image: none;
}
.notification_widget.warning.disabled:hover,
.notification_widget.warning[disabled]:hover,
fieldset[disabled] .notification_widget.warning:hover,
.notification_widget.warning.disabled:focus,
.notification_widget.warning[disabled]:focus,
fieldset[disabled] .notification_widget.warning:focus,
.notification_widget.warning.disabled.focus,
.notification_widget.warning[disabled].focus,
fieldset[disabled] .notification_widget.warning.focus {
  background-color: #f0ad4e;
  border-color: #eea236;
}
.notification_widget.warning .badge {
  color: #f0ad4e;
  background-color: #fff;
}
.notification_widget.success {
  color: #fff;
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.notification_widget.success:focus,
.notification_widget.success.focus {
  color: #fff;
  background-color: #449d44;
  border-color: #255625;
}
.notification_widget.success:hover {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.notification_widget.success:active,
.notification_widget.success.active,
.open > .dropdown-toggle.notification_widget.success {
  color: #fff;
  background-color: #449d44;
  border-color: #398439;
}
.notification_widget.success:active:hover,
.notification_widget.success.active:hover,
.open > .dropdown-toggle.notification_widget.success:hover,
.notification_widget.success:active:focus,
.notification_widget.success.active:focus,
.open > .dropdown-toggle.notification_widget.success:focus,
.notification_widget.success:active.focus,
.notification_widget.success.active.focus,
.open > .dropdown-toggle.notification_widget.success.focus {
  color: #fff;
  background-color: #398439;
  border-color: #255625;
}
.notification_widget.success:active,
.notification_widget.success.active,
.open > .dropdown-toggle.notification_widget.success {
  background-image: none;
}
.notification_widget.success.disabled:hover,
.notification_widget.success[disabled]:hover,
fieldset[disabled] .notification_widget.success:hover,
.notification_widget.success.disabled:focus,
.notification_widget.success[disabled]:focus,
fieldset[disabled] .notification_widget.success:focus,
.notification_widget.success.disabled.focus,
.notification_widget.success[disabled].focus,
fieldset[disabled] .notification_widget.success.focus {
  background-color: #5cb85c;
  border-color: #4cae4c;
}
.notification_widget.success .badge {
  color: #5cb85c;
  background-color: #fff;
}
.notification_widget.info {
  color: #fff;
  background-color: #5bc0de;
  border-color: #46b8da;
}
.notification_widget.info:focus,
.notification_widget.info.focus {
  color: #fff;
  background-color: #31b0d5;
  border-color: #1b6d85;
}
.notification_widget.info:hover {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.notification_widget.info:active,
.notification_widget.info.active,
.open > .dropdown-toggle.notification_widget.info {
  color: #fff;
  background-color: #31b0d5;
  border-color: #269abc;
}
.notification_widget.info:active:hover,
.notification_widget.info.active:hover,
.open > .dropdown-toggle.notification_widget.info:hover,
.notification_widget.info:active:focus,
.notification_widget.info.active:focus,
.open > .dropdown-toggle.notification_widget.info:focus,
.notification_widget.info:active.focus,
.notification_widget.info.active.focus,
.open > .dropdown-toggle.notification_widget.info.focus {
  color: #fff;
  background-color: #269abc;
  border-color: #1b6d85;
}
.notification_widget.info:active,
.notification_widget.info.active,
.open > .dropdown-toggle.notification_widget.info {
  background-image: none;
}
.notification_widget.info.disabled:hover,
.notification_widget.info[disabled]:hover,
fieldset[disabled] .notification_widget.info:hover,
.notification_widget.info.disabled:focus,
.notification_widget.info[disabled]:focus,
fieldset[disabled] .notification_widget.info:focus,
.notification_widget.info.disabled.focus,
.notification_widget.info[disabled].focus,
fieldset[disabled] .notification_widget.info.focus {
  background-color: #5bc0de;
  border-color: #46b8da;
}
.notification_widget.info .badge {
  color: #5bc0de;
  background-color: #fff;
}
.notification_widget.danger {
  color: #fff;
  background-color: #d9534f;
  border-color: #d43f3a;
}
.notification_widget.danger:focus,
.notification_widget.danger.focus {
  color: #fff;
  background-color: #c9302c;
  border-color: #761c19;
}
.notification_widget.danger:hover {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.notification_widget.danger:active,
.notification_widget.danger.active,
.open > .dropdown-toggle.notification_widget.danger {
  color: #fff;
  background-color: #c9302c;
  border-color: #ac2925;
}
.notification_widget.danger:active:hover,
.notification_widget.danger.active:hover,
.open > .dropdown-toggle.notification_widget.danger:hover,
.notification_widget.danger:active:focus,
.notification_widget.danger.active:focus,
.open > .dropdown-toggle.notification_widget.danger:focus,
.notification_widget.danger:active.focus,
.notification_widget.danger.active.focus,
.open > .dropdown-toggle.notification_widget.danger.focus {
  color: #fff;
  background-color: #ac2925;
  border-color: #761c19;
}
.notification_widget.danger:active,
.notification_widget.danger.active,
.open > .dropdown-toggle.notification_widget.danger {
  background-image: none;
}
.notification_widget.danger.disabled:hover,
.notification_widget.danger[disabled]:hover,
fieldset[disabled] .notification_widget.danger:hover,
.notification_widget.danger.disabled:focus,
.notification_widget.danger[disabled]:focus,
fieldset[disabled] .notification_widget.danger:focus,
.notification_widget.danger.disabled.focus,
.notification_widget.danger[disabled].focus,
fieldset[disabled] .notification_widget.danger.focus {
  background-color: #d9534f;
  border-color: #d43f3a;
}
.notification_widget.danger .badge {
  color: #d9534f;
  background-color: #fff;
}
div#pager {
  background-color: #fff;
  font-size: 14px;
  line-height: 20px;
  overflow: hidden;
  display: none;
  position: fixed;
  bottom: 0px;
  width: 100%;
  max-height: 50%;
  padding-top: 8px;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  /* Display over codemirror */
  z-index: 100;
  /* Hack which prevents jquery ui resizable from changing top. */
  top: auto !important;
}
div#pager pre {
  line-height: 1.21429em;
  color: #000;
  background-color: #f7f7f7;
  padding: 0.4em;
}
div#pager #pager-button-area {
  position: absolute;
  top: 8px;
  right: 20px;
}
div#pager #pager-contents {
  position: relative;
  overflow: auto;
  width: 100%;
  height: 100%;
}
div#pager #pager-contents #pager-container {
  position: relative;
  padding: 15px 0px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
div#pager .ui-resizable-handle {
  top: 0px;
  height: 8px;
  background: #f7f7f7;
  border-top: 1px solid #cfcfcf;
  border-bottom: 1px solid #cfcfcf;
  /* This injects handle bars (a short, wide = symbol) for 
        the resize handle. */
}
div#pager .ui-resizable-handle::after {
  content: '';
  top: 2px;
  left: 50%;
  height: 3px;
  width: 30px;
  margin-left: -15px;
  position: absolute;
  border-top: 1px solid #cfcfcf;
}
.quickhelp {
  /* Old browsers */
  display: -webkit-box;
  -webkit-box-orient: horizontal;
  -webkit-box-align: stretch;
  display: -moz-box;
  -moz-box-orient: horizontal;
  -moz-box-align: stretch;
  display: box;
  box-orient: horizontal;
  box-align: stretch;
  /* Modern browsers */
  display: flex;
  flex-direction: row;
  align-items: stretch;
  line-height: 1.8em;
}
.shortcut_key {
  display: inline-block;
  width: 21ex;
  text-align: right;
  font-family: monospace;
}
.shortcut_descr {
  display: inline-block;
  /* Old browsers */
  -webkit-box-flex: 1;
  -moz-box-flex: 1;
  box-flex: 1;
  /* Modern browsers */
  flex: 1;
}
span.save_widget {
  height: 30px;
  margin-top: 4px;
  display: flex;
  justify-content: flex-start;
  align-items: baseline;
  width: 50%;
  flex: 1;
}
span.save_widget span.filename {
  height: 100%;
  line-height: 1em;
  margin-left: 16px;
  border: none;
  font-size: 146.5%;
  text-overflow: ellipsis;
  overflow: hidden;
  white-space: nowrap;
  border-radius: 2px;
}
span.save_widget span.filename:hover {
  background-color: #e6e6e6;
}
[dir="rtl"] span.save_widget.pull-left {
  float: right !important;
  float: right;
}
[dir="rtl"] span.save_widget span.filename {
  margin-left: 0;
  margin-right: 16px;
}
span.checkpoint_status,
span.autosave_status {
  font-size: small;
  white-space: nowrap;
  padding: 0 5px;
}
@media (max-width: 767px) {
  span.save_widget {
    font-size: small;
    padding: 0 0 0 5px;
  }
  span.checkpoint_status,
  span.autosave_status {
    display: none;
  }
}
@media (min-width: 768px) and (max-width: 991px) {
  span.checkpoint_status {
    display: none;
  }
  span.autosave_status {
    font-size: x-small;
  }
}
.toolbar {
  padding: 0px;
  margin-left: -5px;
  margin-top: 2px;
  margin-bottom: 5px;
  box-sizing: border-box;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
}
.toolbar select,
.toolbar label {
  width: auto;
  vertical-align: middle;
  margin-right: 2px;
  margin-bottom: 0px;
  display: inline;
  font-size: 92%;
  margin-left: 0.3em;
  margin-right: 0.3em;
  padding: 0px;
  padding-top: 3px;
}
.toolbar .btn {
  padding: 2px 8px;
}
.toolbar .btn-group {
  margin-top: 0px;
  margin-left: 5px;
}
.toolbar-btn-label {
  margin-left: 6px;
}
#maintoolbar {
  margin-bottom: -3px;
  margin-top: -8px;
  border: 0px;
  min-height: 27px;
  margin-left: 0px;
  padding-top: 11px;
  padding-bottom: 3px;
}
#maintoolbar .navbar-text {
  float: none;
  vertical-align: middle;
  text-align: right;
  margin-left: 5px;
  margin-right: 0px;
  margin-top: 0px;
}
.select-xs {
  height: 24px;
}
[dir="rtl"] .btn-group > .btn,
.btn-group-vertical > .btn {
  float: right;
}
.pulse,
.dropdown-menu > li > a.pulse,
li.pulse > a.dropdown-toggle,
li.pulse.open > a.dropdown-toggle {
  background-color: #F37626;
  color: white;
}
/**
 * Primary styles
 *
 * Author: Jupyter Development Team
 */
/** WARNING IF YOU ARE EDITTING THIS FILE, if this is a .css file, It has a lot
 * of chance of beeing generated from the ../less/[samename].less file, you can
 * try to get back the less file by reverting somme commit in history
 **/
/*
 * We'll try to get something pretty, so we
 * have some strange css to have the scroll bar on
 * the left with fix button on the top right of the tooltip
 */
@-moz-keyframes fadeOut {
  from {
    opacity: 1;
  }
  to {
    opacity: 0;
  }
}
@-webkit-keyframes fadeOut {
  from {
    opacity: 1;
  }
  to {
    opacity: 0;
  }
}
@-moz-keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
@-webkit-keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}
/*properties of tooltip after "expand"*/
.bigtooltip {
  overflow: auto;
  height: 200px;
  -webkit-transition-property: height;
  -webkit-transition-duration: 500ms;
  -moz-transition-property: height;
  -moz-transition-duration: 500ms;
  transition-property: height;
  transition-duration: 500ms;
}
/*properties of tooltip before "expand"*/
.smalltooltip {
  -webkit-transition-property: height;
  -webkit-transition-duration: 500ms;
  -moz-transition-property: height;
  -moz-transition-duration: 500ms;
  transition-property: height;
  transition-duration: 500ms;
  text-overflow: ellipsis;
  overflow: hidden;
  height: 80px;
}
.tooltipbuttons {
  position: absolute;
  padding-right: 15px;
  top: 0px;
  right: 0px;
}
.tooltiptext {
  /*avoid the button to overlap on some docstring*/
  padding-right: 30px;
}
.ipython_tooltip {
  max-width: 700px;
  /*fade-in animation when inserted*/
  -webkit-animation: fadeOut 400ms;
  -moz-animation: fadeOut 400ms;
  animation: fadeOut 400ms;
  -webkit-animation: fadeIn 400ms;
  -moz-animation: fadeIn 400ms;
  animation: fadeIn 400ms;
  vertical-align: middle;
  background-color: #f7f7f7;
  overflow: visible;
  border: #ababab 1px solid;
  outline: none;
  padding: 3px;
  margin: 0px;
  padding-left: 7px;
  font-family: monospace;
  min-height: 50px;
  -moz-box-shadow: 0px 6px 10px -1px #adadad;
  -webkit-box-shadow: 0px 6px 10px -1px #adadad;
  box-shadow: 0px 6px 10px -1px #adadad;
  border-radius: 2px;
  position: absolute;
  z-index: 1000;
}
.ipython_tooltip a {
  float: right;
}
.ipython_tooltip .tooltiptext pre {
  border: 0;
  border-radius: 0;
  font-size: 100%;
  background-color: #f7f7f7;
}
.pretooltiparrow {
  left: 0px;
  margin: 0px;
  top: -16px;
  width: 40px;
  height: 16px;
  overflow: hidden;
  position: absolute;
}
.pretooltiparrow:before {
  background-color: #f7f7f7;
  border: 1px #ababab solid;
  z-index: 11;
  content: "";
  position: absolute;
  left: 15px;
  top: 10px;
  width: 25px;
  height: 25px;
  -webkit-transform: rotate(45deg);
  -moz-transform: rotate(45deg);
  -ms-transform: rotate(45deg);
  -o-transform: rotate(45deg);
}
ul.typeahead-list i {
  margin-left: -10px;
  width: 18px;
}
[dir="rtl"] ul.typeahead-list i {
  margin-left: 0;
  margin-right: -10px;
}
ul.typeahead-list {
  max-height: 80vh;
  overflow: auto;
}
ul.typeahead-list > li > a {
  /** Firefox bug **/
  /* see https://github.com/jupyter/notebook/issues/559 */
  white-space: normal;
}
ul.typeahead-list  > li > a.pull-right {
  float: left !important;
  float: left;
}
[dir="rtl"] .typeahead-list {
  text-align: right;
}
.cmd-palette .modal-body {
  padding: 7px;
}
.cmd-palette form {
  background: white;
}
.cmd-palette input {
  outline: none;
}
.no-shortcut {
  min-width: 20px;
  color: transparent;
}
[dir="rtl"] .no-shortcut.pull-right {
  float: left !important;
  float: left;
}
[dir="rtl"] .command-shortcut.pull-right {
  float: left !important;
  float: left;
}
.command-shortcut:before {
  content: "(command mode)";
  padding-right: 3px;
  color: #777777;
}
.edit-shortcut:before {
  content: "(edit)";
  padding-right: 3px;
  color: #777777;
}
[dir="rtl"] .edit-shortcut.pull-right {
  float: left !important;
  float: left;
}
#find-and-replace #replace-preview .match,
#find-and-replace #replace-preview .insert {
  background-color: #BBDEFB;
  border-color: #90CAF9;
  border-style: solid;
  border-width: 1px;
  border-radius: 0px;
}
[dir="ltr"] #find-and-replace .input-group-btn + .form-control {
  border-left: none;
}
[dir="rtl"] #find-and-replace .input-group-btn + .form-control {
  border-right: none;
}
#find-and-replace #replace-preview .replace .match {
  background-color: #FFCDD2;
  border-color: #EF9A9A;
  border-radius: 0px;
}
#find-and-replace #replace-preview .replace .insert {
  background-color: #C8E6C9;
  border-color: #A5D6A7;
  border-radius: 0px;
}
#find-and-replace #replace-preview {
  max-height: 60vh;
  overflow: auto;
}
#find-and-replace #replace-preview pre {
  padding: 5px 10px;
}
.terminal-app {
  background: #EEE;
}
.terminal-app #header {
  background: #fff;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.2);
}
.terminal-app .terminal {
  width: 100%;
  float: left;
  font-family: monospace;
  color: white;
  background: black;
  padding: 0.4em;
  border-radius: 2px;
  -webkit-box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.4);
  box-shadow: 0px 0px 12px 1px rgba(87, 87, 87, 0.4);
}
.terminal-app .terminal,
.terminal-app .terminal dummy-screen {
  line-height: 1em;
  font-size: 14px;
}
.terminal-app .terminal .xterm-rows {
  padding: 10px;
}
.terminal-app .terminal-cursor {
  color: black;
  background: white;
}
.terminal-app #terminado-container {
  margin-top: 20px;
}
/*# sourceMappingURL=style.min.css.map */
    </style>
<style type="text/css">
    pre { line-height: 125%; }
td.linenos .normal { color: inherit; background-color: transparent; padding-left: 5px; padding-right: 5px; }
span.linenos { color: inherit; background-color: transparent; padding-left: 5px; padding-right: 5px; }
td.linenos .special { color: #000000; background-color: #ffffc0; padding-left: 5px; padding-right: 5px; }
span.linenos.special { color: #000000; background-color: #ffffc0; padding-left: 5px; padding-right: 5px; }
.highlight .hll { background-color: #ffffcc }
.highlight { background: #f8f8f8; }
.highlight .c { color: #408080; font-style: italic } /* Comment */
.highlight .err { border: 1px solid #FF0000 } /* Error */
.highlight .k { color: #008000; font-weight: bold } /* Keyword */
.highlight .o { color: #666666 } /* Operator */
.highlight .ch { color: #408080; font-style: italic } /* Comment.Hashbang */
.highlight .cm { color: #408080; font-style: italic } /* Comment.Multiline */
.highlight .cp { color: #BC7A00 } /* Comment.Preproc */
.highlight .cpf { color: #408080; font-style: italic } /* Comment.PreprocFile */
.highlight .c1 { color: #408080; font-style: italic } /* Comment.Single */
.highlight .cs { color: #408080; font-style: italic } /* Comment.Special */
.highlight .gd { color: #A00000 } /* Generic.Deleted */
.highlight .ge { font-style: italic } /* Generic.Emph */
.highlight .gr { color: #FF0000 } /* Generic.Error */
.highlight .gh { color: #000080; font-weight: bold } /* Generic.Heading */
.highlight .gi { color: #00A000 } /* Generic.Inserted */
.highlight .go { color: #888888 } /* Generic.Output */
.highlight .gp { color: #000080; font-weight: bold } /* Generic.Prompt */
.highlight .gs { font-weight: bold } /* Generic.Strong */
.highlight .gu { color: #800080; font-weight: bold } /* Generic.Subheading */
.highlight .gt { color: #0044DD } /* Generic.Traceback */
.highlight .kc { color: #008000; font-weight: bold } /* Keyword.Constant */
.highlight .kd { color: #008000; font-weight: bold } /* Keyword.Declaration */
.highlight .kn { color: #008000; font-weight: bold } /* Keyword.Namespace */
.highlight .kp { color: #008000 } /* Keyword.Pseudo */
.highlight .kr { color: #008000; font-weight: bold } /* Keyword.Reserved */
.highlight .kt { color: #B00040 } /* Keyword.Type */
.highlight .m { color: #666666 } /* Literal.Number */
.highlight .s { color: #BA2121 } /* Literal.String */
.highlight .na { color: #7D9029 } /* Name.Attribute */
.highlight .nb { color: #008000 } /* Name.Builtin */
.highlight .nc { color: #0000FF; font-weight: bold } /* Name.Class */
.highlight .no { color: #880000 } /* Name.Constant */
.highlight .nd { color: #AA22FF } /* Name.Decorator */
.highlight .ni { color: #999999; font-weight: bold } /* Name.Entity */
.highlight .ne { color: #D2413A; font-weight: bold } /* Name.Exception */
.highlight .nf { color: #0000FF } /* Name.Function */
.highlight .nl { color: #A0A000 } /* Name.Label */
.highlight .nn { color: #0000FF; font-weight: bold } /* Name.Namespace */
.highlight .nt { color: #008000; font-weight: bold } /* Name.Tag */
.highlight .nv { color: #19177C } /* Name.Variable */
.highlight .ow { color: #AA22FF; font-weight: bold } /* Operator.Word */
.highlight .w { color: #bbbbbb } /* Text.Whitespace */
.highlight .mb { color: #666666 } /* Literal.Number.Bin */
.highlight .mf { color: #666666 } /* Literal.Number.Float */
.highlight .mh { color: #666666 } /* Literal.Number.Hex */
.highlight .mi { color: #666666 } /* Literal.Number.Integer */
.highlight .mo { color: #666666 } /* Literal.Number.Oct */
.highlight .sa { color: #BA2121 } /* Literal.String.Affix */
.highlight .sb { color: #BA2121 } /* Literal.String.Backtick */
.highlight .sc { color: #BA2121 } /* Literal.String.Char */
.highlight .dl { color: #BA2121 } /* Literal.String.Delimiter */
.highlight .sd { color: #BA2121; font-style: italic } /* Literal.String.Doc */
.highlight .s2 { color: #BA2121 } /* Literal.String.Double */
.highlight .se { color: #BB6622; font-weight: bold } /* Literal.String.Escape */
.highlight .sh { color: #BA2121 } /* Literal.String.Heredoc */
.highlight .si { color: #BB6688; font-weight: bold } /* Literal.String.Interpol */
.highlight .sx { color: #008000 } /* Literal.String.Other */
.highlight .sr { color: #BB6688 } /* Literal.String.Regex */
.highlight .s1 { color: #BA2121 } /* Literal.String.Single */
.highlight .ss { color: #19177C } /* Literal.String.Symbol */
.highlight .bp { color: #008000 } /* Name.Builtin.Pseudo */
.highlight .fm { color: #0000FF } /* Name.Function.Magic */
.highlight .vc { color: #19177C } /* Name.Variable.Class */
.highlight .vg { color: #19177C } /* Name.Variable.Global */
.highlight .vi { color: #19177C } /* Name.Variable.Instance */
.highlight .vm { color: #19177C } /* Name.Variable.Magic */
.highlight .il { color: #666666 } /* Literal.Number.Integer.Long */
    </style>


<style type="text/css">
/* Overrides of notebook CSS for static HTML export */
body {
  overflow: visible;
  padding: 8px;
}

div#notebook {
  overflow: visible;
  border-top: none;
}@media print {
  div.cell {
    display: block;
    page-break-inside: avoid;
  } 
  div.output_wrapper { 
    display: block;
    page-break-inside: avoid; 
  }
  div.output { 
    display: block;
    page-break-inside: avoid; 
  }
}
</style>

<!-- Custom stylesheet, it must be in the same directory as the html file -->
<link rel="stylesheet" href="custom.css">

<!-- Loading mathjax macro -->
<!-- Load mathjax -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.5/latest.js?config=TeX-AMS_HTML"></script>
    <!-- MathJax configuration -->
    <script type="text/x-mathjax-config">
    MathJax.Hub.Config({
        tex2jax: {
            inlineMath: [ ['$','$'], ["\\(","\\)"] ],
            displayMath: [ ['$$','$$'], ["\\[","\\]"] ],
            processEscapes: true,
            processEnvironments: true
        },
        // Center justify equations in code and markdown cells. Elsewhere
        // we use CSS to left justify single line equations in code cells.
        displayAlign: 'center',
        "HTML-CSS": {
            styles: {'.MathJax_Display': {"margin": 0}},
            linebreaks: { automatic: true }
        }
    });
    </script>
    <!-- End of mathjax configuration --></head>
<body>
  <div tabindex="-1" id="notebook" class="border-box-sizing">
    <div class="container" id="notebook-container">

<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[137]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1">## Libraries</span>

<span class="kn">import</span> <span class="nn">pandas</span> <span class="k">as</span> <span class="nn">pd</span>
<span class="kn">import</span> <span class="nn">matplotlib.pyplot</span> <span class="k">as</span> <span class="nn">plt</span>
<span class="kn">from</span> <span class="nn">joypy</span> <span class="kn">import</span> <span class="n">joyplot</span>
<span class="kn">import</span> <span class="nn">numpy</span> <span class="k">as</span> <span class="nn">np</span>
</pre></div>

    </div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[166]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="c1"># load file</span>
<span class="n">data</span><span class="o">=</span> <span class="n">pd</span><span class="o">.</span><span class="n">read_csv</span><span class="p">(</span><span class="s2">&quot;char3_alojamientos-turisticos-sample.csv&quot;</span><span class="p">)</span> 
<span class="n">data</span><span class="o">=</span><span class="n">data</span><span class="p">[</span><span class="n">data</span><span class="p">[</span><span class="s1">&#39;price&#39;</span><span class="p">]</span><span class="o">&lt;=</span><span class="mi">400</span><span class="p">]</span>
<span class="n">data_alquiler</span><span class="o">=</span><span class="n">data</span><span class="p">[[</span><span class="s1">&#39;city&#39;</span><span class="p">,</span><span class="s1">&#39;price&#39;</span><span class="p">,</span><span class="s1">&#39;insert_date&#39;</span><span class="p">]]</span>
</pre></div>

    </div>
</div>
</div>

</div>
<div class="cell border-box-sizing code_cell rendered">
<div class="input">
<div class="prompt input_prompt">In&nbsp;[167]:</div>
<div class="inner_cell">
    <div class="input_area">
<div class=" highlight hl-ipython3"><pre><span></span><span class="n">plt</span><span class="o">.</span><span class="n">figure</span><span class="p">()</span>

<span class="n">joyplot</span><span class="p">(</span>
    <span class="n">data</span><span class="o">=</span><span class="n">data_alquiler</span><span class="p">[[</span><span class="s1">&#39;price&#39;</span><span class="p">,</span> <span class="s1">&#39;city&#39;</span><span class="p">]],</span> 
    <span class="n">by</span><span class="o">=</span><span class="s1">&#39;city&#39;</span><span class="p">,</span>
    <span class="n">figsize</span><span class="o">=</span><span class="p">(</span><span class="mi">15</span><span class="p">,</span> <span class="mi">8</span><span class="p">)</span>   
    
<span class="p">)</span>


<span class="n">plt</span><span class="o">.</span><span class="n">title</span><span class="p">(</span><span class="s1">&#39;Precio de Alquiler turistico por Ciudad&#39;</span><span class="p">,</span> <span class="n">fontsize</span><span class="o">=</span><span class="mi">20</span><span class="p">)</span>
<span class="n">plt</span><span class="o">.</span><span class="n">show</span><span class="p">()</span>
</pre></div>

    </div>
</div>
</div>

<div class="output_wrapper">
<div class="output">


<div class="output_area">

    <div class="prompt"></div>




<div class="output_text output_subarea ">
<pre>&lt;Figure size 432x288 with 0 Axes&gt;</pre>
</div>

</div>

<div class="output_area">

    <div class="prompt"></div>




<div class="output_png output_subarea ">
<img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAABDAAAAJNCAYAAADH+IUzAAAAOXRFWHRTb2Z0d2FyZQBNYXRwbG90bGliIHZlcnNpb24zLjQuMywgaHR0cHM6Ly9tYXRwbG90bGliLm9yZy/MnkTPAAAACXBIWXMAAAsTAAALEwEAmpwYAAD4p0lEQVR4nOzdd5xU1f3/8deZtr0vuzRpSpEqqKBSBURBEbB3JRrjN0YTUywxJiaaaLpRE40xxjTzMyaxxmhiV+wNRUEBQXrb3qbe8/vjzi67y8JQ9255Px+P6525c+69n/nMzMp85pxzjbUWEREREREREZGOzOd1ACIiIiIiIiIiqaiAISIiIiIiIiIdngoYIiIiIiIiItLhqYAhIiIiIiIiIh2eChgiIiIiIiIi0uGpgCEiIiIiIiIiHZ4KGCIi0mEYY6YZY6wx5kaPzr/aGLPai3PvSjInL3SUcxtjbkxun+ZFTF45kO8PY8yAZE7vPxDHl/b7+2KMecEYYw/wOe5PPpcBB/I8IiIdjQoYIiLdQPIfus2XhDFmmzHmOWPMOV7H1x0ZYzKNMZXJ1+MBr+PpbDpqsWlXvCxEdVXGmPHGmN8bYz4xxtQYYyLGmM+NMf8wxpxhjPF7HaOIiOw/Aa8DEBGRdvX95DoIDAPmAccaY46w1n7du7CavAkcCmzzOpB2cCaQB1jgFGNMkbW2zOOY2nIoUO91EB3EjAN47PW4ua46gOfoMowxQeB24DIgAbwI/BuIAH2B6cCpwD+B05K7dae/LyIiXZIKGCIi3Yi19sbm940xM4D/AV8zxtxurV3tRVyNrLX1wDIvY2hHlwIO8DPgauBC4BeeRtQGa213eT1SstauPIDHjtF93vv7w6+BLwIfAqdbaz9p/mCy58U5wMmN27rZ3xcRkS5JQ0hERLoxa+2zuP+gN8CR0HJ+A2PMOcaYN4wxtc276yeHP1xnjHnfGFOXfPw1Y8zZOzuXMWaWMeZxY8yWZDfvtcaYR40xM5u12ekYdWPMYGPMn4wx640xUWPMhuT9wXvynI3rK8aYj4wx4eTx7jTG5KXY72xjzPPJYR9hY8xSY8x3jDFpe3L+5LFGAkcBzwI/BqLAJXtxnNJk9/nNxpiG5Otx4c7yuKthFzub12JPhz0YY4Ylx+evTb5Om40xDxhjhrbRtnEc/yBjzBXGmA+Sz2On52t8bkB/oH+roVH3J9vscj6JtuYoaJ6z5LCEfxtjyk2zeQbayp8xJmSMudIY864xpsIYU59s1/TeNsZc1Ox8U1vFfGOqmJOft2uMMW8bd5hEbfL9d7sxprRV217GmF8nY4gaY7YaY/5ljDl8ZzndSY5sMk+9jTF/Tn5uG4wx75idDDszxviMMZcZY95KxliXvP1/xpgd/s3Z7Bw9jTH3Jj+LCWPMRSlim4hbvCgHjm9dvACw1iastX8Gzmu23377XCQfOyuZj4Zkfv5sjOm9k+OEjPt350njDnGJJN9fzxhjZu/iuc40xryczGW5MeYRY8ywnbUXEenq1ANDRERMct160rlvAMcBjwPP4w53wBiTDzwHjAXeBe7DLYgfDzxgjBlhrf1OixMY833gu0At8AiwFugNHIP7BeOZXQZozJHJNjnAY8DHuENgzgPmGWNmWmvf2s3nextwJbARuAeI4Q6lmQCEcIsJrc9/H7AQWIfbJb0StwBxEzDDGHOctTa+m+cHt/cFwP3W2nJjzOPAqcaYydbal3fnAMaYYuBVYBDwSnLpBdwN/HcPYtlvjDEnAP/CHaL0OLACtzv/KcCJxphjrbXvtrHrr4DJuEMAnsQdErAzq3GHQn0tef+2Zo+9v9fBb3c0cB1uPu8DimnjPdHM/cDZwBLgT0AD7nt7EnAC7vv2/WTM3wM+T+7T6IVdBWOMKcD9/I0BPknGFAUOxn1P/gvYnGw7MBl3b9zP6N+Ag4DTcfN/qrX2iV0//RYKcN9jlcAfgHzgDOCvxpg+1tqftmr/Z9xeD2uBe3H/piwAfoObj3PbOEch8Dru34Z/4fZK2pwirsbPzz3W2o27amitjaQ41l4xxlyF22OqEvd1r8T9G/gqbQ8DKsR9n7+K2+ttK+7ndS7wpDHmi9bae1ud4zTgQdzX+0Hcv1mTgNeAD/b3cxIR6RSstVq0aNGipYsvuF8kbBvbZ+J+YXCA/sltNybb1wFj29jn/uTjV7fang48lTzWYc22z0q2/wzo08bx+ja7PS3Z9sZm2wywNLn93Fb7npncvgzw7UYejkm2XwEUtor9teRjq1vtc1Fy+7+AjFaPNebqq3vwWqTj/nJc2Xg84KTkcf68i9fvhVbb7klu/2Wr7UfgFmVa5DH52OrWz6+N5zJtN869Q1vcL7sVuPMLDG/VfiTuF9R3d/JeWg8M3MP39K6ey4Dkce/fyeMv0Orz0Oy9Z4Ev7c45cYt6DvA24G+jfVGqXKaKGXgguf2u1u9xIBvIa3b/6WTb69t438eBMiB7N/PbmIu/Nz8vMDD5/o0Cg5ptPzvZ/t3m5wCykvmxwDk7OcefgMAevPYrk/vN3MP3TONrvE+fi+RrFU3mYUCz7T7cAucOf2+BNJr9rWv1HlqSPFZGs+3ZydcrBhzRap9fNsvdgF09Zy1atGjpaouGkIiIdCPJ7tA3GmN+aIz5B27BwQC3WWs/b9X8Hmvte632L8Lt9fC2tfYnzR+z1oaBa5LHa97F/Irk+hvW2vWtY7LWrksR9jG4vS1es9b+tdW+D+L+4jwU95fJVBYm1z+01pa3iv26nezzVdwvf1+w1ja0euwm3C8Zbf2yvDOn437Zf7DZ8Z4CNgGnJX9x3yXjTmB4LlCD+wWribX2beCvbex2oF2A+wv996y1H7eKaQnwO2CsMWZ4G/v+xFq76sCHuFvet9b+djfbWtz3ewS3kNHywX2clNUYU4JbpNsIfNNa2+Ic1tpaa21Vsm1f3GLhGqD1Z/NV3N4Yhbi9YXZXArim+XmTr9PtuL1szm/W9gvJ9bXW2tpm7etw/y5A28Okosnntic9mHol16n+dhwo5+I+/ztss3mDknn6Fm2/FyJt/a1Lvn734f5NOLLZQ/NwX68Hkp/p5m5Ek72KSDelISQiIt3L95Jri9sD4GXg99bav7TR9s02th0J+IE256nA/Uc9uDP9Nzoqeb6n9iJegHHJ9XM7efw53OLFWOCl3TzWi2089gqthi4YYzJxu+5vw53otK1jRmj5fFNp7P7+h8YN1tq4MeavuMN2zsf9grgrw4BM4OXGL7CtvIA7KWh7Ojq5HrOT98aQ5PpQ3CFAzbX1XvPKbsdira1ODv+ZC7xvjPkn7mfqDetOGLmvjsT9Vf+lZCFgV8Ym1y9bd0LQ1p7DLT6Oxe3xsDvW7KSw9ALu35KxzbaNw/3i/kIb7V/E/WyNbeOx1dbaLbsZT0ex078j1trPjDFrcedoacEYMwK3wDEFtwiT3qpJn908R5Ux5n1g6h5HLiLSyamAISLSjVhr2/wGvhOb2thWlFwfSctfC1vLbnY7H6hoo/fC7mqcXHNnY90bt+fvwbF2GGOfLCK0vrxiAe4v7D3YXvzZa8aYQ3GLLcusta+3evh+3ALGF0ldwNjp80hq67U70BrfG19M0S67jW1exLszexrLmbg9DM5h+2WKw8keTt+01qaaz2FX8pPrHXoutWF/fk4apXp/5TXblgeUW2t3mC+k2WerZBfH2hMbced+6YM3VxXZnc9fiwKGMeYo3CJSAHfy3seAapJD7nB7XDSfELgjfsZFRDynISQiIrIzto1tjb/2/9Jaa3axHNtsn0qgwBiTsZdxNJ6z504e79Wq3e4cq7T1A8aYAO6EjW21fy/F893dwlBj74thra5EYXEvBwkw0hhzzN4+j6Sd5cph5z9e5Kc4ZyqNMY1Jkas/trFvW++1fdHYhX9vnusexWKtbbDW3mitHQL0w+3l8Epy/Y89OVYbKpPrPrtqlLQ/PyeNUr2/mh+rCihMDm9qodlnq7qNY+3Na/9Kcj1jL/Zty55+Lvbm8/cdIAOYZa2dba39mrX2u9a9tPUb++kcIiJdngoYIiKyJ97E/cf+5D3Y53XcXgwn7OU5G+fhmLaTxxuLJW1d3aK1xjZtdb2ehDs8pklyLP9HwAhjTOFuHH+njHu51fNx83cf8Ps2lqeTzVP1YlgG1AOHmbYv/zptJ/tVAKVtfcnEnfxzXzT2KNmT98a+SNDq9WqmIrk+qPUDxphctg9n2a+stWuT87QcjztR7KTkvDGNHHYec1saP29TjDFZKdo2fk4mJQsGre3J56RRP5O8hGwr01qds/G2D3d4RGtTcJ/3npx7V+5Jri9tfRnZ1szuXeZ4Tz8XO/07YowZRBvvO+AQ3B4qL7TxWFt/j3Z1jjzcXhsiIt2OChgiIrLbkmPV/wocYYy5wRizw5cxY8zBycs5Nrojuf65MWaHX5Lb2tbKItzLR05KXlaw+b6n4X5h/pTtv8ruyv3J9fXNCxLGmHTglp3s8wvcy6vel7yEbOv4C4wx43bYa0en4g6zeNpae7G19pLWC+4lKuuAM3ZSmAAgOcfBX3EvK3tjq3iOYOeTir6J+0vzwuYbjTEXARN34znsyh9wewx8zxgzvvWDxhifMWbaPp6juTKgR1s9e6y1NbhFnonNJw1Nvl9/gftL+D4zxvQwxoxq46Es3KEycVpegrWMtr/ctslauxX4f7i9J35mjGnx7zZjTHbj+yQ5QeT/cK+Q8bVW7SbgDnGpAB7e3fPjFh1+3Py8yc/2lbjPrfncOfcl17ck545pbJ8J3Jq8+/s9OPdOWWsX4U4KWwQ8ZYwZ3LpN8v12Nu6lXVPZ08/FX3GvDnJF8wJPMk8/pe1/X6/G7aEyutU5LsYteLX2KO7rdU7yM93cjbQcviMi0m1oDgwREdlTXwEGAz8AzjfGvII7Trs37gSNR+JeUnEVgLX2v8aYm3G7UC81xjwCrMXtGj0J95f7i3Z2MmutNcZciPvl7EFjzKO4X06HAvNxr8RxQesrNOzkWIuMMXfgXhllSXKeghju+PMK2pg/wFp7nzHmcODLwEpjzNO4V3ooxL2k5BTcL++XpTh94/CRe3cRX7Ux5iHcfJwH/HoXx/s2bhf6ryW/4LyC+0X3TOBJ4OQ29rkD90vaXcaYGbivw2G4E3A+gXs5171irS1LFpQeBl43xjyL23vF4n5pPxr3C2friQv31rO477WnjDEv4U6mutha+3jy8Z/ifmFelMxpGLcXQhBYjDs5677qA7xnjPkQ+AA3n7m4eewJ3J4spjSP+azkxJ/v4r73XrLW7mry2a/gXob2MmBa8v0XxX3vHY/7Or+QbHsZbsHvp8aYWbiXLz0I98o3DrCwVTypfABMAN4xxvwXdzjFGcn11dbalY0NrbUPGGPmJR//KPk5t7if0YG4V93Zn1fHuRy3F85luH9XXsB9XSO4r8t0oC+7N4xnjz4X1trVxphrgZ/jvv4P4g75OB43Nx8ALQoVwG3Jx18xxvw92f4I3L+B/wBaFGettbXGmEuBB4GXk+fYmGw/EnfC4rZ6u4iIdG2prrOqRYsWLVo6/4L7RcLuZtsbk+2n7aJNCPeL1au4/xCP4H6pfxb319+iNvaZg3slkvJk+7W4X3anN2szLXnuG9vYfyjur6kbcb/4bcT9BXjoHubCJGNfmoxjA26hIA/3V9LVO9nvJNwvM1twv0Buwv3l9mZgWIpzDkk+r01AMEXbY5Jt32/1+r3QRtueuL98bwUagPdxix+7yuMk3C8/9bhzEvwb98tWm697W+fe1XsEtwfAncBy3KJBNW7B6c/A/FZt708eZ8BevKezgLtwL6UZTx7n/lZtLsYtokSSuf8tbhHlBVp9HnaVs2ZtWrw/cL+sfhd3csb1yfNsTB7/bMC02r8EeAC34Jdofr5k3nZ4Ds2e6/W4X4zrcYt2H+N+KS5p1bZPMi+fJ9+n24BHgCP34m/GC7iFyb/gvu/DuIWXc3ayjw+30Pd2Ms564B3cYoNvZ+fY09e+1TEm4BaqPgVqafm35Yzm593Va8wefi6S+5ydzEcY9zP4l2S+dnh/Nfsb8nry9asE/otbhLgoeY6L2tjnONziZD1ukfVR3KsQ3c9efna0aNGipTMvxtr9PW+WiIiIeCk5VON54PvWnSRQZI8kJ5Z90Vo7zetYREREGmkODBERERERERHp8FTAEBEREREREZEOTwUMEREREREREenwNAeGiIiIiIiIiHR4uozqdqrkiIiIiIiIiHjPtLVRQ0hEREREREREpMNTAUNEREREREREOjwVMERERERERESkw9McGCLdXDgc5s033+T1119n5cqVrF27lnA4TDyeoLCwgNLSUoYPH86YMWOYMGECGRkZXocsIiIiIiLdkK5Csp0SId1GPB7n3//+N3/5y1944oknCIfDAASz8vDn9MAG0sAYnHANTm05iYYa9/G0NI46eiIXnHs2p556KgUFBV4+DRERERER6ZranMRTBYztlAjp8mKxGPfddx8/+clP+OyzzwjlFJAxZCI5Bx8OPYfiz8jdYR9rLU5dJZHNK0isXUzN8jeJlW8gEAxxxtnncP0132L48OEePBsREREREemiVMBIQYmQLu1///sfV155JcuWLSOz71AKjz4d34AjMT7/Hh3HWkt00woalvyP6g+ewcajTJ1xPL/86S2MHTv2AEUvIiIiIiLdiAoYKSgR0iXV1NTwta99jfvuu4+Mot4UzbwUX//DMabNvwl7JFFfRe17T1LzzuMkwjXMO/VMbv/5j+nXr99+iFxERERERLopFTBSUCKky3n//fc57bTT+Oyzzyg4+nSyjz4LEwjt9/M4kTqqX3+I6rcexefzce23r+e7376GUGj/n0tERERERLo8FTBSUCKkS3nooYe46KKLsKEsepx8NabXoQf8nPGqLVQ9/3tqP1nEQQcP5cE//4Gjjz76gJ9XRERERES6lDYLGL72jkJEDryf/exnnHHGGfiKB1B6wS/apXgBEMgroWj+dfQ45QY2btnGMRMncvnXvkk0Gm2X84uIiIiISNelHhjbKRHS6Vlruf7667nlllvIHT6FgjlXgT/oSSxOpJ7K539PzeKnGTB0JP955CGGDRvmSSwiIiIiItKpaAhJCkqEdHrXXnstP/7xj8kfN4fcGV/a4yuMHAj1n75K+VN3QiLCj3/yM75+5eX7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wBiijpAJ7/777+elL3sZ6SLM+JvPY+vnVrpJchS5A110/P5rZLY/xJve9k5+9P3vEYvFKt0sEREREZGjTZeQjEEdIRPabbfdxvnnn08xkqT19V/AVrdWuklyDFjPpee2/6Xn7stZtmotN1xzFfPnz690s0REREREjiYFGGNQR8iEdf3113PxxRdjqptped3nscmGSjdJjrH0E3fRce03iUUjXPp/v+YV57280k0SERERETlaNAeGyGT029/+lgsuuACnfjYtb/iSwotpKrHsNGa85Zt4VfW88hXn874P/iP5fL7SzRIREREROWY0AmOIOkImnJ/97Ge84x3vIDFnBU2v/iw2mqx0k6TCvEKW7pt/SN+Df2DRijVcc+WlrFixotLNEhERERE5kjQCQ2Qy+c53vsPb3vY2kgvW0vTaf1V4IQA4kTgN5/49zRf9E9u3b2fN2nV88zv/gcJoEREREZnqNAJjiDpCJgRrLZ///Of5zGc+Q82K06l/xUcgFK10s2QCKvZ30nXdt0k/fT9nvvhl/PbXP6elpaXSzRIRERERea40iecY1BFScdZaPvrRj/KNb3yD2uPPpu5lfw9OqNLNkgnMWo+++zfQ/aefkqiu4ac//AGvfc2rK90sEREREZHnQgHGGNQRUlGu6/Ke97yHH//4x9SffAHVZ/0txugqLxmf/P5tdF7z7+T2Ps3LXnkRP//R9zUaQ0REREQmKwUYY1BHSMXk83ne9KY3cdlll9F45htInv5GjBn1d1bkoKxbpPee39Jz569JJKv5/n/+B5e88Q16L4mIiIjIZKMAYwzqCKmIdDrNq1/9aq6//nqaz/5bEideWOkmySSX37+druu/TXb3E7zopefx8x99n7lz51a6WSIiIiIi46UAYwzqCDnmenp6eOUrX8ntt99Oy3l/T3z1SyvdJJkirOfSd99VdN/2C8LhEJ/558/w8Y/+I5FIpNJNExEREREZiwKMMagj5JjatWsXL3/5y3nk0cdoveAfiSw9s9JNkimo2LOX7pt/yMCTdzNv0TL+50ff56yzzqp0s0REREREDkUBxhjUEXLMPProo5x77rm07Wun9eJP48w9vtJNkikuveVeum/+AYXuvVzw6r/he9/6OnPmzKl0s0RERERERqMAYwzqCDkm7rzzTl7xileQdQ2tr/sctnFhpZsk04RXyNF392X0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XXTd8J8MPHEXi5av4lc/+zGnnnpqpZslIiIiItOX5sAQGY9iscjrX/96uvv6ab7w4wovZMoLJetpvPBTNL3qEzyzu43nnXYab33nu+nu7q5000REREREShRgiIzw0Y9+lNtuu43Gl70fr1bzXsj0YIwhueJMZr7zv6g98QJ+/tMfM2/RUv73l79EI/VEREREZCLQJSRD1BHCT37yE975zndSf8qrqDnrXZVujkjF5Nq20H3D98jueZLjTzqVH/3ndzn55JMr3SwRERERmR40B8YY1BHT3B133MFZZ51FfN4aGi7+LDihSjdJpKKs59L/0I303P4L3IFuLnrt6/n2N77K3LlzK900EREREZnaFGCMQR0xjW3fvp1TTjmFARul5U1fx4umKt0kkQnDy6Xpu/dyeu65klDI4UMf+jCf/tQnqK2trXTTRERERGRqUoAxBnXENNXe3s6ZZ57Jth27mfmWr2E174XIqIo9++i97Wf0bf4ziepaPv7Rj/DhD32Q6urqSjdNRERERKYWBRhjUEdMQwMDA7zkJS/h/o0PMOsNX8DMXFnpJolMeLm2LfTd+SsGnryXVG09H//YR/nA372fmpqaSjdNRERERKYGBRhjUEdMM4VCgQsvvJDrrr+eWa/+FOFFz6t0k0Qmldzux+m769cMbLmPqmSK97znPXzkHz7M7NmzK900EREREZncFGCMQR0xjRQKBd7whjfw29/+ltaX/x3x48+tdJNEJq3cnicZuO9K+h69HcdxePVrX8c/fugDnHLKKRgz6v89IiIiIiKHogBjDOqIaaI8vGg+510kTnhVpZskMiUUuttIb/w9PX/9A7aQZdnK1Xzw797LJZdcogk/RURERORwKMAYgzpiGsjn87zhDW/giiuuoPmcd5M44YJKN0lkyvFyadKP/on+v15Pbu/TRONVvOIVr+Stb76El73sZcRisUo3UUREREQmNgUYY1BHTHE9PT285jWv4aabbqLlpe+mar3CC5GjyVpLvu1JsptuovfR2/EyvSSra7n4ogt59cUX8ZKXvIRUSrcsFhEREZEDKMAYgzpiCtu5cyfnnXcemx95lJbzPkDsuBdXukki04p1i2S3/ZXcE7fR99idePkM4UiUM5//Ai684BWcddZZrF69GsdxKt1UEREREak8BRhjUEdMUffddx8XXngh+zu7ab3oUzhz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
"
>
</div>

</div>

</div>
</div>

</div>
    </div>
  </div>
</body>

 


</html>

