---
title: Распространенные психологические заболевания
description: 
published: true
date: 2025-06-06T17:59:31.208Z
tags: медицинский
editor: markdown
dateCreated: 2024-09-29T18:19:41.899Z
---

<!-- partial:index.partial.html -->
  <div class="container2">
  <div id="score">
    <div class="timer">
      <button id="play-pause">
        <i id="play">Play</i>
        <i id="pause">Pause</i>
      </button>
      <label>Timer:</label>
      <span>00:00</span>
    </div>
    <div class="move-count" data-moves="0">
      <label>Moves:</label>
      <span>0</span>
    </div>
    <div class="score" data-score="0">
      <label>Score:</label>
      <span>0</span>
    </div>
  </div>
  <div id="table">
    <div class="upper-row">
      <div id="stock" class="stock pile" data-pile="stock">
        <i class="reload-icon" data-action="reload">
          <span></span>
        </i>
        <ul></ul>
      </div>
      <div id="waste" class="waste pile" data-pile="waste">
        <ul></ul>
      </div>
      <ul id="fnd" class="fnd">
        <li id="spades" class="spades pile" data-pile="spades" data-empty="true">
          <ul></ul>
        </li>
        <li id="hearts" class="hearts pile" data-pile="hearts" data-empty="true">
          <ul></ul>
        </li>
        <li id="diamonds" class="diamonds pile" data-pile="diamonds" data-empty="true">
          <ul></ul>
        </li>
        <li id="clubs" class="clubs pile" data-pile="clubs" data-empty="true">
          <ul></ul>
        </li>
      </ul>
    </div>
    <div class="lower-row">
      <ul id="tab" class="tab">
        <li class="pile" data-pile="1">
          <ul></ul>
        </li>
        <li class="pile" data-pile="2">
          <ul></ul>
        </li>
        <li class="pile" data-pile="3">
          <ul></ul>
        </li>
        <li class="pile" data-pile="4">
          <ul></ul>
        </li>
        <li class="pile" data-pile="5">
          <ul></ul>
        </li>
        <li class="pile" data-pile="6">
          <ul></ul>
        </li>
        <li class="pile" data-pile="7">
          <ul></ul>
        </li>
      </ul>
    </div>
  </div>
</div>
  <!-- /.container2 -->
  <button id="auto-win">Auto Win</button>
  <canvas id="confetti"></canvas>
  <ul class="template">
  <li data-rank="2">
    <div class="two {{suit}}">
      <div class="corner top">
        <span class="rank">2</span>
        <span class="suit"></span>
      </div>
      <span class="suit top_center"></span>
      <span class="suit bottom_center"></span>
      <div class="corner bottom">
        <span class="rank">2</span>
        <span class="suit"></span>
      </div>
    </div>
  </li>
  <li data-rank="3">
    <div class="three {{suit}}">
      <div class="corner top">
        <span class="rank">3</span>
        <span class="suit"></span>
      </div>
      <span class="suit top_center"></span>
      <span class="suit middle_center"></span>
      <span class="suit bottom_center"></span>
      <div class="corner bottom">
        <span class="rank">3</span>
        <span class="suit"></span>
      </div>
    </div>
  </li>
  <li data-rank="4">
    <div class="four {{suit}}">
      <div class="corner top">
        <span class="rank">4</span>
        <span class="suit"></span>
      </div>
      <span class="suit top_left"></span>
      <span class="suit top_right"></span>
      <span class="suit bottom_left"></span>
      <span class="suit bottom_right"></span>
      <div class="corner bottom">
        <span class="rank">4</span>
        <span class="suit"></span>
      </div>
    </div>
  </li>
  <li data-rank="5">
    <div class="five {{suit}}">
      <div class="corner top">
        <span class="rank">5</span>
        <span class="suit"></span>
      </div>
      <span class="suit top_left"></span>
      <span class="suit top_right"></span>
      <span class="suit middle_center"></span>
      <span class="suit bottom_left"></span>
      <span class="suit bottom_right"></span>
      <div class="corner bottom">
        <span class="rank">5</span>
        <span class="suit"></span>
      </div>
    </div>
  </li>
  <li data-rank="6">
    <div class="six {{suit}}">
      <div class="corner top">
        <span class="rank">6</span>
        <span class="suit"></span>
      </div>
      <span class="suit top_left"></span>
      <span class="suit top_right"></span>
      <span class="suit middle_left"></span>
      <span class="suit middle_right"></span>
      <span class="suit bottom_left"></span>
      <span class="suit bottom_right"></span>
      <div class="corner bottom">
        <span class="rank">6</span>
        <span class="suit"></span>
      </div>
    </div>
  </li>
  <li data-rank="7">
    <div class="seven {{suit}}">
      <div class="corner top">
        <span class="rank">7</span>
        <span class="suit"></span>
      </div>
      <span class="suit top_left"></span>
      <span class="suit top_right"></span>
      <span class="suit middle_left"></span>
      <span class="suit middle_top"></span>
      <span class="suit middle_right"></span>
      <span class="suit bottom_left"></span>
      <span class="suit bottom_right"></span>
      <div class="corner bottom">
        <span class="rank">7</span>
        <span class="suit"></span>
      </div>
    </div>
  </li>
  <li data-rank="8">
    <div class="eight {{suit}}">
      <div class="corner top">
        <span class="rank">8</span>
        <span class="suit"></span>
      </div>
      <span class="suit top_left"></span>
      <span class="suit top_right"></span>
      <span class="suit middle_left"></span>
      <span class="suit middle_top_center"></span>
      <span class="suit middle_right"></span>
      <span class="suit middle_bottom_center"></span>
      <span class="suit bottom_left"></span>
      <span class="suit bottom_right"></span>
      <div class="corner bottom">
        <span class="rank">8</span>
        <span class="suit"></span>
      </div>
    </div>
  </li>
  <li data-rank="9">
    <div class="nine {{suit}}">
      <div class="corner top">
        <span class="rank">9</span>
        <span class="suit"></span>
      </div>
      <span class="suit top_left"></span>
      <span class="suit top_right"></span>
      <span class="suit middle_top_left"></span>
      <span class="suit middle_center"></span>
      <span class="suit middle_top_right"></span>
      <span class="suit bottom_left"></span>
      <span class="suit bottom_right"></span>
      <span class="suit middle_bottom_left"></span>
      <span class="suit middle_bottom_right"></span>
      <div class="corner bottom">
        <span class="rank">9</span>
        <span class="suit"></span>
      </div>
    </div>
  </li>
  <li data-rank="10">
    <div class="ten {{suit}}">
      <div class="corner top">
        <span class="rank">10</span>
        <span class="suit"></span>
      </div>
      <span class="suit top_left"></span>
      <span class="suit top_right"></span>
      <span class="suit middle_top_left"></span>
      <span class="suit middle_top_center"></span>
      <span class="suit middle_top_right"></span>
      <span class="suit bottom_left"></span>
      <span class="suit bottom_right"></span>
      <span class="suit middle_bottom_center"></span>
      <span class="suit middle_bottom_left"></span>
      <span class="suit middle_bottom_right"></span>
      <div class="corner bottom">
        <span class="rank">10</span>
        <span class="suit"></span>
      </div>
    </div>
  </li>
  <li data-rank="J">
    <div class="jack {{suit}}">
      <div class="corner top">
        <span class="rank">J</span>
        <span class="suit"></span>
      </div>
      <span class="face middle_center"></span>
      <div class="corner bottom">
        <span class="rank">J</span>
        <span class="suit"></span>
      </div>
    </div>
  </li>
  <li data-rank="Q">
    <div class="queen {{suit}}">
      <div class="corner top">
        <span class="rank">Q</span>
        <span class="suit"></span>
      </div>
      <span class="face middle_center"></span>
      <div class="corner bottom">
        <span class="rank">Q</span>
        <span class="suit"></span>
      </div>
    </div>
  </li>
  <li data-rank="K">
    <div class="king {{suit}}">
      <div class="corner top">
        <span class="rank">K</span>
        <span class="suit"></span>
      </div>
      <span class="face middle_center"></span>
      <div class="corner bottom">
        <span class="rank">K</span>
        <span class="suit"></span>
      </div>
    </div>
  </li>
  <li data-rank="A">
    <div class="ace {{suit}}">
      <div class="corner top">
        <span class="rank">A</span>
        <span class="suit"></span>
      </div>
      <span class="suit middle_center"></span>
      <div class="corner bottom">
        <span class="rank">A</span>
        <span class="suit"></span>
      </div>
    </div>
  </li>
</ul>
  <!-- /.templates -->
  <!-- partial -->
<h2>Болезни</h2>
<h3><strong>Космическое Безумие</strong></h3>
<p><strong>Полное название: </strong>Шизоаффективное расстройство на почве обострения вакуумной болезни</p>
<p><strong>Проявления и развитие болезни:</strong></p>
<p>Пациент теряет способность адекватно воспринимать окружающую реальность, возможно, начиная верить, что он находится "в игре". В тяжелых случаях заболевание вызывает серьезные изменения личности. У человека формируется безразличие к своим обязанностям, собственной жизни и жизни окружающих. Он может проявлять агрессию, нарушать закон. В запущенных стадиях человек становится жестоким и способен на убийство ради собственного развлечения. Первые симптомы космического безумия можно заметить по несвязности речи. Пациент может задавать странные вопросы, употреблять слова или фразы невпопад, придумывать несуществующие слова.</p>
<p>Точной информации о заразности болезни нет. Риску подвержены люди, длительное время находящиеся в замкнутом пространстве, испытывающие стресс, подвергающиеся воздействию наркотических веществ, электромагнитного излучения или радиации. Исследования также выявили, что определенные психологические особенности часто служат почвой для развития заболевания.</p>
<p><strong>Лечение:</strong></p>
<p>В первую очередь, пациента следует изолировать от коллектива и провести тестирование для определения степени изменения личности. Часто требуется помощь квалифицированного психолога для восстановления адекватного восприятия реальности. В некоторых случаях эффективны медикаментозные препараты. В запущенных случаях применяется <s>избиение</s> электрошоковая терапия.</p>
<p><strong>На заметку:</strong></p>
<p>Это малоизученное и опасное заболевание. При появлении первых признаков необходимо срочно обратиться к охране или медицинскому персоналу. Если на станции будут выявлены случаи заболевания, важно документировать симптомы, поведение больного и применяемые методы лечения. Отчеты врачей в дальнейшем будут направлены в Центком для анализа и совершенствования лечения Космического безумия.</p>

<h3><strong>Космическая апатия</strong></h3>

<p><strong>Проявления и развитие болезни:</strong></p>
<p>Пациент перестает реагировать на внешние стимулы (даже такие сильные, как боль, холод или здравый смысл) и впадает в состояние апатии. Внешне напоминает аутизм или спячку у животных.</p>
<p>Информации о заразности и причинах возникновения заболевания нет. Болезнь может начаться спонтанно и, в некоторых случаях, так же спонтанно пройти, при этом пациент практически ничего не помнит о приступе.</p>
<p><strong>Лечение:</strong></p>
<p>На данный момент эффективного лечения не найдено. Не рекомендуется тревожить больного. Наблюдения показывают, что наибольший процент выздоровления наблюдается в тех случаях, когда пациента оставляли в покое в том же месте и положении, в котором его застал приступ. При длительном наблюдении рекомендуется поместить пациента в палату, комнату отдыха или криогенную капсулу дормитория.</p>

<h3><strong>Шизофрения</strong></h3>

<p><strong>Проявления и развитие болезни:</strong></p>
<p>Пациент, страдающий шизофренией, обычно имеет следующие симптомы: Утрата реальности - человек начинает слышать голоса в голове, чувствовать вкусы и запахи, которых на самом деле нет; Галлюцинации; Расстройства мышления - человек не может выразить свою мысль и путается в словах; Эмоциональные расстройства - резкая смена эмоций, аутизм, асоциальность; Изменения мимики - мимика человека становится менее выразительной.</p>
<p>Во время болезни человек проходит три стадии: Продромальная - человек начинает испытывать беспричинную тревогу; Манифестная - на данном этапе больной имеет яркие признаки психоза, такие как бред, галлюцинации и двигательное возбуждение; Остаточная - больной становится эмоционально холодным, апатичным, безразличным к происходящему вокруг.</p>
В итоге, без нужного лечения, у больного закрепляются стойкие глубокие нарушения мышления, снижение потребностей, апатия и равнодушие.

<p><strong>Лечение:</strong></p>
<p>Для начала больного следует изолировать от общества и поместить в отдельную палату, чтобы он не мог навредить другим пациентам. Обычно для лечения пациенту назначают психолога, антипсихотические препараты и мероприятия по социальной реабилитации. В процессе лечения нужно научить человека справляться с болезнью, контролировать поведение, эмоции и жить максимально полноценно, насколько позволяет расстройство, а также восстановить коммуникативные и социальные навыки.</p>
<p>В случаях, когда заболевание не поддаётся консервативному медикаментозному лечению, используют электросудорожную терапию (ЭСТ) и транскраниальную магнитную стимуляцию (ТМС).</p>

<h3><strong>Невроз</strong></h3>

<p><strong>Проявления и развитие болезни:</strong></p>
<p>Главным симптомом невроза является тревога. Больной испытывает <i>эмоциональную тревогу</i> - постоянные тревожные мысли, связанные с каким-либо событием в жизни, <i>физическую тревогу</i> - мышичные напряжения и невозможность расслабиться и <i>моторную тревогу</i> - неусидчисвоть, постоянные подёргивания ногами, необходимость постоянно двигаться.</p>

<p><strong>Лечение:</strong></p>
<p>Лечение невроза обычно комплексное и включает психотерапию и медикаментозную терапию. Также пациентам рекомендовано: ограничить физическую и психоэмоциональную нагрузку; чередовать режим труда и отдыха; получать положительные эмоции; сбалансированно питаться.</p>

<h3><strong>Афазия</strong></h3>

<p><strong>Проявления и развитие болезни:</strong></p>
<p>Обычно афазия проявляется вследствие инсульта, травмы головы или опухоли в мозгу, что приводит к повреждению нейрональных структур мозга.</p>
<p>Афазия делится на несколько видов: 
<ul>
  <li><i>Моторная</i> - нарушение способности произносить слова и фразы. Речь и смысл слов окружающих понимаются правильно;
  <li><i>Сенсорная</i> - нарушение понимания устной речи; 
  <li><i>Амнестическая</i> - больной забывает, как называются знакомые ему предметы;
  <li><i>Семантическая</i> - больному трудно понимать речь, если в ней используются сложные грамматические конструкции. Речь больного, как парвило, содержит только простые слова, а при попытке использовать сложные слова неизбежно появляются грамматические ошибки.
</ul>
</p>

<p><strong>Лечение:</strong></p>
<p>Лечение афазии должно начинаться сразу после травмы или инсульта. Чем раньше будет начато лечение, тем больше шансов избавиться от патологической симптоматики, не дав ей стать хронической.</p>
<p>Чтобы восстановить нормальную речь, пациент должен посещать специальные логопедические занятия.</p>

<h3><strong>Нозофилия</strong></h3>

<p><strong>Проявления и развитие психиатрического расстройства:</strong></p>
<p>Больные нозофилией люди стараются приписать себе какое-либо заболевание. Они начинают думать, что в организме имеется какое-то нарушение и посещая врачей старательно пытается доказать это, хотя этот человек более чем здоров.</p>
<p>Но это не значит, что не надо даже пытаться узнать, правда ли у этого человека какая-либо болезнь. Проверить его нужно обязательно, а в случае подтверждения отсутствия заболеваний - начать лечение нозофилии.</p>

<p><strong>Лечение:</strong></p>
<p>Основной метод лечения нозофилии - психотерапия. Психолог разбирается, почему человек боится болеть, и помогает рационализировать этот страх. При тяжёлом течении человеку с фобией назначают антидепрессанты и препараты, которые помогают бороться с тревожностью.</p>

<h3><strong>Психалгия</strong></h3>

<p><strong>Проявления и развитие синдрома:</strong></p>
<p>Мнимый болевой синдром обычно является последствием стрессовых ситуаций и может сопровождаться повышенной тревожностью и паническими атаками. Чаще всего подобные болевые ощущения возникают в области головы, спины, желудка и сердца. При этом пациенты не способны дать чёткую характеристику боли. 

  Причины психалгии: низкий уровень стрессоустойчивости, депрессия, неврозы, шизофрения, паническое расстройство, посттравматический синдром.</p>

<p><strong>Лечение:</strong></p>
<p>Лечение психалгии включает психотерапию, медикаментозную терапию (при необходимости), изменение образа жизни (упражнения, релаксация, сон, питание) и, в некоторых случаях, физиотерапию.</p>

<h3><strong>Мутизм</strong></h3>

<p><strong>Проявления и развитие расстройства:</strong></p>
<p>Мутизм - это расстройство, при котором человек не говорит в определенных социальных ситуациях, хотя в других он может говорить нормально.</p>
<p>Признаками расстройства обычно являются: молчание в конкретных социальных ситуациях, где ожидается речь; тревожность; застенчивость; социальная тревога; страх оценки; отказ от зрительного контакта; замкнутость; скованность.</p>

<p><strong>Лечение:</strong></p>
<p>Лечение избирательного мутизма включает когнитивно-поведенческую терапию, медикаментозное лечение при сильной тревожности и логопедическую помощь при нарушениях речи.</p>

<h2><strong>Синдромы</strong></h2>

<h3><strong>Бред величия</strong></h3>

> Бред величия на бытовом уровне называют "манией величия", поэтому это название будет использоваться, чтобы не было путаницы.
{.is-info}


<p><strong>Проявления синдрома:</strong></p>

<p>Мания величия – это не просто чрезмерная самоуверенность или тщеславие. Это психиатрический симптом, обычно связанный с определенными психическими расстройствами. Он характеризуется иррациональной и устойчивой верой человека в свои исключительные способности, талант, власть, богатство или значимость. Важно понимать, что люди с манией величия искренне верят в свои утверждения, даже если они явно не соответствуют реальности.</p>

<p>Мания величия чаще всего встречается при следующих психических расстройствах:
<ul>
  <li>Биполярное расстройство</li>
  <li>Шизофрения</li>
  <li>Бредовое расстройство</li>
  <li>Нарциссическое расстройство личности</li>
  <li>Органические поражения головного мозга</li>
  <li><i>Вещества</i></li>
</ul>
</p>

<p><strong>Лечение:</strong></p>
<p>Лечение мании величия направлено на устранение основного психического расстройства, которое вызывает этот симптом. Обычно используется комплексный подход, включающий в себя медикаментозная терапию, психотерапию, госпитализацию и реабилитацию.</p>

<h3><strong>Синдром Ван Гога</strong></h3>

> Название синдрома связано с именем земного голландского художника XIX века Винсента Ван Гога, который, по одной из версий, страдал хроническим психическим недугом.
{.is-info}

<p><strong>Проявления синдрома:</strong></p>
<p>Синдром Ван Гога — это нанесение психически больным человеком калечащего повреждения самому себе (отрезание части тела, нанесение глубоких порезов) или настойчивое требование произвести ему хирургическое вмешательство.
  Синдром обусловлен наличием <b>ипохондрического бреда</b>, <b>галлюцинаций</b>, <b>импульсивных влечений</b>. </p>

<p><strong>Лечение:</strong></p>
<p>Лечение должно быть индивидуальным, в зависимости от конкретных симптомов и диагноза. Основной метод лечения - <b>психотерапия</b>. Также, в зависимости от степени тяжести и решения психолога, назначается <b>медикаментозная терапия</b>.</p>

> Лекарства назначаются врачом-психиатром после оценки состояния пациента.
{.is-warning}


<h3><strong>Синдром Диогена</strong></h3>

<p><strong>Проявления синдрома:</strong></p>
<p></p>

<p><strong>Лечение:</strong></p>
<p></p>

<h3><strong>Синдром Дориана Грея</strong></h3>

<p><strong>Проявления синдрома:</strong></p>
<p></p>

<p><strong>Лечение:</strong></p>
<p></p>

<h3><strong>Синдром Котара</strong></h3>

<p><strong>Проявления синдрома:</strong></p>
<p></p>

<p><strong>Лечение:</strong></p>
<p></p>

<h3><strong>Синдром нарушенного сознания</strong></h3>

<p><strong>Проявления синдрома:</strong></p>
<p></p>

<p><strong>Лечение:</strong></p>
<p></p>

<h3><strong>Микропсия</strong></h3>

<p><strong>Проявления синдрома:</strong></p>
<p></p>

<p><strong>Лечение:</strong></p>
<p></p>

<h3><strong>Синдром Адели</strong></h3>

<p><strong>Проявления синдрома:</strong></p>
<p></p>

<p><strong>Лечение:</strong></p>
<p></p>

<h3><strong>Обсессивно-компульсивное расстройство</strong></h3>

<p><strong>Проявления синдрома:</strong></p>
<p></p>

<p><strong>Лечение:</strong></p>
<p></p>

<h2><strong>Расстройства личности</strong></h2>

<h3><strong></strong></h3>

<p><strong>Проявления расстройства:</strong></p>
<p></p>

<p><strong>Лечение:</strong></p>
<p></p>