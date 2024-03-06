# Лекция №5. Архитектура ОС.

Свойства кода ядра:

1. резидентность
2. привелигерованный режим

## Архитектуры ОС

1. **Монолитная архитектура.**
	Выделяют 3 слоя:
	1. Main program
	2. Services
	3. Utilites
	[добавить картинку]: #
	_Плюсы:_
	- Быстродействие
	- Безопасность
	_Минусы:_
	- Сложность разработки
	- Проблемы с надежностью
	- Повышенные затраты памяти
2. **Многослойное ядро.**
	1. Аппаратное обеспечение (Hardware)
	2. Аппаратная поддержка ядра 
	3. Машинно-зависимые модули (HAL = Hardware Abstraction Layer)
	4. Базовые механизмы ядра (Слой исполнения решений менеджера ресурсов)
	5. Менеджер ресурсов
	6. Системные вызовы/API
	[добавить картинку]: #
3. **Микроядерная архитектура.**
	[добавить картинку]: #
4. **Экзоядерная архитектура.**
	Менеджеры ресурсов находятся в ядре, а HAL снаружи.