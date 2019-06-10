# Sample for bug: [WEB-39294](https://youtrack.jetbrains.com/issue/WEB-39294)

To reproduce bug follow these steps:
* open this repo in WebStorm
* yarn install
* try to run single test in `packages/ejected`, it fails
* try to run single test in `packages/not-ejected`, it passes