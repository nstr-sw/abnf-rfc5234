# abnf-rfc5234

[![Crates.io](https://img.shields.io/crates/v/abnf-rfc5234?style=flat-square)](https://crates.io/crates/abnf-rfc5234)
[![Crates.io](https://img.shields.io/crates/d/abnf-rfc5234?style=flat-square)](https://crates.io/crates/abnf-rfc5234)
[![License](https://img.shields.io/badge/license-ISC-blue?style=flat-square)](LICENSE)

Rust library for working with Augmented BNF (ABNF) Syntax Specifications
in accordance with RFC 5234 (<https://www.rfc-editor.org/rfc/rfc5234.html>).

Parsing is performed using crates [pest](https://pest.rs/) and
[pest_derive](https://crates.io/crates/pest_derive).

This library is targeted at crates that wish to implement parsing
relating to syntax defined in other RFCs.

It is expected that application crates will NOT use `abnf-rfc5234` directly,
but that they might pull it in as an indirect dependency if they use other
library crates that make use of this library crate for parsing of syntax
defined in other RFCs.

## git repo URLs

- Main repo: https://git.nstr.no/nstr-sw/abnf-rfc5234
- GitHub mirror: https://github.com/nstr-sw/abnf-rfc5234

## Notable library crates that use this library crate

None yet :^)
