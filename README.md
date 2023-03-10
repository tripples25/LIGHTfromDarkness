# LIGHTfromDarkness
## Отчетная работа по Проектному практикуму команды `LIGHTfromDarkness` в рамках разработки 3D игры на Unity в жанре научной фантастики.  

Над проектом работали:  
`Симаков Евгений Сергеевич`  
`Шамонин Филипп Николаевич`  
`Бабин Георгий Константинович`  
`Азеев Борис Михайлович`  

**LIGHTfromDarkness** – это инди-игра, в которой пользователи погрузятся в мрачную атмосферу будущего, столкнуться с неизвестными им технологиями и пройдут вместе с нами незабываемую историю о мире, погибающим из-за нас… отыграв свою роль от лица … и сделав свой собственный выбор.
По мере прохождения основной сюжетной линии, мы столкнёмся с принятием решений, влияющих на исход целой вселенной, ощутим себя в роли Арнольда Шварценеггера, поучаствовав в динамичных перестрелках и пройдем 11 сценарных эпизодов, проходя становление нашего протагониста…  


## Development/Разработка  

На данный момент проект находится в стадии разработки и происходит формирование требующихся игровых механик, которые состоят как из относительно “простых” решений на подобие: передвижение персонажа и его ограничение, механики “капсульного подъема”, отрисовки пола под персонажем, плавной регулировка звуковых эффектов… Так и из более уникальных фич, разработанных специально под наш сценарий:  

* **Динамическая генерация окружения вокруг персонажа** – это одна из них. Ее отличительная особенность заключается в том, что окружение вокруг персонажа изменяется в реальном времени в зависимости от требующихся нам настроек. К тому же она является абсолютно модифицируемой в плане удаления/добавления объектов с игровой сцены в любое время на карте (3d модели), расширению областей генерации окружения и других точечных настроек.  
Основывается данная система на теории вероятности, которая к слову, и была той самой нудной первой парой :l… И разделению области вокруг игрока на несколько игровых секторов. `by Boris A. M.`  

* **Искусственный интеллект противников** – следующая значимая механика проекта. Ее сущность основывается на дополнительных asset'ах Unity и NavMeshComponent'e, позволяющих управлять навигацией противников и высчитывать пути к цели. Благодаря данной системе и реализуется боевая сцена, в которой предполагается три состояния противников: патрулирования, погони и нападения, зависящих от удаленности от протагониста. `by Georgy B. K.`  

* **Отрисовка интерфейсов** – не менее важная часть игры, формирующая общую картину. Ее же реализация основывается на асинхронном подходе к загрузке сцен (фреймов) и динамичного эффекта “Печатной машинки” (loading…). К тому же, в рамках интерфейсов реализуются и базовые внутриигровые настройки. `by Evgenii S. S.`  

* **Диалоговая система** – базовая система, но крайне необходимая система в нашем случае, отвечающая за построения повествования истории. Ее же реализация отталкивается от временных интервалов между фразами и структурным разделением блоков на абзацы. `by Philipp S. N.`  

Касаемо графической части проекта, все немного сложнее. На данный момент за счет библиотек Unity и Blender`a реализовано несколько грубых формовок-моделей без ретопологии и цветовых карт.  


## Total/Заключение  

И обобщая уже проделанную работу, за отведенный временной интервал (1 семестр)  в рамках проекта, были выполнены несколько ключевых моментов, определяющих будущую жизнеспособность: задокументирована идея (а важнее сценарий и визуальный стиль проекта), более основательно изучены использующиеся технологии разработки участниками проекта (Unity, Blender), а так же, наиболее важным, стала реализация черновой версии первых 5-и эпизодов (I, II, III, IV, V)
