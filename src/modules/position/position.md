# Container Fluid

| Class              | Result                                          |
| ------------------ | ----------------------------------------------- |
| .position-static   | position: static;                               |
| .position-absolute | position: absolute;                             |
| .position-fixed    | position: fixed;                                |
| .position-sticky   | position: sticky;                               |

## Install separately

```scss
@import '~scssfold/src/modules/position/position.scss';
```

## Overrides

Override the following variables before including the module.

```scss
$scssfold-positions: (
  static,
  absolute,
  fixed,
  sticky
);
```
