# Holger Trahe

Senior Rust Engineer based in Lüdinghausen, Germany.
13+ years of software engineering, focused on open-source
Rust toolchain for the lighting and BIM industries.

## What I work on

### Lighting & BIM toolchain

Each core crate ships from a single Rust source tree to multiple
ecosystems: Rust (crates.io, 28k+ downloads), Python (PyO3 / PyPI,
200k+ downloads), Swift and Kotlin (UniFFI), Flutter, and WebAssembly.
The same Rust core powers the web showcases and the Apple apps.

- **gldf-rs** — reference Rust implementation of the international
  GLDF standard for photometric lighting data
  · [github](https://github.com/holg/gldf-rs)
  · [crates.io](https://crates.io/crates/gldf-rs)
  · [PyPI](https://pypi.org/project/gldf-rs-python/)

- **eulumdat** — legacy EULUMDAT format with cross-platform bindings
  · [github](https://github.com/holg/eulumdat-rs)
  · [crates.io](https://crates.io/crates/eulumdat)
  · [PyPI](https://pypi.org/project/eulumdat/)

- **l3d-rs** — L3D format support (used as GLDF 3D model input)
  · [github](https://github.com/holg/l3d-rs)
  · [crates.io](https://crates.io/crates/l3d-rs)
  · [PyPI](https://pypi.org/project/l3d-rs-python/)

- **bimifc** — IFC parsing and BIM viewer core with integrated
  lighting visualization
  · [github](https://github.com/holg/bimifc)
  · [crates.io](https://crates.io/crates/bimifc)
  · [PyPI](https://pypi.org/project/bimifc/)

### Live showcase sites (Rust + WebAssembly)

- **[bimifc.de](https://bimifc.de)** — BIM viewer based on the
  `bimifc` crate
- **[gldf.icu](https://gldf.icu)** — GLDF browser toolkit based on
  `gldf-rs`
- **[eulumdat.icu](https://eulumdat.icu)** — EULUMDAT toolkit based
  on `eulumdat`
- **[iesna.eu](https://iesna.eu)** — photometric tools and virtual
  goniophotometer
- **[acadlisp.de](https://acadlisp.de)** — AutoLISP REPL in Rust +
  WASM (7,300+ downloads)

### Native Apple platform apps

App Store-distributed. The Rust libraries powering these apps are
actively maintained; app releases follow as needed.

- **geodb** — offline geolocation lookup based on `geodb-rs`.
  Native iOS, iPadOS, **watchOS**, and **tvOS**.
- **gldf** — photometric data viewer for iOS and macOS, built on
  `gldf-rs`. App release lags the Rust library.
- **eulumdat** — EULUMDAT data viewer for iOS and macOS, built on
  `eulumdat`. App release lags the Rust library.
- **[RoomPlan Simple](https://github.com/holg/RoomPlanExampleApp)** —
  LiDAR room scanning for iOS with multi-format export (STL, USDZ,
  DXF, **IFC** via embedded `bimifc` — enabling full IFC rendering,
  not just conversion), position-tagged photo capture (rendered into
  the 3D model), and live **WiFi strength heatmap** generated during
  the scan.

### Open source contributions

- **Bevy Engine** — Rendering Core PRs (#23436 partial bindless
  on Metal, #23439 GPU clustering), RFC #23480 for photometric
  rendering, with endorsement from core contributor mate-h
- **Burn** — Metal backend optimizations for Apple Silicon
- **CubeCL** — wgpu command encoder, WASM poll gating (#1204)
- **Various OSS projects** — accepted PRs to Pillow, Leptos,
  Synphonyte, diesel_cli_ext, and others

## Stack and interests

Rust · WebAssembly · Bevy · wgpu · Apple Metal · Leptos · Axum
Cross-Platform Bindings (PyO3, UniFFI, Flutter) · watchOS · tvOS
Computer Graphics · Photometric Engineering · BIM/IFC · Lighting
Industry Standards

## Other work

- **[Rusterando](https://github.com/holg/rusterando)** — AGPL
  self-hostable restaurant delivery platform in pure Rust
  (Leptos + Axum + SQLite + Stripe + APNs + Typst). Demo at
  [rusterando.de](https://rusterando.de).

- **geodb-rs** — offline geolocation library in Rust, with Python
  and Flutter bindings. Live demo and benchmark at
  [trahe.eu/geodb-rs.html](https://trahe.eu/geodb-rs.html).
  · [github](https://github.com/holg/geodb-rs)
  · [crates.io](https://crates.io/crates/geodb-rs)
  · [PyPI](https://pypi.org/project/geodb-rs/)
  · [Flutter](https://pub.dev/packages/geodb_flutter)

## Links

- [trahe.eu](https://trahe.eu) — main site
- [crates.io/users/holg](https://crates.io/users/holg) — Rust crates
- [pypi.org/user/holg](https://pypi.org/user/holg/) — Python packages
- [github.com/holg](https://github.com/holg) — all repositories

## Support my open-source work

If your team uses any of my crates in production — whether through
crates.io, PyPI, or WebAssembly — or you find value in standards-level
work for GLDF/EULUMDAT/photometric formats, consider
[sponsoring me on GitHub](https://github.com/sponsors/holg). Every
sponsorship directly supports continued maintenance and new development.
