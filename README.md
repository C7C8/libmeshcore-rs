# meshcore-rs

Meshcore-RS is a project to bring Meshcore to Rust, including native applications for Linux that don't rely
on web browsers. This includes:

* **MeshCore-Chat:** A TUI application for chatting over MeshCore using a client/companion node.
* **Meshcore-CLI:** CLI support for MeshCore, allowing easy administration and scripting
* **libmeshcore-client-support:** Client support library handling connections over BLE
* **libmeshcore-proto:** MeshCore protocol implementation

All projects are licensed freely under the GPLv3 (or the AGPLv3 in the case of libmeshcore-proto)

## Building
Standard `cargo build --release` works fine. **Important - Ubuntu users:** You need `libdbus-1-dev`
installed to successfully build.