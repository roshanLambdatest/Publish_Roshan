---
test: ../verify-supported-release-formats-and-publication-languages_test.md
status: failed
started: 2026-09-11T18:35:53.800Z
duration_s: 298
session_id: 101f2fc1-68f6-4c68-9ddf-48e61210cc8c
---

# Verify supported release formats and publication languages for self-publishing — Result

## Step 1 ✓ passed (36.3s)
md5: f1646f192df5494f8b86ced055e0df5b
Open https://notionpress.com/ and navigate to the self-publishing page that describes the publishing workflow, supported formats, and supported languages.

## Step 2 ✓ passed (105s)
md5: ab006bddf2a373c4f8ee472057000309
Scroll to the publishing workflow section until the "release simultaneously as paperback and eBook" statement is on screen, then wait 3 seconds for the section to finish rendering.

## Step 3 ✓ passed (20.4s)
md5: 31cb5a8171633866abc635fbd43d83fb
Assert the page states that a book can be released simultaneously as paperback and eBook.

## Step 4 ✓ passed (81.7s)
md5: 04e0d6f7a1a128c183759bf03d1ea4b2
Scroll to the formats section until the list of supported formats is on screen, then wait 3 seconds for the section to finish rendering.

## Step 5 ✗ failed (51.3s)
md5: aebc8a5a3eff04be95f411792a768773
Reason: Final verification failed: "the page lists Paperback, Hardbound, and eBook as supported formats" — bug verdict: Format verification ran from an unverified page section [automation_bug/state_transition_bug, confidence 0.88]
Assert the page lists Paperback, Hardbound, and eBook as supported formats.

## Step 6 ⏭ skipped

## Step 7 ⏭ skipped
