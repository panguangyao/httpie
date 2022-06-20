###rustc
`version 1.61.0`

###step1
cargo run -- post httpbin.org/post a=1 b=2

###step2
cargo run -- post https://httpbin.org/post a=1 b=2