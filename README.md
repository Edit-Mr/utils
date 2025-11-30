# utils

一些常用的複製貼上好工具。

文件裡面有：

- 常用 gitignore
- 常用 Actions
- 我的 .prettierrc

## 環境

### 安裝 Node.js

請參考 [Node.js 官方網站](https://nodejs.org/zh-tw/download/) 下載並安裝適合您作業系統的版本。建議使用 nvm 安裝。

### 安裝 pnpm

```sh
npm install --global corepack@latest
corepack enable pnpm
```

> 更新 pnpm 時，請執行：  
> `corepack prepare pnpm@latest --activate`

## 建立專案

### 鎖定專案 pnpm 版本

```sh
corepack use pnpm@latest
```

### [Astro](https://docs.astro.build/zh-tw/install-and-setup/)

```sh
pnpm create astro@latest
pnpm add -D prettier prettier-plugin-astro
```

### React

```sh
pnpm create vite@latest ./ --template react-ts
```

### 其他套件

```sh
pnpm add lenis
```
