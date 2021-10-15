# Align items

## Class reference

| Class           | Properties               |
| --------------- | :----------------------- |
| .items-start    | align-items: flex-start; |
| .items-end      | align-items: flex-end;   |
| .items-center   | align-items: center;     |
| .items-baseline | align-items: baseline;   |
| .items-stretch  | align-items: stretch;    |

## Install separately

```scss
@import '~scssfold/src/modules/flex/align-items';
```

## Customizing

Override the following variable before including the module. Each key is used for the class name, and the value is used for the css property.

```scss
$scssfold-align-items: (
  'start': flex-start,
  'end': flex-end,
  'center': center,
  'baseline': baseline,
  'stretch': stretch
);
```
