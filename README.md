# lab_number_5


## Описание
В левом поддереве все значения меньше корня, в правом — больше.

## Узел
```python
class TreeNode:
    def __init__(self, value):
        self.value = value
        self.left = None
        self.right = None
```
# Функции
Функция	Описание	Сложность
insert(root, value)	Вставить значение	O(h)
search(root, target)	Найти значение	O(h)
inorder(root)	Вывод по возрастанию	O(n)
height(root)	Высота дерева	O(n)

# Пример
Вставляем: [50, 30, 70, 20, 40, 60, 80, 35, 45]
inorder: 20 30 35 40 45 50 60 70 80
Поиск 40: найдено
Высота: 3

    50
   /  \
  30   70
 / \   / \
20 40 60 80
  / \
 35 45
