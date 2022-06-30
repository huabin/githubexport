# gitexport

Exporting content that does not contain .git 

### Intro

`gitexport` is a simple bash script to export content that does not contain .git.

Recently, I need to upload a project without a .git file to another place (E.g. Cloudflare Pages), so I wrote this script.

### Install

```
curl https://raw.githubusercontent.com/huabin/gitexport/master/gitexport | bash
```

### How to use

Run command `gitexport` in the root directory of the project.

The exported content will be generated on your Desktop in a folder named `gitexport`.

### How to Collaborate

Please feel free to submit your PR or issue.

### Copyright

[MIT License](LICENSE)
