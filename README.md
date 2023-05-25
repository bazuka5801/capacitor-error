# Vue 3 + Vite

This template should help get you started developing with Vue 3 in Vite. The template uses Vue 3 `<script setup>` SFCs, check out the [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup) to learn more.

## Recommended IDE Setup

- [VS Code](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).


# How to reproduce
1. `yarn && yarn dev`
2. Copy `ip` from previous command output and replace in `capacito.config.json` (`server.url`)
3. `yarn cap sync && yarn cap open ios`
4. Run on emulator and open safari devtools
5. Just refresh page `CMD+R`
6. No vue logs :(