🛠 В новом коде используйте только `let` или `const`. Используйте `let` в тех случаях, когда значение переменной меняется. Во всех остальных используйте `const`. Проще всего всегда по умолчанию использовать ключевое слово `const` и исправлять объявление переменной на `let` если появляется нужда изменить её значение далее в коде.

🛠  Называйте переменные так, чтобы можно было легко понять, что в ней хранится. Например:

```js
let url = 'https://doka.guide'

const now = Date.now()

const user = {
  name: 'John',
  age: 30,
}
```

Исключением считается именование счётчиков в циклах `for`, в которых обычно используются одиночные буквы `i`, `j` и так далее.

Имена переменных могут состоять из нескольких слов, поэтому для удобства их чтения, в JavaScript принято использовать так называемую «верблюжью нотацию» (_camelCase_), когда каждое новое слово, начиная со второго, пишется с заглавной буквы:

```js
const fullName = 'John Doe'

const arrayOfNumbers = [1, 2, 3]
```

Имена констант (переменные, которые не меняют своё значение) принято писать используя _"screaming_snake_case"_. В данной нотации все слова пишутся заглавными буквами, а разделителем является символ `_`.

```js
const BASE_URL = 'https://doka.guide'

const PORT = 3000

const UNAUTHORIZED_CODE = 401
```
