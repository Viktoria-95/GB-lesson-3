# GB-lesson-3

> git clone - клон репозитория

> cd .. - позволяет вернуться в начальную папку

> cd name_clone - переходит в определенную папку

> git pull - позволяет скопировать данный из одного клона в другой

> git push - отправляет информацию в GitHub

> *Open pull request* - предложение для автора

> git branch - выводим список веток в репозитории

> git branch new_branch_name - создаем новую ветку с именем new_branch_name

> git branch -d branch_to_delete - удаляем ветку с именем new_branch_name

> git checkout branch_name - переходим на ветку branch_name

# Инструкция для Github

[Инструкция первая часть](#Инструкция-для-Github)

>**git config user.name** - инициализация имени

>**git config user.mail** - инициализация email

>**git status** - получить информацию от git о его текущем состоянии

>**git add file_name** - *добавить файл или файлы к следующему коммиту*

>**git commit -m "commit-message"** - закрепить измененя

>**git log** - получаем информацию commit

>**git checkout "1234"** - переход от одного commit к другому

>**git checkout master** – вернуться к актуальному состоянию и продолжить работу

>**git diff** - позволяет увидеть последние измененя

[Инструкция первая часть](#Инструкция-для-Github)
> **Использование ссылок в документации можно посмотреть** [***перейдя по ссылке***](https://learn.microsoft.com/ru-ru/contribute/how-to-write-links)

```csharp
[!ВАЖНО]
Не используйте "щелкните здесь" в качестве текста ссылки. Она плохо сказывается на оптимизации для поисковых систем и не дает адекватного представления о целевой странице.
```

[Ссылка на файл](Github.md) - можно изучить информацию про ссылки внутри каталога

[Ссылка на файл](Git.md)

![Природа](https://s1.1zoom.ru/big7/76/Scenery_Sky_Mountains_356720.jpg)

![alt text for image](///%D0%94%D0%97/images/Images86.jpg)

![alt text for image](///ДЗ\images\Images91.jpg)


> git branch - выводим список веток в репозитории

> git branch new_branch_name - создаем новую ветку с именем new_branch_name

> git branch -d branch_to_delete - удаляем ветку с именем new_branch_name

> git checkout branch_name - переходим на ветку branch_name


 В большинстве случаев для статей в одном наборе документации указывается один и тот же фрагмент URL-адреса <product-service>. Например:

    Один и тот же набор документов:
        https://learn.microsoft.com/dotnet/core/get-started
        https://learn.microsoft.com/dotnet/framework/install
    Другой набор документов:
        https://learn.microsoft.com/dotnet/core/get-started
        https://learn.microsoft.com/visualstudio/whats-new

- *В путях к файлам используются прямые (/), а не обратные косые черты.*
- *Для статьи, в которую добавляется ссылка на другую статью в том же каталоге:*
[link text](article-name.md)
- *Для статьи, в которую добавляется ссылка на статью в родительском каталоге текущего каталога:* [link text](../article-name.md)
- *Для статьи, в которую добавляется ссылка на статью в подкаталоге текущего каталога:* [link text](directory/article-name.md)
- *Для статьи, в которую добавляется ссылка на статью в подкаталоге родительского каталога текущего каталога:* [link text](../directory/article-name.md)
- *Некоторые статьи состоят из **.yml** файла и **.md** файла, где .yml файл содержит метаданные и .md содержит содержимое. В этом случае со ссылкой .yml на файл:* [link text](../directory/article-name.yml) (**не [link text](../directory/article-name-content.md)**)
