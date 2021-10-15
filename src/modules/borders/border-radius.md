# Border radius

## Class reference

| Class                   | Properties                                                                     |
| ----------------------- | ------------------------------------------------------------------------------ |
| .rounded-**name**       | border-radius: **value**;                                                      |
| .rounded-t-**name**     | border-top-left-radius: **value**; border-top-right-radius: **value**;         |
| .rounded-b-**name**     | border-bottom-left-radius: **value**; border-bottom-right-radius: **value**;   |
| .rounded-l-**name**     | border-bottom-left-radius: **value**; border-top-left-radius: **value**;       |
| .rounded-r-**name**     | border-bottom-right-radius: **value**; border-top-right-radius: **value**;     |
| .rounded-tr-**name**    | border-top-right-radius: **value**;                                            |
| .rounded-br-**name**    | border-bottom-right-radius: **value**;                                         |
| .rounded-bl-**name**    | border-bottom-left-radius: **value**;                                          |
| .rounded-tl-**name**    | border-top-left-radius: **value**;                                             |

## Install separately

```scss
@import '~scssfold/src/modules/borders/border-radius';
```

## Customizing

Override the following variable before including the module. Each key is used for the class name, and the value is used for the css property.

```scss
$scssfold-border-radiuses: (
  'none': 0,
  'sm': 4px,
  'md': 6px,
  'lg': 8px,
  'xl': 10px,
  '2xl': 20px,
  'full': 9999px,
);
```
