# Justify self

## Class reference

| Class                  | Properties                |
| ---------------------- | :------------------------ |
| .justify-self-auto     | justify-self: auto;       |
| .justify-self-start    | justify-self: flex-start; |
| .justify-self-end      | justify-self: flex-end;   |
| .justify-self-center   | justify-self: center;     |
| .justify-self-stretch  | justify-self: stretch;    |

## Install separately

```scss
@import '~scssfold/src/modules/flex/justify-self';
```

## Overrides

Override the following variable before including the module. Each key is used for the class name, and the value is used for the css property.

```scss
$scssfold-justify-self: (
  'auto': auto,
  'start': flex-start,
  'end': flex-end,
  'center': center,
  'stretch': stretch,
)
```
