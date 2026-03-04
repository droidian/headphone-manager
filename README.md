# Session headphone manager for Linux

This user service handle headphones:
- Mute/unmute headphone on plug/unplug
- Launch favorite music application on plug

## Depends on

- `glib2`
- `meson`
- `ninja`

## Building from Git

```bash
$ meson builddir --prefix=/usr

$ sudo ninja -C builddir install
```
