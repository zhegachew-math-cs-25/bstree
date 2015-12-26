# bstree
Двоичное дерево поиска (binary search tree, BST) — это двоичное дерево, к каждой вершине которого приклепрены данные, а именно пара (ключ, значение). Ключ обычно является числом (целым или действительным), а в общем виде ключ — это элемент какого то множества, на котором определено отношение "больше" и "равно". В двоичном дереве поиска выполнено свойство: 
значение ключа из левого поддерева вершины A <= значение ключа A < значение ключа любой вершины из правого поддерева.
Применение BST
Указанное свойство BST позволяет осществлять рекурсивый поиск в дереве элемента с нужным ключем. В дерево достаточно ветвистое (а точнее его высота не большая), этот поиск осуществляется достаточно быстро.
Введем обозначения
root — ссылка на некоторую вершину пдерева
root->key — ключ, хранящийся в этой вершине
root->l — ссылку на вершину левого поддерва
root->r — ссылка на вершину правого поддерева
