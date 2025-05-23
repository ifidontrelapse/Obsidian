### Динамическое светорассеяние

- d>100-1000 mkm - сито
- d>0.5-1mkm - дифракция света
- 1<d,5<100 nm - светорассеяние

##### Типы рассеяния 
Фраунгофера, Ми, Релея ([[Types of scattering]])

##### Эквивалентные сферы

Известные физические свойства
Результат сравним с результатом, который может быть получен для сфер
Диаметр сфер, приводящих к такому же результату, известен

## Броуновское движение

Уравнение диффузии, с помощью которого позже доказали существоване атомов и молекул.

Основные принципы Броуновского движения:
- Чем больше частицы, тем медленнее она двигается
- Чем выше температура, тем быстрее двигается частица
- Скорость Броуновского движения определяется кф диффузии.

### Уравнение Стокса-Эйнштейна

Уравнение связывает **коэффициент диффузии** ($D$) сферических частиц в жидкости с её вязкостью и температурой:

$$
D = \frac{k_B T}{6 \pi \eta r}
$$

##### Пояснение символов:
- **$D$** — коэффициент диффузии частицы [м²/с]  
- **$k_B$** — постоянная Больцмана ($1.38 \times 10^{-23}$ Дж/К)  
- **$T$** — абсолютная температура [К]  
- **$\eta$** — динамическая вязкость жидкости [Па·с]  
- **$r$** — радиус частицы [м]  

##### Ключевые допущения:
1. Частица **сферическая** и жесткая.  
2. Жидкость **однородная** и бесконечно протяженная.  
3. **Нет взаимодействия** между частицами (разбавленный раствор).  

> **Применение**: расчет диффузии коллоидов, наночастиц, биомолекул (например, белков в воде).

## Схема устройства DLS

![[Pasted image 20250502031858.png]]
Меняя угол и положения фокуса лазера, мы можем увеличивать объем взаимодействия лазера с нашим веществом.
![[Pasted image 20250502032215.png]]

![[Pasted image 20250502032319.png]]

## Коррелограмма
![[Pasted image 20250502032524.png]]
Важно получить кф диффузии для того, чтобы узнать размер частиц.
Корреляция у маленьких частиц расходится быстрее во времени.

![[Pasted image 20250502032920.png]]
Производная корреляционной функции по времени пропорциональная скорости движения частиц, а следовательно кф диффузии.
![[Pasted image 20250502033219.png]]

## Распределения по размерам
Плохо видно маленькие частицы из-за серьезного увеличения интенсивности на больших частиц.

![[Pasted image 20250502033616.png]]
**Данные, полученные на приборе, характеризуют интенсивность рассеяния, а не соотношения в количестве частиц.**

Для наиболее распространенных типов материалов существуют детальные таблицы, позволяющие выбрать оптимальные параметры для проведения эксперимента.

Также стоит помнить о многоступенчатом рассеянии.

##### Только сферические частицы?

Иногда удается измерить нанообъекты в двух проекциях, но для этого они должы обладать жесткой структурой (несколько атомов) и иметь большое соотношение d1/d2.
***
## Основные выводы

- Распределение частиц по размера - производная их физических свойств
- Почти всегда мы рассматриваем только сферы или заменяем несферические частицы на эквивалентные сферы
- Метод непрямой и заключается в построении автокорреляции флуктуаций рассеяния с целью получить кф диффузии  и использовать уравнения для расчета гидродинамического радиуса
- Анализ данных проводят, как в рамках распределений, так и по кумулятивным параметрам (Z-average, индекс полидисперсности PDI)
- Дополнительная литература и методики позволяют добиться максимально возможного результата!
***
Tags: #method 
