<!-- Banner Image -->

<p align="center">
  <a href=".">
    <img alt="bookhub" height="128" src="./.github/resources/banner.png">
    <h1 align="center">Bookhub</h1>
  </a>
</p>

<p align="center">
  <a aria-label="Numble" href="https://www.numble.it/" target="_blank">
    <img alt="Sponsor" src="https://img.shields.io/badge/Sponsor-Numble-blue?style=flat-square&logo=githubsponsors&logoWidth=15&labelColor=000000&color=4630EB" />
  </a>
   <a aria-label="Expo" href="https://expo.dev/client" target="_blank">
    <img alt="Expo" src="https://img.shields.io/badge/Runs%20with%20Expo%20Go-4630EB.svg?style=flat-square&logo=EXPO&labelColor=f3f3f3&logoColor=000" />
  </a>
  <a aria-label="Expo is free to use" href="https://github.com/expo/expo/blob/main/LICENSE" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-success.svg?style=flat-square&color=33CC12" target="_blank" />
  </a>
</p>


<p align="center">
  <a aria-label="try expo with snack" href="https://snack.expo.dev"><b>Try Expo in the Browser</b></a>
 |
  <a aria-label="expo documentation" href=".">Read the Documentation 📚</a>
</p>
  
---

<p align="center">
<strong>Bookhub</strong> is a next-generation web novel platform:stuck_out_tongue_winking_eye:, developed as a side project by <a aria-label="Numbe deepdive" href="https://www.numble.it/deepdive/41" target="_blank">Numble</a>.
</p>

<p align="center">
   <img alt="Home" width="18%" src="./.github/resources/screenshot_01_home.png" />
   <img alt="Main" width="18%" src="./.github/resources/screenshot_02_main.png" />
   <img alt="Payment Detail" width="18%" src="./.github/resources/screenshot_03_payment_detail.png" />
   <img alt="Payment" width="18%" src="./.github/resources/screenshot_04_payment.png" />
   <img alt="Recommended List" width="18%" src="./.github/resources/screenshot_05_recommended_list.png" />
</p>

## 📚 Documentation

<p>Learn about building and deploying our apps <a aria-label="documentation" href=".">in our official docs!</a></p>

- [Project Introduction](https://www.numble.it/deepdive/41)
- [Getting Started]()
- [Requirement Specification]()
- [Architecture Design]()
- [Wireframe & Storyboard]()
- [API Reference]()
- [Data Modeling & ERD]()

# Project Layout

This project is based on [Turborepo](https://turbo.build/repo/docs), which is an intelligent build system optimized for JavaScript and TypeScript codebases.

## What's inside?

This Turborepo includes the following packages/apps:

### Apps and Packages

- `native`: a [react-native](https://reactnative.dev/) app built with [expo](https://docs.expo.dev/)
- `web`: a [Next.js](https://nextjs.org/) app built with [react-native-web](https://necolas.github.io/react-native-web/)
- `ui`: a stub [react-native](https://reactnative.dev/) component library shared by both `web` and `native` applications
- `tsconfig`: `tsconfig.json`s used throughout the monorepo

Each package/app is 100% [TypeScript](https://www.typescriptlang.org/).

### Utilities

- [Expo](https://docs.expo.dev/) for native development
- [TypeScript](https://www.typescriptlang.org/) for static type checking
- [Prettier](https://prettier.io) for code formatting

## Getting Started

Run the following command:

```sh
cd bookhub
yarn dev
```
