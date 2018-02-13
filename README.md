# Status Code plugin for Craft CMS 3.x

Returns the HTTP status code within twig templates by simply calling `craft.getHttpStatus()`,

![Screenshot](resources/img/plugin-logo.png)

## Requirements

This plugin requires Craft CMS 3.0.0-beta.23 or later.

## Installation

To install the plugin, follow these instructions.

1. Open your terminal and go to your Craft project:

        cd /path/to/project

2. Then tell Composer to load the plugin:

        composer require squaresandbrackets/craft-status-code

3. In the Control Panel, go to Settings → Plugins and click the “Install” button for Status Code.

## How to use it in your twig template

		{{ craft.getHttpStatus() }}


* Release it

Brought to you by [Squares And Brackets](http://squaresandbrackets.com)
