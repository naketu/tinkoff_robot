# tinkoff_robot
ROBOT THAT PERFORMS MARKET MAKER TRADING STRATEGY


Данный торговый бот основан на стратегии высокочастотной торговли для Market Maker, зарабатывающий на спреде и переключающий режимы торговли между пассивным и агрессивным основываясь на изменения в стакане.
Чтобы запустить робота вставьте в начале файла account_id и token, а после раскомментируйте одну из функций в последних двух строках файла.
Чтобы задать параметры чувствительности модели, вызовите функцию set_parameters() у обьекта класса model_1.
Первый параметр регулирует чувствительность модели, рекоммендуется выставлять от 0 до 0.5, где меньшее значение будет увеличивать чувствительность модели. 
Второй параметр - спред, который будет использован алгоритмом, однако изменение спреда уберет автоматическое определение спреда, что негативно скажется на исполняемости запросов.
