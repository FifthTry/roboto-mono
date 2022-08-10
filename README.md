# Roboto Mono Font

[`fifthtry.github.io/roboto-mono`](https://fifthtry.github.io/roboto-mono) is a wrapper over [Roboto Mono font](https://github.com/googlefonts/RobotoMono).

# How To Use This Font

include fifthtry.github.io/roboto-mono package into FPM.ftd file

```ftd
-- fpm.dependency: fifthtry.github.io/roboto-mono

-- fpm.auto-import: fifthtry.github.io/roboto-mono as roboto-mono
```

Inside your .ftd file to change for any specific token use:

```
-- fpm.type.headline-small.font: $roboto-mono.fonts.roboto-mono

-- ftd.text:
role: $fpm.type.headline-small
```

[How to Use fonts](https://fpm.dev/how-to/how-to-use-fonts/).

# License

[Roboto Mono is distributed under  Apache License Version 2.0, January 2004](http://www.apache.org/licenses/). We use the same license to be compatible with them.
