# eslint-config-tdued

同盾科技私有云部-eslint规范

## Usage

### eslint-config-tdued

我们的默认导出包含所有ESLint规则,包括ECMAScript 6。

首先,安装这个包和必要的插件
```sh
npm install --save-dev eslint-config-tdued eslint babel-eslint eslint-plugin-react eslint-plugin-import eslint-plugin-jsx-a11y
```
然后将下面的内容添加到您的.eslintrc文件
```
{
  "extends": "tdued"
}
```

## License
MIT
