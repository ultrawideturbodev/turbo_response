# Changelog

## 0.2.6

* **🔄 Changed:** Renamed internal classes for better code organization
* **🔄 Changed:** Updated method names for better clarity and consistency
* **📝 Docs:** Enhanced documentation with clearer descriptions

## 0.2.5

* **✨ New:** Added title and message support for empty responses
* **🔄 Changed:** Enhanced empty response handling with more descriptive information
* **🔄 Changed:** Renamed internal classes for better code organization
* **🔄 Changed:** Updated method names for better clarity and consistency

## 0.2.4

* **🔄 Changed:** Moved Flutter to dev_dependencies - now works with pure Dart projects with zero Flutter dependencies
* **📝 Docs:** Enhanced documentation to highlight Dart compatibility
* **🎨 Platform:** Added platform-agnostic support with improved package structure
* **🔧 Chore:** Updated package metadata and topics

## 0.2.3

* **✨ New:** Added static `throwFail` method for creating and throwing failures in one step

## 0.2.2

* **🔄 Changed:** Renamed `throwFail` to `throwWhenFail` for better clarity

## 0.2.1

* **🔄 Changed:** Updated package description to be more concise
* **📝 Docs:** Enhanced documentation with emojis and better formatting

## 0.2.0

* **✨ New:** Added support for async operations in `mapSuccess` and `andThen` methods
* **🔄 Changed:** Updated function parameter names to be more descriptive in IDE tooltips
* **📝 Docs:** Improved documentation with better examples and parameter names

## 0.1.0

* Initial release with core functionality
* Added support for success and failure states
* Added pattern matching with `when` and `maybeWhen`
* Added transformation methods like `mapSuccess`, `mapFail`, and `andThen`
* Added utility methods like `unwrap`, `unwrapOr`, and `ensure`
* Added static utility methods `traverse` and `sequence`
