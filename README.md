# sfl-migration-pilot-public
Disposable public validation for the SFL organization migration; outside the 67-source inventory

The reviewer tier is deployed from the private canonical source `hemsoft-dev/set-it-free-loop` at release `v2.1.0-rc.18`. It uses the connected Codex subscription and requires no SFL App key or model API key.

Onboarding updates are reviewed through a pull request. Repeat sync at the same release verifies the managed files and should create no additional deployment pull request.

This documentation update exercises the rc.18 observer after deployment on main. A registered human review request must bind the exact head and base to the authenticated Codex result and required Actions-backed gate. Repeating init and sync must produce no changes. Removing only the SFL gate must preserve CODEOWNERS, labels and unrelated policy.
