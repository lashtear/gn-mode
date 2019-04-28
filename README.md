# GN-mode

[![MELPA](https://melpa.org/packages/gn-mode-badge.svg)](https://melpa.org/#/gn-mode) [![BSD3](https://img.shields.io/badge/license-BSD3-43cd80.svg)](LICENSE.md)

A major-mode for editing GN (ninja generator) config files in Emacs.  Files of this type (e.g. BUILD.gn or *.gni) are common in Chromium-derived projects like Chrome and (Anaheim) Edge.

## Status

* Syntax hilighting - working correct
* Indentation - as correct as feasible without a complete parser
* Context-sensitive-help - keywords and variables only for now

## Changes in 0.4

* Fixed indentation hangs with evil-mode motion control.
* Fixed indentation text removal or hangs with over-indented regions at the end of the buffer.

## To-Do features

* Maybe better help for operators / site-defined symbols
* Maybe offer to use "gn format" for cleanup

