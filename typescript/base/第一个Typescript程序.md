1. `mkdir ts-demo`

2. `npm i -g typescript`

3. `tsc -init` 创建tsconfig.json文件

4. 创建`src/index.ts`文件，并输入以下内容:
```typescript
let hello : string = 'Hello Typescript';
```

5. 执行`tsc src/index.ts`, 得到index.js文件, 内容如下:
```js
var hello = 'Hello Typescript';
```