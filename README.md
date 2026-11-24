# BoxedIn releases

Signed releases of [BoxedIn](https://beetlebug.org/boxedin/), a tiling window manager for macOS. This repository holds the release files only. BoxedIn is free while it is in preview, and its source is not public.

Each release has three files:

| File | Contents |
|---|---|
| `BoxedIn-VERSION.zip` | The app, signed with Developer ID and notarized by Apple. |
| `SHA256SUMS` | The SHA-256 of the zip. |
| `SHA256SUMS.sig` | An Ed25519 signature of `SHA256SUMS`. |

BoxedIn checks this repository for a new release and installs one only when the signature matches its built-in public key and the zip matches `SHA256SUMS`.

The public key (Ed25519, base64):

```
60YcqR5usmND8hbivrNRjEj6TAWw694wsIcII+DdCcI=
```
