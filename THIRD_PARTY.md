# Third-party code and filter data

- SafariConverterLib 4.3.1 and its FilterEngine: GPL-3.0, original source and LICENSE in Vendor/SafariConverterLib.
- Scriptlets 2.3.1: GPL-3.0. Preferred source in Vendor/scriptlets-source, published runtime in Vendor/scriptlets; fixed runtime generated from dist/scriptlets.corelibs.json.
- ExtendedCss 2.1.1: GPL-3.0. Preferred source in Vendor/extended-css-source; published runtime in Vendor/extended-css.
- PunycodeSwift 3.0.0: MIT, original notice in Vendor/Punycode/LICENSE.
- swift-psl 1.1.43, commit 7ccee9d576d4ca45219440e346f61117f44c816f: MIT, original notice and public suffix data in Vendor/swift-psl.
- AdGuard iOS optimized lists 2, 11, 224, 1, 19, 20: original snapshots, upstream headers and GPL license in FilterSources. Base includes EasyList material; its upstream has GPL-3.0 / CC-BY-SA-3.0 license alternatives. This project's current integration follows the supplied GPL path, not a blanket relicensing of every upstream contribution.

Detailed notices are also shipped in VeilBrowser/FilterResources/NOTICES.txt. FilterSources/sources.json records the URLs, header versions, and SHA-256 hashes of the six original input files. RELEASE-MANIFEST.json records hashes of files in this source archive. Upstream source files have not been modified; Vendor/Package.swift is the app-specific offline target composition. The bundled upstream version-generation plugin and CLI targets are not required for the app build.

Current source license declarations do not establish a third-party App Store redistribution exception. No commercial SDK redistribution agreement has been received.
