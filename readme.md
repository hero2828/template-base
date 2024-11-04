### [eslint-plugin-command](https://eslint-plugin-command.antfu.me/) 配置

- keep-sorted

保持对象键或数组项排序

```ts
/// keep-sorted { "keys": ["index", "name"] }
const arr = [
  { index: 0, name: 'zip' },
  { index: 2, name: 'apple' },
  { index: 2, name: 'bar' },
  { index: 4, name: 'foo' },
]
```

将转换为：

```ts
/// keep-sorted { "keys": ["index", "name"] }
const arr = [
  { index: 0, name: 'zip' },
  { index: 2, name: 'apple' },
  { index: 2, name: 'bar' },
  { index: 4, name: 'foo' },
]
```
