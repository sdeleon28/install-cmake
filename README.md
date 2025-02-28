# [install-cmake](https://github.com/marketplace/actions/install-cmake)

[![Action Status](https://github.com/Symbitic/install-cmake/workflows/build-test/badge.svg)](https://github.com/Symbitic/install-cmake/actions)

Downloads CMake and ninja-build binaries.
Works for Linux, macOS, and Windows.

This fork has updated links for new release file namings. It does not attempt to handle links to old versions gracefully.
It also updates the default version.

*Uses some code from <https://github.com/lukka/get-cmake> and <https://github.com/seanmiddleditch/gha-setup-ninja>.*

## Using

```yaml
    - name: Get CMake
      uses: symbitic/install-cmake@master
```

## Developing

Build with `tsc` by running:

    > npm run build

Launch `lint` by:

    > npm run lint

Build, lint, validate, and package for release:

    > npm run pack

Run unit tests:
 
    > npm run test

## License

Source code is licensed under the [MIT License](LICENSE.md).

Copyright (c) 2020 Alex Shaw  
