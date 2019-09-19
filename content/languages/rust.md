---
title: Rust
weight: 4
---

# Overview

<table>
  <tr><th>Crate</th><th>Repository</th><th>Examples</th><th>ZMTP engine</th><th>Description</th></tr>
  <tr>
    <td>https://crates.io/crates/zmq</td>
    <td>https://github.com/erickt/rust-zmq</td>
    <td>https://github.com/erickt/rust-zmq/tree/master/examples</td>
    <td>libzmq</td>
    <td></td>
  </tr>
  <tr>
    <td>https://crates.io/crates/zeromq</td>
    <td>https://github.com/zeromq/zmq.rs</td>
    <td></td>
    <td>custom</td>
    <td></td>
  </tr>
  <tr>
    <td>https://crates.io/crates/futures-zmq</td>
    <td></td>
    <td></td>
    <td>libzmq (via zmq crate)</td>
    <td></td>
  </tr>
  <tr>
    <td>https://crates.io/crates/tokio-zmq</td>
    <td></td>
    <td></td>
    <td>libzmq (via zmq crate)</td>
    <td></td>
  </tr>
  <tr>
    <td>https://crates.io/crates/tmq</td>
    <td></td>
    <td></td>
    <td>libzmq (via zmq crate)</td>
    <td></td>
  </tr>
  <tr>
    <td>https://crates.io/crates/sawtooth-zmq</td>
    <td></td>
    <td></td>
    <td>libzmq (via zmq crate)</td>
    <td></td>
  </tr>
  <tr>
    <td>https://crates.io/crates/libzmq</td>
    <td></td>
    <td></td>
    <td>libzmq</td>
    <td></td>
  </tr>
  <tr>
    <td>https://crates.io/crates/libzmq-sys</td>
    <td></td>
    <td></td>
    <td>libzmq</td>
    <td></td>
  </tr>
  <tr>
    <td>https://crates.io/crates/zmq-pw</td>
    <td></td>
    <td></td>
    <td>libzmq</td>
    <td>Looks similar to sawtooth-zmq??</td>
  </tr>
  <tr>
    <td>https://crates.io/crates/tmq-zmq</td>
    <td></td>
    <td></td>
    <td>libzmq</td>
    <td>Looks similar to sawtooth-zmq??</td>
  </tr>
  <tr>
    <td>https://crates.io/crates/zmq-rs</td>
    <td></td>
    <td></td>
    <td>libzmq</td>
    <td></td>
  </tr>
  <tr>
    <td>https://crates.io/crates/rustyq</td>
    <td></td>
    <td></td>
    <td>custom</td>
    <td></td>
  </tr>
  <tr>
    <td></td>
    <td>https://github.com/petehayes102/rust-czmq</td>
    <td></td>
    <td>libzmq</td>
    <td></td>
  </tr>  
</table>

# zmq crate

## Installation

[Install libzmq]({{< relref "/docs/download" >}}).

Add the following Cargo.toml file:

```toml
[dependencies]
zmq = "0.9"
```

