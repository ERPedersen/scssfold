# Flex sizing

| Class           | Properties      |
| --------------- | --------------- |
| .flex-1         | flex: 1 1 0%;   |
| .flex-auto      | flex: 1 1 auto; |
| .flex-initial   | flex: 0 1 auto; |
| .flex-none      | flex: none;     |

## Install separately

```scss
@import '~scssfold/src/modules/flex/sizing';
```

## Customizing

Override the following variable before including the module. Each key is used for the class name, and the value is used for the css property.

```scss
$scssfold-flex-sizes: (
  '1': 1 1 0%,
  'auto': 1 1 auto,
  'initial': 0 1 auto,
  'none': none,
);
```
