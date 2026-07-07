### Added

- Per-builder `builders` entries in proposer settings with url, pubkey, proxy, and max_execution_payment, decoupling the VC-signed builder identity from the HTTP dial target and crediting trusted execution payments only for listed builder pubkeys, and per-builder min_bid and builder_boost_factor selection knobs; `relays` remains a deprecated alias.
