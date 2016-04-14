# intermezzOS libcore

A libcore for intermezzOS.

Thanks to @thepowersgang and @phil-opp for their ‘remove floats from libcore’ patches and projects.

You usually won’t need to deal with this yourself, it will get pulled in by the kernel’s build
system.

This version of libcore is for:

```text
$ rustc --version

rustc 1.9.0-nightly (b622c3e08 2016-04-11)
```

To build:

```bash
$ cargo build --release --features disable_float --target=x86_64-unknown-intermezzos-gnu
```

After grabbing the `.json` file for the target from the `kernel` repo and copying it here.
