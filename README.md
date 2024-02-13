# action-yarn-setup-berry

哈喽哇！这是一个可以快速设置 Yarn berry 环境的 Action。  

Hi! Here is an action to help you setup Yarn (version berry) environment quickly!

## 基本用法 / Basic usage
```yaml
- uses: crrashh1542/action-setup-yarn-berry@main
```

## 添加输入 / Inputs to add
以下输入继承自 [`actions/checkout`](https://github.com/actions/checkout) 与 [`actions/setup-node`](https://github.com/actions/setup-node)，你可以像在以上 action 中一样地使用输入。

Parameters shown below was extended from [`actions/checkout`](https://github.com/actions/checkout) and [`actions/setup-node`](https://github.com/actions/setup-node), which enables you to input like what you does with such actions.
```yaml
- uses: crrashh1542/action-setup-yarn-berry@main
  with:
    fetch-depth: '1'
    node-version: '20'
```
