# Plane Theme Shell

## How to Update

**Notes**

1. The `main` branch contains the stylization.
2. The `gnome-shell` branch contains the latest downloaded version.

**Steps**

1. Switch to the `gnome-shell` branch.
2. Download the version equivalent to the one installed on the operating system [from the link](https://gitlab.gnome.org/GNOME/gnome-shell/-/tree/main/data/theme?ref_type=heads) and overwrite the contents in the `theme` folder. and commit with the specifc gnome-shell version: ex: `git commit -m 'v45.3'`
3. Merge the `gnome-shell` branch into `main`.
4. Install dependencies with `npm i`.
5. Compile with `npm run build`.
6. Copy the theme content to `/home/[USERNAME]/.local/share/themes/Plane-dark/gnome-shell` excluding the `gnome-shell-sass` folder.
7. Select the theme in the Tweaks tool under Shell Theme.
