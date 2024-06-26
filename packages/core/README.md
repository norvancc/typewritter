<p align="center">
<a href="https://github.com/norvancc/typewritter#gh-light-mode-only">
  <img src="https://github.com/norvancc/typewritter/raw/main/public/logo_light.png#gh-light-mode-only" alt="Typewritter - A typewritter effect for vue3 and typescript" width="300">
</a>
<a href="https://github.com/norvancc/typewritter#gh-dark-mode-only">
  <img src="https://raw.githubusercontent.com/norvancc/typewritter/main/public/logo_dark.png#gh-dark-mode-only" alt="Typewritter - A typewritter effect for vue3 and typescript" width="300">
</a>
<br>
 A typewritter effect for vue3 and typescript
</p>
<p align="center"> 
<a href="https://www.npmjs.com/package/vue-typewritter">
  <img src="https://img.shields.io/badge/npm-v0.0.5-blue" alt="Typewritter - A typewritter effect for vue3 and typescript" alt="NPM version">
</a>
<a href="https://github.com/norvancc/vue-typewritter?tab=MIT-1-ov-file">
  <img src="https://img.shields.io/badge/license-MIT-yellow" alt="Typewritter - A typewritter effect for vue3 and typescript" alt="LICENSE">
</a>
<a href="http://typewritter.norvan.cc">
  <img src="https://img.shields.io/badge/docs & demo-green" alt="Typewritter - A typewritter effect for vue3 and typescript" alt="Docs & Demo">
</a>
</p>

## 🚀 Features

- 📝 Pure string input support
- <img src="https://raw.githubusercontent.com/norvancc/typewritter/main/public/vue.svg" width="14"> Vue component support
- <img src="https://raw.githubusercontent.com/norvancc/typewritter/main/public/tsx.svg" width="14"> TSX/JSX grammer support
- 🔫 Customizable styles for each step
- 🚀 Each step supports custom speed
- 🚅 Chain call support

## 🦄 Usage

```ts
<template>
  <div id="typewritter"></div>
</template>
<script setup lang="tsx">
import { Typewriter } from 'vue-typewritter';

const typewriter = new Typewriter('#typewritter');
onMounted(() => {
  nextTick(() => {
    typewriter.setText('Hello World!');
  });
});
</script>
```

## 📦 Install

> 🎩 From v1.0, it works for Vue 2 & 3

```bash
npm i vue-typewriter
```

## 📄 License

[MIT License](https://github.com/norvancc/typewritter/blob/main/LICENSE) © 2024-PRESENT [Norvan CC](https://norvan.cc)
