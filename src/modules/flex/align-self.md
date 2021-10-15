# Align self

| Class         | Properties              |
| ------------- | ----------------------- |
| .self-auto    | align-self: auto;       |
| .self-start   | align-self: flex-start; |
| .self-end     | align-self: flex-end;   |
| .self-center  | align-self: center;     |
| .self-stretch | align-self: stretch;    |

## Install separately

```scss
@import '~scssfold/src/modules/flex/align-self';
```

## Customizing

Override the following variable before including the module. Each key is used for the class name, and the value is used for the css property.

```scss
$scssfold-align-self: (
  'auto': auto,
  'start': flex-start,
  'end': flex-end,
  'center': center,
  'stretch': stretch,
);
```
