# Justify items

## Class reference

| Class                   | Properties                 |
| ----------------------- | :------------------------- |
| .justify-items-auto     | justify-items: auto;       |
| .justify-items-start    | justify-items: flex-start; |
| .justify-items-end      | justify-items: flex-end;   |
| .justify-items-center   | justify-items: center;     |
| .justify-items-stretch  | justify-items: stretch;    |

## Install separately

```scss
@import '~scssfold/src/modules/flex/justify-items';
```

## Overrides

Override the following variable before including the module. Each key is used for the class name, and the value is used for the css property.

```scss
$scssfold-justify-items: (
  'auto': auto,
  'start': flex-start,
  'end': flex-end,
  'center': center,
  'stretch': stretch,
);
```
