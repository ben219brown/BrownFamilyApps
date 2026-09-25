# ServiceAll site image manifest

This staging branch refreshes `index.html` and `serviceall.html` using new ServiceAll promotional imagery and genuine app screenshots. **Do not merge until the assets below have been uploaded to this branch.**

The corresponding optimized WebP assets are supplied in the conversation as **ServiceAll-Website-Images.zip**. Extract that ZIP. Keep the folder structure intact and upload the contents of its `assets/serviceall/` directory to `assets/serviceall/` in this repository.

Required files:

| File | Purpose |
| --- | --- |
| assets/serviceall/feature-banner.webp | Main homepage ServiceAll card and ServiceAll page hero |
| assets/serviceall/garage-overview.webp | Garage overview promotional panel |
| assets/serviceall/log-service.webp | Service logging promotional panel |
| assets/serviceall/service-history.webp | History promotional panel |
| assets/serviceall/parts-specs.webp | Parts/specs promotional panel |
| assets/serviceall/photos-records.webp | Photos/receipts promotional panel |
| assets/serviceall/backup-restore.webp | Local backup promotional panel |
| assets/serviceall/screens/garage.webp | Unmodified-layout real app garage screenshot |
| assets/serviceall/screens/cj-detail.webp | Real equipment details |
| assets/serviceall/screens/history.webp | Real service history |
| assets/serviceall/screens/specs.webp | Real equipment specifications |
| assets/serviceall/screens/photos.webp | Real photo records |
| assets/serviceall/screens/settings.webp | Real settings and local backup |

All images are already resized, compressed and named for GitHub Pages. On this branch: verify the relative paths after upload, inspect `index.html` and `serviceall.html` on mobile, then merge the PR into `main` to publish on brownfamilyapps.com. The site uses lowercase `serviceall.html` (case-sensitive).

The app's current website status remains "in testing"; don't add a Play Store link without confirming its exact package/URL and availability. Local backup is described accurately; cloud sync and planned AI tools are not claimed as shipping features.
