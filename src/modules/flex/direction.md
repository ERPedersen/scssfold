# Flex direction

| Class             | Properties                   |
| ----------------- | ---------------------------- |
| .flex-row         | flex-direction: row;         |
| .flex-row-reverse | flex-direction: row-reverse; |
| .flex-col         | flex-direction: col;         |
| .flex-col-reverse | flex-direction: col-reverse; |

## Install separately

```scss
@import '~scssfold/src/modules/flex/direction';
```

## Customizing

Override the following variable before including the module. Each key is used for the class name, and the value is used for the css property.

```scss
$scssfold-flex-direction: (
  'row': row,
  'row-reverse': row-reverse,
  'col': column,
  'col-reverse': column-reverse,
);
```
