# Uncommon Tailwind CSS Bug: @apply Directive Issue

This repository demonstrates an uncommon bug encountered when using the `@apply` directive in Tailwind CSS with complex selectors.  The issue involves unexpected behavior and styling inconsistencies.

## Bug Description

The `@apply` directive, intended for applying utility classes, exhibits unusual behavior when combined with selectors that include pseudo-classes or multiple levels of nesting.  This leads to styles not applying as expected, or applying inconsistently across different elements.

## Reproduction

1. Clone the repository.
2. Install the dependencies using `npm install`.
3. Start the development server.
4. Observe the styling inconsistencies in the browser.

## Solution

The provided solution addresses the issue by restructuring the CSS classes and potentially refactoring the selector usage.  Specific workarounds for this uncommon scenario might be necessary, depending on the exact nature of the complex selector causing trouble. In the provided example, a refactoring of the CSS classes will solve the issue.