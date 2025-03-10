# Build systems

## Links

* [Please](https://github.com/thought-machine/please) - High-performance extensible build system for reproducible builds.
* [sbt](https://github.com/sbt/sbt) - Build tool for Scala, Java, and more.
* [Tundra](https://github.com/deplinenoise/tundra) - Code build system that tries to be accurate and fast for incremental builds.
* [gg](https://github.com/StanfordSNR/gg) - The Stanford Builder.
* [mmake](https://github.com/tj/mmake) - Small program which wraps make to provide additional functionality, such as user-friendly help output, remote includes, and eventually more. It otherwise acts as a pass-through to standard make.
* [Build Systems a la Carte](https://github.com/snowleopard/build) - Provides an executable framework for developing and comparing build systems, viewing them as related points in landscape rather than as isolated phenomena. ([Paper](https://www.cambridge.org/core/journals/journal-of-functional-programming/article/build-systems-a-la-carte-theory-and-practice/097CE52C750E69BD16B78C318754C7A4))
* [checkmake](https://github.com/mrtazz/checkmake) - Experimental linter/analyzer for Makefiles.
* [CMake](https://cmake.org) - Build, test and package software.
* [Effective Modern CMake](https://gist.github.com/mbinna/c61dbb39bca0e4fb7d1f73b0d66a4fd1)
* [CMake Scripts](https://github.com/StableCoder/cmake-scripts) - Selection of useful scripts for use in CMake projects.
* [BLT](https://github.com/LLNL/blt) - Streamlined CMake-based foundation for Building, Linking and Testing large-scale high performance computing (HPC) applications.
* [zld](https://github.com/michaeleisel/zld) - Faster version of Apple's linker.
* [Automation and Make](https://swcarpentry.github.io/make-novice/)
* [Meson](https://github.com/mesonbuild/meson) - Project to create the best possible next-generation build system. ([Article](https://nibblestew.blogspot.com/2020/10/cargo-style-dependency-management-for-c.html)) ([HN](https://news.ycombinator.com/item?id=24845031))
* [mbt](https://github.com/mbtproject/mbt) - Most flexible build orchestration tool for monorepo.
* [Earthly](https://github.com/earthly/earthly) - Run all your builds containerized. ([Web](https://www.earthly.dev))
* [Synchronicity](https://github.com/iqlusioninc/synchronicity) - Distributed build system providing cryptographic proofs-of-reproducibility via Byzantine Fault Tolerant (BFT) consensus.
* [Ninja](https://github.com/ninja-build/ninja) - Small build system with a focus on speed. ([ninja: a simple way to do builds](https://jvns.ca/blog/2020/10/26/ninja--a-simple-way-to-do-builds/)) ([Lobsters](https://lobste.rs/s/94llji/ninja_simple_way_do_builds)) ([HN](https://news.ycombinator.com/item?id=24904617))
* [The Success and Failure of Ninja (2020)](http://neugierig.org/software/blog/2020/05/ninja.html) ([HN](https://news.ycombinator.com/item?id=23157783))
* [samurai](https://github.com/michaelforney/samurai) - Ninja-compatible build tool written in C99 with a focus on simplicity, speed, and portability.
* [Apple’s Linker & Deterministic Builds (2020)](https://milen.me/writings/apple-linker-ld64-deterministic-builds-oso-prefix/)
* [my love letter to redo (2020)](https://fzakaria.com/2020/06/08/my-love-letter-to-redo.html) ([Lobsters](https://lobste.rs/s/j96fsz/my_love_letter_redo))
* [Awesome CMake](https://github.com/onqtam/awesome-cmake)
* [Build](https://github.com/rizsotto/Bear) - Tool that generates a compilation database for clang tooling.
* [How to list all the targets on a Makefile (2020)](https://diamantidis.github.io/tips/2020/07/01/list-makefile-targets) ([HN](https://news.ycombinator.com/item?id=23702756))
* [You don’t need reproducible builds (2020)](http://blog.cmpxchg8b.com/2020/07/you-dont-need-reproducible-builds.html) ([Lobsters](https://lobste.rs/s/ha8c42/you_don_t_need_reproducible_builds)) ([HN](https://news.ycombinator.com/item?id=24059410))
* [Strategies for Binary Relocation In Functional Build Systems (2020)](https://maxmcd.com/posts/strategies-for-binary-relocation/) ([Lobsters](https://lobste.rs/s/2lnncd/strategies_for_binary_relocation))
* [Reproducible Telegram Builds for iOS and Android](https://core.telegram.org/reproducible-builds)
* [Faster Builds with Code Signing Hacks (2020)](https://eisel.me/jekyll/update/2020/08/07/signing.html)
* [Allowing CMake functions to return(value) (2020)](https://oleksandrkvl.github.io/2020/08/09/allowing-cmake-functions-to-return-value.html)
* [The quest to the perfect Makefile (2018)](https://r4nd0m6uy.ch/the-quest-to-the-perfect-makefile.html)
* [Build systems with Andrey Mokhov (2020)](https://overcast.fm/+hrS7F9\_XA)
* [Amazon's Build System](https://gist.github.com/terabyte/15a2d3d407285b8b5a0a7964dd6283b0) ([HN](https://news.ycombinator.com/item?id=24722214))
* [Pondering Amazon's Manyrepo Build System (2020)](http://beza1e1.tuxen.de/amazon_manyrepo_builds.html) ([Lobsters](https://lobste.rs/s/v6vmov/pondering_amazon_s_manyrepo_build_system))
* [xmake](https://github.com/xmake-io/xmake) - Cross-platform build utility based on Lua. ([Docs](https://xmake.io/#/))
* [Merkle trees and build systems](https://lwn.net/Articles/821367/)
* [Introduction to Makefiles (2020)](https://xs-labs.com/en/blog/2020/11/07/introduction-to-makefiles/) ([HN](https://news.ycombinator.com/item?id=25026656))
* [engage](https://github.com/breuleux/engage) - Incremental build tool with automatic dependency tracking.
* [remake](https://github.com/rocky/remake) - Enhanced GNU Make - tracing, error reporting, debugging, profiling and more.
* [Goma](https://chromium.googlesource.com/infra/goma/client/) - Distributed compiler service for open-source project such as Chromium and Android. It's some kind of replacement of distcc+ccache.
* [musl-cross-make](https://github.com/richfelker/musl-cross-make) - Fast, simple, but advanced makefile-based approach for producing musl-targeting cross compilers.
* [Reducing flaky builds by 18x (2020)](https://github.blog/2020-12-16-reducing-flaky-builds-by-18x/)
* [Reproducible Builds](https://reproducible-builds.org)
* [Tup](https://github.com/gittup/tup) - File-based build system. It takes as input a list of file changes and a directed acyclic graph (DAG). ([Web](http://gittup.org/tup/))
* [The Problem with Gradle (2021)](https://www.bruceeckel.com/2021/01/02/the-problem-with-gradle/) ([HN](https://news.ycombinator.com/item?id=25801986))
* [distcc](https://github.com/distcc/distcc) - Distributed builds for C, C++ and Objective C.
* [CMake Examples](https://github.com/ttroy50/cmake-examples) ([Web](http://ttroy50.github.io/cmake-examples/))
* [ninja-rs](https://github.com/nikhilm/ninja-rs) - Educational implementation of the ninja build system, based on ideas from the Build Systems a la Carte paper.
* [Cutting Build Time in Half with Docker’s Buildx Kubernetes Driver (2021)](https://releaseapp.io/blog/cutting-build-time-in-half-docker-buildx-kubernetes)
* [Persistent Storage and Fast Remote Builds (2021)](https://fly.io/blog/persistent-storage-and-fast-remote-builds/)
