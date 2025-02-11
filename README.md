# Tailwind CSS Bug: Non-Existent Utility Class

This repository demonstrates a common yet subtle bug in Tailwind CSS: using a utility class that does not exist or has a typo. This can lead to unexpected visual results or no effect at all.

## Bug Description

The `bug.js` file contains a simple example of a Tailwind CSS class that uses a utility that doesn't exist. This could be due to a typo, outdated Tailwind version, or simply a class that isn't defined in your `tailwind.config.js`.

## Solution

The `bugSolution.js` file shows how to fix this bug by correcting the typo or ensuring all used utility classes are correctly defined in your config file and included via `purge` or `content` configuration.  The key is to carefully review your Tailwind configuration and the used class names for typos or inconsistencies.

## How to Reproduce

1. Clone this repository.
2. Run `npm install` to install the dependencies (if any).
3. Open `bug.js` and `bugSolution.js` to see the erroneous code and solution.
4. Observe the different output of each file.   You may need to set up a basic React or similar environment to see the visual differences.
