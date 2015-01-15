OXID eShop Mobile Theme & OXID eShop theme switch
============================================

The extension OXID eShop Mobile Theme consists of a mobile theme and a module that is able to switch between different user agents.

![OXID eShop mobile theme](mobile.png)

###Features

* Checkout
* Products filter
* Products sorting
* Search
* Browse through categories and products
* Login/Register
* PayPal is already built in
* CMS pages
* Switch to standard website
* Supporting OXID eShop Community Edition & Enterprise Edition
* Full legal compliance

###Setup

As this extension consists of two components, the "theme switch" module and the theme itself, two installation steps have to be done.

<b>Theme installation</b>:

1. Copy the files from "theme/source" to your shop directory.<br>
2. Please do not activate the OXID eShop mobile theme. Leave the theme you want to be displayed, for non-mobile devices, activated (for example "Azure"). The "theme switch" module will recognize a mobile device and switch automatically to the mobile theme.<br>

<b>"Theme switch" module installation:</b>

1. Copy the files from "module/source" to your shop directory.<br>
2. Activate the module.<br>
3. The "theme switch" module allows you to switch to any theme you want. To use a different theme then the default, enter the name of the theme that should be used with mobile devices in the module settings. This theme must be installed before configured in the theme switcher settings.<br>
4. If you are using the varnish cache (EE only), please merge the file "device.vcl" with your existing varnish configuration file. If you're not running an EE you can ditch this file.<br>

###License

OXID eSales Mobile Theme extension is free software: you can redistribute and/or modify it under the terms of the GNU General Public License as published by Free Software Foundation, either version 3 of the License, or (at your option) any later version.

OXID eSales Mobile Theme extension is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with OXID eSales Mobile Theme extension.  If not, see <http://www.gnu.org/licenses/>.
