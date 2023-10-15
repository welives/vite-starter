# ts-vant-starter

这是一个 `Vant` + `TailwindCSS` + `TypeScript` + `ESLint` + `Prettier` 的起手式

`main`分支是以 Vite 为基础搭建的，`with-nuxt3`分支是以 Nuxt3 为基础搭建的

## 使用

```sh
pnpm install
```

### 开发模式

生成环境变量文件，并填入项目所需信息

```sh
mv example.env .env.local
```

启动开发模式

```sh
pnpm dev
```

### 打包

生成环境变量文件，并填入项目所需信息

```sh
mv example.env .env.production
```

执行打包

```sh
pnpm build
```

### 代码规范检查

```sh
pnpm lint
```

## 相关文档

- [Vant](https://vant-ui.github.io/vant/#/zh-CN)
- [TypeScript](https://www.tslang.cn/)
- [Vite](https://cn.vitejs.dev/)
- [Nuxt3](https://nuxt.com.cn/)
- [TailwindCSS](https://tailwind.nodejs.cn/)
- [ESLint](https://eslint.nodejs.cn/)
- [Prettier](https://prettier.nodejs.cn/)