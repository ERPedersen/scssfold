# Scssfold

[![npm][npm]][npm-url]
[![node][node]][node-url]
[![downloads][downloads]][downloads-url]
[![contributors][contributors]][contributors-url]
[![install-size][install-size]][install-size-url]
[![PR's welcome][prs]][prs-url]

# What is Scssfold?

> This repository is a work in progress

Scssfold is a small utility-first CSS framework. Its purpose is to deliver reusable media-width aware
utility classes, which speeds up the scaffolding process when developing user interfaces.

# Requirements

- NPM
- Ability to compile SCSS

> Due to the nature of how this framework works, it will increase the size of your final build dramatically.
> To circumvent this caveat, it is recommended that you purge any unused classes using [purgecss](/).

# Installation

## Install the package

Start by installing the package using either NPM or Yarn as specified below.

```bash
$ yarn add scssfold
$ npm install scssfold --save
```

## Include the package

Include the package by importing it in either a JavaScript or SCSS file. We recommend that you 
import the package in an SCSS file, since that enables you to customize the framework to your needs.

### Basic (all modules)

Importing the base module will give you all the modules specified in the [Modules section](#Modules):

```scss
@import '~scssfold';
```
### Select modules

In case you wish to import only a select number of the modules specified in the
[Modules section](#Modules), you can target them directly as specified below.

```scss
@import '~scssfold/src/modules/spacing/margins';
@import '~scssfold/src/modules/spacing/paddings';
```

# Responsiveness

All classes listed in the [Modules section](#Modules) below can be prefixed with breakpoints, making them active only once the width of the browser matches the given breakpoint.

If for example, we wanted to use the `flex` class, but we'd only want it to be applied on screens that are equal to or greater than the `md` breakpoint, we can use it as such:

Take for example the below HTML. We apply the `flex` class, determining that the items should flex on the horizontal axis:

```html
<div class="flex">
  <p>Item 1</p>
  <p>Item 2</p>
  <p>Item 3</p>
</div>
```

But what if we wanted the `display: flex` styling only to apply to screens that are equal to or greater than the `md` breakpoint? We could write it as such:

```html
<div class="md:flex">
  <p>Item 1</p>
  <p>Item 2</p>
  <p>Item 3</p>
</div>
```

This applies to all classes delivered by Scssfold. Very convenient and yes - heavily inspired by [Tailwind CSS](https://tailwindcss.com/).

# Modules

## Flex

- [Align Content](src/modules/flex/align-content.md)
- [Align Items](src/modules/flex/align-items.md)
- [Align Self](src/modules/flex/align-self.md)
- [Columns](src/modules/flex/columns.md)
- [Direction](src/modules/flex/direction.md)
- [Grow](src/modules/flex/grow.md)
- [Justify Content](src/modules/flex/justify-content.md)
- [Justify Items](src/modules/flex/justify-items.md)
- [Justify Self](src/modules/flex/justify-self.md)
- [Order](src/modules/flex/order.md)
- [Percentage Width](src/modules/flex/percentage.md)
- [Shrink](src/modules/flex/shrink.md)
- [Sizing](src/modules/flex/sizing.md)
- [Wrap](src/modules/flex/wrap.md)


## Layout
- [Container](src/modules/layout/container.md)
- [Container Fluid](src/modules/layout/container-fluid.md)
- [Row](src/modules/layout/row.md)

## Position

- [Position](src/modules/position/position.md)

## Reset

- [Reset](src/modules/reset/reset.md)

## Spacing

- [Margin](src/modules/spacing/margins.md)
- [Padding](src/modules/spacing/margins.md)

## Visibility

- [Display](src/modules/visibility/display.md)

## Borders

- [Border Radius](src/modules/borders/border-radius.md)

# Why Scssfold?

I initially wrote this framework for myself, but chose to make it public for others to use. I've always been a fan of the BEM methodology. However, over the years, it became more and more clear to me that BEM is not an all-or-nothing approach. Sticking to the BEM methodology strictly resulted in a lot of repetitive CSS, which had both performance and development drawbacks. This framework aims to solve the issue of writing the rough layout of an application; spacings, columns, containers etc. - responsively.

I still use BEM for component styling but try to make components as context-unaware as possible, meaning they have no impact on the layout outside of the component. This makes them more reusable and contributes to a cleaner and more maintainable codebase.

[contributors]: https://img.shields.io/github/contributors/erpedersen/scssfold.svg
[contributors-url]: https://github.com/erpedersen/scssfold/graphs/contributors
[downloads]: https://img.shields.io/npm/dm/scssfold.svg
[downloads-url]: https://img.shields.io/npm/dm/scssfold.svg
[install-size]: https://packagephobia.com/badge?p=webpack
[install-size-url]: https://packagephobia.com/result?p=webpack
[npm]: https://img.shields.io/npm/v/scssfold.svg
[npm-url]: https://npmjs.com/package/scssfold
[node]: https://img.shields.io/node/v/scssfold.svg
[node-url]: https://nodejs.org
[tests]: https://img.shields.io/travis/erpedersen/scssfold/master.svg
[tests-url]: https://travis-ci.org/erpedersen/scssfold
[prs]: https://img.shields.io/badge/PRs-welcome-brightgreen.svg
[prs-url]: https://github.com/ERPedersen/scssfold/pulls
[builds-url]: https://ci.appveyor.com/project/sokra/webpack/branch/master
[builds]: https://ci.appveyor.com/api/projects/status/github/webpack/webpack?svg=true
[builds2]: https://dev.azure.com/webpack/webpack/_apis/build/status/webpack.webpack
[builds2-url]: https://dev.azure.com/webpack/webpack/_build/latest?definitionId=3
[licenses-url]: https://app.fossa.io/projects/git%2Bhttps%3A%2F%2Fgithub.com%2Fwebpack%2Fwebpack?ref=badge_shield
[licenses]: https://app.fossa.io/api/projects/git%2Bhttps%3A%2F%2Fgithub.com%2Fwebpack%2Fwebpack.svg?type=shield
[cover]: https://img.shields.io/coveralls/webpack/webpack.svg
[cover-url]: https://coveralls.io/r/webpack/webpack/
