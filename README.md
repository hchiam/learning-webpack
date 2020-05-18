# Learning Webpack

Just one of the things I'm learning. <https://github.com/hchiam/learning>

```bash
npm install webpack webpack-cli --save-dev
```

and then

```bash
webpack # or: npx webpack
```

creates a `dist` folder with bundled files.

## Notes

- <https://webpack.js.org>
- <https://webpack.js.org/guides/getting-started/>
- [Colt Steele's](https://github.com/Colt) Webpack course repo: <https://github.com/hchiam/webpack-demo-app>
- ([This repo](https://github.com/hchiam/learning-webpack) was partially created using [`yo hchiam-learning`](https://github.com/hchiam/generator-hchiam-learning))
- Remember that loaders run from the bottom up!
- And finally, here's a practical example walk-through of using Webpack: <https://github.com/material-components/material-components-web/blob/master/docs/getting-started.md> for using [Material Design Components for the web](https://github.com/hchiam/learning-material-design-components).
- Tree shaking seems to be on by default, but you can turn it on with `mode: "production",` (note that there's even more you can do to optimize or mark files).
- Live reload with [`webpack-dev-server`](https://github.com/webpack/webpack-dev-server)
