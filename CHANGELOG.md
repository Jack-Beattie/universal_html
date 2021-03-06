## 1.2.4
* Fixes dependency constraints.

## 1.2.3
* Fixes a missing getter (referrerPolicy in IFrameElement).

## 1.2.2
* Improves documentation.
* Deprecates some libraries.

## 1.2.1
* Eliminates dependency on an XML parsing package by introducing our own XML parser.
* Improves documentation.

## 1.2.0
* Adds `package:universal_html/parsing.dart`.

## 1.1.21
* Lowers minimum version of `csslib` ([#17](https://github.com/dint-dev/universal_html/issues/17)) and `html` dependencies.
* Adds @nodoc to helper libraries.

## 1.1.20
* Adds various missing APIs.

## 1.1.19
* Fixes a bug in FileReader that caused compile-time errors.
* Updates DIFFERENCES.md

## 1.1.18
* Fixes parsing of non-standard HTML attribute names ([#15](https://github.com/dint-dev/universal_html/issues/15))
  and various other issues.

## 1.1.17
* Restores old conditional exports because of a bug in dartdevc ([#16](https://github.com/dint-dev/universal_html/issues/16)).

## 1.1.16
* Fixes conditional imports in Node.JS when developer imports 'package:universal_io/X.dart' or
  'package:universal_io/prefer_sdk/X.dart'.

## 1.1.15
* Improved documentation.
* Removed 'package:universal_html/browser/html.dart', which has been marked with @Deprecated for
  long time. This is a breaking change, but unlikely to affect anyone.

## 1.1.14
* Fixes bugs related to HTML attributes and namespaces.

## 1.1.13
* Fixes 'universal_io' dependency constraint so that it supports 1.x.x.

## 1.1.12
* Fixed a CSS printing issue.

## 1.1.11
* Fixed pedantic warnings.

## 1.1.10
* Raised minimum SDK to 2.6 and updated dependencies.

## 1.1.9
* Improved test coverage.
* Fixed a bug in _window.localStorage_.
* Fixed an analysis error in _JsArray_ ([issue #8](https://github.com/dart-browser/universal_html/issues/8)).

## 1.1.8
* A large number of linter fixes.
* Some additional assertions/tests.

## 1.1.7
* Fixed element.innerHtml.
* Added PositionError and a test for navigator.geolocation.

## 1.1.6
* Implemented anchor clicks and form submission.

## 1.1.5
* Made it easier to implement file access APIs.

## 1.1.3
* Fixed problematic dependency constraints.
* Improved documentation and developer scripts.

## 1.1.2
* Fixed a test failure caused by Dart SDK 2.5.0-dev-2.0.
* Improved documentation.

## 1.1.1
* EventTarget now has a private getter `_htmlDriver`.
* _BrowserImplementation_ now receives events unless `event.preventDefault()` is called.
* Replaced _BrowserImplementation_ getter _browserClassFactory_ with getter _browserImplementation_. Deprecated the old method.
* Improved tests of various elements and fixed a few small bugs.
* Improved tests that compare 'dart:html' and 'package:universal_html'.
* Added various missing classes/class members.
* Improved documentation and formatting.
* Improved explanation that 'src/html/html_common/*.dart' were adopted from Dart SDK without much
  modifications.

## 1.1.0
* The sole copyright owner (except for code derived from the Dart SDK as noted in the relevant
  files) decided to publish the source code the Apache License 2.0. to make the project more
  enterprise-happy. Previous versions were published under the MIT License.
* Many new tests and bug fixes.
* Many new _dart:html_ APIs.
* Removed class factory APIs in _HtmlDriver_ in favor of separate _BrowserImplementation_ and
  _BrowserImplementationUtils_.
* Deprecated "package:universal_html/browser/(library).dart" in favor of more descriptive
  "package:universal_html/prefer_sdk/(library).dart". Deprecated APIs will be removed in future.
* Added "package:universal_html/prefer_universal/(library).dart".

## 1.0.13
* Fixed dependencies.

## 1.0.12
* A fix related to Dart SDK 2.5.

## 1.0.11
* Fixes compatibility with Dart SDK 2.5.
* EventSource support.

## 1.0.10
* Eliminated the following error that Dart build system threw in some cases:
  _Unsupported conditional import of dart:html found in universal_html|lib/html.dart_

## 1.0.9

* Fixed bugs related to XML handling.

## 1.0.8

* Fixed various bugs.

## 1.0.7

* Fixed various bugs.

## 1.0.6

* Fixed various bugs.
* Added _browser/html.dart_ and related documentation.
* Added _ServerSideRenderer_.

## 1.0.5

* Fixed a dependency.

## 1.0.4

* Fixed various bugs and added dart:html APIs.

## 1.0.3

* Fixed various bugs.

## 1.0.2

* Added dart:html APIs (HttpRequest, etc.) and new libraries (js.dart, js_util.dart, etc.).

## 1.0.1

* Fixed various bugs and added dart:html APIs.

## 0.0.1

* Initial release