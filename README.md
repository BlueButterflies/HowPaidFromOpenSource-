# Удобно ръководство за финансова подкрепа за отворен код.

*„Работя с отворен код, как да намеря финансиране?“*

Този документ има за цел да предостави списък на всички начини, по които хората получават заплащане за работа с отворен код. Надяваме се, че проектите и сътрудниците ще намерят това полезно при намирането на най-добрите опции за тях.

Списъкът по-долу е грубо подреден от малък към голям. Всяка категория за финансиране се свързва с няколко реални примера (използвайки тематични статии или страници, където е възможно, вместо само началната страница на проект.)

Категориите не се изключват взаимно. Например един проект може да има фондация, но също така да използва групово финансиране за набиране на пари. Някой друг може да направи консултации и също да има бутон за дарение. и т.н.

---

# Съдържание

1. [Бутон за дарение](#donation-button)
2. [Награди](#bounties)
3. [Спонсорски софтуер](#sponsorware)
4. [Групово финансиране (еднократно)](#crowdfunding-one-time)
5. [Групово финансиране (повтарящо се)](#crowdfunding-recurring)
6. [Книги и стоки](#books-and-merchandise)
7. [Реклама и спонсорство](#advertising--sponsorships)
8. [Наемете се от компания за работа по проект](#get-hired-by-a-company-to-work-on-project)
9. [Започнете проект, докато сте на работа](#start-a-project-while-currently-employed)
10. [Безвъзмездни средства](#grants)
11. [Консултиране](#consulting)
12. [Платена поддръжка](#paid-support)
13. [SaaS](#saas)
14. [Copyleft + платен лиценз](#copyleft--paid-license)
15. [Open core](#open-core)
16. [Фондации и консорциуми](#foundations--consortiums)
17. [Рисков капитал](#venture-capital)
18. [Ограничен лиценз](#restricted-license)


ПРИЛОЖЕНИЕ: [Принос към това ръководство](#contributing-to-this-guide) // [Лиценз и авторство](#license-and-attribution)
ПРЕВОДИ: [Английски(english)](https://github.com/nayafia/lemonade-stand) // [Традиционен китайски(繁體中文)](https://github.com/jserv/lemonade-stand) // [Опростен китайски(簡體中文)](https://github.com/wizicer/FinancialSupportForOpenSource) // [Италиански(italiano)](https://github.com/dakk/lemonade-stand) // [Японски(日本語)](https://github.com/fumikito/lemonade-stand) // [Руски(русский)](https://github.com/saviorand/lemonade-stand_ru)

**Бележките за „лични усилия“ се отнасят до примери за финансиране, включващи един разработчик

## Бутон за дарение

*Включете бутон за дарение на вашия сайт. Stripe и PayPal са примери за услуги, които можете да използвате за приемане на дарения.
Друга възможност е да приемате дарения чрез криптовалути като биткойн, като в този случай просто вмъкнете изображението на QR кода на вашия портфейл.*

#### Плюсове

* Включва малко усилия за интеграция
* Малка работа: „задайте го и го забравете“

#### Минуси

* Обикновено не са много пари, освен ако не сте посветили усилия за набиране на средства
* Имате нужда от юридическо лице, което да приема дарения, което може да изисква такса за това. Примери за това са Stripe и PayPal.
* За да направите даренията освободени от данъци за лицето/организацията, която дарява, може да се нуждаете от законно благотворително дружество (в Съединените щати, 501(c)(3) дружество с нестопанска цел), което да приема дарения. [Software Freedom Conservancy](https://sfconservancy.org) и [NumFOCUS](https://www.numfocus.org) са примери. По-трудно за управление на физически лица или международни дарения
* Понякога не е ясно кой „заслужава“ пари в даден проект или как те се разпределят. Субект като [OpenCollective](http://opencollective.com) може да помогне с това.

#### Казуси от практиката

* [ChatSecure](https://chatsecure.org/blog/sustainable-open-source-starts-with-you/)
* [Git](https://git-scm.com/sfc)
* [Transmission](https://www.transmissionbt.com/)
* [Twisted](https://twistedmatrix.com/trac/wiki/WhyDonate)

## Награди

*Понякога проекти или компании публикуват премии за работа с отворен код (напр. „поправете тази грешка и съберете $100“). Има няколко уебсайта, изброени по-долу, които помагат за улесняване на публикуването и събирането на награди.*

#### Плюсове

* Отворено за участие на общността
* Парите са обвързани с извършването на конкретна работа (по-скоро като плащане за услуга, отколкото като дарения)
* Особено популярен за охранителна работа

#### Минуси

* Може да създаде погрешни стимули в проект (нискокачествени PR, разсейващи приоритети)
* Могат да възникнат конфликти относно това дали работата изпълнява награда
* Обикновено не много пари за награда (~<$500)
* Не осигурява повтарящи се приходи

#### Казуси от практиката

* [Gitcoin](https://gitcoin.co/explorer)
* [GitHub Bug Bounty Program](https://bounty.github.com/)
* [Google Patch Rewards](https://www.google.com/about/appsecurity/patch-rewards/)
* [Inkscape's "funded development" system](https://inkscape.org/support-us/funded-development/)
* [Internet Bug Bounty](https://internetbugbounty.org/)
* [IssueHunt](https://issuehunt.io)
* [The Bounties Network](https://www.bounties.network/)

## Спонсорски софтуер

*Ако искате да отворите проект с отворен код, но искате да сте сигурни, че други ще инвестират в неговата дългосрочна поддръжка, можете да кажете на общността си, че ще отворите проекта с отворен код, след като постигнете определено количество спонсорство. (Писателят Тим Кармоди нарича това ["отключване на общите блага."](https://www.niemanlab.org/2019/01/unlocking-the-commons/))*

*Това е подобно на [Групово финансиране (еднократно)]((#crowdfunding-one-time)), описано по-долу, с изключение на това, че вместо да финансирате работата предварително, вие създавате софтуера от самото начало, след което избирате дали или да не го отваряте в зависимост от това дали сте постигнали целта си.*

#### Плюсове

* Може да бъде повтарящ се източник на приходи след първоначалното разработване, в зависимост от това как сте задали условията за пускане на проекта
* Може да бъде полезен сигнал за това дали хората ценят пакета
* Дава на хората незабавна стойност – хората могат да ви спонсорират и да получат достъп до пакета веднага
* Не ограничава бъдещия потенциален растеж на проекта и поддържа духа на отворения код

#### Минуси

* Не работи за проекти, които вече са пуснати
* Вероятно работи само за привличащи вниманието проекти, където демонстрацията или доказателството за концепция са много вълнуващи

#### Казуси от практиката

* [Caleb Porzio's `sushi` package](https://calebporzio.com/sponsorware)

## Групово финансиране (еднократно)

*Ако имате конкретна идея, която искате да реализирате (вместо текуща работа по проект), еднократна кампания за групово финансиране може да помогне за набирането на средствата, от които се нуждаете. Както физически лица, така и компании може да са склонни да дарят за вашата кампания.*

#### Плюсове

* Приложени са няколко низа
* Може да бъде по-лесно за физическо лице да управлява законно чрез, напр. [Kickstarter](https://kickstarter.com/)

#### Минуси

* Много работа, свързана с пазарната кампания
* Обикновено трябва да бъде обвързано с конкретен резултат, предимства
* Обикновено не толкова много пари (~$50K за един път)
* Компаниите не винаги се чувстват удобно да даряват за кампании

#### Казуси от практиката

* [Andrew Godwin + Django (personal effort)](https://www.kickstarter.com/projects/andrewgodwin/schema-migrations-for-django)
* [Dave Gandy + Font Awesome](https://www.kickstarter.com/projects/232193852/font-awesome-5)
* [GDAL Coordinate System Barn Raising](https://gdalbarn.com/)
* [Michal Papis + Rvm (personal effort)](https://www.bountysource.com/teams/rvm/fundraiser)
* [Monero Community Crowdfunding System (CCS)](https://ccs.getmonero.org/)
* [RESTful WP-CLI](https://poststatus.com/kickstarter-open-source-project/)

## Групово финансиране (повтарящо се)

*Ако искате да финансирате текуща работа по проект, можете да настроите периодична кампания за групово финансиране с месечен или годишен финансов ангажимент, който се подновява за неопределено време (или докато донорът не се откаже). Тези, които използват вашия проект редовно (включително физически лица и компании), може да са готови да финансират работата ви.*

#### Плюсове

* Приложени са няколко низа
* Може да бъде по-лесно за физическо лице да управлява законно чрез, напр. [Patreon](https://patreon.com), [Salt](https://salt.bountysource.com/), [Liberapay](https://liberapay.com/), [OpenCollective](https:/ /opencollective.com), [Flattr](https://flattr.com/)

#### Минуси

* По-трудно е да се поемат ангажименти за повтарящи се дарения (често се изисква предварително съществуваща марка/репутация)
* По-трудни за обяснение конкретни резултати, предимства, които идват с повтарящи се дарения
* Обикновено не толкова много пари (~$1-4K месечно)
* Компаниите не винаги се чувстват удобно да даряват за кампании

#### Казуси от практиката

* [Babel](https://opencollective.com/babel)
* [Caleb Porzio + Laravel Livewire and more](https://calebporzio.com/i-just-hit-dollar-100000yr-on-github-sponsors-heres-how-i-did-it)
* [Clojurists Together](https://clojuriststogether.org)
* [Eran Hammer + hapi Patreon](https://www.patreon.com/eranhammer)
* [ESLint](https://eslint.org/blog/2019/02/funding-eslint-future)
* [Evan You + Vue.js Patreon](https://www.patreon.com/evanyou)
* [GnuPG](https://www.gnupg.org/donate/index.html)
* [Ruby Together](https://rubytogether.org)
* [Tom Christie + Django REST framework (personal effort)](https://fund.django-rest-framework.org/topics/funding/)
* [webpack](https://opencollective.com/webpack)

## Книги и стоки

*Ако сте експерт в област, за която други хора може да намерят полезно да научат, можете да напишете и продадете книга или поредица от книги. Можете да намерите издател (като O'Reilly) или да публикувате сами. В допълнение към продажбата на книги, някои проекти продават стоки (напр. ризи, качулки), за да подкрепят работата си.*

#### Плюсове

* Резултатът не е обвързан със самата работа по проекта, така че запазвате творческата свобода
* Може да служи като маркетинг за самия проект
* Може да бъде повтарящ се източник на приходи след първоначалното разработване

#### Munuses

* Често не е значителен източник на приходи
* Може да отвлече вниманието от основното развитие на проекта
* Стоката може да има предварителни разходи

#### Казуси от практиката

* [CocoaPods (набиране на средства за благотворителност)](https://cocoapods.org/socks)
* [Daniel and Audrey Roy Greenfeld + Two Scoops of Django (лични усилия)](https://www.twoscoopspress.com/products/two-scoops-of-django-1-8)
* [Kyle Simpson + You Don't Know JS (лични усилия)](https://github.com/getify/You-Dont-Know-JS)
* [Lua](https://www.lua.org/pil/)
* [Sandi Metz + Practical Object-Oriented Design in Ruby (лични усилия)](http://www.poodr.com/)

## Реклама и спонсорство

*Ако вашият проект има голяма аудитория, можете да продавате спонсорства на рекламодатели, които може да искат да достигнат до тях. Вероятно имате много целева аудитория (напр. ако имате проект на Python, можете да предположите, че вашата аудитория вероятно са хора, които са технически запознати с Python), така че използвайте това в своя полза.*

#### Плюсове

* Бизнес модел, съобразен с нещо, за което хората са готови да платят

#### Минуси

* Нуждаете се от достатъчно голяма публика, за да оправдаете спонсорството
* Необходимост от управление на доверието и прозрачността с потребителска база (напр. без проследяване)
* Може да бъде много работа за намиране и управление на клиенти
* Може да включва етични съображения относно маркетинга
* Може да въведе конфликт на интереси; извършването на противоречиви промени може да доведе до загуба на спонсори/рекламодатели

#### Казуси от практиката

* [CodeFund](https://codefund.io)
* [GitFund](https://gitfund.io)
* [Hoodie](http://hood.ie/sponsoring/)
* [Read the Docs](http://blog.readthedocs.com/ads-on-read-the-docs/)
* [Feross's experiment with StandardJS](https://feross.org/funding-experiment-recap/)
* Kite sponsorship of Minimap ([summary](https://medium.com/@nayafia/the-kite-debacle-is-democracy-at-work-6a04bc043c50))
* [Caddy](https://github.com/caddyserver/caddy) (exclusively sponsorships)

## Наемете се от компания за работа по проект

*Компаниите понякога наемат хора за работа с отворен код. Намерете компания, която използва проекта, по който искате да работите. Често това е разделно споразумение (напр. 50% работа на компанията, 50% работа с отворен код). Като алтернатива, ако имате идея за нов проект, намерете компания, която би била заинтересована да използва това, което произвеждате. В тези ситуации наличието на демонстриран опит, който можете да посочите, ще бъде много полезно.*

#### Плюсове

* Докосва се до тези, които имат ресурси (т.е. компании)
* Може да бъде добре приведен в съответствие с нуждите на компанията
* Стабилен доход

#### Минуси

* Обикновено включва „изваждане на късмет“: няма ясен, повтарящ се път за намиране на тази подредба
* Проектът вече трябва да бъде добре познат и използван
* Човек, който не допринася за крайния резултат на компанията, което го прави разходен
* Проблеми с управлението, компанията може да има неоправдано влияние върху проекта
* Може да повлияе на динамиката на проекта + баланса

#### Казуси от практиката

* [Aaron Patterson + ManageIQ and Ruby, Rails (лични усилия)](http://community.redhat.com/blog/2014/09/tenderlove-joins-manageiq/)
* [Donald Stufft + Hewlett-Packard and Python packaging (лични усилия)](https://twitter.com/dstufft/status/594119386333609984)
* [Rich Hickey + Cognitect and Clojure](http://www.bizjournals.com/triangle/news/2013/09/17/durhams-relevance-to-merge-with.html?full=true)
* [Ryan Dahl + Joyent and Node.js (opens a YouTube video) (лични усилия)](http://www.youtube.com/watch?v=SAc0vQCC6UQ&t=29m20s)

## Започнете проект, докато в момента сте на работа

*Много проекти с отворен код започнаха като проекти на служителите. Проектът може в крайна сметка да надрасне компанията, но стартирането му като страничен проект може да бъде чудесен начин за инкубиране на идеята.*

*Ако следвате този път, уверете се, че разбирате политиката на вашата компания относно работата с отворен код. Някои компании насърчават служителите да допринасят за отворен код през работно време. Някои може да третират вашата работа с отворен код като фирмен проект. Не предполагайте нищо; попитайте някой във вашата компания, преди да започнете.*

#### Плюсове

* Свобода да тествате нови идеи, без да се притеснявате за заплатата
* Може да бъде добре приведен в съответствие с нуждите на компанията
* Подходящо за по-нови, експериментални идеи

#### Минуси

* Трябва да го направите като страничен проект или да бъдете одобрени да работите по него през платеното време
* Риск от неоправдано влияние на компанията
* Може да доведе до сложно управление по-късно

#### Казуси от практиката

* [Facebook and React](https://www.quora.com/How-was-the-idea-to-develop-React-conceived-and-how-many-people-worked-on-developing-it-and-implementing-it-at-Facebook/answer/Bill-Fisher-17)
* [Futurice's open source program](http://futurice.com/blog/sponsoring-free-time-open-source-activities)
* [Google and Go](https://golang.org/doc/faq#history)
* [Mozilla and Rust](https://prev.rust-lang.org/en-US/faq.html#is-this-project-controlled-by-mozilla)
* [Formidable's Sauce program](https://formidable.com/blog/2019/sauce-program/), където плащат на служителите за техните вноски с отворен код

## Безвъзмездни средства

*Грантовете са парични подаръци, които не изискват връщане. Често субсидиращият получава други ползи от предоставянето на субсидията, като например достъп до вас, демонстрация на въздействие, отчет за вашата работа или данъчни облекчения.*

*Грантовете могат да идват от много места, включително компании, софтуерни фондации, филантропски фондации и правителството. Техническите и правните аспекти на безвъзмездната помощ варират значително в зависимост от това откъде идва. Например, една компания може да ви даде „безвъзмездна помощ“, но законно да я третира като консултантска фактура. Една филантропска фондация може да предоставя безвъзмездни средства само на организации с нестопанска цел, така че вие самите трябва да сте организация с нестопанска цел или (по-често) да намерите организация с нестопанска цел, която да ви спонсорира. Ако не сте запознати с грантовете, най-добрият начин да разберете как работят грантовете е да говорите с някой, който е получавал такива преди. Някои примери за получатели на безвъзмездни средства са изброени по-долу.*

#### Плюсове

* По-малко прикачени низове
* Гарантираните пари могат да помогнат за фокусирането на проекта за непрекъснат период от време
* Дава на проекта място за дишане и експериментиране

#### Минуси

* Няма много субсидии, свързани със софтуер (филантропски, правителствени, корпоративни)
* Безвъзмездните средства са ограничени. Все още трябва да се намери устойчивост след живота на безвъзмездната помощ

#### Казуси от практиката

* [Andrey Petrov + Stripe Open-Source Retreat and urllib3](https://medium.com/@shazow/urllib3-stripe-and-open-source-grants-edb9c0e46e82#.45ylnxrh4)
* [Chan-Zuckerberg Initiative grant program for open source software in science](https://chanzuckerberg.com/rfa/essential-open-source-software-for-science/)
* [Dash Budget Proposal Tracker](https://dashvotetracker.com/)
* [Dat Project](https://blog.datproject.org/2017/09/15/dat-funding-history/)
* [Django + Mozilla Open Source Support](https://www.djangoproject.com/weblog/2015/dec/11/django-awarded-moss-grant/)
* [Grin General Fund](http://grin-tech.org/funding.html)
* [Handshake community grant program](https://handshake.org)
* [Libraries.io grant applications](https://github.com/librariesio/supporters)
* [ralphtheninja/open-funding](https://github.com/ralphtheninja/open-funding#grants) has a list of grants
* [Segment Open Fellowship](https://segment.com/blog/segment-open-fellowship-2017/)
* [Sentry Open Source Grant](https://blog.sentry.io/2019/01/29/apply-sentry-open-source-grant)

## Консултации

*Консултирането може да бъде гъвкав начин за финансиране на работа с отворен код. Имате повече свобода да структурирате времето си, както желаете (например, консултиране 30 часа от седмицата и прекарване на 10 часа от седмицата за работа с отворен код). Консултантите обикновено могат да таксуват повече за времето си, отколкото служителите на заплата, защото работата е по-малко стабилна, те не получават обезщетения и т.н. Ако планирате да извършвате този вид работа редовно, вероятно ще искате да създадете LLC (или еквивалентен извън САЩ).*

*Ако вашият проект е популярен, можете също да предложите консултации и услуги около самия проект. Например клиент може да ви плати, за да изпълните проекта вместо него, да изградите нещо по поръчка или да го обучите как да го използва.*

#### Плюсове

* Бизнес модел, съобразен с нещо, за което хората са готови да платят

#### Минуси

* Консултирането изисква човешка сила, не се мащабира добре (с изключение на редки отклонения)
* Бизнес нуждите могат да отвлекат вниманието от писането на код или други задачи, свързани със самия проект
* Може да бъде в противоречие с лесния за използване софтуер
* Проектът трябва да бъде достатъчно популярен, така че хората да са готови да плащат за свързани услуги

#### Казуси от практиката

* [Baroque Software](http://baroquesoftware.com/)
* [Neighbourhoodie](https://neighbourhood.ie/)
* [OpenSSL Software Foundation](https://www.openssl.org/community/contacts.html) formerly [OpenSSL Software Services](https://web.archive.org/web/20180817114118/opensslservices.com/what.html)
* [Varnish Moral License](http://phk.freebsd.dk/VML/)

## Платена поддръжка

*В този модел кодът е свободно достъпен, но потребителите трябва да платят, за да получат поддръжка от поддържащите проекта. Това може да означава таксуване за достъп до инструмента за проследяване на проблеми, работно време, общност Slack или SLA (споразумение за ниво на обслужване).*

#### Плюсове

* Бизнес модел, съобразен с нещо, за което хората са готови да платят

#### Минуси

* Може да бъде в противоречие с лесния за използване софтуер
* Проектът трябва да бъде достатъчно популярен, така че хората да са готови да плащат
* Поддържащите не искат непременно да предлагат професионална поддръжка

#### Казуси от практиката

* [Fody](https://github.com/Fody/Fody/blob/master/readme.md): Трябва да сте поддръжник на Patreon, за да отворите проблем или заявка за изтегляне
* [Prism](https://www.patreon.com/prismlibrary): Подкрепата на техния Patreon ви дава достъп до техния канал Slack на общността за поддръжка на проекти
* [Red Hat](https://en.wikipedia.org/wiki/Red_Hat#Business_model)
* [Tidelift paid subscriptions](https://tidelift.com/subscription)

## SaaS

*SaaS означава [Софтуер като услуга](https://en.wikipedia.org/wiki/Software_as_a_service). В този модел самата кодова база може да остане с отворен код, но вие предлагате платени услуги, като например таксуване за използване на основен хостван сайт или за обслужване на хостинг на специални екземпляри за клиенти. Обикновено плащащите клиенти също получават приоритетна поддръжка.*

#### Плюсове

* Може да изгради общност около отворен проект и да печели пари от услуги за хостинг
* Позволява на проекта с отворен код да се съсредоточи върху потребителите и с нарастването на нуждите да помогне на предприятията да приемат проекта
* Може да мащабира според броя на потребителите

#### Минуси

* Често означава, че хостингът трябва да е по-евтин от наемането на разработчик, който да изпълнява проекта вместо вас.
* „Двете нива“ на продуктова поддръжка могат да направят безплатните потребители нещастни

#### Казуси от практиката

* [Discourse](https://www.discourse.org/)
* [Forge Laravel](https://forge.laravel.com/)
* [Ghost](https://ghost.org/about/)
* [GitLab](https://gitlab.com) (also uses open core licensing)
* [Moodle](https://moodle.org/)
* [Sentry](https://getsentry.com/)
* [Travis CI](https://travis-ci.org/)
* [WordPress.com](http://wordpress.com/)

## Copyleft + платен лиценз

*Компаниите, продаващи патентован софтуер, предпочитат да включват разрешително лицензиран код (като MIT или Apache 2.0), вместо лицензиран код с копилефт (като GPL) в своя софтуер, тъй като последният изисква от тях да спазват същите условия за копилефт за крайните си продукти. Така че някои проекти с отворен код използват лиценз за копилефт по подразбиране, но те продават изключения от лицензи, патентовани лицензи или разрешителни търговски лицензи на компании, които искат да заобиколят изискванията за копилефт.*

#### Плюсове

* Бизнес модел, съобразен с нещо, за което хората са готови да платят
* Може да мащабира добре, ако успее

#### Минуси

* Може да бъде в противоречие с правенето на софтуер свободно достъпен
* Проектът трябва да е достатъчно голям, за да има нужда от клиента
* Работи само за софтуер нагоре по веригата, който се използва в софтуер надолу по веригата
* Може да има правни или парични бариери за преместване на код от отворен към патентован

#### Казуси от практиката

* [Metafizzy](https://metafizzy.co) (ex. [Isotope](https://isotope.metafizzy.co/license.html), [Flickity](https://flickity.metafizzy.co/license.html))
* [MySQL](http://www.mysql.com/about/legal/licensing/oem/)
* [Qt](https://www1.qt.io/faq/#_Toc_3)
* [SQLite](https://www.sqlite.org/copyright.html)

## Open core

*При [open core](https://en.wikipedia.org/wiki/Open_core) модел някои аспекти на проекта са безплатни, но други функции са частна собственост и са достъпни само за платени потребители. Обикновено това работи, когато има корпоративно търсене за проекта.*

#### Плюсове

* Бизнес модел, съобразен с нещо, за което хората са готови да платят
* Може да мащабира добре, ако успее

#### Минуси

* Трябва да имате нещо, за което можете да таксувате (което означава да направите определени функции изключителни)
* Може да бъде в противоречие с правенето на софтуер свободно достъпен
* „Двете нива“ на продуктова поддръжка могат да направят безплатните потребители нещастни
* Може да изисква CLA (Лицензионно споразумение за сътрудник), за да приеме изпращане на код от външни сътрудници, като същевременно запазва възможността за повторно лицензиране на тези изпращания съгласно лиценза за собственост

#### Казуси от практиката

* [GitLab](https://about.gitlab.com/)
* [Docker](https://www.docker.com/)
* [Elastic](https://www.elastic.co/)
* [Mesosphere](https://mesosphere.com/)
* [Phusion Passenger](https://www.phusionpassenger.com/); вижте и техния разговор, ["Bootstrapping a Business Around Open Source"](https://www.youtube.com/watch?v=uHaMpLyMOL0&feature=youtu.be) (видео)
* [Sidekiq](http://sidekiq.org/)

## Фондации и консорциуми

*[Фондация](https://en.wikipedia.org/wiki/Foundation_(nonprofit)) е юридическо лице, което може да приема и/или изплаща дарения. Тъй като тяхната цел не е да правят печалби, те могат да бъдат чудесен избор за сигнализиране на неутралност и управление на проект. В САЩ фондациите са или 501(c)(3) (с нестопанска цел) или 501(c)(6) (търговски консорциум). Много софтуерни фондации са 501(c)(6), тъй като 501(c)(3) изисква демонстриране на благотворителна цел, което може да бъде по-трудно при софтуера.*

#### Плюсове

* Неутралност. Фондацията защитава кода и помага на стюард общността
* Влияние, разпределено между множество донори
* Може да легитимира проект, компаниите може да се чувстват по-удобно да дават на фондации, отколкото на отделни лица

#### Минуси

* Наистина си струва само за големи проекти
* Трудно за настройка поради причини, свързани с IRS (много правят 501(c)(6) вместо 501(c)(3)), ограничения за това, което можете да правите
* Изисква сериозни усилия на общността и разнообразни умения (все още трябва да набирате средства, след като създадете организацията!)

#### Казуси от практиката

* [Linux Foundation](https://www.linuxfoundation.org/)
* [Node.js Foundation](https://www.sitepoint.com/goodbye-joyent-hello-node-js-foundation/)
* [Python Software Foundation](https://www.python.org/psf/)
* [Ruby Together](http://rubytogether.org/)
* [Signal Foundation](https://signal.org/blog/signal-foundation/)

## Рисков капитал

*Рисковият капитал е форма на финансиране за фирми с висок растеж. За разлика от банков заем или други форми на дългово финансиране, рисковите капиталисти вземат собствен капитал (процент собственост във вашия бизнес) в замяна на финансиране. За разлика от тегленето на заем, не е нужно да изплащате кредиторите си, ако бизнесът ви пропадне. Ако все пак успеете, трябва да очаквате да върнете капитала на вашия инвеститор многократно.*

* Рисковият капитал е „възнаграждение с висок риск и висока стойност“: VC са по-толерантни към риска от банките, но също така очакват голяма печалба, ако успеете. Ако планирате да набирате рисков капитал, трябва да създадете бизнес единица, структурирана като C Corp, за предпочитане в Делауеър. Ако не сте запознати с процеса на рисков капитал, най-доброто място да започнете е като се свържете с подобни основатели, които успешно са набрали рисков капитал.*

#### Плюсове

* Институционалната подкрепа може да бъде полезна за разрастване на бизнес
* Наличен голям капитал

#### Минуси

* Рисковият капитал идва с очаквания за изход (т.е. връщане на парите на инвеститорите при многократно). Историята показва, че това е структурно трудно постижимо за бизнеса с отворен код. Рисковият капитал всъщност не е бизнес модел, а само инвестиционен капитал за тези, които имат някакъв *друг* бизнес модел за бъдещи приходи.
* Рисковият капитал може да промени мотивацията и да отвлече вниманието от приоритетите
* Недостъпно за нестопански организации

#### Казуси от практиката

* [Confluent](http://www.confluent.io/blog/confluent-raises-a-series-b-funding)
* [Gatsby](https://www.gatsbyjs.org/blog/2018-05-24-launching-new-gatsby-company/)
* [Meteor](http://info.meteor.com/blog/announcing-our-20m-series-b-funding)
* [NodeSource](https://techcrunch.com/2015/02/09/nodesource-raises-3-million-to-build-new-programming-tools/)
* [Npm](http://blog.npmjs.org/post/76320673650/funding)
* [OSS Capital](https://oss.capital/)

## Ограничен лиценз

*Ограничените лицензи (напомнящи на по-старото движение [shareware](https://en.wikipedia.org/wiki/Shareware)) **не са с отворен код**, защото не отговарят на [определението](https:// en.wikipedia.org/wiki/The_Open_Source_Definition) на лиценз с отворен код. Изходният код е достъпен (публично или на клиенти, които плащат за лиценз), но те могат да ограничат свободите да разпространяват и модифицират или да използват софтуера с търговска цел.*

#### Плюсове

* Бизнес модел, съобразен с нещо, за което хората са готови да платят
* Потенциал за добро мащабиране при успех

#### Минуси

* Всъщност не е с отворен код (така че може да не успее да постигне много или повечето от предимствата на отворения код)
* Може да бъде противоречиво, да подкопае доверието на общността

#### Казуси от практиката

* [BSL (Business Source License)](https://mariadb.com/bsl-faq-adopting), used by [MariaDB](https://mariadb.com/)
* [Fair Source](https://fair.io/), used by [Sourcegraph](https://sourcegraph.com/)
* [License Zero](https://medium.com/licensezero/the-license-zero-manifesto-fecb7aaf4c0a)
* [Markdown Monster](https://markdownmonster.west-wind.com/)
  * Изходният код може да се види, но [трябва да се закупи лиценз](https://markdownmonster.west-wind.com/download.aspx) за продължителна употреба
   * Сътрудниците на проекта са [допустими за безплатен лиценз](https://markdownmonster.west-wind.com/download.aspx#Contribute)
* [Onivim 2](https://github.com/onivim/oni2#license)
  * Търговският лиценз е плащане каквото искаш, като минималната цена за предварителна поръчка се увеличава с наближаването на доставката на MVP
   * Всеки, който спонсорира финансово проекта OSS, получава безплатен лиценз за цял живот
   * Ангажиментите са двойно лицензирани с MIT след 18 месеца от датата на ангажимента до мастера
* [Redis Commons Clause](https://redislabs.com/community/licenses/)
* [Ungit превключи обратно от Faircode към MIT License](https://github.com/FredrikNoren/ungit/issues/997)

---

### Принос към това ръководство

Всеки, който иска да допринесе за това ръководство с допълнителни допълнения, промени, нови категории и предложения, може да го направи чрез заявка за изтегляне или като постави проблем в хранилището. Описаните предимства и недостатъци са субективни, поради което отразяват гледната точка на автора и тези, които са направили промените.

### Лиценз и авторство

Това ръководство е достъпно под „Лиценза Creative Commons CC-BY 3.0“, вие сте свободни да го използвате за всякакви цели, търговски или нетърговски, с единственото задължение да цитирате оригиналния автор.

Ръководството е създадено от  ([@BlueButterflies](https://github.com/BlueButterflies)). Документът е базиран на англоезичният проект [lemonade-stand](https://github.com/nayafia/lemonade-stand).