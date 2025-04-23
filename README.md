# QEmacs for Embedding

This repository builds the small static terminal-only QEmacs with the size
optimizations applied.

The resulting binary is intended for embedding it into limited environments
like k8s containers or initramfs for cases when some text/config editing is
required but the size is limited and usual libraries are not available.

# Using

Just download binary and place it where it's required

# Sources

- musl from https://github.com/ifduyue/musl
- qemacs from https://github.com/qemacs/qemacs
