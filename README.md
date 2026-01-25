# Quassel Client

___Modern distributed IRC client___

Quassel IRC is a modern, cross-platform, distributed IRC client based on the Qt framework.

---

## Manual Install and Run

Make sure you follow the [setup guide for your Linux distribution](https://flathub.org/en/setup) before installing.

```bash
flatpak install flathub org.quassel_irc.QuasselClient
flatpak run org.quassel_irc.QuasselClient
```

## Building

```bash
git clone git@github.com:flathub/org.quassel_irc.QuasselClient.git
flatpak run org.flatpak.Builder build-dir --user --ccache --force-clean --install org.quassel_irc.QuasselClient.json
```
