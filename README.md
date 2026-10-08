# SFL public organization pilot

Disposable [organization rollout validation](https://github.com/hemsoft-dev/set-it-free-loop/issues/139), outside the original source inventory; no production data.

The reviewer package is pinned to canonical release `v2.1.0-rc.29`, source `f07ab8ca3d58a7a5a6bbf88ff1bc8e3a359b6e53`. It uses connected Codex without an SFL App key or model credential.

After this package upgrade merges, a separate documentation PR exercises a registered current-head review with rc29 installed on the default branch. Its successful gate must bind the exact head, base, human request and authenticated Codex artifact. Repeat init/sync must create no changes. Gate cleanup must preserve ownership files, labels and unrelated policy.

Overlapping registered requests stay blocked on the same head because native artifacts cannot identify which request produced them. Advance the PR head, then register one fresh review. Requests and artifacts from the previous head cannot satisfy that new review.

## rc28 overlapping review protection

The installed reviewer is pinned to immutable SFL rc28. A newer registered review request supersedes older results, including overlapping requests that cannot be attributed safely on the same head. Advance the PR head before registering one fresh review after overlap.

This update exercises the observer installed on the current default branch with a registered current-head review and the Actions-owned required gate. Synthetic negative fixtures remain separate evidence from this live review.

Native reviews identify their head but not their originating base. The observer requires one trusted opened or head-change context for that PR and base. Base edits, reopened PRs, legacy context records, and multiple contexts on one head require advancing the branch to a new head before registering a fresh review. This prevents late automatic or unregistered old-base reviews from approving the current diff.

## rc28 native base-context validation

The installed observer stores trusted PR number, event action and base SHA in check output while retaining a compact context token for request and result IDs. A single fresh opened or head-change context can approve this diff. Legacy records, base edits, reopened PRs and multiple contexts on a head remain blocked until the branch advances.

This documentation change verifies the installed rc28 observer using one registered human request and the actual Actions-owned required gate. The separate synthetic fixture receipts test negative contexts and API identifier length; they do not claim live provider events.

Registered requests are evaluated against their immediate predecessor, including rejected overlaps. If a request overlaps an unfinished review, advance the branch before registering a new request. Terminal serial requests remain eligible. Both authenticated clean review wordings are accepted; malformed context provenance fails with recovery instructions.

## rc28 immediate predecessor runtime verification

The installed reviewer is pinned to immutable SFL rc28. Every registered request must follow its immediate predecessor after terminal completion. An unresolved overlapping request blocks all later requests on that head, including a third request after the first completes. Advance the PR head before registering one fresh review after overlap.

This update exercises the observer installed on the current default branch with a registered current-head review and the Actions-owned required gate. Synthetic negative fixtures remain separate evidence from this live review.

Edited or malformed registered request history blocks the head, including later attempts to skip it. Advance to a new head for recovery. Same-repository retargeting away from the default branch invalidates prior review; a fresh terminal publication snapshot must preserve request authorization, head, base and context.

Deleted historical registrations block every final publication snapshot. Issue-comment invalidation runs preserve their PR identity after request markers are edited or removed.

Registered authors may invalidate their earlier review after access is revoked. Ordinary comments do not block registered review publication. Retargeting between non-default branches remains outside reviewer admission.

Authorized request-marker runs serialize review publication while their registration materializes. Denied authors get one historical registration lookup without retry waits. Ordinary comment runs require an actual matching registration to block publication.

Registered request contexts must be nonempty opaque tokens. Successful required-status repairs recheck history before and after the write; verification errors restore a blocking status with bounded retries and preserve the original failure.

Registry-free marker runs require an authenticated exact, unchanged request for the current head and base. Marker quotations and ordinary comments cannot block publication; genuine fresh requests still serialize while the registry materializes.

## rc28 request-history and marker admission runtime verification

This update exercises the observer installed on the current default branch through one registered current-head review and its Actions-owned required gate. Synthetic negative fixtures remain separate from this live event.

Registry-free marker runs must match an authenticated, unchanged current request before they block publication. Marker quotations and ordinary comments cannot block a valid result; genuine fresh requests still serialize until their registry materializes. Registered revocation and verification-error blocking remain enforced.

## rc29 chained-retarget protection

Unsupported nondefault retarget events use a separate concurrency group. They cannot cancel a pending or running default-departure invalidation, including a chain that returns to the same nondefault target. Nondefault-to-nondefault admission remains read-only. After this package upgrade, verify the installed production regressions and a separate registered live review.
