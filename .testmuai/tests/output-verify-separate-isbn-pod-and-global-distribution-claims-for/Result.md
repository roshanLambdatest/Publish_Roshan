---
test: ../verify-separate-isbn-pod-and-global-distribution-claims-for_test.md
status: failed
started: 2026-09-11T17:43:41.331Z
duration_s: 215
session_id: b5718627-75d9-41f9-b95a-4075d5b735f3
---

# Verify separate ISBN, POD, and global distribution claims for self-publishing — Result

## Step 1 ✓ passed (25.2s)
md5: 06989fb839708536f09adb73f12cd1b0
Open https://notionpress.com/ and navigate to the self-publishing page that presents the publishing workflow, format details, and distribution information.

## Step 2 ✓ passed (50.6s)
md5: 23aaa667c0dcb993470b43789503655d
On the self-publishing page's formats and printing sections, review the ISBN and production statements, then assert the page states that each format is issued its own separate ISBN and that printing uses a print-on-demand model driven by sales velocity.

## Step 3 ✗ failed (135.7s)
md5: e5b891129a2662c82f186a71411e220e
Reason: AP determined agent is stuck — no viable actions remain — bug verdict: Agent stopped before completing distribution verification [automation_bug/agent_misstep, confidence 0.94]
On the same page's distribution section, review the named channels and reach statement, then assert Amazon, Flipkart, and the Notion Press Store are listed and the reach claim shows 30,000+ stores across 150+ countries.
