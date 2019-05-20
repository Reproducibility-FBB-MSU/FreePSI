FreePSI

авторы - Волобуева, Трифонова

Этот проект посвящен реализации алгоритма "FreePSI" на симулированных данных, которые были получены при помощи алгоритма flux simulator.

Код запуска алгоритма "FreePSI" скрипт "FreePSI.sh", данные с полученными PSI в файле "psi_freePSI.summary", данные о истинных значения PSI  лежат в файле "TruePSI". Скрипт, который строит scatter plot для genome-wide оценки PSI файл "genome-wide.ipynb"(на вход подается файл TruePSI, psi_FreePSI.summary), полученная картинка "genome-wide.png".

Если будет желание запучтить скрипт(предварительно установив Jellyfish) , то лучше всего в директории /FreePSI/example
написать команду: bash run_FreePSI.sh
Дело в том, что именно в этой папке правильное расположение директории с референсным геномом, РНК-ридами, которые картировали на хромосому 21. На выходе программа даст файл "run_FreePSI.sh".
