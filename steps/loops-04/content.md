# Инвертирование массива циклом 

Напишите программу, которая перевернет порядок элементов любого исходного массива. Переверните массив сами с помощью цикла. 

Не используя встроенные методы `reverse` или `reverse!`

**Например:**

```
Исходный массив:
[1, 2, 3, 4, 5, 6, 7]
Новый массив, полученный из исходного:
[7, 6, 5, 4, 3, 2, 1]
```

<div class="rubyrush-task-hint">

Задачу можно решить разными способами, один из простейших в руби будет с помощью метода `unshift` — в цикле пройдитесь по элементам исходного массива и добавьте их этим методом в новый массив. 

См. документацию на класс `Array` в ссылках к уроку. `unshift` делает то же самое, что и `push` (или `<<`), только добавляет элемент не в конец массива как обычно, а в начало.

</div>


<div class="rubyrush-task-answer">


<ul>
<li><a href="https://github.com/aristofun/rubyrush-path/blob/master/steps/loops-04/solution/reverse_array.rb" class="rubyrush-task-solution-link">Наш вариант решения</a></li></ul>

</div>