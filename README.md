[![License](https://img.shields.io/badge/License-BSD%202--Clause-blue.svg)](https://opensource.org/licenses/BSD-2-Clause)

# About
This library provides basic functionality to create/send and receive/parse HTTP-headers and -bodies.

We provide the following building blocks:
 - Creating/sending and receiving/parsing of arbitrary HTTP-request- and -response-headers
 - Helper functions for parsing a chunked HTTP-body
 
# Build Library and Documentation
To build the documentation, go into the projects root-directory and run `cargo doc --release`; to open the documentation
in your web-browser, run `cargo doc --open`.

To build the library, go into the projects root-directory and run `cargo build --release`; you can find the build in
target/release.