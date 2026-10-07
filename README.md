# A67LG2 HubbleNullCorrector

Disables the hidden hubble/canary component baked into the factory firmware.

A KernelSU Next module for the **Foxxd A67L Gen 2**.

The factory firmware ships a hidden component (hubble/canary) that loads into apps and system
services. It only loads when two system properties have their factory values. This module sets
both to `off` early in every boot, so the component never loads. Nothing is removed or patched.

## Requirements

- Foxxd A67L Gen 2
- Rooted with KernelSU Next

The installer stops without changing anything if either is missing.

## Install

1. Download [`A67LG2-HubbleNullCorrector.zip`](https://github.com/thewickedlabs/A67LG2-HubbleNullCorrector/releases/latest/download/A67LG2-HubbleNullCorrector.zip) (latest release).
2. KernelSU Next → Modules → Install from storage → select the zip.
3. Reboot.

## Uninstall

Disable or remove the module and reboot. The firmware goes back to its factory behavior.

## License

[WTFPL](LICENSE).

---

Wicked Labs · https://www.cyberspace7.org
