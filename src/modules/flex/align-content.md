# Align content

## Class reference

| Class            | Properties                    |
| ---------------- | ----------------------------- |
| .content-start   | align-content: flex-start;    |
| .content-end     | align-content: flex-end;      |
| .content-center  | align-content: center;        |
| .content-between | align-content: space-between; |
| .content-around  | align-content: space-around;  |
| .content-evenly  | Align-content: space-evenly;  |

## Install separately

```scss
@import '~scssfold/src/modules/flex/align-content';
```

## Overrides

Override the following variable before including the module. Each key is used for the class name, and the value is used for the css property.

```scss
$scssfold-align-content: (
  'start': flex-start,
  'end': flex-end,
  'center': center,
  'between': space-between,
  'around': space-around,
  'evenly': space-evenly,
);
```
