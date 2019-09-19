---
title: Rust
weight: 4
---

# Overview

## Current (updated within 2018 or later)

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
    <td>https://crates.io/crates/futures-zmq</td>
    <td>https://git.asonix.dog/asonix/async-zmq</td>
    <td></td>
    <td>libzmq (via zmq crate)</td>
    <td></td>
  </tr>
  <tr>
    <td>https://crates.io/crates/tokio-zmq</td>
    <td>https://git.asonix.dog/asonix/async-zmq</td>
    <td></td>
    <td>libzmq (via zmq crate)</td>
    <td></td>
  </tr>
  <tr>
    <td>https://crates.io/crates/tmq</td>
    <td>https://github.com/cetra3/tmq</td>
    <td></td>
    <td>libzmq (via zmq crate)</td>
    <td></td>
  </tr>
  <tr>
    <td>https://crates.io/crates/libzmq</td>
    <td>https://github.com/jean-airoldie/libzmq-rs</td>
    <td></td>
    <td>libzmq</td>
    <td></td>
  </tr>
  <tr>
    <td>https://crates.io/crates/libzmq-sys</td>
    <td>https://github.com/jean-airoldie/libzmq-rs</td>
    <td></td>
    <td>libzmq</td>
    <td>Low-level layer of libzmq crate</td>
  </tr>
</table>

## Historic (last updated 2017 or earlier)

<table>
  <tr><th>Crate</th><th>Repository</th><th>Examples</th><th>ZMTP engine</th><th>Description</th></tr>
  <tr>
    <td>https://crates.io/crates/zeromq</td>
    <td>https://github.com/zeromq/zmq.rs</td>
    <td></td>
    <td>custom</td>
    <td></td>
  </tr>
  <tr>
    <td>https://crates.io/crates/zmq-pw</td>
    <td>https://github.com/evernym/rust-zmq-pw</td>
    <td></td>
    <td>libzmq</td>
    <td>Fork of zmq crate?</td>
  </tr>
  <tr>
    <td>https://crates.io/crates/zmq-rs</td>
    <td>https://github.com/Ginurx/zmq-rs</td>
    <td></td>
    <td>libzmq</td>
    <td></td>
  </tr>
  <tr>
    <td>https://crates.io/crates/rustyq</td>
    <td>https://bitbucket.org/jjpe/rustyq/ (apparently non-public)</td>
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

## Missing repository

<table>
  <tr><th>Crate</th><th>Repository</th><th>Examples</th><th>ZMTP engine</th><th>Description</th></tr>
  <tr>
    <td>https://crates.io/crates/sawtooth-zmq</td>
    <td></td>
    <td></td>
    <td>libzmq</td>
    <td>Fork of zmq crate?</td>
  </tr>
  <tr>
    <td>https://crates.io/crates/tmq-zmq</td>
    <td></td>
    <td></td>
    <td>libzmq</td>
    <td>Fork of zmq crate??</td>
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

