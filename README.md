# SFL public organization pilot

Disposable [organization rollout validation](https://github.com/hemsoft-dev/set-it-free-loop/issues/139), outside the original source inventory; no production data.

The reviewer package is pinned to canonical release `v2.1.0-rc.20`, source `292336619aaf8a484e45590bb8897902c7ce7fce`. It uses connected Codex without an SFL App key or model credential.

After this package upgrade merges, a separate documentation PR exercises a registered current-head review with rc20 installed on the default branch. Its successful gate must bind the exact head, base, human request and authenticated Codex artifact. Repeat init/sync must create no changes. Gate cleanup must preserve ownership files, labels and unrelated policy.

Overlapping registered requests stay blocked on the same head because native artifacts cannot identify which request produced them. Advance the PR head, then register one fresh review. Requests and artifacts from the previous head cannot satisfy that new review.

## rc20 overlapping review protection

The installed reviewer is pinned to immutable SFL rc20. A newer registered review request supersedes older results, including overlapping requests that cannot be attributed safely on the same head. Advance the PR head before registering one fresh review after overlap.

This update exercises the observer installed on the current default branch with a registered current-head review and the Actions-owned required gate. Synthetic negative fixtures remain separate evidence from this live review.
