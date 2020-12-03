<!--
https://readme42.com
-->



[![](https://img.shields.io/badge/OS-macOS-blue.svg?longCache=True)]()
[![](https://img.shields.io/pypi/v/mac-app-factory.svg?maxAge=3600)](https://pypi.org/project/mac-app-factory/)
[![](https://img.shields.io/npm/v/mac-app-factory.svg?maxAge=3600)](https://www.npmjs.com/package/mac-app-factory)[![](https://img.shields.io/badge/License-Unlicense-blue.svg?longCache=True)](https://unlicense.org/)
[![](https://github.com/andrewp-as-is/mac-app-factory/workflows/tests42/badge.svg)](https://github.com/andrewp-as-is/mac-app-factory/actions)

### Installation
```bash
$ [sudo] pip install mac-app-factory
```

```bash
$ [sudo] npm i -g mac-app-factory
```

#### How it works
```
<name>.app
├── Contents
│   ├── MacOS
│   │   └── executable
│   ├── Resources
│   │   └── Icon.icns
│   └── Info.plist
│   executable          # edit this file. shebang required
│   <image>.png         # copy any png image
│   reveal.sh           # helper for reveal folder from your IDE
```

#### Features
+   super fast (pure shell)
+   safe (native apps ignored)

#### Examples
```bash
$ mac-app-factory path/to/my-finder-toolbar-apps path/to/my-dock-apps
```

```bash
$ mac-app-factory path/to/name1.app path/to/name2.app
```

<p align="center">
    <a href="https://readme42.com/">readme42.com</a>
</p>
