# Цвет

<figure>
  <img src="/Suitability_3.svg" style="width: 710px !important;">
</figure>

---
zoom: 1.0
---

# Цвет

* Первое правило цвета: цвет - неоднозначное понятие!
  * Понятие цвета сбивает с толку, если рассматривать его как нечто единое

<div class="grid grid-cols-[5fr_4fr] gap-20">
<div>

* Цвет воспринимается в трёх каналах
  * Порядковые каналы показывают величину
    * **Освещенность**: светлее/темнее
    * **Насыщенность**: ярче/тусклее
  * Категориальный канал идентифицирует
    * **Оттенок**: какой именно цвет
</div>
<div>
<br>
<br>
<figure>
  <img src="/HSL.svg" style="width: 480px !important;">
</figure>
</div>
</div>

* Каналы имеют различные свойства
  * Что именно они передают в систему восприятия?
  * Как много они могут передать?
  * Сколько дискриминируемых значений мы можем использовать?

---
zoom: 1.0
---

# Цвет

<figure>
  <img src="/A_vs_B.png" style="width: 480px !important;">
</figure>

---
zoom: 1.0
---

# Цвет

<div class="grid grid-cols-[5fr_5fr] gap-20">
<div>
<figure>
  <img src="/girl_1.png" style="width: 480px !important;">
</figure>
</div>
<div>
<v-click at="1">
<figure>
  <img src="/girl_2.png" style="width: 480px !important;">
</figure>
</v-click>
</div>
</div>

---

# Цвет

<div class="grid grid-cols-[4fr_5fr] gap-20">
<div>
<figure>
  <img src="/The_dress_blueblackwhitegold.jpg" style="width: 200px !important;">
  <figcaption style="color:#b3b3b3ff; font-size: 11px; position: relative; top: 20px; left: 0px;">
  <a href="https://ru.wikipedia.org/wiki/%D0%A4%D0%B5%D0%BD%D0%BE%D0%BC%D0%B5%D0%BD_%D1%81%D0%B8%D0%BD%D0%B5%D0%B3%D0%BE_%D0%B8%D0%BB%D0%B8_%D0%B1%D0%B5%D0%BB%D0%BE%D0%B3%D0%BE_%D0%BF%D0%BB%D0%B0%D1%82%D1%8C%D1%8F">https://ru.wikipedia.org/wiki/Феномен_синего_или_белого_платья</a>
  </figcaption>
</figure>
</div>
<div>
<v-click at="1">
<figure>
  <img src="/dress_2.png" style="width: 580px !important;">
</figure>
</v-click>
</div>
</div>

---

# Цвет

#### На цветовое восприятие влияют:
- хроматическая адаптация
- адаптация яркости
- одновременный контраст
- пространственные эффекты
- угол обзора
- лингвистические и культурные особенности

---

# Почему просто не использовать цвета радуги?

<div class="grid grid-cols-[3fr_5fr] gap-20">
<div v-click at="1">
<figure>
  <img src="/Light_dispersion_of_a_mercury-vapor_lamp_with_a_flint_glass_prism_IPNr°0125.jpg" style="width: 290px !important;">
  <figcaption style="color:#b3b3b3ff; font-size: 11px; position: relative; top: 20px; left: 0px;">Источник изображений:<br>
  <a href="https://en.wikipedia.org/wiki/Visible_spectrum">https://en.wikipedia.org/wiki/Visible_spectrum</a>
  </figcaption>
</figure>
</div>
<div>
<div v-click at="2">
<br>
<br>
<figure>
  <img src="/Linear_visible_spectrum.svg" style="width: 490px !important;">
</figure>
</div>
<br>

<v-clicks depth="2">

* Проблемы восприятия цвета в спектре:
  * Цвет неупорядочен
  * Цвет нелинеен 
* С другой стороны, названия цветов закреплены в культуре
  * Именованные цвета легче (точнее и быстрее) воспринимаются 
</v-clicks>
</div>
</div>

---

# Названия цветов

<br>
<figure>
  <img src="/color_names_1.png" style="width: 390px !important;">
</figure>

---

# Названия цветов

<br>
<figure>
  <img src="/color_names_2.png" style="width: 390px !important;">
  <figcaption style="color:#b3b3b3ff; font-size: 11px; position: relative; top: -20px; left: 400px;">Источник:
  <a href="http://www.thedoghousediaries.com/1406">http://www.thedoghousediaries.com/1406</a>
  </figcaption>
</figure>

---

# Названия цветов

<figure>
  <img src="/color_names_3.png" style="width: 390px !important;">
  <figcaption style="color:#b3b3b3ff; font-size: 11px; position: relative; top: -20px; left: 400px;">Источник:
  <a href="https://blog.xkcd.com/2010/05/03/color-survey-results/">https://blog.xkcd.com/2010/05/03/color-survey-results/</a>
  </figcaption>
</figure>

---

# Цветовые модели

#### **Цветовая модель** — математическая модель описания представления цветов в виде кортежей чисел (обычно из 3-4 значений), называемых цветовыми компонентами, или цветовыми координатами (например `rgb(0,128,255)`, `#1E90FF`, `HSL(220 100% 50%)`)


<div class="grid grid-cols-[5fr_4fr] gap-10">
<div>
<br>
<center>

#### Цветовая модель CIE XYZ
<figure>
  <img src="/CIE1931_XYZCMF.png" style="width: 370px !important;">
  <figcaption style="color:#b3b3b3ff; font-size: 11px; position: relative;">Источник изображений:
  <a href="https://ru.wikipedia.org/wiki/Цветовая_модель">https://ru.wikipedia.org/wiki/Цветовая_модель</a>
  </figcaption>
</figure>
</center>
</div>
<div>
<figure>
  <img src="/CIExy1931_fixed.svg" style="width: 300px !important;">
</figure>
</div>
</div>

---
zoom: 0.99
---

# Цветовые модели

#### Производные от CIE XYZ цветовые пространства:

* `L*a*b*` — равноконтрастное цветовое пространство, в котором расстояние между цветами соответствует мере ощущения их различия
* `RGB`, `sRGB`,... - аддитивные модели, где цвет получается путём добавления к черному
* Субтрактивные модели `CMY` и `CMYK` — получение цвета "вычитанием" краски из белого листа
* `Pantone` - модель, где соответствие цветов задаётся таблицей (каталог цветов)
* `HSV` - математические модели, полезные для обработки изображения
* Модели для кодирования цветовой информации при сжатии изображений и видео

<br>

#### Важно: многие модели позволяют представлять цвет, который может не воспроизводить носитель (экран) и даже **может не воспринимать человеческий глаз**
<br>

#### Один и тот же цвет можно преобразовывать из одной цветовой модели в другую

---

# Цветовые модели

#### Исследование представления цветов - динамичная область на стыке компьютерных наук и психофизики

<div class="grid grid-cols-[5fr_4fr] gap-10">
<div>
<br>

* Появляются новые цветовые модели
  * [https://oklch.com](https://oklch.com)
* Находятся новые цвета
  * [https://science.org/doi/epdf/<br>10.1126/sciadv.adu1052](https://www.science.org/doi/epdf/10.1126/sciadv.adu1052)

<br>
<center>
<figure>
  <img src="/Olo_color.png" style="width: 170px !important;">
  <figcaption style="color:#b3b3b3ff; font-size: 11px; position: relative;">Этот оттенок наиболее близок к Olo
  </figcaption>
</figure>
</center>
</div>
<div>
<figure>
  <img src="/Linear,_sRGB,_OKLAB.gif" style="width: 370px !important;">
  <figcaption style="color:#b3b3b3ff; font-size: 11px; position: relative;">Источник анимации:
  <a href="https://en.wikipedia.org/wiki/Oklab_color_space">https://en.wikipedia.org/wiki/Oklab_color_space</a>
  </figcaption>
</figure>
</div>
</div>

---
zoom: 1.1
---

# Цвет для категориальных данных

<div class="grid grid-cols-[5fr_4fr] gap-10">
<div>
<br>
<br>

* Восприятие человека основано на сопоставлении
  * Хорошо, если цвета смежные
  * Очень плохо для абсолютных выводов
  * Мы можем различить $\leq 12$ несмежных областей, включая фон
</div>
<div>
<br>
<br>
<figure>
  <img src="/categorical_color.png" style="width: 510px !important;">
</figure>

#### Насколько эффективно использован цвет в данных визуализациях?
</div>
</div>


---

# Цвет для категориальных данных

<figure>
  <img src="/Diseasome_NYTimes.com.png.jpg" style="width: 610px !important;">
  <figcaption style="color:#b3b3b3ff; font-size: 11px; position: relative; top: -80px; left: 700px;">Источник изображения:<br>
  <a href="https://archive.nytimes.com/www.nytimes.com/interactive/2008/05/05/science/20080506_DISEASE.html">https://archive.nytimes.com/<br>www.nytimes.com/<br>interactive/2008/05/05/science/<br>20080506_DISEASE.html</a>
  </figcaption>
</figure>

---

# Цвет для порядковых данных

<div class="grid grid-cols-[5fr_4fr] gap-10">
<div>
<figure>
  <img src="/fusiontables.png" style="width: 280px !important;">
</figure>
</div>
<div>
<v-click at="1">

#### Проблемы:
</v-click>
<v-click at="2">

* Масштаб величин
<figure>
  <img src="/limits2.png" style="width: 280px !important;">
</figure>
</v-click>
<v-click at="3">

* Палитра 
<figure>
  <img src="/guardian1.png" style="width: 180px !important;">
</figure>
</v-click>
</div>
</div>

<br>
<v-click at="4">
<div class="grid grid-cols-[5fr_4fr] gap-10">
<div>
<figure>
  <img src="/choropleth-classes.gif" style="width: 265px !important;">
  <figcaption style="color:#b3b3b3ff; font-size: 11px; position: relative; top: 20px; left: 0px;">Источники изображений: <a href="https://www.vis4.net/blog/choropleth-maps/">https://www.vis4.net/blog/choropleth-maps</a><br><a href="http://www.guardian.co.uk/news/datablog/interactive/2011/sep/15/us-poverty-mapped">http://www.guardian.co.uk/news/datablog/interactive/2011/sep/15/us-poverty-mapped</a>
  </figcaption>
</figure>
</div>
<div>
<br>

#### В исправленных картограммах:  
* Масштаб величин
<figure>
  <img src="/limits1.png" style="width: 280px !important;">
</figure>

* Палитра 
<figure>
  <img src="/hsv-colors.png" style="width: 180px !important;">
</figure>
</div>
</div>
</v-click>

---

# Цвет для порядковых данных

<div class="grid grid-cols-[2fr_5fr] gap-1">
<div>
<figure>
  <img src="/poverty-bar-chart.png" style="width: 240px !important;">
</figure>

</div>
<div>
<div class="grid grid-cols-[2fr_2fr] gap-5">
<div>
<v-click at="1">
<figure>
  <img src="/newpoverty-map-same-number.png" style="width: 280px !important;">
  <figcaption style="color:black; font-size: 14px; position: relative; top: 0px; left: 40px;">Равное число штатов в бине
  </figcaption>
</figure>
</v-click>
</div>
<div>
<v-click at="2">
<figure>
  <img src="/newpoverty-map-range.png" style="width: 280px !important;">
  <figcaption style="color:black; font-size: 14px; position: relative; top: 0px; left: 40px;">Равные интервалы по величине
  </figcaption>
</figure>
</v-click>
</div>
</div>
<br>
<div class="grid grid-cols-[2fr_2fr] gap-5">
<div>
<v-click at="3">
<figure>
  <img src="/newpoverty-map-positive-negative.png" style="width: 280px !important;">
  <figcaption style="color:black; font-size: 14px; position: relative; top: 0px; left: 20px;">Равное количество бинов<br>вверх/вниз от среднего значения
  </figcaption>
</figure>
</v-click>
</div>
<div>
<v-click at="4">
<figure>
  <img src="/newpoverty-map-emphasis.png" style="width: 280px !important;">
  <figcaption style="color:black; font-size: 14px; position: relative; top: 0px; left: 40px;">Выделение экстремальных значений
  </figcaption>
</figure>
</v-click>
</div>
</div>
</div>
</div>

<figure>
  <figcaption style="color:#b3b3b3ff; font-size: 11px; position: relative; top: 10px; left: 0px;">Источник изображений: <a href="http://excelcharts.com/the-same-data-the-same-map-different-stories/">http://excelcharts.com/the-same-data-the-same-map-different-stories</a>
  </figcaption>
</figure>

---
zoom: 0.9
---

# Цвет для порядковых данных

<div class="grid grid-cols-[2fr_2fr] gap-15">
<div>

* Проблемы восприятия цвета:
  * Не воспринимается упорядоченным
  * Воспринимается нелинейно

* Преимущества восприятия цвета:
  * Помогает увидеть и проинтерпретировать детали

* Альтернативы
  * Крупномасштабная структура: меньшее количество оттенков
  * Мелкая структура: множество оттенков с монотонно возрастающей яркостью
    * например, цветовая палитра viridis
</div>
<div>
<figure>
  <img src="/spectra.svg" style="width: 290px !important;">
<figcaption style="color:#b3b3b3ff; font-size: 11px; position: relative; top: 0px; left: 0px;">Источники изображений:<br>
  <a href="https://www.cs.ubc.ca/~tmm/vadbook/">Рис. 10.4. T. Munzner. Visualization Analysis and Design (2014)</a><br>
  <a href="https://mycartablog.com/2012/10/06/">https://mycartablog.com/2012/10/06/</a>
  </figcaption>
</figure>

<br>
<div class="grid grid-cols-[2fr_2fr] gap-5">
<div>
<figure>
  <img src="/luminosity.png" style="width: 280px !important;">
</figure>
</div>
<div>
<figure>
  <img src="/Stevens_law.svg" style="width: 180px !important;">
</figure>
</div>
</div>
</div>
</div>

---

# Цветовые палитры: Viridis и Inferno

<div class="grid grid-cols-[5fr_5fr] gap-10">
<div>
<figure>
  <img src="/viridis.png" style="width: 510px !important;">
  <figcaption style="color:#b3b3b3ff; font-size: 11px; position: relative; top: 0px; left: 0px;">Источник изображения:<br>
  <a href="https://cran.r-project.org/web/packages/viridis/vignettes/intro-to-viridis.html">https://cran.r-project.org/web/packages/viridis/vignettes/intro-to-viridis.html</a>
  </figcaption>
</figure>
</div>
<div>
<figure>
  <img src="/infr1.jpg" style="width: 370px !important;">
  <figcaption style="color:#b3b3b3ff; font-size: 11px; position: relative; top: 0px; left: 0px;">Источник изображения:<br>
  <a href="https://www.geeksforgeeks.org/python/matplotlib-pyplot-inferno-in-python/">https://www.geeksforgeeks.org/python/matplotlib-pyplot-inferno-in-python/</a>
  </figcaption>
</figure>
</div>
</div>
<br>

* Монотонно изменяющаяся освещенность
  * Воспринимается равномерной

---
zoom: 0.97
---

# Цветовые каналы не полностью независимые

<div class="grid grid-cols-[5fr_4fr] gap-20">
<div>

* Взаимодействие цветовых каналов
  * Размер области сильно влияет на воспринимаемую насыщенность
      * Маленькие области требуют высокой насыщенности
      * Большие области нуждаются в низкой насыщенности

</div>
<div>
<br>
<figure>
  <img src="/HSL.svg" style="width: 480px !important;">
</figure>
</div>
</div>

* Насыщенность и освещенность:
  * неразделимы
  * также не отделимы от прозрачности
  * маленькие разделенные области: рекомендуется использовать 2 бина (либо насыщенность, либо освещенность, но не вместе), в крайнем случае < 3-4 бинов
  * смежные области: много бинов (используйте только один из этих каналов)

---

# Цветовые палитры

#### Существует множество цветовых палитр, которые можно применить для определенных типов признаков в различных задачах. Используйте [https://colorbrewer2.org](https://colorbrewer2.org)
<br>
<figure>
  <img src="/palette_choice.svg" style="width: 680px !important;">
<figcaption style="color:#b3b3b3ff; font-size: 11px; position: relative; top: -210px; left: 700px;">Источник изображения:<br>
  <a href="https://www.cs.ubc.ca/~tmm/vadbook/">Рис. 10.6. T. Munzner.<br> Visualization Analysis and Design (2014)</a>
  </figcaption>
</figure>

---

# Цветовые палитры: примеры

<figure>
  <img src="/palettes_example_10.11.png" style="width: 600px !important;">
</figure>
<br>
<figure>
  <img src="/palettes_example_10.12.png" style="width: 600px !important;">
<figcaption style="color:#b3b3b3ff; font-size: 11px; position: relative; top: -210px; left: 700px;">Источник изображениий:<br>
  <a href="https://www.cs.ubc.ca/~tmm/vadbook/">Рис. 10.11 и 10.12. T. Munzner.<br> Visualization Analysis and Design (2014)</a>
  </figcaption>
</figure>

---

# Одномерные цветовые палитры

<br>
<div class="grid grid-cols-[5fr_4fr] gap-20">
<div>

#### Признак:
* Расходящийся
  * Полезно, когда данные имеют отличимую "среднюю точку"
    * Используйте для неё нейтральный цвет
      * Белый, серый, иногда желтый
  * Используйте насыщенные цвета для крайних значений
* Последовательный
  * Кодируйте в освещенности или насыщенности

</div>
<div>
<br>
<figure>
  <img src="/diverging_and_sequential.png" style="width: 380px !important;">
  <figcaption style="color:#b3b3b3ff; font-size: 11px; position: relative; top: 10px; left: 0px;">Источник изображениий:<br>
  <a href="https://www.sciencedirect.com/science/article/abs/pii/B9780080424156500144">Cynthia A. Brewer, Color Use Guidelines for Mapping and Visualization (1994)</a>
  </figcaption>
</figure>
</div>
</div>

---
zoom: 0.9
---

# Выбор цветовой палитры

<br>
<div class="grid grid-cols-[5fr_4fr] gap-20">
<div>

#### Выбранная схема / палитра:
- сегментированная или непрерывная?
- расходящаяся, последовательная или циклическая?
- имеет один оттенок, два оттенка или много оттенков?
- линейная по восприятию?
- упорядочена по яркости?
- доступна для людей с нарушенным цветовосприятием?

</div>
<div>
<figure>
  <img src="/continuous_palettes.png" style="width: 320px !important;">
</figure>
</div>
</div>

<br>

#### См. также [https://observablehq.com/@d3/color-schemes?collection=@d3/d3-scale-chromatic](https://observablehq.com/@d3/color-schemes?collection=@d3/d3-scale-chromatic)
[https://seaborn.pydata.org/tutorial/color_palettes.html](https://seaborn.pydata.org/tutorial/color_palettes.html)

---

# Двумерные цветовые палитры

* Двумерные данные в цвете может быть очень сложно интерпретировать при наличии нескольких уровней в каждом направлении

<br>
<div class="grid grid-cols-[5fr_2fr] gap-10">
<div>
<figure>
  <img src="/palette_choice.svg" style="width: 650px !important;">
<figcaption style="color:#b3b3b3ff; font-size: 11px; position: relative; top: -210px; left: 700px;">Источник изображения:<br>
  <a href="https://www.cs.ubc.ca/~tmm/vadbook/">Рис. 10.6. T. Munzner.<br> Visualization Analysis and Design (2014)</a>
  </figcaption>
</figure>
</div>
<div>

#### Пример палитры: сочетание оттенка и насыщенности
<br>

<figure>
  <img src="/hue_saturation.png" style="width: 180px !important;">
</figure>
</div>
</div>

---

# Доступность для людей с нарушенным цветовосприятием

<br>
<div class="grid grid-cols-[5fr_4fr] gap-20">
<div>

* Подумайте о людях с нарушенным цветовосприятием
  * Или о людях без цветного принтера...
  * Используйте **избыточное кодирование**, чтобы люди могли интерпретировать ваши визуализации

</div>
<div>
<figure>
  <img src="/accessibility.png" style="width: 300px !important;">
  <figcaption style="color:#b3b3b3ff; font-size: 11px; position: relative; top: -50px; left: -400px;">Источник изображения:<br>
  Franconeri, Steven L. et al. “The Science of Visual Data Communication: What Works.” (2021)
  </figcaption>
</figure>
</div>
</div>


---

# Семантика цвета
<br>

<div class="grid grid-cols-[5fr_4fr] gap-20">
<div>

* Когда используется много цветов, нам трудно вспомнить абстрактные ассоциации
* Использование **семантики цвета** - хорошая идея *в теории*, но она работает лишь в ряде случаях
* Если вы собираетесь использовать цвет, постарайтесь подумать, как облегчить людям
расшифровку цвета без необходимости постоянно заглядывать в легенду
  * Так время декодирования будет меньше

</div>
<div>
<br>
<figure>
  <img src="/color_semantics.png" style="width: 380px !important;">
</figure>
</div>
</div>

<figure>
<figcaption style="color:#b3b3b3ff; font-size: 11px; position: relative; top: 10px; left: 0px;">Изображение: <a href="https://idl.cs.washington.edu/files/2013-SemanticColor-EuroVis.pdf">Sharon Lin, Julie Fortuna, Chinmay Kulkarni, Maureen Stone, Jeffrey Heer. Selecting Semantically-Resonant Colors for Data Visualization (2013)</a>
  </figcaption>
</figure>

---

# Цвет и культура

<div class="grid grid-cols-[3fr_4fr] gap-20">
<div>

#### "*Виноцветное море*" у Гомера

<figure>
  <img src="/IMG_1461.jpg" style="width: 380px !important;">
<figcaption style="color:#b3b3b3ff; font-size: 11px; position: relative; top: 5px; left: 0px;">о. Андипакси в Ионическом море (фото А.Б.)
  </figcaption>
</figure>

</div>
<div>
<v-click at="1">

#### Что, если цвет культурно обусловлен и связан с языком?
</v-click>
<br>
<v-click at="2">
<figure>
  <img src="/deutscher_4a.png" style="width: 380px !important;">
</figure>
</v-click>
<v-click at="3">
<figure>
  <img src="/deutscher_4b.png" style="width: 380px !important;">
</figure>
</v-click>
</div>
</div>

<figure>
<figcaption style="color:#b3b3b3ff; font-size: 11px; position: relative; top: 10px; left: 350px;">Источник: Гай Дойчер, Сквозь зеркало языка. Почему на других языках мир выглядит иначе (2010)
  </figcaption>
</figure>

---

# Цвет и культура

<div class="grid grid-cols-[3fr_4fr] gap-20">
<div>

<figure>
  <img src="/deutscher_1.png" style="width: 330px !important;">
</figure>
<br>
<figure>
  <img src="/deutscher_2.png" style="width: 380px !important;">
</figure>
</div>
<div>

<figure>
  <img src="/deutscher_6.png" style="width: 220px !important;">
</figure>
<br>
<figure>
  <img src="/deutscher_3.png" style="width: 260px !important;">
</figure>

</div>
</div>

<figure>
<figcaption style="color:#b3b3b3ff; font-size: 11px; position: relative; top: 25px; left: 350px;">Источник: Гай Дойчер, Сквозь зеркало языка. Почему на других языках мир выглядит иначе (2010)
  </figcaption>
</figure>


---

# Цвет и культура

<div class="grid grid-cols-[3fr_4fr] gap-20">
<div>

<figure>
  <img src="/Red-yellow-and-green-traffic-lights.jpg" style="width: 300px !important;">
</figure>
<br>
<v-click at="1">
<figure>
  <img src="/Red-yellow-and-blue-traffic-lights.jpg" style="width: 300px !important;">
</figure>
</v-click>
</div>
<div>
<v-click at="2">
<figure>
  <img src="/deutscher_5.png" style="width: 260px !important;">
  <figcaption style="color:#b3b3b3ff; font-size: 11px; position: relative; top: 55px; left: 0px;">Источники изображений:<br>
    <a href="https://tagan.mos.ru/presscenter/news/detail/5689481.html">https://tagan.mos.ru/presscenter/news/detail/5689481.html</a><br>
    <a href="https://japantravelplanning.com/japan-traffic-lights">https://japantravelplanning.com/japan-traffic-lights</a><br>
    Гай Дойчер, Сквозь зеркало языка. Почему на других языках мир выглядит иначе (2010)
  </figcaption>
</figure>
</v-click>
</div>
</div>
