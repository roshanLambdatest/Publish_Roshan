---
test: ../verify-supported-release-formats-and-publication-languages_test.md
status: failed
started: 2026-09-11T18:28:41.938Z
duration_s: 278
session_id: 4157603d-041d-4aad-b103-c8916500dec7
---

# Verify supported release formats and publication languages for self-publishing — Result

## Step 1 ✓ passed (103.1s)
md5: f1646f192df5494f8b86ced055e0df5b
Open https://notionpress.com/ and navigate to the self-publishing page that describes the publishing workflow, supported formats, and supported languages.

## Step 2 ✓ passed (126s)
md5: 3c726d1478bf071d1f2da9b33f4a9b3f
Scroll through the publishing workflow and formats sections and wait for the release-format statements ("release simultaneously as paperback and eBook", and the list of supported formats) to be fully visible on screen before continuing.

## Step 3 ✗ failed (46s)
md5: f6a5cfe0c1d6ea03a562657565075e64
Reason: Final verification failed: "the page offers simultaneous paperback and eBook release and lists Paperback, Hardbound, and eBook as supported formats" — bug verdict: Verification ran before all release-format statements were visible [automation_bug/state_transition_bug, confidence 0.90]
Now that the release-format statements are visible, assert the page offers simultaneous paperback and eBook release and lists Paperback, Hardbound, and eBook as supported formats.

## Step 4 ⏭ skipped
