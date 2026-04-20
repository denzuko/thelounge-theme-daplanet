# thelounge-theme-daplanet

Da Planet Security / Da Planet Radio theme for [TheLounge](https://thelounge.chat/).

Matches the design system of [klaxon.dapla.net](https://klaxon.dapla.net) — the Da Planet Radio icecast2 status page.

## Design

- **Fonts**: Orbitron (display/headers) + Rajdhani (body)
- **Palette**: Deep navy/cyber — `#030a14` background, `#00f0ff` cyber accent, `#4a9eff` glow
- **Style**: Terminal/hacker aesthetic, scanline texture, boot-glow animation on connect
- **Bonus**: Styled integration with `thelounge-plugin-webcal` — webcal links render as palette-matched buttons

## Install

```sh
thelounge install thelounge-theme-daplanet
```

Then in TheLounge → Settings → Appearance → Theme → select **daplanet**.

## Manual install

```sh
THELOUNGE_HOME=$(thelounge --help | grep home | awk '{print $NF}')
mkdir -p $THELOUNGE_HOME/packages/node_modules
cd $THELOUNGE_HOME/packages/node_modules
npm pack thelounge-theme-daplanet
tar xzf thelounge-theme-daplanet-*.tgz
mv package thelounge-theme-daplanet
```

## License

MIT — Da Planet Security, Albany NY
