`juniper_graphql_ws` changelog
==============================

All user visible changes to `juniper_graphql_ws` crate will be documented in this file. This project uses [Semantic Versioning 2.0.0].




## master

### BC Breaks

- Switched to 0.16 version of [`juniper` crate].
- Switched to 0.17 version of [`juniper_subscriptions` crate].

### Changed

- Made fields of `ConnectionConfig` public to reuse in [`juniper_graphql_transport_ws` crate]. ([#1191])

[#1191]: /../../pull/1191




## Previous releases

See [old CHANGELOG](/../../blob/juniper_graphql_ws-v0.3.0/juniper_graphql_ws/CHANGELOG.md).




[`juniper` crate]: https://docs.rs/juniper
[`juniper_graphql_transport_ws` crate]: https://docs.rs/juniper_graphql_transport_ws
[`juniper_subscriptions` crate]: https://docs.rs/juniper_subscriptions
[Semantic Versioning 2.0.0]: https://semver.org
