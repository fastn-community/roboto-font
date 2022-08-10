# Roboto Font

`fifthtry.github.io/roboto` is a wrapper over [Inter font](https://github.com/googlefonts/roboto/).

# How To Use This Font

include fifthtry.github.io/roboto package into FPM.ftd file

```ftd
-- fpm.dependency: fifthtry.github.io/roboto

-- fpm.auto-import: fifthtry.github.io/roboto as roboto
```

Inside your .ftd file to change for any specific token use:

```
-- fpm.type.headline-small.font: $roboto.fonts.roboto

-- ftd.text:
role: $fpm.type.headline-small
```

[Details](the link to our new how to).

# License

[Roboto is distributed under  Apache License Version 2.0, January 2004](http://www.apache.org/licenses/)(https://github.com/googlefonts/roboto/blob/main/LICENSE). We use the same license to be compatible with them.
