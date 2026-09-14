# Brown Family Apps website

This package is structured for the existing `brownfamilyapps.com` GitHub Pages repository.

## Resulting URLs

- `/index.html` → https://brownfamilyapps.com/
- `/eggsy/index.html` → https://brownfamilyapps.com/eggsy/
- `/privacy.html` → https://brownfamilyapps.com/privacy.html
- `/account-deletion.html` → https://brownfamilyapps.com/account-deletion.html

## Upload to GitHub

Copy everything inside this folder to the root of the GitHub Pages repository. Keep the `eggsy` folder intact.

The Eggsy page uses its own stylesheet and image folder, so it will not conflict with the redesigned main site.

## Important privacy review before publishing

The new privacy policy is intentionally written to support:

- Eggsy's local flock records and CSV exports
- Eggsy's AI/photo feature in a provider-neutral way
- JobSnap account/authentication, client/job data, Google Drive backups, Firebase Analytics and Crashlytics based on the privacy policy currently published at jobsnapapp.com
- Firebase Crashlytics across current/future apps
- subscriptions, in-app purchases and future microtransactions
- data minimization and no sale of personal information
- JobSnap account deletion requests

Please verify these implementation-specific points before publishing:

1. If JobSnap no longer uses Firebase Analytics, remove that reference from `privacy.html` and update the Play Console Data safety form.
2. Confirm what cloud/AI provider Eggsy uses for the breed scanner and whether bird photos leave the device. The current policy uses conditional/provider-neutral wording.
3. If Crashlytics is not yet enabled in an app, the policy says "if enabled" for app-specific diagnostics while explaining the general Crashlytics practice.
4. When the game launches, update the policy with the game's exact purchase system, account model, multiplayer/cloud features, and any other SDKs actually included.
5. Keep each Google Play Data safety declaration consistent with the actual SDKs and this policy.

This is a practical policy draft, not legal advice. For a commercial release involving accounts, user-generated client data, children, or purchases in multiple jurisdictions, legal review is worth considering.
