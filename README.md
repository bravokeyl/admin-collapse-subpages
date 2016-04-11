# Admin Collapse Subpages

- Contributors:  bravokeyl ,lupka 

- Tags: page, post, links,pages, admin , link ,plugin, random, posts, widget, categories, date, date range, timeframe, excerpt, randomize, sidebar, category

- Requires at least: 3.0

- Tested up to: 4.5

- Stable tag: trunk

- License: GPLv2 or later

- License URI: http://www.gnu.org/licenses/gpl-2.0.html

Using this plugin one can easily collapse/expand pages with children and grand children.

## Description

Simple plugin that allows you to collapse subpages in the Pages admin list also for custom post types that are heirarchial. Especially helpful if you have a ton of pages /cpt's with heiararchial set to true. It uses a cookie to save the expand/collapse status of your pages.

This is loosely based on Collapse Sub-Pages by Dan Dietz, which broke with the 3.0 upgrade due to UI changes and hasn't been updated. I've had to rewrite the jQuery to make it work with 3.x versions. 

Because this is a jQuery, it's possible that they could make additional changes that would break it. I'll do my best to stay on top of it, but let me know if it stops working.

** What's new in Version 2.0 ? **

- Fix en-queuing of scripts .
- Expand all , Collapse all links appear only on the pages list not on every list (like plugins ,posts etc.,)
- Updated jQuery.cookie.js to 1.4.0

## Installation

- Download, unzip, and upload the 'admin-collapse-subpages' folder along with all its files to the '/wp-content/plugins/'' directory.
- Activate the plugin through the 'Plugins' menu in WordPress.
- Visit your Pages admin page and notice the lovely +/- buttons.

## Frequently Asked Questions
(TO DO)
### Why is there a delay after I use "Quick Edit"? 

The WordPress Quick Edit functionality is a little buggy in my opinion. To make a long story short, this delay is so that WordPress can complete the edit(and any possible parent changes) before refreshing the expand/collapse status.
I'd recommend not using Quick Edit to change parent/child pages at all. It often doesn't refresh any changed rows properly.

## Screenshots

- Example Edit Page menu.
- Same menu with a group of subpages minimized.
- Same menu completely minimized.
- Expand/collapse all buttons at the top of the page.

## Changelog

### 1.0

* Initial version of the plugin

### 2.0

* Fixed bug - Adding expand/collapse links to all list tables
* Updated jquery.cookie.js to 1.4.0
* Enhanced loading of scripts and styles 

### 2.1

* Added support custom post types which are hieararchial

## Upgrade Notice
