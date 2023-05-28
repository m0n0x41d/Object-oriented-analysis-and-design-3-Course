# Задание 3. Выделите основные классы анализа (АТД) в проекте -- только на уровне их названий (на английском) и краткого описания в несколько слов (на русском). 

Классы анализа — это классы, напрямую моделирующие сущности реального мира. Как уже отмечалось, методологически корректнее говорить не о реальном мире, а о внешнем мире — внешнем по отношению к замкнутому внутреннему миру создаваемой программной системы. Программная модель внешнего мира будет операционной — это значит, что она формирует объективные практические результаты, и может как-то взаимодействовать с окружающим её миром. 

--- 

* Astronaut - класс моделирующий астронавтов на станции.
* StationModule - класс, моделирующий модули станции. 
* Event - класс, моделирующий псевдослучайные и запланированные (любые) события на станции.
* Resource - класс, моделирующий тип ресурса.
* ResourceManager - класс, моделируюий структуру-хранилище ресурсов, и управление ими (потребление\воспроизводство).
* Clock - класс, моделирующий течение времени на станции. 
* Adjutant - класс, агрегирующий информацию о событиях на станции (логирование). Моделирует Бортового "ИИ" Помошника - информатора.
* Screen - класс, моделирующий терминал-интерфейс симулятора (экран).


