<a name="3.1.1"></a>

## [3.1.1](https://github.com/mapbox/remark-react/compare/v3.1.0...v3.1.1) (2017-03-07)

### Bug Fixes

*   **output:** Remove unknown prop 'align' ([e0462f1](https://github.com/mapbox/remark-react/commit/e0462f1))

# 3.1.0

*   Adds `toHast` option that allows customization at the [mdast-util-to-hast](https://github.com/wooorm/mdast-util-to-hast#api)
    level.

# 3.0.2

*   Fixes interpretation of the `sanitize` option, allowing users to pass
    `false` to disable sanitization.

# 2.1.0

*   Only allows `http`, `mailto`, and `https` schemes for links.

# 2.0.0

*   Update to Remark 4

# 0.3.0

*   Added `mdastReactComponents` option #[9](https://github.com/mapbox/mdast-react/pull/9)
*   React 0.14 support #[8](https://github.com/mapbox/mdast-react/pull/8)

# 0.2.0

*   Support for Markdown footnotes

# 0.1.2

*   Fix sequential key ordering so that server-side renders
    of Markdown will match client-side binding
