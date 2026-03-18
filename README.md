# fastled-playground

A sandbox for experimenting with the latest FastLED master commits — develop animations, establish standards and guidelines, and test and deploy them in one place.

Work developed here can be submitted as pull requests to [FastLED/FastLED](https://github.com/FastLED/FastLED) when ready.

## Active Development Areas

FastLED is currently expanding into several new functional areas:

* **[FastLED Audio](https://github.com/FastLED/FastLED/blob/master/src/fl/audio/README.md)** — Audio-reactive LED system with 19+ detectors for beat detection, frequency analysis, pitch estimation, and FFT spectrum analysis. Supports callback-based events, polling getters, and multiple microphone backends.

* **[FastLED Channels API](https://github.com/FastLED/FastLED/blob/master/src/fl/channels/README.md)** — Modern hardware abstraction for DMA-based parallel LED strip driving with automatic driver selection (PARLIO, RMT, SPI, I2S, UART). Supports per-channel gamma correction and lifecycle callbacks.

* **[FastLED FX](https://github.com/FastLED/FastLED/tree/master/src/fl/fx)** — Visual effects and animation primitives built on top of the FastLED rendering pipeline, designed for composable and reusable LED animations.

* **[FastLED GFX Canvas](https://github.com/FastLED/FastLED/tree/master/src/fl/gfx)** — Graphics rendering and drawing capabilities for LED matrices and complex layouts, including geometry primitives and compositing.

* **[FastLED Font](https://github.com/FastLED/FastLED/tree/master/src/fl/font)** — Typography and character rendering for LED displays, enabling text output on matrix-style LED setups.

* **[FastLED std (`fl::` namespace)](https://github.com/FastLED/FastLED/blob/master/src/fl/README.md)** — Cross-platform foundation layer providing embedded-friendly alternatives to standard C++ facilities: STL-like data structures, concurrency/async utilities, color/math/signal processing, and I/O/JSON/text formatting.

* **[FastLED fixed-point](https://github.com/FastLED/FastLED/blob/master/src/fl/stl/fixed_point/README.md)** — Integer-only arithmetic for embedded systems without FPU, offering 5–100× speed improvements over floating-point on ARM. Provides templated `sfixed_integer`/`ufixed_integer` types with math functions and SIMD variants.

* **[fbuild](https://github.com/FastLED/fbuild/blob/master/README.md)** — Fast, next-generation multi-platform compiler and deployer for embedded development (Arduino, ESP32, Teensy, WebAssembly). A modern PlatformIO replacement with LTO and URL-based package management.

* **[WebAssembly (wasm)](https://github.com/FastLED/FastLED/blob/master/src/platforms/wasm/README.md)** — Browser platform implementation using WebAssembly with Web Workers for multithreading. Follows a data-export approach where C++ allocates LED buffers returned to JavaScript, with full Emscripten pthread/atomic support.

> **Status:** This repository is brand new. Initial efforts will focus on defining a contribution workflow and making the first PRs.
