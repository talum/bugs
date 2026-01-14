# Sample Document for Testing URL Anchors

This document contains multiple sections with anchor points to demonstrate the URL fragment issue.

## Table of Contents

- [Introduction](#introduction)
- [Section One](#section-one)
- [Section Two](#section-two)
- [Important Section](#important-section)
- [Conclusion](#conclusion)

---

## Introduction

This is the introduction section. When you click a link with `#introduction`, you should land here.

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

---

## Section One

This is Section One. Links with `#section-one` should navigate to this heading.

Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

---

## Section Two

This is Section Two. Links with `#section-two` should navigate to this heading.

Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.

---

## Important Section

**This is a critical section** that demonstrates the anchor issue. Links with `#important-section` should bring you directly here.

### The Problem

When clicking a link like `https://github.com/myorg/myrepo?tab=readme-ov-file#important-section`:
- Opening in the **same tab** truncates everything after the `#`, so you only get `https://github.com/myorg/myrepo?tab=readme-ov-file`
- Opening in a **new tab** works correctly and navigates to the anchor

### Why This Matters

Document anchors are essential for:
1. Deep linking to specific documentation sections
2. Referencing particular parts of long documents
3. Creating navigable documentation structures
4. Improving user experience when sharing documentation

---

## Conclusion

This section concludes our sample document. Links with `#conclusion` should navigate here.

Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
