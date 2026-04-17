![Demo](demo.gif) [![Backend Tests Status](https://github.com/ether/ep_prefer_color_scheme/actions/workflows/test-and-release.yml/badge.svg)](https://github.com/ether/ep_prefer_color_scheme/actions/workflows/test-and-release.yml)

# Make  Etherpad react to your systems default settings


For dark mode the following settings apply: 

```javascript
  const nightColors = {
    toolbar: 'dark',
    background: 'super-dark',
    editor: 'dark',
  }
```

For light mode: 

```javascript
  const dayColors = {
    toolbar: 'super-light',
    background: 'light',
    editor: 'super-light',
  }
```

## Installation

Install from the Etherpad admin UI (**Admin → Manage Plugins**,
search for `ep_prefer_color_scheme` and click *Install*), or from the Etherpad
root directory:

```sh
pnpm run plugins install ep_prefer_color_scheme
```

> ⚠️ Don't run `npm i` / `npm install` yourself from the Etherpad
> source tree — Etherpad tracks installed plugins through its own
> plugin-manager, and hand-editing `package.json` can leave the
> server unable to start.

After installing, restart Etherpad.
