# Максимальное из произвольных 

Объявите в программе пустой массив. Спросите у пользователя какой длины должен быть массив.

Запомните выбор пользователя и наполните массив нужным количеством случайных чисел. Числа должны быть в диапазоне от 0 до 100 (вспомните метод `rand` из прошлых задач). Выведите получившийся массив на экран.

После вывода массива найдите в нем максимальный по величине элемент и выведите на экран его значение.

**Например:**

```
Какой длины будет массив случайных чисел?
> 9
[55, 19, 54, 41, 74, 94, 87, 85, 49]
Самое большое число:
94
```

<div class="rubyrush-task-hint">

Для наполнения массива используйте цикл `while` и отдельную переменную в условии цикла, которая позволит считать итерации цикла (как мы делали на видео в уроке).

Следующий шаг — в цикле `for ... in` пройтись по элементам массива.

При этом в отдельной переменной сохранить хранить текущее значение максимального элемента массива, и сохранять туда текущий элемент массива, если он больше прошлого значения этой переменной.

Если сразу не получается представить это, не спешите заглядывать в ответ, нарисуйте на бумажке пример какого–нибудь массива и тут же на бумажке пройдите по нему вручную. Обратите внимание на то, как вы сами ищите максимальный элемент в массиве. 

Программа часто работает так же как наша собственная голова.

</div>


<div class="rubyrush-task-answer">


<ul>
<li><a href="https://github.com/aristofun/rubyrush-path/blob/master/steps/loops-02/solution/max_in_array.rb" class="rubyrush-task-solution-link">Наш вариант решения</a></li></ul>


</div>
