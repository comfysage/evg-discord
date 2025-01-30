<h3 align="center">
  Evergarden for <a href="https://discord.com/">Discord</a>
</h3>

## Usage

### [BetterDiscord](https://betterdiscord.app)

1. Download the theme [here](./themes/evergarden.theme.css?raw=1).
2. Copy the downloaded file to your BetterDiscord themes folder.
3. Enable the theme in BetterDiscord settings.

### [Vencord](https://github.com/Vendicated/Vencord)

1. Download the theme [here](./themes/evergarden.theme.css?raw=1).
2. Copy the downloaded file to your Vencord themes folder (on linux `~/.config/Vencord/themes`).
3. Enable the theme in Vencord settings.

### Clients/Mods with custom CSS support

1. Simply add your theme into your discord clients CustomCSS file/editor.

```css
@import url("https://raw.githubusercontent.com/comfysage/evg-discord/main/themes/evergarden.theme.css");

/* You can also append color names to customize the accent, e.g. */
/* green accent */
@import url("https://raw.githubusercontent.com/comfysage/evg-discord/main/themes/evergarden-green.theme.css");
/* pink accent*/
@import url("https://raw.githubusercontent.com/comfysage/evg-discord/main/themes/evergarden-pink.theme.css");
```

### [Stylus](https://github.com/openstyles/stylus)

1. Enable CSP Patching from Stylus Settings > Advanced.
2. [Click here to install](https://github.com/comfysage/evg-discord/raw/main/discord.user.css).
3. Choose your preferred accent color from the Stylus preference dropdown.

## 🙋 FAQ

- Q: **_"Can this get my account banned?"_**
- A: Using third party clients and injecting custom css is against the ToS. While nobody has ever been banned for simply using discord client mods, We are not responsible for anything that might happen to your account by using third party clients. Use at your own discretion!

- Q: **_"Can I automatically switch flavors between light and dark mode?"_**
- A: The following snippet showcases a configuration that switches between latte in light mode and mocha in dark mode by adding an inline [`prefers-color-scheme` media feature](https://developer.mozilla.org/en-US/docs/Web/CSS/@media/prefers-color-scheme), `(prefers-color-scheme: <light-or-dark>)`, after each `@import` statement (see ["Importing CSS rules conditional on media queries" - MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/@import#importing_css_rules_conditional_on_media_queries)).

  ```css
  @import url("https://catppuccin.github.io/discord/dist/catppuccin-mocha.theme.css")
  (prefers-color-scheme: dark);
  @import url("https://catppuccin.github.io/discord/dist/catppuccin-latte.theme.css")
  (prefers-color-scheme: light);
  ```

## 💝 Thanks to

- [GlowingUmbreon](https://github.com/glowingumbreon)
- [Isabelinc](https://github.com/Isabelincorp)
- [Ren](https://github.com/watatomo)
- [winston](https://github.com/nekowinston)
- [rubyowo](https://github.com/rubyowo)
- [Aven](https://github.com/ToxicAven)
- [comfysage](https://github.com/comfysage)

&nbsp;

<p align="center">Copyright &copy; 2021-present <a href="https://github.com/catppuccin" target="_blank">Catppuccin Org</a>
<p align="center">Copyright &copy; 2024-present <a href="https://github.com/comfysage" target="_blank">comfysage</a>
<p align="center"><a href="https://github.com/comfysage/evg-discord/blob/main/LICENSE"></p>
