# Setup scripts

Welcome to TotallyMoney! This install.sh script will install some generic packages that are needed to run various components of TotallyMoney's codebases locally. To clone and run:

```
git clone git@github.com:totallymoney/tm-setup-scripts.git
cd tm-setup-scripts
./install.sh
```

If there's other packages you needed to install that you think would be useful for others, please make a PR to add them! If the package is only likely to be used on one repository/codebase (e.g `fastlane` for Native App), add it to the native app repository's Brewfile instead.
