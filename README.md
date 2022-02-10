# WebFont Hero

Пакет для установки веб-шрифта: Hero.

## Установка

Чтобы установить пакет, Вы можете воспользоваться командой в CLI:

```bash 
npm install --save https://github.com/getscope/npm-webfont-hero
```

или в файле `package.json` создать свойство `dependencies` и добавить ссылку на github-репозиторий:

```json 
{
    "dependencies": {
        "@getscope/npm-webfont-hero": "github:getscope/npm-webfont-hero"
    }
}
```

и выполнить команду в CLI для обновления установленных зависимостей:

```bash 
npm update
```

## Примеры использования и подключения

```css 
body {
    font-family: 'Hero', sans-serif;
}
```

Для импорта веб-шрифта в SCSS, Вы можете воспользоваться следующими путями:

```scss 
@import "node_modules/@getscope/npm-webfont-hero/src/scss/_200-normal.scss";
@import "node_modules/@getscope/npm-webfont-hero/src/scss/_400-normal.scss";
@import "node_modules/@getscope/npm-webfont-hero/src/scss/_700-normal.scss";
@import "node_modules/@getscope/npm-webfont-hero/src/scss/_all-normal.scss";
```
