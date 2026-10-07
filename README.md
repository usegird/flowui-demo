# FlowStyleDemo

A flow-based take on node-based workflows: a ComfyUI workflow laid out as a top-to-bottom
column of cards, with the app inputs on the left and the variables on the right.

**Try it:** https://usegird.github.io/flowui-demo/

## What this is

- A static, compiled demo page. Everything runs in your browser.
- It does **not** connect to ComfyUI and sends nothing anywhere.
- **Run (simulated)** only replays progress and shows sample images. They are not generated
  from the workflow on screen.
- You can open your own workflow (`.json`, or a `.png` with an embedded workflow). Nodes the demo
  has no definition for are marked as missing.

## About the source code

This demo is a mock-up built only to test whether the idea is practical, so the source code
is not published. This repository holds only the build output.

## Third-party notices

Licenses of the third-party packages included in the build are listed in
[THIRD-PARTY-NOTICES.txt](THIRD-PARTY-NOTICES.txt).
