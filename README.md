# Sir Chester's `cors-anywhere`

This is a fork of the excellent [`cors-anywhere`]() library, which allows any website to be embedded in an iframe.

More speficially, to disallow themselves to be shown in an iframe, some websites:

- add an `X-Frame-Options` header,
- add some CSP.

This fork just removes those checks. See [PR #1](https://github.com/SirChesterApp/cors-anywhere/pull/1) for more info.

## License

All changes in this repo are licensed under MIT, the same license as the upstream project.

## Acknowledgements

This original author, [Rob--W](https://github.com/Rob--W).
