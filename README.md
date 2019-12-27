## package.josn を用意する

{
  "name": "nuxt-scratch-app",
  "dependencies": {
    "nuxt": "^2.8.1"
  },
  "scripts": {
    "dev": "nuxt",
    "build": "nuxt build",
    "start": "nuxt start"
  }
}

## package.json のあるディレクトリ上で、以下のコマンドを打つ

$ npm install --save nuxt
「pages」ディレクトリを作成して、その中に「index.vue」ファイルを作成する

## 「npm run dev」でコンパイルをして、http://localhost:3000/　にアクセスすると 「Hello World」 （index.vueの内容） が表示されている。あとは必要に応じて、ディレクトリやファイルを追加してやればよい。

$ npm run dev