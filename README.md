# 3x-ui Ad-Free Edition

This is an ad-free version based on the original 3x-ui project, with built-in advertisements and promotional content removed.

Original project: [MHSanaei/3x-ui](https://github.com/MHSanaei/3x-ui)

Fork releases prefix the upstream version number with `10`. For example, upstream `v3.11.0` becomes `v103.11.0`.

## One-Command Installation

Run the following command as root on a Linux server to install the latest stable release from this repository:

```bash
bash <(curl -fsSL https://raw.githubusercontent.com/OJZen/3x-ui/main/install.sh)
```

A stable release with installation packages must be published before this command can be used. With GitHub Actions enabled, push a version tag matching `v*.*.*` or run the release workflow manually on that tag to build and publish the packages. Manual runs on a branch only produce build artifacts. The installer displays the panel URL and login credentials when installation finishes.
