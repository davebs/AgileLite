# Agile Lite: Agile без перегрева

"Agile разработка программного обеспечения" это отличная идея, котороая в итоге была переусложненна умными дядьками из мира таймменеджемента и консалтинговых услуг. Представленный в данной статье подход `Agile Lite` призван упростить ситуацию. Вам не нужны книги или семинары чтобы понять что такое `Agile Lite`. Вам достаточно иметь текстовый файл с несколькими параграфами описывающими этот подход. Это и есть этот текстовый файл.

`Agile Lite` очень прост. Он может быть применен к любому проекту с людьми работающими над ним в команде, и если эта работа может быть разбита на мелкие компоненты (таски), которые в дальнейшем мы будем называть задачами (Issues). Как и другие Agile методологии `Agile Lite` использует короткие циклы разработки именуемые `Спринты` (Sprints). Что уникально в данном подходе, дак это то, что `Agile Lite` учитывает тенденцию команды к выгоранию при усиленной работе над проектом и призвана уменьшить или даже исключить данный фактор путем разбиения цикла разработки на **3-х недельный период спринта и 1-но недельный период разгрузки** для для команды (**3 weeks on/1 week off**).


Базовое использование методологии состоит в следующем:

* Первая неделя каждого цикла тратится на работу проджект-менеджеров и владельцев проекта на выработку предстоящего `спринта`. В независимости от того что на это выделена неделя, сессия планирование спринта не должно занимать более 2 часов в день, а вообще в идеале достаточно 45 минут в день. Эта неделя разгруки и в течении нее команда может просто отдыхать, занимаясь различной интересной ей работой, например своими хобби-проектами, самообучением и т.д., в общем, по максимуму расслабляться в эту неделю.

* Далее начинается период 3-х недельного цикла спринта. В этот период разработчики работают над Задачами (Issues), которые были определены в первой неделе на сессиях планирования. Т.к. команда может быть удаленной и распределенной по часовым зонам, то живые митинги проводятся не часто и в основном вся коммуникация происходит через систему трекинга задач (issue tracking system), т.к. это более быстрый способ общения нежели по e-mail. Системой трекинга в данном случае может выступать Trello, не используйте для этого эксель таблицы гуглдокс, они для этого не годятся. Ежедневные стендапы не приветствуются; текущее состояние хода работы можно смотреть в системе трекинга тасков по мере обновления статусов задач разработчиками.

* Как только начался период спринта, новые задачи не могут быть добавлены в текущий спринт, но они могут удалятся. Тем самым мы уменьшаем переключение между контектами у разработчиков и не нарушаем их текущий поток (flow) - не отвлекаем их от решения текущего потока задач, что есть хорошо.

----
* Issues that are not completed during the sprint are reviewed at the next sprint planning session and it's decided whether to move the Issue forward into the next sprint, put it back in the Backlog, or reassign it to a different developer.

* An issue is either in the `backlog` or in the `current sprint`.

* As mentioned, developers are encouraged to take the planning week off to allow their brain to recover from the previous sprint. There are no death marches. Developers don't work on the weekends. This all helps avoid burnout. Avoiding burnout is good for everyone.

That's pretty much it. The system doesn't really prescribe engineering practices and I think that's ok. Engineering practices can be defined at a per project level.

Support work is done on a rotating basis because sometimes things do happen unexpectedly and need to be dealt with, but a surprising number of issues can wait until later.

Agile Lite is a better, more sustainable way to develop software. It empowers software developers while delivering a consistently solid level of productivity to project stakeholders.

To learn more about Agile Lite, I encourage you to read:

[Agile Lite for developers](agile_lite_for_developers.md)

[Agile Lite for managers](agile_lite_for_managers.md)

[Frequently Asked Questions](faq.md)


---
If you would like to see more workplaces implement a system such as this, please star this repo on github and share on social media to increase visibility.  
Dave Sullivan 2019 dave.brian.sullivan@gmail.com
