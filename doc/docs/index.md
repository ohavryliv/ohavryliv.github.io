# Простой подход к ведению заметок. MkDocs Material & Gitlab!

### Mkdocs Material

<!-- <div class="embed-responsive embed-responsive-16by9">
  <iframe src="https://www.youtube.com/embed/ljRDkQVOlqU" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div> -->

<a href="https://www.youtube.com/watch?v=V2ZNzqwlQjw" class="video-link">Video Мануал</a>

<a href="https://www.youtube.com/watch?v=ziX6QcFvP-8" class="video-link">Video Мануал 2</a>

Официальный гайд [mkdocs-material/getting-started](https://squidfunk.github.io/mkdocs-material/getting-started/). Я переработал данную тему под ру сегмент, обновил `css` файл Font Awesome, иконочный шрифт и добавил некоторые библиотеки js.

### Markdown

Для использования необходимо знать Markdown разметку [markdown_cheatsheet](https://paulradzkov.com/2014/markdown_cheatsheet/), больше в google.

### Клонируем данный репозиторий, или форкаем на gitlab.

Затем переходим в дерикторию.

```sh
git clone https://gitlab.com/creio/cvc.git

cd cvc
```

### Устанавливаем `pip` на примере Arch Linux.

```sh
pacman -S python-pip
```

### Устанавливаем виртуальное окружение `python` и активируем его

```sh
pip install --upgrade virtualenv

virtualenv ve

source ve/bin/activate
```

### Устанавливаем mkdocs и необходимые зависимости через `pip`

```sh
pip install -r requirements.txt
```

### Запускаем `mkdocs` сервер локально

```sh
mkdocs serve
```

По данному адресу на localhost работает mkdocs [127.0.0.1:8000](http://127.0.0.1:8000).

### Markdown редакторы

Мне очень понравился [typora.io](https://typora.io/), установка через yay, он в Aur.

```sh
yay -S typora
```

Онлай редактор [stackedit.io](https://stackedit.io/app).