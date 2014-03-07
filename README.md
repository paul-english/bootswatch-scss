Bootswatch-Sass
==========

Bootswatch-sass is a version of the [bootswatch](https://github.com/thomaspark/bootswatch) themes
packaged as scss and made for use as a bower component.

Usage
-----

Install it to your bower componenet using,

    bower install bootswatch-scss

In the styles file you wish to use it in you may have something
similar to,

    @import "bootstrap-sass-official/vendor/assets/stylesheets/bootstrap/variables;
    @import "bootswatch-scss/readable/variables";
    @import "bootstrap-sass-official/vendor/assets/stylesheets/bootstrap/bootstrap";
    @import "bootswatch-scss/readable/bootswatch";

It seems you have to shuffle the variables import around to make it load correctly. Some variable files will require the original bootstrap variables before as well. See `global/build.scss` for a working example.

Copyright and License
----

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
