---
layout: post
title:  "How my blog is made?!"
date:   2022-01-03 00:56:42 +0300
categories: how_made
---
Краткая последовательность создания блога.

• Создаём репозиторий на github. Определенные требования к наименованию.

• Клонируем репозиторий на локальный комп, через командную строку или через  гитхаб десктоп.
git clone https://github.com/NikLaz25/Niklaz25.github.io

• Уcтанавливаем ruby, git,  gem, jekill:

{% highlight ruby %}
sudo apt-get update
sudo apt-get install git
sudo apt install ruby
sudo apt install gem
gem install jekyll bundler
sudo apt install jekyll
jekyll -v   смотрим что установилось
{% endhighlight %}

• Создаём скелет блога:

	○ cd myblog
	○ jekyll new . --force устанавливает файлы прямо в папку 
	○ Я сервер не ставил…  bundle exec jekyll serve

• Заходим в IDE.

• Открываем проект - локальную папку.

• Вносим корректировки: настройки, посты.

• Добавляем +Add.

• Комментируем.

• Пушим на гитхаб.

• Наслаждаемся блогом!


P.S. Так-то всё просто, но по факту пришлось потратить время, чтобы покопаться и въехать :)

• Ссылки:

[Основная инструкция] [1]
[Джекилл] [2]
[Крутая статья, вроде всё по делу] [3]
[Лена делает блог на github pages #1] [4]

[1]: https://pages.github.com
[2]: https://jekyllrb.com
[3]: https://gosha20777.github.io/blog/github/jekyll/2017/01/28/blog-with-github/
[4]: https://www.youtube.com/watch?v=DFDlQWAP8Y4