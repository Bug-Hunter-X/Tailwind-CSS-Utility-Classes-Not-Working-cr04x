# Tailwind CSS Utility Classes Not Working

This repository demonstrates a common issue encountered when using Tailwind CSS: utility classes not working as expected. The problem occurs when using the `w-1/2` class on two elements within a flex container.  The text overlaps instead of distributing evenly.

## Problem

The provided HTML uses Tailwind classes to create a two-column layout. However, the layout breaks, and text overlaps. This is because the `w-1/2` class, which should occupy half the available width, needs a parent element with specific Tailwind classes to work correctly within a flexible layout.

## Solution

The solution involves adding a parent container with the `flex` class.  This allows Tailwind's responsive features to work properly and properly distributes the elements within the available space.