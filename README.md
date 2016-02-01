# target_info

Super simple library to get stringified versions of the various build target configuration attributes.

Example:

```rust
use target_info::Target;
println!("Target is {}-{}-{}", Target::arch(), Target::env(), Target::os());
```
