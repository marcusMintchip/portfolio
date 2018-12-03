# portfolio

node-sass动态编译sass文件为css文件

```bash
node-sass -w scss/ -o dist/css/ --recursive
```

- `-w` watch
- `-o` output
- `--recursive` resolve partial auto-reload problem

使用npm运行，sass文件变化就会自动生成css文件

```bash
npm run sass
```

使用live-server启动浏览页面