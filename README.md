# Graia 社区文档

## 许可协议

- 文档正文内容使用 [署名-非商业性使用-相同方式共享 4.0 国际 (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.zh) 协议进行许可

  > 正文内容指的是 `docs` 目录下的所有 Markdown 文件（`/docs/**/*.md`）

  1. 转载或修改后转载请注明本仓库地址
  2. 转载时请注明是否对原文进行了修改
  3. 你不能将本文档用于商业用途
  4. 你的转载也必须使用 CC BY-NC-SA 4.0 协议进行许可

- 本仓库的组件其余文件（如：`*.ts`、`*.js`、`*.vue`）使用 MIT 协议进行许可
- 仓库中的字体文件（`*.ttf`)及媒体文件（`*.webp`、`*.m4a`、`*.svg`、`*.png`）为非开源内容（No License）

## 开发&构建

> 本项目使用 **pnpm** 作为包管理器  
> 如果你没有安装 **pnpm**，那你可以使用 `corepack enable` 命令来安装 **pnpm** 和 **yarn**  
> 后续如果需要升级 **pnpm** 则可以使用命令 `corepack prepare pnpm@x.x.x --activate` 来完成

1. clone 本仓库
2. 使用命令 `pnpm install` 安装依赖
3. 开发环境使用命令 `pnpm serve` 启动服务器
4. 使用命令 `pnpm build` 生成最终页面

### 注意事项

1. 请勿手动安装 `vite` 依赖，否则工作不正常（`vue` 选装）
