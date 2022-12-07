[nav_order: 7]

# Testing

In order to test your Sway and TS-SDK applications, you can test your code in a number of ways:

1. Testing with TS-SDK: Compiling you Sway code and connecting to the methods using TS-SDK and JS testing frameworks
2. Using `forc test` see [the Sway docs](https://fuellabs.github.io/sway/v{{site.data.versions.sway}}/forc/commands/forc_test.html) for more info
3. Using [the Rust SDK](https://fuellabs.github.io/fuels-rs/v0.31.1/testing/index.html)

### Testing with TS-SDK

To test your Sway applications using the TS-SDK, you can pick whatever testing library or framework you feel comfortable with. There isn't any specific testing framework needed, it is entirely up to the user. That being said, the TS-SDK uses [Jest](https://jestjs.io/) for its tests.