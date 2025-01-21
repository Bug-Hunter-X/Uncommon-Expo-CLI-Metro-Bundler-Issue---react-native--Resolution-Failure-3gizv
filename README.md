# Uncommon Expo CLI Metro Bundler Issue: 'react-native' Resolution Failure

This repository demonstrates an uncommon bug encountered while using Expo CLI and the Metro bundler. The issue involves the bundler failing to resolve the 'react-native' module, even though it's correctly installed. The problem is inconsistent and difficult to reproduce, making debugging challenging.

## Bug Description
The main problem is that the Metro bundler fails to find the 'react-native' module.  The error message is typically generic and unhelpful (e.g., 'Could not resolve module 'react-native' in file 'App.js''). Standard troubleshooting steps like clearing the cache and reinstalling packages often do not resolve the issue.

## Reproduction Steps
Reproducing this bug has proven difficult. It seems to occur sporadically, often after making certain code changes or after prolonged development sessions.  Further investigation is needed to pinpoint the exact conditions leading to the error.

## Solution (Potential)
The solution involves the steps described in the `bugSolution.js` file, including checking specific project configurations and potentially using specific commands to force the Metro bundler to re-evaluate dependencies.