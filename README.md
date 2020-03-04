# REGEXP

<strong>JavaScript</strong>
```console.log('Oleh Hatsenko'.search(/^[A-Z][a-z]{3} \s*[A-Z][a-z]{7}$/gu) ? false : true);```

Варіанти із Юнікодом

```/^([A-Z]|[\u0410-\u042F]|\u0490)([a-z]|[\u0430-\u044F]|\u0491){0,19}\s+([A-Z]|[\u0410-\u042F]|\u0490)([a-z]|[\u0430-\u044F]|\u0491){0,19}$/g```

```/^([A-Z]|[А-Я]|[Ґ])([a-z]|[а-я]|[ґ]){0,19}\s+([A-Z]|[А-Я]|[Ґ])([a-z]|[а-я]|[ґ]){0,19}$/gu```

Матеріал для кращого розуміння регулярних виразів -REGEXP (Regular Expression), це посуті мова вибірки, щось назразок мови SQL =)
Використовується багато де ;)

Сайт для перевірки та тестування REGEXP з чудовим описом кожного виразу

[![regex101.com](https://regex101.com/static/assets/android-icon-192x192.png)](https://regex101.com/r/06kFc0/1)

а також їх <em>репозиторій</em> https://github.com/firasdib/Regex101

Ще є такий цікавий ресурс для тестування:

[![regexr.com](https://github.com/gskinner/regexr/blob/master/dev/icons/RegExr.svg)](https://regexr.com/)

ну і їх <em>репозиторій</em> https://github.com/gskinner/regexr/

А це необхідно, якщо наважитесь на використання <strong>Unicode</strong> у REGEXP:

[![regular-aexpressions.info](https://www.regular-expressions.info/img/header125.png)](https://www.regular-expressions.info/unicode.html)
