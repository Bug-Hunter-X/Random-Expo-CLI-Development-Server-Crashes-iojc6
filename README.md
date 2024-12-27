# Random Expo CLI Development Server Crashes

This repository demonstrates a bug where the Expo CLI development server randomly crashes without providing any helpful error messages.  The issue is intermittent and difficult to reproduce consistently.

## Bug Description

The Expo development server crashes unexpectedly during app development. No error messages are logged to the console, making debugging challenging. The app functions correctly until the crash, then abruptly stops without warning.

## Reproduction Steps

Reproducing this bug is inconsistent.  The crash seems to happen randomly during development, possibly under heavy load or after a period of inactivity. The specific steps to reproduce reliably have not yet been found. 

## Solution

The solution (located in `expoBugSolution.js`) demonstrates some strategies that can help alleviate this issue.  While they may not fix the root cause in all situations, they improve stability.  These include enabling the Metro Bundler's debug mode and ensuring sufficient memory resources.

## Technologies Used

* Expo CLI
* React Native
* JavaScript
