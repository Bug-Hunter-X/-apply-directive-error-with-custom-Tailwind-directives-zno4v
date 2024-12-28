# Tailwind CSS @apply Directive Error

This repository demonstrates a common error encountered when using Tailwind's `@apply` directive within a custom directive.

The `@apply` directive is designed to apply existing utility classes.  Attempting to use it with custom directives or other CSS rules results in an error.  This example showcases the issue and its resolution.

## Problem

The `bug.css` file illustrates the incorrect usage of `@apply` with a custom directive.  The error occurs because `@apply` expects valid utility classes as arguments.

## Solution

The `bugSolution.css` file demonstrates the correct approach.  Instead of using `@apply`, you should directly include the custom styles within your component styles.

This avoids the error and provides the desired styling.  Remember, `@apply` is specifically for applying pre-defined utility classes.