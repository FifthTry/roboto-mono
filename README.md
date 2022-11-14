# Roboto Mono: FPM Font Package

This repository contains a [fpm font package](https://fpm.dev/featured/fonts/) containing [Google Font: 
Roboto Mono](https://fonts.google.com/specimen/Roboto+Mono/about?query=roboto).

Roboto Mono is a monospaced addition to the Roboto type family. Like the other 
members of the Roboto family, the fonts are optimized for readability on screens
across a wide variety of devices and reading environments. 

Designers: Christian Robertson, Principal design

## How To Use This Font In Your FPM Package:

[Read the docs and demo](https://fifthtry.github.io/roboto-mono).

TLRD:

Include fifthtry.github.io/roboto package into `FPM.ftd` file:

```ftd
;-- fpm.dependency: fifthtry.github.io/roboto-mono
```

Inside your `FPM/config.ftd` use the font:

```ftd
;-- import: fifthtry.github.io/roboto-mono

;-- fpm.type.headline-small: $roboto-mono.fonts.Roboto
```

Now if in any file you do:

```ftd
;-- ftd.text:
role: $fpm.type.headline-small
```

You will see the `roboto-mono` font.

## 👀 Want to learn more?

Feel free to check [our documentation](https://fpm.dev/) or jump into our [FifthTry Discord 
server](https://discord.gg/bucrdvptYd).

## License

Since Roboto Mono Font is under [Apache License](https://fonts.google.com/specimen/Roboto+Mono/about?query=roboto), this FPM wrapper is also
under [Apache License](LICENSE).




