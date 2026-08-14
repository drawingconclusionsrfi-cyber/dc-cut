# DC CUT Pro — GitHub Pages Upload

## Do this

1. Download and unzip this folder.
2. Open **your GitHub repository**.
3. Delete your old single `index.html` file.
4. Upload **everything inside this unzipped folder**. Do not upload the folder itself.
5. Click **Commit changes**.
6. In GitHub, open **Settings → Pages**.
7. Under **Build and deployment**, choose **Deploy from a branch**.
8. Select your `main` branch and the **`/ (root)`** folder, then click **Save**.
9. Wait about one minute. GitHub will show your live link in the same Pages screen.

## Important

- The updated app needs **all files in this folder**. Do not upload only `index.html`.
- Do **not** upload `node_modules`, source code, or any other old project files.
- `index.html` is the updated starting file. The `assets` folder and `dccut-legacy` folder are also required.
- GitHub Pages must be served over HTTPS. Do not test this package by double-clicking `index.html` on your computer.

## What is included

| Folder or file | Keep it? | Why |
| --- | --- | --- |
| `index.html` | Yes | Opens DC CUT Pro. |
| `assets/` | Yes | The app’s JavaScript, styles, visual art, and local AI runtime. |
| `dccut-legacy/` | Yes | The actual browser compositor. |
| `.nojekyll` | Yes | Prevents GitHub Pages from changing app files. |

If you see a blank screen after deployment, make sure the uploaded files are at the **repository root**—not inside an extra nested folder.
