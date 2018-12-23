# Сундук несбывшихся желаний 

А теперь стремительно напишите для вашего «Сундука желаний» скрипт, который выводит

1. желания, которые уже должны были сбыться на текущий день;
2. желание, которым ещё предстоит сбыться.

**Как-то так:**

```sh
Эти желания должны уже были сбыться к сегодняшнему дню
13.08.1912: Найти священный Грааль
20.07.1944: Захватить мир
13.08.2015: Протестировать работу программы "Сундук желаний"

А этим желаниям ещё предстоит сбыться
08.03.2018: Сделать курс по Node.JS
```

<div class="rubyrush-task-hint">

Получить все желания можно с помощью метода

```ruby
doc.elements.each("wishes/wish")
```

Проверить, должно ли желание было выполниться к текущей дате можно сравнивая её с `Date.today`. 

Не забудьте подключить библиотеку для работы с датами командой `require 'date'`

</div>


<div class="rubyrush-task-answer">

<p>
<a href="https://github.com/aristofun/rubyrush-path/tree/master/steps/xml-write-02/solution/" class="rubyrush-task-solution-link">Вариант решения задачи</a>
</p>

</div>