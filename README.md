# SUMI Dynamic Build Guide

A self-contained interactive guide built around the ink-wash 3D game workflow @xikhar shared in their 24-hour AI game thread.

This is a thank-you. No strings attached. Just my way of saying thanks for the post and for making cool stuff for fun.

## Live guide

**https://jamestrichmond.github.io/sumi-dynamic-build-guide-xikhar/**

Open it in any browser. It tracks progress, has guidance levels, agent prompts, and a starter kit download.

## What’s in the repo

- `index.html` — the full interactive guide (served at the root)
- `sumi-starter-kit.zip` — the working Three.js + Vite project with the ink renderer, controller, cloth, QA harness, and agent charters

## Starter kit

Unzip, then:

```bash
cd sumi-slice
npm install
npm run dev
```

The ronin should appear at the foot of the stairs. WASD to walk, Shift to run, Space to jump.
