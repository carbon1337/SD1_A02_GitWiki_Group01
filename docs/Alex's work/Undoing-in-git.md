---
title: Undoing in git 
layout: default
nav_order: 15
---

# Undoing in git
{: .no_toc }

## Overview

With git, ALMOST anything can be undone.

There are 3 normal was to undo in git.
- Checkout (Slightly Dangerous)
- Reset (Destructiive)
- Revert (Safe)

## Table of Contents
{: .no_toc }

- TOC
{:toc}

## When to Undo with Checkout?
The simplest private undo. Discard uncommitted local changes

```bash
git checkout <path-or-filename>
```

Works if:
- The changes you wish to undo haven't yet been committed. (Dirty files.)
- You wish to revert to the most recently committed version of a file or files.

## Undoing with Checkout
Let's say you made a bunch of changes to your 'readme.md' that you now regret.

If you haven't committed these changes, you can undo them like this:
```bash
git checkout readme.md
```
If you want to revert all folders and files to the most recent commit:
```bash
git checkout .
```
WARNING: Slightly dangerous. The discarded changes cannot be recovered!