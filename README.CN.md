<p align="center">
  <a href="https://use-kfc.deno.dev" target="_blank" rel="noopener noreferrer">
    <img width="180" src="https://api.iconify.design/noto-v1:french-fries.svg" alt="kfc logo" />
  </a>
  <br />
  <h3 align="center">
  <span>
    <a href="./README.md">英文</a> | 
    <a>中文</a>
  </span>
  <h3>
</p>
<br />
<p align="center">
  <a href="https://www.npmjs.com/package/@crazy-thursday/use-kfc"><img src="https://img.shields.io/npm/v/@crazy-thursday/use-kfc" alt="npm package"></a>
  <a href="https://nodejs.org/en/about/releases/"><img src="https://img.shields.io/node/v/@crazy-thursday/use-kfc" alt="node compatibility"></a>
  <a href="https://github.com/crazy-thursday/useKFC/actions/workflows/deploy-deno.yml"><img src="https://github.com/crazy-thursday/useKFC/actions/workflows/deploy-deno.yml/badge.svg?branch=main" alt="build status"></a>
  <a href="https://discord.gg/b2SCucyKyn"><img src="https://img.shields.io/badge/chat-discord-blue?style=flat&logo=discord" alt="discord chat"></a>
</p>
<br />
<div align="center">
  <h1>useKFC</h1>
  <p>生成疯狂星期四的文字!!!<p>
</div>

## Usage

- hooks 🌩

```jsx
import useKFC from '@crazy-thursday/use-kfc'
```

- api 💻

```bash
$ curl 'https://use-kfc-serve.deno.dev/kfc'
```

- data struct 📚

```ts
export enum CODE {
  /**
   * @description success code
   */
  SUCCESS = 10086,
  /**
   * @description failed code
   */
  FAILED = 10087,
  /**
   * @description deny code
   */
  DENY = 10089
}

type DataStruct = {
  code: CODE
  ip: string
  method: 'GET'
  data: {
    content: string
    id: string
    createUser: string
  }
}
```

## Slogen

仓库内置了部分 slogen. 此外你也可以使用 issue 来进行 slogen 贡献. 但请确保 issue 包含完整且不带有争议的文字或表情. 在完成内容编辑之后增加 slogen 的标签. Github CI 会自动收集你贡献的内容到仓库内.

## Contribution

查看 [贡献指南](CONTRIBUTING.md).

## License

[MIT](LICENSE).

## Sponsoring

<table>
  <tr align="center">
    <td>
      <a href="https://www.buymeacoffee.com/innocces" target="_blank">
        <img width="120" src="https://api.iconify.design/simple-icons:buymeacoffee.svg">
      </a>
    </td>
    <td>
      <a href="https://afdian.net/a/innocces" target="_blank">
        <img width="150" src="https://cdn.jsdelivr.net/gh/innocces/DrawingBed/2022-12-04/1670124736895-afdian.png">
      </a>
    </td>
  </tr>
</table>
