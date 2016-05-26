[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg?style=flat)](LICENSE.md) [![Haxelib Version](https://img.shields.io/github/tag/openfl/extension-steamworks.svg?style=flat&label=haxelib)](http://lib.haxe.org/p/extension-steamworks)

Steamworks
==========

Provides support for the Steamworks SDK for integration with Steam APIs.


Installation
============

You can easily install Steamworks using haxelib:

    haxelib install extension-steamworks

To add it to a Lime or OpenFL project, add this to your project file:

    <haxelib name="extension-steamworks" />

You need to define "STEAMWORKS_SDK" in .hxcpp_config.xml, or your environment to use the 
extension. You can fill out a license agreement and download the SDK from https://partner.steamgames.com


Development Builds
==================

Clone the Steamworks repository:

    git clone https://github.com/openfl/extension-steamworks

Tell haxelib where your development copy of Steamworks is installed:

    haxelib dev extension-steamworks extension-steamworks

You can build the binaries using "lime rebuild"

    lime rebuild extension-steamworks windows

To return to release builds:

    haxelib dev extension-steamworks
