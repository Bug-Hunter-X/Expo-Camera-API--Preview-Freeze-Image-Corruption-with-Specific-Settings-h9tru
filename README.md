# Expo Camera API Bug: Preview Freeze and Image Corruption

This repository demonstrates a bug encountered when using the Expo Camera API with certain settings combinations. The issue results in the camera preview freezing or producing corrupted images. The problem is not consistently reproducible across devices and requires specific settings to manifest. This repo provides code examples to reproduce the issue and a proposed solution.

## Steps to Reproduce

1. Clone this repository.
2. Run `npm install` or `yarn install`.
3. Run the application using Expo Go.
4. Observe the camera preview and try different settings combinations (especially `flashMode`, `autoFocus`, `whiteBalance`).  You may need to test on several different devices to consistently reproduce the issue.

## Solution

The solution involves carefully managing the camera settings and potentially adding error handling. This may involve trying alternative settings or using a more robust approach to image capture.