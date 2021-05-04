# tiny
this is tiniest npm module

Removes all spaces from a string.

# Install

$ npm install @samrat122138/tiny

# Usage

const tiny = require("@samrat122138/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
