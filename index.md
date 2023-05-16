# Roman Peshkurov

_Software engineer based in London, United Kingdom_ <br>

[Telegram](https://t.me/blazerer) / [Email](mailto:roman.peshkurov@gmail.com) / [LinkedIn](https://www.linkedin.com/in/blazerer) / [Github](https://github.com/blazerer) / [PDF](RomanPeshkurov.pdf) 

<br>

## 💾 Technical Experience
**SDE** @ [Wintermute Trading Ltd](https://www.wintermute.com/) _(May 2022 - ...)_ <br>
Development of server components at HFT company
<details align="justify">
 <summary>Details</summary>
 <ul>
  <li>Development of pricing- and accounting- components for traders and quants </li>
  <li>Created trades data logger for some exchange integrations</li>
  <li>Migrated almost every microservice in company into the new proprietary configuration service</li>
  <li>Participated in regular on call shifts, conducted analysis of anomalies on demand and took part in interviews</li>
  <li>Tools: C++, Python, PostgreSQL, Internal tools</li>
 </ul>
</details>
<br>

**SDE** @ One of FAANG _(Dec 2020 - Apr 2022)_ <br>
Antifraud investigations, training of models and development of server components
<details align="justify">
 <summary>Details</summary>
 <ul>
  <li>Worked in the antifraud field, so can't share many details</li>
  <li>Trained models in ambiguous area</li>
  <li>Developed data pipelines and implemented business logic around them</li>
  <li>Performed anomalies investigations </li>
  <li>Managed bootcampers and interns, conducted interviews </li>
  <li>Tools: Python, Internal ML libraries, Hive/Spark, MySQL, HG, Internal tools</li>
 </ul>
</details>
<br>

**Technical lead** @ [Yandex.Auto](https://auto.yandex/promo) _(Jun 2019 - Nov 2020)_ <br>
Management of the team responsible for the server-side components of the navigation service
<details align="justify">
 <summary>Details</summary>
 <ul>
  <li>Designed and developed server-side applications for the integrations of our service with partners (eg. Remote-Access-To-Car)</li>
  <li>Introduced dashboards and metrics recalculation processes</li>
  <li>Leaded development of push-service for proprietary devices</li>
  <li>Developed Logs-On-Demand system for our devices</li>
  <li>Participated in interviewing, onboarding, mentorship, project management routines of the team</li>
  <li>Tools: C++14, PostgreSQL, PlantUML, Java, Yandex-tools</li>
</ul>
 <i>
 <br>
 <b>Remote-Access-To-Car Demonstration</b><br>
 We integrated our navigation app with the telematics system, so that allowed our customers to have access to car's features (ignition, locks, etc.) via app.
 Was responsible for the design and development of server components via management of the team of 4 developers.<br>
 Here you can see <a href="https://vc.ru/transport/84796-foto-prototip-yandeks-avto-kotoraya-umeet-udalenno-upravlyat-mashinoy-i-sledit-za-ee-sostoyaniem">post</a> about presentation from the conference with a part about our project:
</i>
 <br>
 <br>
 <div class="video-container">
 <iframe src="https://www.youtube.com/embed/28R7JjUjjGY?start=2560" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen class="video"></iframe>
 </div>

</details>
<br>

**Senior SDE** @ [Yandex.Translator](https://translate.yandex.com/) _(May 2018 - Jun 2019)_ <br>
Training translation models and development of data pipelines
<details align="justify">
 <summary>Details</summary>
 <ul>
  <li>Designed and developed end-to-end data aggregation pipeline: from application on device to table into the MR-storage</li>
  <li>Improved translation quality on Turkish language family via training new types of neural models, <b>waiting for <a href="https://patents.google.com/patent/US20220198159A1/">patent</a></b></li>
  <li>Implemented Alternatives-For-Translation backend based on neural language model API</li>
  <li>Tools: C++14, Python, NLTK, TF, Yandex MapReduce, Transformer RNNs, HG</li>
 </ul>
 <i>
 <br>
 <b>Alternatives-For-Translation Demonstration</b><br>
 Worked on an optimal extraction of probabilities' values from translation model to allow us to suggest alternative words in the translation.<br>
 As a result, we obtained server API for this task, and here you can see example of this tool's usage on en-ru language pair:
 </i>
 <br>
 <br>
 <p class="video-container">
  <iframe src="https://www.youtube.com/embed/qzsiknOQsZI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen class="video"></iframe>
 </p>
 <i>
 <br>
 <b>Turkish Languages Translator and Yakut Language</b><br>
 Worked on the multi-language translation models with Tranformer RNNs and tried to find the best experiments' setup by preparation of corpora and tuning of models.<br>
 In the end, we achieved better quality in comparison to our baselines on the az-ru, kz-ru, uz-ru and other turk languages. <br>
 Yakut language is endangered one and our translator was the first registered translation system for it. As this language has high significance for the russian indigenous people, this achievement was reflected in the dedicated documentary:
 </i>
 <br>
 <br>
 <p class="video-container">
  <iframe src="https://www.youtube.com/embed/HupI6xOvWkc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen class="video"></iframe>
 </p>
</details>
<br>

**SDE** @ [Yandex.Appmetrica](https://appmetrica.yandex.com/about) _(Mar 2015 - May 2018)_ <br>
Server-side development of real-time analytical service for mobile applications
<details align="justify">
 <summary>Details</summary>
 <ul>
  <li>Developed distributed fault-tolerant real-time data pipeline (40·10^9 rows/day) as a set of microservices</li>
  <li>Maintained and optimised self-written backend servers' layer (140·10^3 RPS of HTTPS in peak)</li>
  <li>Developed various utils: internal/external APIs, MR-jobs, monitorings and testing solutions</li>
  <li>Performed investigations on petabytes of data via MR and ClickHouse SQL</li>
  <li>Tools: C++14, Boost, Poco, MySQL, <a href="https://clickhouse.tech/">ClickHouse</a> (developed in my department), Nginx, Python, Yandex MapReduce, Apache Zookeeper, Git</li>
 </ul>
 <i>
 <br>
 <b>Logs API Demonstration</b><br>
 Designed and developed the server side of this API to allow customers extracting logs of their applications from our storage.<br>
 Here you can see how process of the data download looks like:
 </i>
 <br>
 <br>
 <p class="video-container">
  <iframe src="https://www.youtube.com/embed/S7wl_8sTrAY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen class="video"></iframe>
 </p>
</details>
<br>

**SDE** @ [ModuleWorks](https://www.moduleworks.com/) 3ax Team _(Mar 2012 - Feb 2015)_ <br>
Development of the solutions for the CAD/CAM software
<details align="justify">
 <summary>Details</summary>
 <ul>
  <li>Solving sculpture surface machining and computational geometry problems</li>
  <li>Implemented library for the toolpath smoothing - based my master's thesis on it</li>
  <li>Developed and maintained project of Multiaxis Roughing (see below)</li>
  <li>Tools: C++03, Boost, Computational geometry tools, Svn</li>
 </ul>
 <i>
<br>
<b>Multiaxis Roughing Demonstration</b><br>
This toolpath generation algorithm was implemented as a combination of approaches between 5ax and 3ax project areas.
My aim was to make an actual implementation of an already scoped project and pushing it to the production.<br>
Here is the marketing demonstration of this tool:
 </i>
 <br>
 <br>
 <p class="video-container">
  <iframe src="https://www.youtube.com/embed/nHLNZ-Zp-r4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen class="video"></iframe>
 </p>
</details>

<br>

## 🎓 Education
**Master Program in CS and DA** @ [Yandex Data School](https://yandexdataschool.com/) _(Sep 2015 - Jun 2017)_ <br>
* Theory of computation
* Machine learning
* Data processing in external memory
* Tools: C++14, Python, Jupyter, OpenMP, Hadoop, Pandas, Sklearn, NLTK, Theano, TF, Keras, Lasagne

<br>

**Master Degree in Computer Engineering** @ Sevastopol National University of Nuclear Energy and Industry _(Sep 2008 - Jan 2014)_ <br>
* Software development and databases
* Сomputer architecture and microelectronics
* Tools: C/C++03, MySQL, PHP, AutoCAD

<br>

## 🏆 Achievements 
* [Codeforces](http://codeforces.com/profile/blazerer) max rating: **1976** (2015)
* [Topcoder](https://www.topcoder.com/members/blazerer/) max rating: **1808** (2014)
* ACM ICPC SEERC World Semifinal: **participant** (2011-2014)
* ACM ICPC Ukraine-South: **2nd** (2011), **3rd** (2012 - 2014)
* ACM ICPC Uni Level: **1st** (2010 - 2014)
* Vekua Cup: **3rd** (2013)
* KPI-OPEN: **high achievements** (2010 - 2011)
* Osipovsky Cup: **high achievements** (2011 - 2012)
* Kharkov winter programming school: **participant** (2010 - 2013)
* Sevastopol summer programming school: **participant** (2010 - 2012)
* Yandex school of distributional computing: **participant** (2011)
* Yandex credit scoring contest: **2nd** (2017)
* Prepared and conducted webinars for [SkillFactory](https://skillfactory.ru/) on MultiThreading as a part of C++ course

<br>

## 💬 Personal Qualities
* Languages: Russian, English, Ukrainian
* Able to immerse in any area
* Communicative
* Thoughtful

<br>

## 🎸 Outside Of Work
* [Habr](https://habr.com/ru/users/MrBlazerer/posts/) with rare posts
* [TG channel](https://t.me/imposter_and_ocd) for thoughts
* [Blog](https://vk.com/blazerer_about_music) about music gigs
* Development of [tg bot](https://t.me/MusicPracticeBot) for learning of CAGED-system on guitar
* Maintaining [tg sticker pack](https://t.me/addstickers/NorwegianFun)
* Playing any kind of guitar
* Swimming, snowboarding, watching football 🔴🟢
* Metal fests, escape rooms, board games, [travels](country_counter.md)
* [FB](https://www.facebook.com/MrBlazerer) with annual updates
* [IG](https://www.instagram.com/blazerer_about_everything/) about everything
* [Wishlist](wishlist.md)
