# Updating ServiceAll screenshots

Upload the original **Marketing Photos.zip** file to this directory. The GitHub Action `serviceall-refresh-assets.yml` processes the original ServiceAll screenshots into optimized WebP files and updates `serviceall.html` to use them.

The ZIP is removed from the branch after successful processing; the optimized files are saved under `assets/serviceall/screens-2026/`. This directory is intentionally kept with this README so it can accept later updated screenshot ZIP files.

Expected format: filenames like `Screenshot_20260929_092658_ServiceAll.jpg` inside the ZIP. The images are genuine app screenshots and are not regenerated or replaced with mock interfaces.
