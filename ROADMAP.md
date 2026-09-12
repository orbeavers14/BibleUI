# BibleUI Roadmap

BibleUI is a SwiftUI component library for presenting BibleKit content with
native Apple conventions. It intentionally does not know about SWORD directly.

## Principles

- Use native navigation, sheets, popovers, menus, context menus, Dynamic Type,
  accessibility, keyboard, and platform-specific behavior.
- Components are capability-driven: unavailable provider actions are absent or
  clearly explained rather than simulated.
- Apps own product navigation, persistence, branding, and release policy.

## Ordered milestones

1. BibleKit integration baseline
   - Depend on the first tagged BibleKit release.
   - Provide catalog, license-attribution, and availability presentation models.

2. Reader primitives
   - Rich text, configurable typography, text selection, accessibility, and
     adaptive Scripture/keyed-content reader components.

3. Library and module management
   - Installed-content and discovery sections, language filtering, downloads,
     removals, progress, errors, and attribution.

4. Study interactions
   - Native selected-passage context actions for bookmarking, highlighting, and
     notes without cluttering every verse.

5. SwordReader extraction
   - Move reusable, tested reader and library components from SwordReader while
     retaining product-specific navigation and application state in the app.
