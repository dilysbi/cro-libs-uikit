# 🥞 Soupswap UIkit

**This repository is not used anymore. See the [https://github.com/binance/binance-toolkit](binance toolkit) instead**

[![Version](https://img.shields.io/npm/v/binance-libs-uikit)](https://www.npmjs.com/package/binance-libs-uikit) [![Size](https://img.shields.io/bundlephobia/min/binance-libs-uikit)](https://www.npmjs.com/package/binance-libs-uikit)

Soupswap UIkit is a set of React components and hooks used to build pages on binance apps. It also contains a theme file for dark and light mode.

## Install

`yarn add binance-libs-uikit`

## Setup

### Theme

Before using Soupswap UIkit, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
import { light, dark } from 'binance-libs-uikit'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Reset

A reset CSS is available as a global styled component.

```
import { ResetCSS } from 'binance-libs-uikit'
...
<ResetCSS />
```

### Types

This project is built with Typescript and export all the relevant types.
