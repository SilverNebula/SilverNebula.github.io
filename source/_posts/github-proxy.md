---
title: github proxy
date: 2022-09-23 10:39:18
tags: Links
---

**enable:**
git config --global http.proxy http://127.0.0.1:[port]
git config --global https.proxy https://127.0.0.1:[port]

**disable:**
git config --global --unset http.proxy
git config --global --unset https.proxy