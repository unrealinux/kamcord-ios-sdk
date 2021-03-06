Kamcord iOS Framework
======================

<h3>The documentation can be found at the <a href="https://github.com/kamcord/kamcord-ios-sdk/wiki">wiki</a>.</h3>

This repository contains a build of Kamcord for integrating into cocos2d/cocosd-x and native iOS game engines. The current version is 1.7.4. If you are updating from an older version, please visit the <a href="https://github.com/kamcord/kamcord-ios-sdk/wiki/Change-log">Change Log</a>.

If you'd like to enable WeChat support in Kamcord, please add <code>WeChat/libWeChatSDK.a</code> as a link target of your application and add <code>-ObjC</code> as a linker flag in <code>Build Settings => Other Linker Flags</code>. Note that <code>libWeChatSDK.a</code> only has slices for <code>armv7</code>, <code>armv7s</code>, and <code>i386</code>. Once WeChat adds support for <code>arm64</code> and <code>x86_64</code>, we will bundle that updated library.

If you are looking for the Kamcord Unity Plugin, please visit this repository: <a href="https://github.com/kamcord/Unity-Kamcord">https://github.com/kamcord/Unity-Kamcord</a>.

