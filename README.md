# Patch Viewer

[![Ask DeepWiki](https://deepwiki.com/badge.svg)](https://deepwiki.com/megatops/PatchViewer) ![GitHub License](https://img.shields.io/github/license/megatops/PatchViewer?logo=license) ![GitHub top language](https://img.shields.io/github/languages/top/megatops/PatchViewer) ![GitHub contributors](https://img.shields.io/github/contributors-anon/megatops/PatchViewer) ![GitHub forks](https://img.shields.io/github/forks/megatops/PatchViewer) ![GitHub Repo stars](https://img.shields.io/github/stars/megatops/PatchViewer)

Single file, browser based side-by-side patch viewer.

Try it online: https://megatops.github.io/PatchViewer/

Just save the `PatchViewer.html` to use it offline. No any other dependencies or network access are needed.

Screenshot:

![image](https://github.com/megatops/PatchViewer/assets/13481083/7154076b-4561-45ff-a286-4323576d85d8)

## Release History

**v0.8**

- Add save button in the viewer (by Dror Harari)
- Hide the patch text entry dialog to get more screen space - revealed again by pressing "Load a new patch" button (by Dror Harari)

**v0.7**

- Support multi-line selection (by Sebastian).
- Support dark mode (follow system theme).

**v0.6.1**

- Fixed a regression bug when parsing diff with only 1 line changed.

**v0.6**

- Better support for `git format-patch` patches.

**v0.5**

- Resolved the issue when parsing `git diff` which contains `\ No newline at end of file`;
- Fix for easy selection of multiple lines (by Sajal Gautam).

**v0.4**

- Support file list and file navigator;
- Open source.

**v0.3**

- Bug fixes;
- First public release.

**v0.2**

- Support unified diff.

**v0.1**

- Initial release, support context diff.

