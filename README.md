# BlenderRender

A Mac app that sends `.blend` files to your own Windows GPU PC on the local network, renders them there and brings the results back.

This repo only holds the app downloads.

## Install

**[Download BlenderRender.zip](https://github.com/AlbertIpsen/blender-render-releases/releases/latest/download/BlenderRender.zip)**

1. Unzip it and drag `BlenderRender.app` into Applications.
2. Open it. macOS will block it the first time because the app isn't notarized.
3. Go to System Settings > Privacy & Security, scroll down and click **Open Anyway**.

Or do steps 2 and 3 in Terminal:

```bash
xattr -dr com.apple.quarantine /Applications/BlenderRender.app
```

## Set up

You need macOS 14 or later, Blender in Applications, and a Windows PC with an NVIDIA GPU running the same Blender version.

In the app, open Help > Set Up a Render PC and follow the steps.

The app offers new versions itself: click **Update & Restart** when it asks.
