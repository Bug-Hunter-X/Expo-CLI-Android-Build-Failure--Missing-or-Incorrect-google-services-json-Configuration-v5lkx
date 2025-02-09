# Expo CLI Android Build Failure: Missing or Incorrect google-services.json Configuration

This repository demonstrates a common issue encountered when building Android apps with the Expo CLI: build failures due to problems with the `google-services.json` file.  The error messages are often unhelpful, making it difficult to diagnose the root cause.

**Problem:**  The Expo CLI doesn't always provide clear guidance on ensuring the correct configuration and placement of this file, which is crucial for integrating Firebase and other Google services.  A missing or misconfigured `google-services.json` file can lead to build failures.

**Solution:** This repository provides a solution by clearly demonstrating how to properly integrate the `google-services.json` file into the Android project directory.  The solution involves creating a correctly configured `google-services.json` file and placing it in the appropriate location within the Expo project.  Specific instructions are within the code comments.