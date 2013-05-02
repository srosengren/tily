# Tily - A CSS based flexible tile system
## Project site
[http://srosengren.github.io/tily/](http://srosengren.github.io/tily/)

## Documentation
[http://srosengren.github.io/tily/how-to.html](http://srosengren.github.io/tily/how-to.html)

## Why?
Defining tiles for a simple use case isn't hard, but when you add requirements of a fluid site layout and device specific layouts, the complexity adds up. Tily solves these issues for you, all you have to do is drop your tiles in wherever you need them.

## Devices?
Tily is a fully fluid system meaning that your tiles will fit wherever you put them. The default Tily configuration also ships with transforming rows and tiles that allows you to create layouts that will look different depending on the devices screen size.

## Browsers?
Tily is built to support modern and semi-modern browsers that support the box-sizing: border-box; CSS attribute. This means that IE8 and up is supported along with most other browsers.

## Installation and dependancies
Tily has no dependancies since it's built from the ground up as a single file CSS framework. This also means that installation is as simple as adding a reference to tily.css to your website.

## Usage
The simplest usage of tily is to add * number of tiles to a container, this is done by inserting a .tile-row with .tile's in it.
<div class="tile-row tiles4">
	<div class="tile">
		<div class="tile-content"></div>
	</div>
	<div class="tile">
		<div class="tile-content"></div>
	</div>
	<div class="tile">
		<div class="tile-content"></div>
	</div>
	<div class="tile">
		<div class="tile-content"></div>
	</div>
</div>

## Copyright and license
Copyright 2013 Sebastian Rosengren

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

[http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.