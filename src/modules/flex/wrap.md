# Flex wrap

| Class              | Properties                   |
| ------------------ | ---------------------------- |
| .flex-wrap         | flex-wrap: wrap;             |
| .flex-wrap-reverse | flex-wrap: wrap-reverse;     |
| .flex-no-wrap      | flex-wrap: nowrap;           |

## Install separately

```scss
@import '~scssfold/src/modules/flex/wrap';
```

## Overrides

Override the following variable before including the module. Each key is used for the class name, and the value is used for the css property.

```scss
$scssfold-flex-wrap: (
  'wrap': wrap,
  'wrap-reverse': wrap-reverse,
  'no-wrap': nowrap,
);
```
