# SFL public organization pilot

Disposable [organization rollout validation](https://github.com/hemsoft-dev/set-it-free-loop/issues/139), outside the original source inventory; no production data.

The reviewer package is pinned to canonical release `v2.1.0-rc.25`, source `8c53c43a860a0471308f11501352a9f2b43c7efd`. It uses connected Codex without an SFL App key or model credential.

After this package upgrade merges, a separate documentation PR exercises a registered current-head review with rc25 installed on the default branch. Its successful gate must bind the exact head, base, human request and authenticated Codex artifact. Repeat init/sync must create no changes. Gate cleanup must preserve ownership files, labels and unrelated policy.

Overlapping registered requests stay blocked on the same head because native artifacts cannot identify which request produced them. Advance the PR head, then register one fresh review. Requests and artifacts from the previous head cannot satisfy that new review.

## rc25 overlapping review protection

The installed reviewer is pinned to immutable SFL rc25. A newer registered review request supersedes older results, including overlapping requests that cannot be attributed safely on the same head. Advance the PR head before registering one fresh review after overlap.

This update exercises the observer installed on the current default branch with a registered current-head review and the Actions-owned required gate. Synthetic negative fixtures remain separate evidence from this live review.

Native reviews identify their head but not their originating base. The observer requires one trusted opened or head-change context for that PR and base. Base edits, reopened PRs, legacy context records, and multiple contexts on one head require advancing the branch to a new head before registering a fresh review. This prevents late automatic or unregistered old-base reviews from approving the current diff.

## rc25 native base-context validation

The installed observer stores trusted PR number, event action and base SHA in check output while retaining a compact context token for request and result IDs. A single fresh opened or head-change context can approve this diff. Legacy records, base edits, reopened PRs and multiple contexts on a head remain blocked until the branch advances.

This documentation change verifies the installed rc25 observer using one registered human request and the actual Actions-owned required gate. The separate synthetic fixture receipts test negative contexts and API identifier length; they do not claim live provider events.

Registered requests are evaluated against their immediate predecessor, including rejected overlaps. If a request overlaps an unfinished review, advance the branch before registering a new request. Terminal serial requests remain eligible. Both authenticated clean review wordings are accepted; malformed context provenance fails with recovery instructions.

## rc25 immediate predecessor runtime verification

The installed reviewer is pinned to immutable SFL rc25. Every registered request must follow its immediate predecessor after terminal completion. An unresolved overlapping request blocks all later requests on that head, including a third request after the first completes. Advance the PR head before registering one fresh review after overlap.

This update exercises the observer installed on the current default branch with a registered current-head review and the Actions-owned required gate. Synthetic negative fixtures remain separate evidence from this live review.

Edited or malformed registered request history blocks the head, including later attempts to skip it. Advance to a new head for recovery. Same-repository retargeting away from the default branch invalidates prior review; a fresh terminal publication snapshot must preserve request authorization, head, base and context.

Deleted historical registrations block every final publication snapshot. Issue-comment invalidation runs preserve their PR identity after request markers are edited or removed.

Registered authors may invalidate their earlier review after access is revoked. Ordinary comments do not block registered review publication. Retargeting between non-default branches remains outside reviewer admission.
