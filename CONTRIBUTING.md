# Contributing

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Prerequisites

- [Node.js](https://nodejs.org/) (14.x or higher)
- [.NET runtime and SDK](https://aka.ms/dotnet-download)
- [.NET CLI tools](https://github.com/dotnet/cli/releases) version 2.0.0 or higher
  > You want the **.NET Core SDK Binaries** for your platform
  >
  > `dotnet --version`
  > `2.0.2`

Note: Users on Apple-silicon Macs must use the X64 dotnet install (for now).

## Build scripts

## How to build

Run `npm install` to install the required modules.  Then build with `npm run dn.build`.

```sh
npm install
npm run dn.build
```

## How to test

To run all tests under the repo

```sh
npm run dn.test
```

## How to run locally

## How to bundle node package & install

```javascript
gulp pack
npm install -g oad-0.1.0.tgz
```

This will install all of the npm dependencies of all projects in the
repo. Do this whenever you `git pull` or your workspace is freshly
cleaned/cloned.
