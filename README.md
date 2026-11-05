# 👋🧩 Pablobaro Morphe patches

Spotify patches for use with Morphe.

## ❓ About

This repository provides patches for Spotify, such as removing ads, hiding upsells and
removing tracking parameters from shared links.

### How to use these patches

Click the button below, or manually add this repo url to Morphe Manager: https://github.com/pablobaro/pablobaro-morphe-patches

<a href="https://morphe.software/add-source?github=pablobaro/pablobaro-morphe-patches">
  <img src=".github/assets/add-to-morphe.svg" alt="Add to Morphe" height="48">
</a>

## 🩹 Patches list

<!-- PATCHES_START EXPANDED -->

<!-- Do not modify this section by hand. The patch list is generated when release.yml creates a new release.
     
     If you wish for the patches list to be collapsed, then remove the word 'EXPANDED' from the comment tag above.

     If you wish to manually keep this list updated then remove the PATCHES_START and PATCHES_END 
     comment blocks entirely. -->

#### The list of patches will automatically be shown here after the first patches release is created.

&nbsp;

## 🧑‍💻 Dev usage

- **Make all changes to the `dev` branch.**
- Use [Semantic commit](https://kapeli.com/cheat_sheets/Semantic_Commits.docset/Contents/Resources/Documents/index) messages (`feat:`, `fix:`, `chore:`).
  `fix:` and `feat:` commits create new pre-releases, `chore:` commits do not.
- Merge `dev` into `main` (do not squash) for a stable release.
- **Always use semantic release (release.yml)**. Do not create releases or edit generated files
  (`patches-list.json`, `patches-bundle.json`, `CHANGELOG.md`) by hand.

<!-- The patches end tag is intentionally placed here so the first release will clean up 
     this readme of all developer instructions above. -->
<!-- PATCHES_END -->

### 🛠️ Building locally

- Run `./gradlew buildAndroid`
- The built patches .mpp file is found in `patches/build/libs/patches-*.mpp`
- Patch the mpp file using [Morphe-Desktop](https://github.com/MorpheApp/morphe-desktop)
  like any other patch bundle.

See the [Morphe documentation](https://github.com/MorpheApp/morphe-documentation) for more information.

## 🙏 Credits

The Spotify patches are derived from [2eno's patches](https://github.com/2eno/morphe-patches),
licensed under the GNU General Public License v3.0. They have been modified by pablobaro
(support for newer Spotify versions and the new "Disable ad breaks" patch).

## 📜 License

Pablobaro Morphe patches are licensed under the [GNU General Public License v3.0](LICENSE)
