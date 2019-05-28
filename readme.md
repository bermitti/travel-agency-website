# travel agency website

* сборка сайта в VSCode
* для конвертации scss в css
  * npm i node-sass
  * package.json

    ```js
    "scripts": {
        "compile:sass": "node-sass sass/main.sass css/style.css -w"
    }
    ```

  * node-sass: Ссылается на пакет node-sass
  * -watch OR -w: флаг, который означает “следить за всеми .scss файлами в папке sass/main.sass и перекомпилировать их каждый раз когда они изменяются в папку css/style.css”

* npm run compile:sass ==>> следим и компилируем SCSS(SASS)