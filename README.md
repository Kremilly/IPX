# IPInfo

Get IP info of a url using Rust

> [!important]
>
> This is a simple example of get information's of website

Basic usage:

```shell
cargo run kremilly.com

# OR

ipfinfo kremilly.com
```

Dependencies:

```toml
ipgeolocate = "0.3.6"
tokio = { version = "1.37.0", features = ["full"] }
whois-rust = "1.6.0"
```
