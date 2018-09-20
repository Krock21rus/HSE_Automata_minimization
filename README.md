# HSE_Automata_minimization

Настроить автоматическую установку graphviz не получилось. Для работы в стандартном режиме требуется dot.

Компиляция(установка) с помощью запуска ./compile.

Запуск самой программы с помощью ./run file.txt [-raw]

На стандартный вход необходимо подать автомат в формате:

Первая строка входного файла содержит алфавит Σ, который является непустым подмножество латинского алфавита (все буквы строчные).

Следующая строка содержит число |Q| — количество состояний автомата (1≤|Q|≤1000).

Состояния нумеруются числами от 1до |Q|.

Следующая строка содержит число q0(1≤q0≤|Q|) — номер начального состояния, затем число |T| — количество терминальных состояний, затем |T| чисел от 1 до |Q| — номера терминальных состояний.

Следующие |Q| строк содержат по |Σ| чисел — описание функции перехода σ. (Для каждого состояния в отдельной строке приводятся номера состояний, в которые из него ведут переходы по всем символам алфавита).

если программа запускалась с аргументом -raw, то вывод будет аналогичный, только без указания алфавита, иначе создастся файл out.png с понятной картинкой графа.