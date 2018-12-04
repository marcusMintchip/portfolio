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

sass使用编程延迟实现动画

```scss
@for $x from 1 through 4 {
  .nav-item:nth-child(#{$x}) {
    transition-delay: $x * 0.1s;
  }
}
```

