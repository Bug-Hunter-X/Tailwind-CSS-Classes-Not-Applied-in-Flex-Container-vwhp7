# Tailwind CSS Classes Not Applied in Flex Container

This repository demonstrates a bug where Tailwind CSS classes are not applied correctly to elements within a flex container. The issue occurs even when seemingly correct syntax is used. The styles associated with the classes appear to be ignored by the browser.

## Bug Description

When using the flex utility in Tailwind, the background colors specified using `bg-red-500` and `bg-blue-500` are not applied to the divs within the flex container. This leads to the divs being displayed without any background styling.

## Reproduction Steps

1. Clone this repository.
2. Open `bug.html` in a web browser.
3. Observe that the divs within the flex container do not have the expected background colors.

## Solution

The solution may involve identifying any conflicting styles or ensuring that the Tailwind CSS configuration is correctly set up.