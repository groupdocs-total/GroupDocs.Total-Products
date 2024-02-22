# GroupDocs.Total Landing Pages

This repository contains the files used to generate GroupDocs.Total landing pages e.g. <https://products.groupdocs.com/total/net/>

## Prerequisites

Install Hugo and related tools

`npm i -g hugo-extended@0.101.0 postcss postcss-cli autoprefixer`

## Clone the theme

1. Make sure to add a record to your `.ssh\config` file

```
#aspose.github.com
    Host aspose.github.com
    HostName github.com
    User git
    IdentityFile ~/.ssh/<your-private-key>
```

2. Clone the theme to the `common` folder `git submodule update --recursive --init`

3. Remove all the folders except `total` in the `common/content` folder with `find './common/content' -mindepth 1 -type d -not -regex '^./common/content/total\(/.*\)?' -exec rm -rf {} +` (bash)

## Run

* Copy files from `content\total` folder to `common\content\total` with `cp -r ./content/total ./common/content/total`

* Navigate to `common` folder with `cd common`

* Execute `hugo server --config "./total-staging-config.toml" --disableFastRender` to build pages and start Hugo server

## Publishing

Commit your changes or create a pull request into `master` branch and GitHub actions will do the rest.
