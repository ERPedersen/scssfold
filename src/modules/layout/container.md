# Container

| Class         | Result                                          |
| ------------- | ----------------------------------------------- |
| .container    | A fixed width responsive container element.     |

## Install separately

```scss
@import '~scssfold/src/modules/layout/container';
```

## Customizing

Override the following variables before including the module. `$scssfold-container-sizes` control
the `max-width` of a container at a given breakdpoint.

```scss
$scssfold-grid-gutter: 20px;
$scssfold-screen-xl: 1440px;
$scssfold-screen-lg: 1280px;
$scssfold-screen-md: 991px;
$scssfold-screen-sm: 768px;

$breakpoints: (
  'sm': $scssfold-screen-sm,
  'md': $scssfold-screen-md,
  'lg': $scssfold-screen-lg,
  'xl': $scssfold-screen-xl,
);

$scssfold-container-sizes: (
  'sm': ($scssfold-screen-sm, $scssfold-screen-sm - ($scssfold-grid-gutter * 2)),
  'md': ($scssfold-screen-md, $scssfold-screen-md - ($scssfold-grid-gutter * 2)),
  'lg': ($scssfold-screen-lg, $scssfold-screen-lg - ($scssfold-grid-gutter * 2)),
  'xl': ($scssfold-screen-xl, 1320px),
);
```
