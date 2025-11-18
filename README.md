Delighted Services (Online Donation Platform)

Project Goal: Developed an online platform to facilitate the donation of reusable clothing, food, and money by connecting givers with volunteers and local orphanages.
Problem Solved: Addressed the lack of a centralized, efficient online system for coordinating and acknowledging clothing donations in India, moving beyond existing static websites and manual processes.

Key Features & Impact:
Designed a system for fast and easy donation record saving via a database, replacing time-consuming manual file systems.
Implemented a clear form of acknowledgement for every donation and provided a system for easy announcements and updates.
Structured the application using the Waterfall Model and defined four core modules: Registration, Monitoring (for orders/requests), Report (for initiating delivery), and Media (for awareness and updates).
Improved search efficiency and incorporated an identification number system to easily manage and retrieve records for orphans and assistance recipients.

Technical Stack:
Frontend Languages: HTML, CSS, JavaScript.
Backend & Database: PHP and MySQL.
Development Tools: Visual Studio Code.


/*!
 *  Font Awesome 4.0.3 by @davegandy - http://fontawesome.io - @fontawesome
 *  License - http://fontawesome.io/license (Font: SIL OFL 1.1, CSS: MIT License)
 */
/* FONT PATH
 * -------------------------- */
@font-face {
  font-family: 'FontAwesome';
  src: url('../fonts/fontawesome-webfont.eot?v=4.0.3');
  src: url('../fonts/fontawesome-webfont.eot?#iefix&v=4.0.3') format('embedded-opentype'), url('../fonts/fontawesome-webfont.woff?v=4.0.3') format('woff'), url('../fonts/fontawesome-webfont.ttf?v=4.0.3') format('truetype'), url('../fonts/fontawesome-webfont.svg?v=4.0.3#fontawesomeregular') format('svg');
  font-weight: normal;
  font-style: normal;
}
.fa {
  display: inline-block;
  font-family: FontAwesome;
  font-style: normal;
  font-weight: normal;
  line-height: 1;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
/* makes the font 33% larger relative to the icon container */
.fa-lg {
  font-size: 1.3333333333333333em;
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
  width: 1.2857142857142858em;
  text-align: center;
}
.fa-ul {
  padding-left: 0;
  margin-left: 2.142857142857143em;
  list-style-type: none;
}
.fa-ul > li {
  position: relative;
}
.fa-li {
  position: absolute;
  left: -2.142857142857143em;
  width: 2.142857142857143em;
  top: 0.14285714285714285em;
  text-align: center;
}
.fa-li.fa-lg {
  left: -1.8571428571428572em;
}
.fa-border {
  padding: .2em .25em .15em;
  border: solid 0.08em #eeeeee;
  border-radius: .1em;
}
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
  -webkit-animation: spin 2s infinite linear;
  -moz-animation: spin 2s infinite linear;
  -o-animation: spin 2s infinite linear;
  animation: spin 2s infinite linear;
}
@-moz-keyframes spin {
  0% {
    -moz-transform: rotate(0deg);
  }
  100% {
    -moz-transform: rotate(359deg);
  }
}
@-webkit-keyframes spin {
  0% {
    -webkit-transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(359deg);
  }
}
@-o-keyframes spin {
  0% {
    -o-transform: rotate(0deg);
  }
  100% {
    -o-transform: rotate(359deg);
  }
}
@-ms-keyframes spin {
  0% {
    -ms-transform: rotate(0deg);
  }
  100% {
    -ms-transform: rotate(359deg);
  }
}
@keyframes spin {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(359deg);
  }
}
.fa-rotate-90 {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=1);
  -webkit-transform: rotate(90deg);
  -moz-transform: rotate(90deg);
  -ms-transform: rotate(90deg);
  -o-transform: rotate(90deg);
  transform: rotate(90deg);
}
.fa-rotate-180 {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=2);
  -webkit-transform: rotate(180deg);
  -moz-transform: rotate(180deg);
  -ms-transform: rotate(180deg);
  -o-transform: rotate(180deg);
  transform: rotate(180deg);
}
.fa-rotate-270 {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=3);
  -webkit-transform: rotate(270deg);
  -moz-transform: rotate(270deg);
  -ms-transform: rotate(270deg);
  -o-transform: rotate(270deg);
  transform: rotate(270deg);
}
.fa-flip-horizontal {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=0, mirror=1);
  -webkit-transform: scale(-1, 1);
  -moz-transform: scale(-1, 1);
  -ms-transform: scale(-1, 1);
  -o-transform: scale(-1, 1);
  transform: scale(-1, 1);
}
.fa-flip-vertical {
  filter: progid:DXImageTransform.Microsoft.BasicImage(rotation=2, mirror=1);
  -webkit-transform: scale(1, -1);
  -moz-transform: scale(1, -1);
  -ms-transform: scale(1, -1);
  -o-transform: scale(1, -1);
  transform: scale(1, -1);
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
  color: #ffffff;
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
.fa-bar-chart-o:before {
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
.fa-sort-asc:before {
  content: "\f0dd";
}
.fa-sort-up:before,
.fa-sort-desc:before {
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
.fa-reply-all:before {
  content: "\f122";
}
.fa-mail-reply-all:before {
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
.fa-gittip:before {
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


<?php
$server = "localhost";
$username = "root";
$password = "";
$dbname = "ecom";
 
$con = mysqli_connect($server,$username,$password,$dbname);

if(isset($_POST['submit']))
   {
       if(!empty($_POST['firstName']) && !empty($_POST['lastName']) && !empty($_POST['email']) && !empty($_POST['number']) && !empty($_POST['feedBack']))
       {
        $firstName = $_POST['firstName'];
        $lastName = $_POST['lastName'];
        $email = $_POST['email'];
        $number = $_POST['number'];
        $feedBack = $_POST['feedBack'];

        $query =  "insert into feedback(firstName,lastName,email,number,feedBack) values('$firstName','$lastName','$email','$number','$feedBack')";

        $run = mysqli_query($con,$query) or die(mysqli_error());

        if($run){
            echo "Form Submitted Successfully";
        }
        else{
            echo "Form not Submitted";
        }

       }
       else{
           echo "all fields required";
       }
}

?>


.fa-turkish-lira:before,
.fa-try:before {
  content: "\f195";
}
.fa-plus-square-o:before {
  content: "\f196";
}
<?php

	//SMTP server settings	
	$host = "smtp.host.com";
    $port = "587";
    $username = "";
    $password = "";
	
	
	$messageBody = "";
	
	if($_POST['name']!='false'){
		$messageBody .= '<p>Visitor: ' . $_POST["name"] . '</p>' . "\n";
		$messageBody .= '<br>' . "\n";
	}
	if($_POST['subject']!='false'){
		$messageBody .= '<p>Subject: ' . $_POST["subject"] . '</p>' . "\n";
		$messageBody .= '<br>' . "\n";
	}
	if($_POST['email']!='false'){
		$messageBody .= '<p>Email Address: ' . $_POST['email'] . '</p>' . "\n";
		$messageBody .= '<br>' . "\n";
	}else{
		$headers = '';
	}
	if($_POST['state']!='false'){		
		$messageBody .= '<p>State: ' . $_POST['state'] . '</p>' . "\n";
		$messageBody .= '<br>' . "\n";
	}
	if($_POST['phone']!='false'){		
		$messageBody .= '<p>Phone Number: ' . $_POST['phone'] . '</p>' . "\n";
		$messageBody .= '<br>' . "\n";
	}	
	if($_POST['fax']!='false'){		
		$messageBody .= '<p>Fax Number: ' . $_POST['fax'] . '</p>' . "\n";
		$messageBody .= '<br>' . "\n";
	}
	if($_POST['message']!='false'){
		$messageBody .= '<p>Message: ' . $_POST['message'] . '</p>' . "\n";
	}
	
	if($_POST["stripHTML"] == 'true'){
		$messageBody = strip_tags($messageBody);
	}
	
	if($host=="" or $username=="" or $password==""){
		$owner_email = $_POST["owner_email"];
		$headers = 'From:' . $_POST["email"] . "\r\n" . 'Content-Type: text/plain; charset=UTF-8' . "\r\n";
		$subject = 'A message from your site visitor ' . $_POST["name"];
		
		try{
			if(!mail($owner_email, $subject, $messageBody, $headers)){
				throw new Exception('mail failed');
				}else{
				echo 'mail sent';
			}
			}catch(Exception $e){
			echo $e->getMessage() ."\n";
		}
	}else{	
		require_once 'Mail.php';

		$to = $_POST["owner_email"];
		$subject = 'A message from your site visitor ' . $_POST["name"];
		$headers = array (
		'From' => 'From:' . $_POST["email"] . "\r\n" . 'Content-Type: text/plain; charset=UTF-8' . "\r\n",
		'To' => $to,
		'Subject' => $subject);
		
		$smtp = Mail::factory(
					'smtp',
					array (
						'host' => $host,
						'port' => $port,
						'auth' => true,
						'username' => $username,
						'password' => $password));

		$mail = $smtp->send($to, $headers, $messageBody);
		
		try{
			if(PEAR::isError($mail)){
				echo $mail->getMessage();
				}else{
				echo 'mail sent';
			}
			}catch(Exception $mail){
			echo $mail->getMessage() ."\n";
		}
	}	
?>
<?php
	$sbj_visitor='Newsletter subscription confirmation email from ';
	$sbj_owner='Newsletter subscription request from ';
	$header="Content-type: text/html; charset=utf-8 \r\n";

	$name=$_POST['name'];
	$email=$_POST['email'];
	$owner=$_POST['owner'];
	$owner_email=$_POST['owner_email'];
	$sitename=$_POST['sitename'];
	$sbj_visitor.=$sitename;
	$sbj_owner.=$sitename;
	
	$msg_visitor='<a href="http://'.$sitename.'">'.$sitename.'</a>'."\n".'<br>'.'Hi, '.$name."\n".'<br>'.'Thank you for subscribing to our newsletter!';		
	$msg_owner='<a href="http://'.$sitename.'">'.$sitename.'</a>'."\n".'<br>'.'This email has been sent via newsletter subscription form on your website. A new visitor would like to be added to your website\'s newsletter:'."\n".'<br>'.'Visitor name: '.$name."\n".'<br>'.'Visitor email: '.$email."\n".'<br>'.'Please add him (her) to your newsletter list.';
	
	try{
		if(!mail($email,$sbj_visitor,$msg_visitor,$header.'From: '.$owner_email)){
			throw new Exception('mail failed');
		}else{
			echo "mail to visitor sent \n";
		}
	}catch(Exception $e){
		echo $e->getMessage() ."\n";
	}
	
	try{
		if(!mail($owner_email,$sbj_owner,$msg_owner,$header.'From: '.$email)){
			throw new Exception('mail failed');
		}else{
			echo "mail to owner sent";
		}
	}catch(Exception $e){
		echo $e->getMessage() ."\n";
	}
?>


<!DOCTYPE html>
<html lang="en">
	<head>
	<title>Home</title>
	<meta charset="utf-8">
	<meta name = "format-detection" content = "telephone=no" />
	<link rel="icon" href="images/favicon.ico">
	<link rel="shortcut icon" href="images/favicon.ico" />
	<link rel="stylesheet" href="css/form.css">
	<link rel="stylesheet" href="css/thumbs.css">
	<link rel="stylesheet" href="css/slider.css">
	<link rel="stylesheet" href="css/style.css">
	<script src="js/jquery.js"></script>
	<script src="js/jquery-migrate-1.2.1.js"></script>
	<script src="js/script.js"></script>
	<script src="js/superfish.js"></script>
	<script src="js/sForm.js"></script>
	<script src="js/jquery.ui.totop.js"></script>
	<script src="js/jquery.equalheights.js"></script>
	<script src="js/jquery.easing.1.3.js"></script>
	<script src="js/jquery.iosslider.min.js"></script>
	<script>
	$(document).ready(function(){
		$().UItoTop({ easingType: 'easeOutQuart' });
		});
	</script>
	<!--[if lt IE 8]>
	<div style=' clear: both; text-align:center; position: relative;'>
		<a href="http://windows.microsoft.com/en-US/internet-explorer/products/ie/home?ocid=ie6_countdown_bannercode">
			<img src="http://storage.ie6countdown.com/assets/100/images/banners/warning_bar_0000_us.jpg" border="0" height="42" width="820" alt="You are using an outdated browser. For a faster, safer browsing experience, upgrade for free today." />
		</a>
	</div>
	<![endif]-->
	<!--[if lt IE 9]>
	<script src="js/html5shiv.js"></script>
	<link rel="stylesheet" media="screen" href="css/ie.css">
	<![endif]-->
	</head>
	<body class="page1" id="top">
<!--==============================header=================================-->
		<header>
			<div class="container_12">
				<div class="grid_12">
					<h1>
						<a href="index.html">
							<img src="images/logo.jpg" alt="Your Happy Family">
						</a>
					</h1>
					<div class="menu_block ">
						<a href="index-4.html" class="donate">DONATE</a>
						<div class="clear"></div>
						<nav class="horizontal-nav full-width horizontalNav-notprocessed">
							<ul class="sf-menu">
								<li class="current"><a href="index.html">Home</a></li>
								<li><a href="index-1.html">What We Do</a></li>
								<li><a href="index-2.html">Media</a></li>
								<li><a href="index-3.html">Take Part</a></li>
								<li><a href="index-4.html">Contacts</a></li>
							</ul>
						</nav>
						<div class="clear"></div>
					</div>
				</div>
			</div>
		</header>
		<div class="fluidHeight container_12">
			<div class="sliderContainer">
				<div class="iosSlider">
					<div class="slider">
						<div class="item item1">
							<div class="inner">
								<div class="text1"><span> Don’t Leave orphans alone <br>they didn’t choose their way here.</span></div>
							</div>
						</div>
						<div class="item item2">
							<div class="inner">
								<div class="text1"><span>Help Children without family <br>as being a part of our family.</span></div>
							</div>
						</div>
						<div class="item item3">
							<div class="inner">
								<div class="text1"><span>The Struggles they go through – unbearable <br> but they bare it with your help.</span></div>
							</div>
						</div>
					</div>
				</div>
				<div class="slideSelectors">
					<div class="item selected"></div>
					<div class="item"></div>
					<div class="item"></div>
				</div>
			</div>
		</div>
<!--==============================Content=================================-->
			<div class="container_12">
				<div class="grid_6">
					<h2>Meet Our Team</h2>
					<img src="images/page1_img1.jpg" alt="" class="img_inner fleft">
					<div class="extra_wrapper">
						<p style="text-align:justify;"class="col2"><a href="#">Initially our team started with three members, or three friends, with the head of this idea specializing in social service, things were made easier for us.
							Things started progressing quickly and now our team grew a lot.</p><br>
						
					</div>
					<div class="clear"></div>
				</div>
				<div class="grid_5 prefix_1">
					<h2>Our Mission</h2>
					<div class="rel1">
						<p style="text-align:justify;">Our approach is to help people who are in need. The children
							without a family is a terror to imagine. We will be able to comprehend to
							their pain. So we decided to help them in whatever we can. So we
							started with clothes. The clothes we need to cover ourselves in both
							winter or rainy days. WE need them as much as food. And that’s when
							we came up with an idea of clothes, we all have clothes extra clothes
							which we never use or moved on to a different style.so we decided to
							collect all of those non-used , well conditioned clothes and give it to the
							children who needs it. We started to the service that takes clothes from
							one person to another who is in need despite of their age.</p>
					</div>
					
				</div>
			</div>
			<div class="hor"></div>
			<div class="container_12">
				<div class="grid_3">
					<h2></h2><br><br>
					<img src="images/newpic1.jpeg">
					
				</div>
				<div class="grid_9">
					<h2>Our Campaigns</h2>
					<div class="rel1">
						<p style="text-align:justify;"><b><time datetime="2014-10-07">07<span>OCT</span></time><br>POOJA FESTIVAL</b><br>On 2019, on a Pooja festival,we were on a campus around Guindy and t nagar area as we were crossing through the streets. 
							We came across few women trying to burn bags and bags of old non used clothes. 
							And we explained them about the service do and they were kind enough to give us those clothes and some sweets. 
							We took it to our place, washed the clothes and separated into reusable clothes, 
							gave it to St.Anthony's orphanage to around 150+ children. 
							The children were beyond happy and was so nice to look at their faces.<br>
						</div>
						<div class="rel1">
							<p style="text-align:justify;"><b><time datetime="2014-01-26">26<span>JAN</span></time><br>REPUBLIC DAY</b>
								<br>On republic day. We went to 20+orphanages in vellor. 
								We celebrated the day with sweets and few new clothes from the donation and 
								we were so happy to give awareness to the children about independence and how strong they should be to come across all the struggles in their lives. 
								We were so happy to be a part of their lives and help to grow strong in this world and they were to happy and motivated to proceed their ways in life.<br>
							</div>
							<div class="rel1">
								<p style="text-align:justify;"><b><time datetime="2014-08-02">02<span>AUG</span></time><br>WITH A SPECIAL GUEST</b>
									<br>The word of our work has spread! 
									On 15th August we were so surprised to get a call from Suriya, 
									the actor and he was so kind and appreciated us  for the work we do and 
									took part in it by supported us with some cash and new clothes for the childrenand elders.
									He presented some gifts to the orphanages and 
									we were so glad that our work as a service which we do will all our hearts have grown so much, 
									that we can help others as much as we can with the help of such good hearted people.	
				</div>
			</div>
		</div>
		<!-- <div class="bottom_block">
			<div class="container_12">
				<div class="grid_4">
					<h3>Stay Informed</h3>
					<div class="text1">Subscribe to Our Newsletter</div>
					<form id="newsletter">
						<div class="rel">
							<div class="success">Your subscribe request has been sent!</div>
							<label class="email">
								<input type="email" value="Enter your Email" >
								<span class="error">*This is not a valid email address.</span>
							</label>
						</div>
						<a href="#" class="btn" data-type="submit">Submit</a>
					</form>
				</div>  -->
				<div class="grid_5 prefix_3">
					<h3>Stay Connected</h3>
					<div class="text1">Follow Us on Social Media Accounts </div>
					<div class="socials">
						<a href="#"><div class="fa fa-twitter"></div></a>
						<a href="#"><div class="fa fa-facebook"></div></a>
						<a href="#"><div class="fa fa-pinterest-square"></div></a>
						<a href="#"><div class="fa fa-google-plus"></div></a>
						<a href="#"><div class="fa fa-instagram"></div></a>
					</div>
				</div>
			</div>
		</div>
<!--==============================footer=================================-->
		<footer>
			<div class="container_12">
				<div class="grid_12">
					<div class="copy">
						Delighted services &copy; 2021 | <a href="#">Privacy Policy</a> <br> Website designed by Saai, Prithvi, Merlin</a>
					</div>
				</div>
			</div>
		</footer>
		
		<script>
		$(document).ready(function() {
		 $('.iosSlider').iosSlider({
			desktopClickDrag: true,
			snapToChildren: true,
			navSlideSelector: '.sliderContainer .slideSelectors .item',
			onSlideComplete: slideComplete,
			onSliderLoaded: sliderLoaded,
			onSlideChange: slideChange,
			scrollbar: false,
			autoSlide: true,
			autoSlideTimer: 3300,
			infiniteSlider: true
		 });
		});
		function slideChange(args) {
		 $('.sliderContainer .slideSelectors .item').removeClass('selected');
		 $('.sliderContainer .slideSelectors .item:eq(' + (args.currentSlideNumber - 1) + ')').addClass('selected');
		}
		function slideComplete(args) {
		 if(!args.slideChanged) return false;
		 $(args.sliderObject).find('.text1, .text2').attr('style', '');
		 $(args.currentSlideObject).find('.text1').animate({
			right: '100px',
			opacity: '0.72'
		 }, 400, 'easeOutQuint');
		 $(args.currentSlideObject).find('.text2').delay(200).animate({
			right: '70px',
			opacity: '0.72'
		 }, 400, 'easeOutQuint');
		}
		function sliderLoaded(args) {
		 $(args.sliderObject).find('.text1, .text2').attr('style', '');
		 $(args.currentSlideObject).find('.text1').animate({
			right: '100px',
			opacity: '0.72'
		 }, 400, 'easeOutQuint');
		 $(args.currentSlideObject).find('.text2').delay(200).animate({
			right: '70px',
			opacity: '0.72'
		 }, 400, 'easeOutQuint');
		 slideChange(args);
		}
		</script>
	</body>
</html>


<!DOCTYPE html>
<html lang="en">
	<head>
		<title>What We Do</title>
		<meta charset="utf-8">
		<meta name = "format-detection" content = "telephone=no" />
		<link rel="icon" href="images/favicon.ico">
		<link rel="shortcut icon" href="images/favicon.ico" />
		<link rel="stylesheet" href="css/form.css">
		<link rel="stylesheet" href="css/style.css">
		<script src="js/jquery.js"></script>
		<script src="js/jquery-migrate-1.2.1.js"></script>
		<script src="js/script.js"></script>
		<script src="js/superfish.js"></script>
		<script src="js/sForm.js"></script>
		<script src="js/jquery.ui.totop.js"></script>
		<script src="js/jquery.equalheights.js"></script>
		<script src="js/jquery.easing.1.3.js"></script>
		<script>
		$(document).ready(function(){
			$().UItoTop({ easingType: 'easeOutQuart' });
			});
		</script>
		<!--[if lt IE 8]>
		<div style=' clear: both; text-align:center; position: relative;'>
			<a href="http://windows.microsoft.com/en-US/internet-explorer/products/ie/home?ocid=ie6_countdown_bannercode">
				<img src="http://storage.ie6countdown.com/assets/100/images/banners/warning_bar_0000_us.jpg" border="0" height="42" width="820" alt="You are using an outdated browser. For a faster, safer browsing experience, upgrade for free today." />
			</a>
		</div>
		<![endif]-->
		<!--[if lt IE 9]>
		<script src="js/html5shiv.js"></script>
		<link rel="stylesheet" media="screen" href="css/ie.css">
		<![endif]-->
		</head>
	<body class="" id="top">
<!--==============================header=================================-->
		<header>
			<div class="container_12">
				<div class="grid_12">
					<h1>
						<a href="index.html">
							<img src="images/logo.jpg" alt="Your Happy Family">
						</a>
					</h1>
					<div class="menu_block">
						<a href="#" class="donate">DONATE</a>
						<div class="clear"></div>
						<nav class="horizontal-nav full-width horizontalNav-notprocessed">
							<ul class="sf-menu">
								<li><a href="index.html">Home</a></li>
								<li class="current"><a href="index-1.html">What We Do</a></li>
								<li><a href="index-2.html">Media</a></li>
								<li><a href="index-3.html">Take Part</a></li>
								<li><a href="index-4.html">Contacts</a></li>
							</ul>
						</nav>
						<div class="clear"></div>
					</div>
				</div>
			</div>
		</header>
<!--==============================Content=================================-->
		<div class="content"><div class="ic"></div>
			<div class="container_12">
				<div class="grid_6">
					<h2>We Care About Giving</h2>
					<img src="images/page2_img1.jpg" alt="" class="img_inner fleft">
					<div class="extra_wrapper">
						<p class="col2"><a href="#">Most of us are living a not so bad life, so why not give some to 
							kids who haven't even know what it is. Just send us the details and we will take it from there.					<br>
						
					</div>
					<div class="clear cl1"></div>
					<img src="images/page2_img2.jpg" alt="" class="img_inner fleft">
					<div class="extra_wrapper">
						<p class="col2"><a href="#">We will dry clean the clothes you donate and personally see to 
							that, they are delivered safely.
						<br>
						
					</div>
					<div class="clear cl2"></div>
					<img src="images/page2_img3.jpg" alt="" class="img_inner fleft">
					<div class="extra_wrapper">
						<p class="col2"><a href="#">Every donating personality or donating group will get a confirmation of their 
						things getting delivered, which can be pictures or a signed confirmation from the orphanage authority.
						<br>
						
					</div>
					<div class="clear cl1"></div>
				</div>
				<div class="grid_5 prefix_1">
					<h2>Upcoming Actions</h2>
					<ul class="list l1 col2">
						<li>
							<time datetime="2021-04-14">14<span>APR</span></time>
							<div class="extra_wrapper">
								<div class="title col2"><a href="#">MADURAI</a></div>
								To Celebrate Tamil New Year with orphans in Madurai muthu orphanage.
							</div>
						</li>
						<li>
							<time datetime="2021-04-22">22<span>APR</span></time>
							<div class="extra_wrapper">
								<div class="title col2"><a href="#">VELLOR</a></div>
								Will be taking children from vellor gokul orphanage to farm land to celebrate Earth day.
							</div>
						</li>
						<li>
							<time datetime="2021-05-14">14<span>MAY</span></time>
							<div class="extra_wrapper">
								<div class="title col2"><a href="#">CHENNAI</a></div>
								Planing on distributing biriyanis to all the orphan children in chennai, on occasion of ramzan. 
							</div>
						</li>
					</ul>
				</div>
			</div>
			<div class="hor hr1"></div>
			<div class="container_12">
				<div class="grid_3 maxheight">
					<h2>Testimonials</h2>
					<blockquote class="bq2">
						<p>We started our journey with Delighted service over 2 years ago and have 
							worked with quite a few staff members in both hosting and adoption. 
							Everyone has been amazing in helping us work through the process. You 
							guys truly care about these kiddos and have become like family to us!</p>
						<div class="bq_bot">Kowshik Khan, <a href="#" class="col1">KowshikM@demolink.org</a></div>
					</blockquote>
				</div>
				<div class="grid_4 prefix_1 suffix_1 ver maxheight">
					<h2>Testimonials</h2>
					<blockquote class="bq2">
						<p>All of the staff were friendly, helpful and encouraging. This was a 
							wonderful experience. Thank you,</p>
							<div class="bq_bot">Janz Ro, <br><a href="#" class="col1">Janzro@demolink.org</a></div>
					</blockquote>
				</div>
				<div class="grid_3 maxheight">
					<h2>Testimonials</h2>
					<blockquote class="bq2">
						<p>Most wonderful experience and would definitely do it again cause
							money wasn’t an obstacle, actually they never asked it for the service 
							they do! It’s an incredible feeling to know that you were a link to a child 
							finding their forever family!</p>
						<div class="bq_bot">Artist Naresh, <a href="#" class="col1">Smilyarts@demolink.org</a></div>
					</blockquote>
					
				</div>
			</div>
		</div>
		<!--div class="bottom_block">
			<div class="container_12">
				<div class="grid_4 ">
					<h3>Stay Informed</h3>
					<div class="text1">Subscribe to Our Newsletter</div>
					<form id="newsletter">
						<div class="rel">
							<div class="success">Your subscribe request has been sent!</div>
							<label class="email">
								<input type="email" value="Enter your Email" >
								<span class="error">*This is not a valid email address.</span>
							</label>
						</div>
						<a href="#" class="btn" data-type="submit">Submit</a>
					</form>
				</div -->
				<div class="grid_5 prefix_3">
					<h3>Stay Connected</h3>
					<div class="text1">Follow Us on Social Media Accounts </div>
					Cras facilisis, nulla vel viverra auctor, leo magna sodales felis, quis malesuada nibh odio ut velit. Proin pharetra
					<div class="socials">
						<a href="#"><div class="fa fa-twitter"></div></a>
						<a href="#"><div class="fa fa-facebook"></div></a>
						<a href="#"><div class="fa fa-pinterest-square"></div></a>
						<a href="#"><div class="fa fa-google-plus"></div></a>
						<a href="#"><div class="fa fa-instagram"></div></a>
					</div>
				</div>
			</div>
		</div>
<!--==============================footer=================================-->
		<footer>
			<div class="container_12">
				<div class="grid_12">
					<div class="copy">
						Life &copy; 2021 | <a href="#">Privacy Policy</a> <br> Website designed by Saai, Prithvi, Merlin</a>
					</div>
				</div>
			</div>
		</footer>
	</body>
</html>


<!DOCTYPE html>
<html lang="en">
	<head>
		<title>Media</title>
		<meta charset="utf-8">
		<meta name = "format-detection" content = "telephone=no" />
		<link rel="icon" href="images/favicon.ico">
		<link rel="shortcut icon" href="images/favicon.ico" />
		<link rel="stylesheet" href="css/form.css">
		<link rel="stylesheet" href="css/style.css">
		<script src="js/jquery.js"></script>
		<script src="js/jquery-migrate-1.2.1.js"></script>
		<script src="js/script.js"></script>
		<script src="js/superfish.js"></script>
		<script src="js/sForm.js"></script>
		<script src="js/jquery.ui.totop.js"></script>
		<script src="js/jquery.equalheights.js"></script>
		<script src="js/jquery.easing.1.3.js"></script>
		<script>
		$(document).ready(function(){
			$().UItoTop({ easingType: 'easeOutQuart' });
			});
		</script>
		<!--[if lt IE 8]>
		<div style=' clear: both; text-align:center; position: relative;'>
			<a href="http://windows.microsoft.com/en-US/internet-explorer/products/ie/home?ocid=ie6_countdown_bannercode">
			<img src="http://storage.ie6countdown.com/assets/100/images/banners/warning_bar_0000_us.jpg" border="0" height="42" width="820" alt="You are using an outdated browser. For a faster, safer browsing experience, upgrade for free today." />
			</a>
		</div>
		<![endif]-->
		<!--[if lt IE 9]>
		<script src="js/html5shiv.js"></script>
		<link rel="stylesheet" media="screen" href="css/ie.css">
		<![endif]-->
	</head>
	<body class="" id="top">
<!--==============================header=================================-->
		<header>
			<div class="container_12">
				<div class="grid_12">
					<h1>
						<a href="index.html">
							<img src="images/logo.jpg" alt="Your Happy Family">
						</a>
					</h1>
					<div class="menu_block ">
						<a href="#" class="donate">DONATE</a>
						<div class="clear"></div>
						<nav class="horizontal-nav full-width horizontalNav-notprocessed">
							<ul class="sf-menu">
								<li><a href="index.html">Home</a></li>
								<li><a href="index-1.html">What We Do</a></li>
								<li class="current"><a href="index-2.html">Media</a></li>
								<li><a href="index-3.html">Take Part</a></li>
								<li><a href="index-4.html">Contacts</a></li>
							</ul>
						</nav>
						<div class="clear"></div>
					</div>
				</div>
			</div>
		</header>
<!--==============================Content=================================-->
		<div class="content"><div class="ic"></div>
			<div class="container_12">
				<div class="grid_7">
					<div class="block2">
						<h2><a href="https://youtu.be/gg16HNVtAO0">Orphans of India</a></h2>
						<figure class="video">
							<iframe width="640" height="360" src="http://www.youtube.com/embed/gg16HNVtAO0?feature=player_detailpage" frameborder="0" allowfullscreen></iframe>
						</figure>
						A Short documentry on Orphans of India.
					</div>
					<div class="block2">
						<h2> <a href="https://youtu.be/iXel1Vmvmhw">Run It Forward - Official Charity (Promo Video)</a></h2>
						<figure class="video">
							<iframe width="640" height="360" src="http://www.youtube.com/embed/iXel1Vmvmhw?feature=player_detailpage" frameborder="0" allowfullscreen></iframe>
						</figure> Here is a famous motivational video on "Sharing is Caring"
					</div>
					<div class="block2">
						<h2><a href="http://www.youtube.com/watch?v=DEnlrE4iMBU">World Water Day Video from Charity: Water</a></h2>
						<figure class="video">
							<iframe width="640" height="360" src="http://www.youtube.com/embed/DEnlrE4iMBU?feature=player_detailpage" frameborder="0" allowfullscreen></iframe>
						</figure>
						An awarness video on World water day.
					</div>
				</div>
				<div class="grid_4 prefix_1">
					<h2>Top Videos</h2>
					<ul class="list2 col2">
						<li><a href="https://youtu.be/ciDWsRc0zMM">Orphan Prevention</a></li>
						<li><a href="https://youtu.be/isnt5XU1NQQ">Orphans in need</a></li>
						<li><a href="https://youtu.be/Q4SO49Sfk6Y">The orphan complex</a></li>
						<li><a href="https://youtu.be/QeLCumGkXd8">Five basic needs of child</a></li>
						<li><a href="https://youtu.be/9M9KotK1gYM">World Earth day</a></li>
						<li><a href="https://youtu.be/otrpxtAmDAk">Fresh water scarcity</a></li>
						<li><a href="https://youtu.be/uWvQdBJqqWE">Orphanage Visit</a></li>
					</ul>

				</div>
			</div>
		</div>
		<!--div class="bottom_block">
			<div class="container_12">
				<div class="grid_4 ">
					<h3>Stay Informed</h3>
					<div class="text1">Subscribe to Our Newsletter</div>
					<form id="newsletter">
						<div class="rel">
							<div class="success">Your subscribe request has been sent!</div>
							<label class="email">
								<input type="email" value="Enter your Email" >
								<span class="error">*This is not a valid email address.</span>
							</label>
						</div>
						<a href="#" class="btn" data-type="submit">Submit</a>
					</form>
				</div -->
				<div class="grid_5 prefix_3">
					<h3>Stay Connected</h3>
					<div class="text1">Follow Us on Social Media Accounts </div>
					<div class="socials">
						<a href="#"><div class="fa fa-twitter"></div></a>
						<a href="#"><div class="fa fa-facebook"></div></a>
						<a href="#"><div class="fa fa-pinterest-square"></div></a>
						<a href="#"><div class="fa fa-google-plus"></div></a>
						<a href="#"><div class="fa fa-instagram"></div></a>
					</div>
				</div>
			</div>
		</div>
<!--==============================footer=================================-->
		<footer>
			<div class="container_12">
				<div class="grid_12">
					<div class="copy">
						Life &copy; 2021 | <a href="#">Privacy Policy</a> <br>Website designed by Saai, Prithvi, Merlin </a>
					</div>
				</div>
			</div>
		</footer>
	</body>
</html>


<!DOCTYPE html>
<html lang="en">
	<head>
		<title>Get Involved</title>
		<meta charset="utf-8">
		<meta name = "format-detection" content = "telephone=no" />
		<link rel="icon" href="images/favicon.ico">
		<link rel="shortcut icon" href="images/favicon.ico" />
		<link rel="stylesheet" href="css/form.css">
		<link rel="stylesheet" href="css/touchTouch.css">
		<link rel="stylesheet" href="css/style.css">
		<script src="js/jquery.js"></script>
		<script src="js/jquery-migrate-1.2.1.js"></script>
		<script src="js/script.js"></script>
		<script src="js/superfish.js"></script>
		<script src="js/sForm.js"></script>
		<script src="js/jquery.ui.totop.js"></script>
		<script src="js/jquery.equalheights.js"></script>
		<script src="js/jquery.easing.1.3.js"></script>
		<script src="js/touchTouch.jquery.js"></script>
		<script>
		$(document).ready(function(){
			$().UItoTop({ easingType: 'easeOutQuart' });
			$('.gallery a.gal').touchTouch();
			});
		</script>
		<!--[if lt IE 8]>
		<div style=' clear: both; text-align:center; position: relative;'>
			<a href="http://windows.microsoft.com/en-US/internet-explorer/products/ie/home?ocid=ie6_countdown_bannercode">
			<img src="http://storage.ie6countdown.com/assets/100/images/banners/warning_bar_0000_us.jpg" border="0" height="42" width="820" alt="You are using an outdated browser. For a faster, safer browsing experience, upgrade for free today." />
			</a>
		</div>
		<![endif]-->
		<!--[if lt IE 9]>
		<script src="js/html5shiv.js"></script>
		<link rel="stylesheet" media="screen" href="css/ie.css">
		<![endif]-->
	</head>
	<body class="" id="top">
<!--==============================header=================================-->
		<header>
			<div class="container_12">
				<div class="grid_12">
					<h1>
						<a href="index.html">
							<img src="images/logo.jpg" alt="Your Happy Family">
						</a>
					</h1>
					<div class="menu_block ">
						<a href="#" class="donate">DONATE</a>
						<div class="clear"></div>
						<nav class="horizontal-nav full-width horizontalNav-notprocessed">
							<ul class="sf-menu">
								<li><a href="index.html">Home</a></li>
								<li><a href="index-1.html">What We Do</a></li>
								<li><a href="index-2.html">Media</a></li>
								<li class="current"><a href="index-3.html">Take Part</a></li>
								<li><a href="index-4.html">Contacts</a></li>
							</ul>
						</nav>
						<div class="clear"></div>
					</div>
				</div>
			</div>
		</header>
<!--==============================Content=================================-->

<div class="grid_5 prefix_1">
	<h2>Our Mission</h2>
	<div class="rel1">
		<p style="text-align:justify;">Help bring that purest smile of happiness in the face
			- And you are the reason for it. We are the reason for it. We all are!
			We are humble enough to take out time from our lives to help children 
			those are in need. Our holistic approach begins by nurturing orphans 
			with their needs cause if they get proper attention and care, they will 
			the future gentlemen and women in our society bring it forward. Our 
			care starts in the cradle and ends with them becoming interdependent, 
			contributing members of the society</p>
	</div>

	<div class="container_12">
				<div class="gallery">
					<div class="grid_3">
						<h2>MEDICAL</h2>
						<a href="images/medical.jpg" class="gal"><img src="images/medical.jpg" alt=""></a>
						We provide basic and urgent medical needs of the children with all we've got.
					
					</div>
					<div class="grid_3">
						<h2>MATERIAL</h2>
						<a href="images/materials.jpg" class="gal"><img src="images/materials.jpg" alt=""></a>
						All material needs like books, clothes will be taken care of.
					</div>
					<div class="grid_3">
						<h2>EDUCATION</h2>
						<a href="images/education.jpg" class="gal"><img src="images/education.jpg" alt=""></a>
						We also provide education to the children with workshops and classes then and there.
					</div>
					<div class="grid_3">
						<h2>SPORTS</h2>
						<a href="images/sports.jpg" class="gal"><img src="images/sports.jpg" alt=""></a>
						Sports events will be conducted on certain occasion.
					</div>
					</div>
					</div>
	<div class="grid_5 prefix_1">
		<h2>Our Mission</h2>
		<div class="rel1">
			<p style="text-align:justify;">Our Focus:
				Fortunately, our idea blow up…many people were kind to take 
				part with us in our service. With all your help we have helped more than 
				1000+ children and adults and gave them to orphanages.
				So now we have planned to expand it to more other states and our next 
				plan is to include food in our service. We will collect the food that goes 
				unused in many restaurants and make sure that children in the 
				orphanages gets them on time. And are taking all the steps forward for 
				the plan to work and will be update on this page.</p>

<div class="content"><div class="ic"></div>
			<div class="container_12">
				<div class="gallery">
					<div class="grid_3">
						<h2>EXTRA CURRICULAR</h2>
						<a href="images/extra.jpg" class="gal"><img src="images/extra.jpg" alt=""></a>
						We appreciate, encourage and support all extra curricular activities by children
					</div>
					<div class="grid_3">
						<h2>FOOD</h2>
						<a href="images/food.jpg" class="gal"><img src="images/food.jpg" alt=""></a>
						We provide special meals during special occasions to some orphanages
					</div>
					<div class="grid_3">
						<h2>ENTERTAINMENT</h2>
						<a href="images/entertainment.jpg" class="gal"><img src="images/entertainment.jpg" alt=""></a>
						Entertainment based programs will be conducted then and there.
					
					</div>
					<div class="grid_3">
						<h2>HEALTH</h2>
						<a href="images/Health.png" class="gal"><img src="images/Health.png" alt=""></a>
					Regular health checkups, food and water testing will be conducted.
					</div>
				</div>
			</div>
		</div>
		<!--div class="bottom_block">
			<div class="container_12">
				<div class="grid_4 ">
					<h3>Stay Informed</h3>
					<div class="text1">Subscribe to Our Newsletter</div>
					<form id="newsletter">
						<div class="rel">
							<div class="success">Your subscribe request has been sent!</div>
							<label class="email">
								<input type="email" value="Enter your Email" >
								<span class="error">*This is not a valid email address.</span>
							</label>
						</div>
						<a href="#" class="btn" data-type="submit">Submit</a>
					</form>
				</div-->
				<div class="grid_5 prefix_3">
					<h3>Stay Connected</h3>
					<div class="text1">Follow Us on Social Media Accounts </div>
					<div class="socials">
						<a href="#"><div class="fa fa-twitter"></div></a>
						<a href="#"><div class="fa fa-facebook"></div></a>
						<a href="#"><div class="fa fa-pinterest-square"></div></a>
						<a href="#"><div class="fa fa-google-plus"></div></a>
						<a href="#"><div class="fa fa-instagram"></div></a>
					</div>
				</div>
			</div>
		</div>
<!--==============================footer=================================-->
		<footer>
			<div class="container_12">
				<div class="grid_12">
					<div class="copy">
						Life &copy; 2021 | <a href="#">Privacy Policy</a> <br> Website designed by Saai, Prithvi, Merlin </a>
					</div>
				</div>
			</div>
		</footer>
	</body>
</html>


<!DOCTYPE html>
<html lang="en">
	<head>
		<title>Contacts</title>
		<meta charset="utf-8">
		<meta name = "format-detection" content = "telephone=no" />
		<link rel="icon" href="images/favicon.ico">
		<link rel="shortcut icon" href="images/favicon.ico" />
		<link rel="stylesheet" href="css/form.css">
		<link rel="stylesheet" href="css/style.css">
		<script src="js/jquery.js"></script>
		<script src="js/jquery-migrate-1.2.1.js"></script>
		<script src="js/script.js"></script>
		<script src="js/superfish.js"></script>
		<script src="js/sForm.js"></script>
		<script src="js/TMForm.js"></script>
		<script src="js/jquery.ui.totop.js"></script>
		<script src="js/jquery.equalheights.js"></script>
		<script src="js/jquery.easing.1.3.js"></script>
		<script>
		$(document).ready(function(){
			$().UItoTop({ easingType: 'easeOutQuart' });
			});
		</script>
		<!--[if lt IE 8]>
		<div style=' clear: both; text-align:center; position: relative;'>
			<a href="http://windows.microsoft.com/en-US/internet-explorer/products/ie/home?ocid=ie6_countdown_bannercode">
			<img src="http://storage.ie6countdown.com/assets/100/images/banners/warning_bar_0000_us.jpg" border="0" height="42" width="820" alt="You are using an outdated browser. For a faster, safer browsing experience, upgrade for free today." />
			</a>
		</div>
		<![endif]-->
		<!--[if lt IE 9]>
		<script src="js/html5shiv.js"></script>
		<link rel="stylesheet" media="screen" href="css/ie.css">
		<![endif]-->
	</head>
	<body class="" id="top">
<!--==============================header=================================-->
		<header>
			<div class="container_12">
				<div class="grid_12">
					<h1>
						<a href="index.html">
							<img src="images/logo.jpg" alt="Your Happy Family">
						</a>
					</h1>
					<div class="menu_block">
						<a href="#" class="donate">DONATE</a>
						<div class="clear"></div>
						<nav class="horizontal-nav full-width horizontalNav-notprocessed">
							<ul class="sf-menu">
								<li><a href="index.html">Home</a></li>
								<li><a href="index-1.html">What We Do</a></li>
								<li><a href="index-2.html">Media</a></li>
								<li><a href="index-3.html">Take Part</a></li>
								<li class="current"><a href="index-4.html">Contacts</a></li>
							</ul>
						</nav>
						<div class="clear"></div>
					</div>
				</div>
			</div>
		</header>
<!--==============================Content=================================-->
		<div class="content"><div class="ic"></div>
			<div class="container_12">
				<div class="grid_12">
					<h2>Find Us</h2>
					<div class="map">
						<figure class="">
							<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3890.401741846896!2d80.03807321413366!3d12.817296221714928!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3a52f76e6445c2f5%3A0x683ba4681cb9b36a!2sAbode%20Valley!5e0!3m2!1sen!2sin!4v1615713586021!5m2!1sen!2sin" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
						</figure>
						<div class="grid_4 alpha">
							<h2>Address:</h2>
							<address>
								<span class="fa fa-home"></span>
								54, Kakkan St, <br>
								Potheri <br>
								Tamil Nadu 603203
							</address>
						</div>
						<div class="grid_4">
							<h2>Phones:</h2>
							<div class="m_phone">
								<div class="fa fa-phone"></div>
								+91 9003658020
							</div>
							<div class="m_phone">
								<div class="fa fa-print"></div>
								+91 9003658030
							</div>
						</div>
						<div class="grid_4 omega">
							<h2>Email:</h2>
							<a href="#"><span class="fa fa-envelope-o"></span> DsContact@DS.org</a>
						</div>
						<div class="clear"></div>
					</div>
				</div>
			</div>
		</div>
					<!-- feedback form -->
<section class="feed">
	<div class="feed-container">
	  <div class="contactInfo">
		<h2 class="title">Feedback</h2></div>
		<div class="contactForm">
		  <h2>Send a Message</h2>
		  <form action="./bat/connect.php" method="POST">
		  <div class="formBox">
			<div class="inputBox w50">
			  <input type="text" name="firstName" id="text" required>
			  <span>First Name</span>
			</div>
			<div class="inputBox w50">
			  <input type="text" name="lastName" required>
			  <span>Last Name</span>
			</div>
			<div class="inputBox w50">
			  <input type="text" name="email" required>
			  <span>E-Mail Address</span>
			</div>
			<div class="inputBox w50">
			  <input type="text" name="number" required>
			  <span>Mobile Number</span>
			</div>
			<div class="inputBox w100">
			  <textarea name="feedBack" required></textarea>
			  <span>Write your message here...</span>
			</div>
			<div class="inputBox w100">
			  <input type="submit" value="Submit" name="submit">
			</div>
		  </div>
		</form>
		</div>
	</div>
  </section>
			
		<!--div class="bottom_block">
			<div class="container_12">
				<div class="grid_4 ">
					<h3>Stay Informed</h3>
					<div class="text1">Subscribe to Our Newsletter</div>
					<form id="newsletter">
						<div class="rel">
							<div class="success">Your subscribe request has been sent!</div>
							<label class="email">
								<input type="email" value="Enter your Email" >
								<span class="error">*This is not a valid email address.</span>
							</label>
						</div>
						<a href="#" class="btn" data-type="submit">Submit</a>
					</form>
				</div-->
				<div class="grid_5 prefix_3">
					<h3>Stay Connected</h3>
					<div class="text1">Follow Us on Social Media Accounts </div>
					<div class="socials">
						<a href="#"><div class="fa fa-twitter"></div></a>
						<a href="#"><div class="fa fa-facebook"></div></a>
						<a href="#"><div class="fa fa-pinterest-square"></div></a>
						<a href="#"><div class="fa fa-google-plus"></div></a>
						<a href="#"><div class="fa fa-instagram"></div></a>
					</div>
				</div>
			</div>
		</div>
<!--==============================footer=================================-->
		<footer>
			<div class="container_12">
				<div class="grid_12">
					<div class="copy">
						Life &copy; 2021 | <a href="#">Privacy Policy</a> <br> Website designed by Saai, Prithvi, Merlin</a>
					</div>
				</div>
			</div>
		</footer>
	</body>
</html>



