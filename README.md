marionette.roadmap
==================

The roadmap for major Marionette releases.

This only highlights the biggest of changes, and is intended to give a **broad** look at what each version changes. There will be many details left out here, and this should not be considered a replacement to the official CHANGELOG for each version.

#### v2 - API Cleanup

It's been over a year since a breaking change was introduced in Marionette, and because of that the API has gotten a bit messy. v2 is largely about cleaning up the API to make things clearer and more consistent. It's the clean up release.

- Resolves inconsistencies
- Method name changes to be more explicit about intent
- Some argument refactors
- Changes to Class names to reduce confusion (Layout => LayoutView)

#### v3 - Architecture

A release intended to provide better architectural classes to build large SPAs. Some ideas we're considering are:

- Updates to the App and Module Classes. Potential merger of the two.
- Marionette.Namespace. A means to namespace your code, similar to the current Module system
- Marionette.Router. A brand new router that will be *much* more useful. You'll love it.
- Marionette.Controller - A real controller to go with the router.
- Animated Regions - This is the black swan of the group, but it should be mostly backwards compatible.

#### v4 - Views

These changes may sound drastic at first, but we're thinking that feature parity can be reached in this library with a great reduction in source code. This version is so far out that these are all subject to change, but here are some of the crazy ideas we've been throwing around:

- RegionManager to become a mixin
- Renderer to be a part of Marionette.View
- Marionette.View to potentially disolve
- CollectionView to be refactored for efficiency and succinctness
- CompositeView removed from library and moved to the cookbook.
- Potentially remove LayoutView in favor of the RegionManager mixin
