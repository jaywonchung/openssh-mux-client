# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.17.6](https://github.com/jaywonchung/openssh-mux-client/compare/openssh-mux-client-v0.17.5...openssh-mux-client-v0.17.6) - 2024-09-10

### Other

- Check `read` 0 for local forwarding as well
- `read` returning 0 seems to mean a closed socket
- Try read instead
- Test socket accept after closure
- Fix fmt
- Format nits and doc comments
- Fix fmt
- Implement port forwarding closure

## [0.17.5](https://github.com/openssh-rust/openssh-mux-client/compare/openssh-mux-client-v0.17.4...openssh-mux-client-v0.17.5) - 2024-08-23

### Other
- Update typed-builder requirement in /crates/mux-client ([#55](https://github.com/openssh-rust/openssh-mux-client/pull/55))

## [0.17.4](https://github.com/openssh-rust/openssh-mux-client/compare/openssh-mux-client-v0.17.3...openssh-mux-client-v0.17.4) - 2024-07-15

### Other
- Update typed-builder requirement in /crates/mux-client ([#52](https://github.com/openssh-rust/openssh-mux-client/pull/52))
