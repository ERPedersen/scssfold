# Justify content

## Class reference

| Class            | Properties                      |
| ---------------- | ------------------------------- |
| .justify-start   | justify-content: flex-start;    |
| .justify-end     | justify-content: flex-end;      |
| .justify-center  | justify-content: center;        |
| .justify-between | justify-content: space-between; |
| .justify-around  | justify-content: space-around;  |
| .justify-evenly  | justify-content: space-evenly;  |

## Install separately

```scss
@import '~scssfold/src/modules/flex/justify-content';
```

## Overrides

Override the following variable before including the module. Each key is used for the class name, and the value is used for the css property.

```scss
$scssfold-justify-content: (
  'start': flex-start,
  'end': flex-end,
  'center': center,
  'between': space-between,
  'around': space-around,
  'evenly': space-evenly
) !default;
```
