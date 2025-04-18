---
title: Газы
description: 
published: true
date: 2025-03-16T15:29:58.946Z
tags: инженерный, руководство, атмос
editor: markdown
dateCreated: 2024-09-28T09:40:05.422Z
---

<h1 id="основная-информация" class="toc-header"><a class="toc-anchor" href="#основная-информация">¶</a> Основная информация</h1>
<p>Все газы могут течь по различным трубам, найденным в игре. Газ всегда будет пытаться течь от более высокого давления к более низкому давлению. Если газа нет в трубе, канистре или баке, он будет в атмосфере и будет взаимодействовать с другими объектами.</p>
<p>Газ всегда будет пытаться выровнять давление. Например, если пустая канистра подключена к трубе, находящейся под давлением 4500 кПа, давление в канистре также будет составлять только 4500 кПа. Если к той же трубе подсоединить канистру под давлением 9000 кПа, газ будет вытекать из канистры до тех пор, пока не будет достигнуто одинаковое давление.</p>
<p>У вас есть возможность изменить внешний вид и название канистры для хранения, если она не заполнена газом, не закреплена и не заблокирована. Для этого щёлкните правой кнопкой мыши по канистре и выберите «Перекрасить». Затем перед вами появятся колёса с облаками канистр, выберите нужный цвет и немного подождите.</p>
<h1 id="устройства-работы-с-газами" class="toc-header"><a class="toc-anchor" href="#устройства-работы-с-газами">¶</a> Устройства работы с газами</h1>
<div style="overflow-x: auto;" class="biba">
  <table class="table">
    <tbody><tr>
      	<td>
          <a href="#anchor_pipe">
     	    <img src="/pipes/pipestraight.png">
          </a>
          <div class="text-under-image"> Труба </div>
      	</td>
      	<td>
          <a href="#anchor_pressure_pump">
     	    <img src="/pipes/pumppressure.png">
          </a>
          <div class="text-under-image"> Стандартный насос </div>
      	</td>
      	<td>
          <a href="#anchor_volume_pump">
     	    <img src="/pipes/pumpvolume.png">
          </a>
          <div class="text-under-image"> Объёмный насос </div>
      	</td>
      	<td>
          <a href="#anchor_valve">
     	    <img src="/pipes/pumpmanualvalve.png">
          </a>
          <div class="text-under-image"> Клапан </div>
      	</td>
    </tr>
    <tr>
      	<td>
          <a href="#anchor_mixer">
     	    <img src="/pipes/gasmixer.png">
          </a>
          <div class="text-under-image"> Смеситель </div>
      	</td>
      	<td>
          <a href="#anchor_filter">
     	    <img src="/pipes/gasfilter.png">
          </a>
          <div class="text-under-image"> Фильтр </div>
      	</td>
      	<td>
          <a href="#anchor_vent">
     	    <img src="/pipes/vent_off.png">
          </a>
          <div class="text-under-image"> Вентиляция </div>
      	</td>
      	<td>
          <a href="#anchor_scrubber">
     	    <img src="/pipes/scrub_off.png">
          </a>
          <div class="text-under-image"> Скруббер </div>
      	</td>
    </tr>
    <tr>
      	<td>
          <a href="#anchor_pneumatic_valve">
     	    <img src="/pipes/pneumaticvalve.png">
          </a>
          <div class="text-under-image"> Пневматический клапан </div>
      	</td>
      	<td>
          <a href="#anchor_port">
     	    <img src="/pipes/gascanisterport.png">
          </a>
          <div class="text-under-image"> Порт </div>
      	</td>
      	<td>
          <a href="#anchor_canister">
     	    <img src="/pipes/canister.png">
          </a>
          <div class="text-under-image"> Канистра </div>
      	</td>
      	<td>
          <a href="#anchor_gasminer">
     	    <img src="/pipes/gasminer.png">
          </a>
          <div class="text-under-image"> Газодобытчик </div>
      	</td>
    </tr>
    <tr>
      	<td colspan="2">
          <a href="#anchor_radiator">
     	    <img src="/pipes/hestraight.png">
          </a>
          <div class="text-under-image"> Радиатор </div>
      	</td>
      	<td colspan="2">
          <a href="#anchor_condenser">
     	    <img src="/pipes/condenser.png">
          </a>
          <div class="text-under-image"> Конденсатор </div>
      	</td>
    </tr>
  </tbody></table>
</div>
<p>Если трубы под давлением открутить, они выбросят все свое содержимое в окружающую атмосферу и, в зависимости от уровня давления, с силой сдуют пользователя с гаечным ключом. Вы поймете, что откручиваете находящуюся под давлением трубу, если получите сообщение, в котором говорится: <em>«Поток воздуха дует вам в лицо... Может быть, вам стоит передумать?»</em> Хорошей практикой является всегда использовать газоанализатор на каждой трубе перед откручиванием, чтобы убедиться, что давление в ней сброшено.</p>
<p>Все трубы можно открутить, чтобы отсоединить их от других. Используя сварочный аппарат на отвинченном сегменте трубы, вы можете разобрать его на сталь.</p>
<p>Сломанный или неподсоединенный сегмент трубы НЕ ПРОПУСКАЕТ газ. Не беспокойтесь о том, что весь ваш газ выйдет из сломанного или неподсоединенного сегмента трубы.</p>
<p>Для работы большинства насосов, миксеров и фильтров не требуется питание. Только вентиляционные отверстия и скрубберы требуют питания. Вы можете щелкнуть по сегменту, удерживая клавишу ⇧ Shift, чтобы проверить, включен ли он.</p>
<h2 id="трубы" class="toc-header"><a class="toc-anchor" href="#трубы">¶</a> Трубы</h2>
<p id="anchor_pipe">Позволяет газу свободно проходить. Есть 4 вида трубы: </p>
<div class="table-container"><table>
<thead>
<tr>
<th><strong>Картинка</strong></th>
<th><strong>Название</strong></th>
<th><strong>Описание</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td><img src="/pipes/pipestraight.png" alt=""></td>
<td>Прямая труба</td>
<td>Прямой сегмент трубы.</td>
</tr>
<tr>
<td><img src="/pipes/pipebend.png" alt=""></td>
<td>Угловая труба</td>
<td>Угловой сегмент трубы.</td>
</tr>
<tr>
<td><img src="/pipes/pipetjunction.png" alt=""></td>
<td>Т-образная труба</td>
<td>Сегмент трубы с 3 путями.</td>
</tr>
<tr>
<td><img src="/pipes/pipefourway.png" alt=""></td>
<td>Четверная труба</td>
<td>Сегмент трубы с 4 путями.</td>
</tr>
</tbody>
</table></div>
<h2 id="насосы" class="toc-header"><a class="toc-anchor" href="#насосы">¶</a> Насосы</h2>
<p>Перекачивает газ на другую сторону в зависимости от заданного давления. Блокирует прохождение газа, если отключён. В игре есть два вида:</p>
<h3 id="стандартный-насос" class="toc-header"><a class="toc-anchor" href="#стандартный-насос">¶</a> Стандартный насос</h3>
<img src="/pipes/pumppressure.png" class="deviceFour" id="anchor_pressure_pump">
<p><img src="/pipes/pumppressureui.png" alt=""></p>
<p>Стандартный газовый насос. Перекачивает газ за счет внутреннего и внешнего давления. Имеет максимальную пропускную способность <strong>4,5 МПа</strong>. В основном используется в качестве клапана, позволяющего/запрещающего перетекание газа из одной трубы в другую. Очень хорошо работает в трубах высокого давления, но теряет эффективность при более низком давлении. Обычные газовые насосы более эффективны в системах с более низким давлением, но теряют эффективность по мере увеличения объема газа.</p>
<p>При более низком давлении газовый насос, как правило, является лучшим вариантом для перемещения газа.</p>
<h3 id="объемный-насос" class="toc-header"><a class="toc-anchor" href="#объемный-насос">¶</a> Объемный насос</h3>
<img src="/pipes/pumpvolume.png" class="deviceFour" id="anchor_volume_pump">
<p><img src="/pipes/pumpvolumeui.png" alt=""></p>
<p>Перекачивает газ в зависимости от количества внутренних и внешних молей. Имеет максимальную пропускную способность <strong>200 л/с</strong>. Действует точно так же, как газовый насос, но работает от количества молей, а не от давления. может перекачивать примерно в два раза больше газа по сравнению с обычным газовым насосом, если условия подходящие.</p>
<p>Для труб с чрезвычайно высоким давлением объемный насос, как правило, является лучшим вариантом для перемещения газа.</p>
<p>В некоторых случаях объемные насосы также лучше, если вы используете большое количество газа.</p>
<h2 id="клапаны" class="toc-header"><a class="toc-anchor" href="#клапаны">¶</a> Клапаны</h2>
<p id="anchor_valve">Действует как переключатель, который либо пропускает газ, либо препятствует его прохождению. Можно включать и выключать. Сбоку имеются фонари, показывающие, включен ли клапан. Красный - выключен, зелёный - включён. </p>
<div class="table-container"><table>
<thead>
<tr>
<th><strong>Картинка</strong></th>
<th><strong>Название</strong></th>
<th><strong>Описание</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td><img src="/pipes/pumpmanualvalve.png" alt=""></td>
<td>Ручной клапан</td>
<td>Можно открывать и закрывать рукой.</td>
</tr>
<tr>
<td><img src="/pipes/pumpsignalvalve.png" alt=""></td>
<td>Сигнальный клапан</td>
<td>Можно включать и выключать путём присоединения его конфигуратором сетей к любому раздатчику сигналов. (К примеру кнопка, или передатчик сигналов).</td>
</tr>
</tbody>
</table></div>
<h2 id="газовый-смеситель" class="toc-header"><a class="toc-anchor" href="#газовый-смеситель">¶</a> Газовый Смеситель</h2>
<img src="/pipes/gasmixer.png" class="deviceFour" id="anchor_mixer">
<p><img src="/pipes/gasmixerui.png" alt=""></p>
<p>Газовый смеситель — это причудливая версия газового насоса. Он позволяет объединить газовый поток двух разных труб и смешать их в одну трубу. Газосмеситель объединит содержимое двух разных труб и даст вам возможность установить процент пропускной способности, который вы хотите для каждой из входных труб. Основной порт будет параллелен выходу, а боковой порт будет перпендикулярен.</p>
<p>Газосмесители необходимы для дистрибутива, так как атмосфера станции состоит на <strong>20%</strong> из кислорода и на <strong>80%</strong> из азота. Газосмесители также используются для комбинирования двух разных газов для создания нового газа, такого как обычная горючая смесь.</p>
<p>Если газовый смеситель выключен, он не пропускает газ.</p>
<p>Если оба входа настроены на прием газа, то для работы насоса через оба входа должен проходить газ. Например, если смеситель настроен на смешивание газа в соотношении <strong>80</strong> к <strong>20</strong>, а во входной трубе при <strong>20&nbsp;%</strong> газа нет, то смеситель не пропустит входную трубу с <strong>80&nbsp;%</strong> газа, и наоборот.</p>
<h2 id="газовый-фильтр" class="toc-header"><a class="toc-anchor" href="#газовый-фильтр">¶</a> Газовый фильтр</h2>
<img src="/pipes/gasfilter.png" class="deviceFour" id="anchor_filter">
<p><img src="/pipes/gasfilterui.png" alt=""></p>
<p><strong>Газовые фильтры</strong> - еще один особый тип газового насоса. Газовые фильтры в основном используются для извлечения определенного типа газа из трубы. Они работают аналогично газовому смесителю, за исключением того, что у них есть один входной порт и два выходных порта. Когда газ проходит через смеситель, выбранный для фильтрации газ выходит через перпендикулярный выпускной порт, в то время как все остальные газы продолжают течь через параллельный выпускной порт. Если вы хотите отфильтровать более одного газа, вам необходимо установить газовые фильтры последовательно для каждого конкретного газа.</p>
<p>Газовые фильтры используются для извлечения каждого отдельного газа из петли отходов. Это гарантирует, что в каждом конкретном резервуаре для хранения газа присутствует только один тип газа. Газовые фильтры необходимы, когда вы пытаетесь найти и изолировать определенный газ.</p>
<p>Для работы газовых фильтров не требуется подключение обоих выходов, если для фильтрации не выбран газ или отфильтрованный газ отсутствует. В этом случае фильтр будет действовать как простой прямой отрезок трубы. Однако фильтр не будет пропускать газ, если выбранный газ присутствует и к перпендикулярному отверстию фильтра не подключена труба.</p>
<h2 id="вентиляция" class="toc-header"><a class="toc-anchor" href="#вентиляция">¶</a> Вентиляция</h2>
<img src="/pipes/vent_off.png" class="deviceFour" id="anchor_vent">
<p>Вентиляция бывает трех видов: стандартная, двухпортовая и пассивная.</p>
<p>Все Вентиляции используются исключительно для перемещения газа из труб в окружающую атмосферу. Они обычно используются в сочетании с распределительным трубопроводом для подачи пригодного для дыхания воздуха на станцию. За пополнение атмосферы на станции отвечают вентиляции и дистрибутив.</p>
<p>Стандартая Вентиляция пропускает только максимальное давление <strong>101,3 кПа</strong>. Если внешнее давление выше предела, газ не будет выходить из вентиляционного отверстия. Требует энергию для работы.</p>
<p>Двухпортовая Вентиляция аналогична стандартной, но имеет два впускных порта.</p>
<p>Пассивная вентиляция не требует питания и позволяет любому давлению течь в «обоих» направлениях в зависимости от внутреннего и внешнего давления. Если внутреннее давление или давление в трубе выше, чем внешняя или внешняя атмосфера, газ будет вытекать. Верное и обратно, если внешнее давление выше, чем внутреннее давление, то газ будет уходить в вентиляцию. Пассивные вентиляционные отверстия в основном используются в смесительном баке и камере Суперматерии, где требуется очень высокое давление.</p>
<h2 id="скруббер" class="toc-header"><a class="toc-anchor" href="#скруббер">¶</a> Скруббер</h2>
<img src="/pipes/scrub_off.png" class="deviceFour" id="anchor_scrubber">
<p>Скрубберы воздуха медленно высасывают газ из окружающей атмосферы, и их можно найти разбросанными по всей станции. В основном используемые в газопроводе отходов, воздушные скрубберы будут откачивать газ из атмосферы и направлять его по трубам отходов, где газ затем будет рециркулироваться и фильтроваться в камерах хранения газов.</p>
<p><em>Для работы скрубберы должны быть запитаны и подключены к выходному отверстию. Правильно работающий очиститель воздуха будет светиться синим цветом.</em></p>
<h2 id="инжектор" class="toc-header"><a class="toc-anchor" href="#инжектор">¶</a> Инжектор</h2>
<img src="/pipes/injector.png" class="deviceFour">
<p>Воздушные форсунки имеют одну цель. Они просто существуют только для того, чтобы позволить газу течь из трубы под давлением в окружающую атмосферу. Этот удобный маленький инструмент полезен, когда вы хотите ввести газ в область, но не допустить обратного потока. обычно используется с комбинацией фильтр/инжектор, чтобы выделить определенный газ и закачать его в камеру удержания.</p>
<p>Воздушные форсунки имеют максимальное выходное давление <strong>9000 кПа</strong>.</p>
<h2 id="пневматический-клапан" class="toc-header"><a class="toc-anchor" href="#пневматический-клапан">¶</a> Пневматический Клапан</h2>
<img src="/pipes/pneumaticvalve.png" class="deviceFour" id="anchor_pneumatic_valve">
<p>Пневматические клапаны имеют три порта: <strong>управляющий</strong>, <strong>впускной</strong> и <strong>выпускной</strong>. Подобно ручным клапанам, пневматические клапаны допускают двунаправленный поток между входом и выходом, но только в том случае, если давление в порте управления достаточно высокое.</p>
<p>Для включения пневматического клапана управляющее давление должно быть как минимум на 1 атм выше самого низкого давления, подключенного к пневматическому клапану, т. е. меньшего из входного и выходного давления. Направление потока между входом и выходом – от более высокого давления к более низкому.</p>
<p>Предел расхода пневматического значения линейный (пропорциональный управляющему давлению) в небольшой области выше порога включения. Затем он насыщается со скоростью 200 л/сек.</p>
<h3 id="примеры-работы" class="toc-header"><a class="toc-anchor" href="#примеры-работы">¶</a> Примеры Работы</h3>
<p><strong>Клапан сброса давления</strong></p>
<p><img src="/pipes/300px-pressure_relief_system(rus).png" alt=""></p>
<p>Эта система сброса давления сбрасывает воздух внутри в космос, если давление превышает 1 атм, что можно использовать для защиты от случайных случаев избыточного давления на станции. Пассивная вентиляция внутри (1) соединена с регулятором и входом. Другой пассивный вентиль в космосе (2) соединен с выпускным отверстием. Поскольку давление на выходе равно 0 кПа, то пневматический клапан будет включен только в том случае, если внутреннее давление превысит 1 атм. При этом воздух изнутри переносится в космос до тех пор, пока внутреннее давление не станет равным 1 атм.</p>
<h3 id="если-вам-всё-ещё-не-понятно" class="toc-header"><a class="toc-anchor" href="#если-вам-всё-ещё-не-понятно">¶</a> Если вам всё ещё не понятно</h3>
<p>Как работает пневматический Клапан <a href="https://github.com/space-wizards/space-station-14/pull/10520" class="is-external-link">atmos turing-complete</a>.</p>
<h2 id="соединительный-порт" class="toc-header"><a class="toc-anchor" href="#соединительный-порт">¶</a> Соединительный Порт</h2>
<img src="/pipes/gascanisterport.png" class="device" id="anchor_port">
<p>Соединительные порты используются для передачи газа из трубы в канистру и наоборот. Прикрутите канистру, или переносной скруббер к порту гаечным ключом, чтобы соединить их. Подключенная канистра позволит газу течь до тех пор, пока давление не выровняется.</p>
<h2 id="канистры" class="toc-header"><a class="toc-anchor" href="#канистры">¶</a> Канистры</h2>
<img src="/pipes/canister.png" class="device" id="anchor_canister">
<p><img src="/pipes/canisterui.png" alt=""></p>
<p>Канистры используются для хранения и транспортировки газа. Перетащите канистру к порту разъема и используйте гаечный ключ, чтобы подключить ее. Если внутреннее давление порта соединителя выше, чем давление в канистре, газ будет поступать в неё до тех пор, пока давление не выровняется.</p>
<p>Если канистра имеет более высокое давление, газ будет вытекать до тех пор, пока разница давлений не выровняется. Канистры могут выпускать газ по-разному в зависимости от ситуации. Газ будет вытекать только в том случае, если выпускной клапан открыт. Если давление выпускного клапана ниже, чем внешнее давление, газ не будет выходить.</p>
<ul>
<li>Если канистра привинчена к порту соединителя, газ будет поступать в порт соединителя.</li>
<li>Если баллон с кислородом вставлен в канистру, газ будет поступать в баллон с кислородом.</li>
<li>Если канистра ни к чему не подключена, газ будет вытекать в окружающую атмосферу.</li>
</ul>
<h2 id="газодобытчик" class="toc-header"><a class="toc-anchor" href="#газодобытчик">¶</a> Газодобытчик</h2>
<img src="/pipes/gasminer.png" class="device" id="anchor_gasminer">
<p>Газодобытчики создают новый газ из ничего и в настоящее время используются для обеспечения бесконечного количества определенного газа на станции. Газодобытчики бывают разных типов и создают разные типы газа. Газодобытчик Кислорода будет создавать газообразный кислород, а Газодобытчик Плазмы будет создавать плазменный газ. Газодобытчики можно найти в Атмосии внутри каждой камеры хранения газа.</p>
<h2 id="радиатор" class="toc-header"><a class="toc-anchor" href="#радиатор">¶</a> Радиатор</h2>
<img src="/pipes/hestraight.png" class="deviceFour" id="anchor_radiator"><div>
Осуществляет обмен температур между газом внутри него и атмосферой, в которой он находится. Можно использовать для нагрева газа в камере сгорания, или для охлаждения его в космосе.
</div><h2 id="конденсатор" class="toc-header"><a class="toc-anchor" href="#конденсатор">¶</a> Конденсатор</h2>
<img src="/pipes/condenser.png" class="device" id="anchor_condenser"><div>
При подведении к нему газа будет превращать его в жидкость и наполнять свой резервуар. Затем, жидкость можно собрать с помощью мензурки.
</div><h1 id="датчик-воздушной-тревоги" class="toc-header"><a class="toc-anchor" href="#датчик-воздушной-тревоги">¶</a> Датчик воздушной тревоги</h1>
<p>Используется для настройки устройств, таких как скрубберы и вентиляции, а также проверки состояния атмосферы рядом с ним.</p>
<p><img src="/pipes/air-alarm.png" alt="airalarmtopui.png"></p>
<ul>
<li>Зелёная секция - состояние атмосферы у воздушной сигнализации. Если написано "Normal" - атмосфера благоприятна для живых существ.</li>
<li>Желтая секция - адрес самой воздушной сигнализации и количество устройств, подключенных к ней. Кнопка "Ресинхр" используется для обновления количества устройств.</li>
<li>Красная секция - настройки разных типов устройств.</li>
</ul>
<h3 id="настройка-вентиляций" class="toc-header"><a class="toc-anchor" href="#настройка-вентиляций">¶</a> Настройка вентиляций</h3>
<p><img src="/pipes/airalarmventuinew.png" alt="airalarmventui.png"></p>
<ul>
<li>Красная секция - название устройства и статус его работы. Название также можно увидеть, осмотрев устройство, чтобы точно удостовериться, что вы работаете с нужным вам оборудованием. Если снять галочку, то можно выключить устройство.</li>
<li>Синяя секция - направление работы вентиляции. Releasing выпускает газ, Siphoning засасывает.</li>
<li>Зелёная секция ограничивает работу вентиляции по давлению. При пересечении границ работа устройства будет остановлена. NoBound - Ни одна граница не будет воздействовать на работу вентиляции. External Bound - работа остановится только при пересечении внешней границы, Internal Bound - только по внутренней границе. Both - по обеим границам.</li>
</ul>
<h3 id="настройка-скрубберов" class="toc-header"><a class="toc-anchor" href="#настройка-скрубберов">¶</a> Настройка скрубберов</h3>
<p><img src="/pipes/airalarmscrubuinew.png" alt="airalarmscrubui.png"></p>
<ul>
<li>Красная секция - название устройства и статус его работы. Название также можно увидеть, осмотрев устройство, чтобы точно удостовериться, что вы работаете с нужным вам оборудованием. Если снять галочку, то можно выключить устройство.</li>
<li>Синяя секция - режим работы вентиляции. Scrubbing - обычный режим работы, полностью зависит от остальных настроек. Siphoning будет засасывать все газы, вне зависимостри от фильтра, в радиусе три на три тайла.</li>
<li>Зелёная секция - обьем закачиваемого скруббером газа. Влияет на скорость его работы.</li>
<li>Жёлтая секция - радиус работы скруббера. При включенной широкой сети он работает в радиусе 3х3, при выключенном - 1х1.</li>
<li>Белая секция - газовые фильтры. Скруббер будет засасывать лишь газы, выделенные чёрным цветом.</li>
</ul>
<h3 id="режимы" class="toc-header"><a class="toc-anchor" href="#режимы">¶</a> Режимы</h3>
<p><img src="/pipes/airalarmdownui.png" alt="airalarmdownui.png"><br>
Режимы - предустановки работы устройств. При включенном авто режиме, воздушная сигнализация будет автоматически ставить режим в зависимости от атмосферы.</p>
<h3 id="сенсры" class="toc-header"><a class="toc-anchor" href="#сенсры">¶</a> Сенсры</h3>
<p>Сенсор показывает данные об атмосфере, в которой он находится. Сенсор есть как отдельное устройство, так и в вентиляциях и скрубберах.</p>
<h1 id="термоэлектрический-генератор" class="toc-header"><a class="toc-anchor" href="#термоэлектрический-генератор">¶</a> Термоэлектрический генератор</h1>
<center>
<img src="/pipes/tegfull.png" class="teg">
</center>
<p>Термоэлектрический генератор, или ТЭГ генерирует электричество из высокой температуры газов. Для его работы требуется сам генератор  и два циркулятора по его бокам. Генератор выводит энергию через высоковольтный провод, который следует поставить под ним. Для начала его работы требуется подать газы с разными температурами в левый и правый циркуляторы. При осмотре циркулятора, используя меню на <kbd>ПКМ</kbd>, или <kbd>Shift+ЛКМ</kbd> по нему, будут видны синие стрелки, указывающие, в каком направлении следует подавать по нему газ. Обратите внимание, что чем больше разница в температурах подаваемых вами газов, тем больше энергии будет вырабатывать ТЭГ.</p>
<h1 id="базовые-газы" class="toc-header"><a class="toc-anchor" href="#базовые-газы">¶</a> Базовые газы</h1>
<div class="table-container"><table>
<thead>
<tr>
<th>Картинка</th>
<th>Название</th>
<th>Синтез</th>
<th>Воздействие при вдыхании</th>
<th>Цена в кредитах за моль</th>
<th>Внешний вид</th>
<th>Прочее</th>
</tr>
</thead>
<tbody>
<tr>
<td><center><img src="/pipes/blue.png" class="canister"></center></td>
<td>Кислород (O2)</td>
<td>Является одним из побочных продуктов <a href="/guides/supermatter" class="is-internal-link is-valid-page">суперматерии</a>, при поглощении ею газа. На станции присутствует его газодобытчик.</td>
<td>Необходим для дыхания всех живых существ, кроме слаймолюдов.</td>
<td>0</td>
<td>Не имеет</td>
<td>При его наличии в атмосфере возможно возгарание некоторых газов при достижении их температуры горения. Является частью микса для дыхания на станции (20% Кислорода на 80% Азота).</td>
</tr>
<tr>
<td><center><img src="/pipes/red.png" class="canister"></center></td>
<td>Азот (N2)</td>
<td>На станции присутствует его газодобытчик.</td>
<td>Необходим для дыхания слаймолюдов.</td>
<td>0</td>
<td>Не имеет</td>
<td>Так как не способствует возгоранию, находится в лёгком доступе на станции и имеет относительно высокую теплоёмкость, является одним из самых безопасных газов, используемых в охлаждении <a href="/guides/supermatter" class="is-internal-link is-valid-page">суперматерии</a>. Является частью микса для дыхания на станции (20% Кислорода на 80% Азота).</td>
</tr>
<tr>
<td><center><img src="/pipes/black.png" class="canister"></center></td>
<td>Углекислый газ (CO2, Диоксид углерода)</td>
<td>Является побочным продуктом реакции горения, на станции присутствует его газодобытчик.</td>
<td>Крайне ядовит для вдыхания живыми существами, кроме дион, для которых он может послужить заменой кислорода.</td>
<td>0</td>
<td>Не имеет</td>
<td>Отсутствует</td>
</tr>
<tr>
<td><center><img src="/pipes/orange.png" class="canister"></center></td>
<td>Плазма</td>
<td>Является одним из побочных продуктов <a href="/guides/supermatter" class="is-internal-link is-valid-page">суперматерии</a>.</td>
<td>Крайне ядовит для вдыхания живыми существами.</td>
<td>1,5</td>
<td>Розовый пар</td>
<td>Единственное вещество, которое можно добыть на станции во всех трёх агреганых состояниях. В среде с кислородом, при достижении определенных температур, может воспламеняться.</td>
</tr>
<tr>
<td><center><img src="/pipes/redws.png" class="canister"></center></td>
<td>Оксид азота (N2O)</td>
<td>Является побочным продуктом некоторых реакций.</td>
<td>Усыпляет вдыхающих его существ.</td>
<td>2,5</td>
<td>Не имеет</td>
<td>Отсутствует</td>
</tr>
<tr>
<td><center><img src="/pipes/water_vapor.png" class="canister"></center></td>
<td>Водяной пар</td>
<td>Является побочным продуктом некоторых реакций. На станции присутствует его газодобытчик.</td>
<td>Не имеет</td>
<td>0</td>
<td>Серый пар</td>
<td>Отсутствует</td>
</tr>
<tr>
<td><center><img src="/pipes/greenys.png" class="canister"></center></td>
<td>Аммония</td>
<td>Появляется в результате гниения чего-либо, а также с помощью способности <a href="/roles/ratking" class="is-internal-link is-valid-page">крысинного короля</a>.</td>
<td>Отравляет всех существ, кроме крыс, которых он лечит.</td>
<td>0,15</td>
<td>Тёмно-фиолетовый пар</td>
<td>Отсутствует</td>
</tr>
<tr>
<td><center><img src="/pipes/antinoblium.png" class="canister"></center></td>
<td>Анти-ноблиум</td>
<td>Рецепта для синтеза нет.</td>
<td>Не имеет.</td>
<td>2,5</td>
<td>Черный рой мошек</td>
<td>Отсутствует</td>
</tr>
<tr>
<td><center><img src="/pipes/geliy.png" class="canister"></center></td>
<td>Гелий</td>
<td>Рецепта для синтеза нет.</td>
<td>Не имеет</td>
<td>7</td>
<td>Не имеет</td>
<td>Отсутствует</td>
</tr>
<tr>
<td><center><img src="/pipes/galon.png" class="canister"></center></td>
<td>Галон</td>
<td>Рецепта для синтеза нет.</td>
<td>Не имеет</td>
<td>8</td>
<td>Сине-серый пар</td>
<td>При высокой температуре поглащает тепло и кислород, предотвращая тем самым горение.</td>
</tr>
</tbody>
</table></div>