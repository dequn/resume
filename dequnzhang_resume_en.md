<style>
h1 {
    border: none;
    margin: 0 0 1em 0;
    padding: 0;
}
h2, h3 {
    margin: 1em 0 0 0;
}
p {margin: 0;} /* 单行的段落，一般在列表中，就不要这么大间距了 */
#projects + ul > li > p {margin: 0.5em 0 0 0;} /* 为了让段落之间稍微有点间隔，不显得那么拥挤 */
</style>
<h1 style="text-align:center">Dequn Zhang</h1>
Mobile: (+86)13070175160&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
E-mail: <dqzhangchn@gmail.com>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
Blog: <https://blog.92qun.de>

## Education
* **Institute of Geographic Sciences and Natural Resources Research, Chinese Academy of Sciences, Beijing, China**

    Master of Cartography and Geography Information System, Top 10%, 2014 - 2017

* **Henan Polytechnic University, Jiaozuo, China**

    Bachelor of Geography Information System, Rank 1/48, 2010 - 2014

## Work Experience


* **New Horizons Risk Management Tech. Ltd. Wuhan. &nbsp;&nbsp;&nbsp;&nbsp;Senior R&D &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2018.04 - Current**
* **Power Search Dept. Baidu Inc. Beijing. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Machine Learning R&D&nbsp;&nbsp;&nbsp; 2017.07 - 2018.04**

## Skills
* Familiar with typical **Data Structure** and **Algorithm**

* Proficient in **Python**, familiar with **Sci-kit, PyTorch** machine learning framework, and libraries such as *Numpy, pandas*

* Advanced experience in **Python web** (Django, DRF, Channels), once one year experience in front-end (AngularJS + Bootstrap)

* Two years experience in **Hadoop, HBase, Spark**, knowledge of Java and Scala

* Good knowledge of Database and SQL, familiar with **PostgreSQL, PostGIS**

* Work on **Linux**, intermediate master of standard **Shell**, git, git review, etc.

* Basic experience in product prototype design on Axure, basic CI&CD experience in Jenkins

## Projects
* **Aquaculture IoT and BigData system &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Principal/Back-end &nbsp;&nbsp;&nbsp;2018.06 - 2019.10** 

    Utilize IoT technique to monitor water quality, build model of the relation between water quality, weather and aquaculture losses to predict and reduct risks.

    Responsibilities: *1)* Responsible for requirement analysis, solution making, system structure design, and product design; *2)* Developed **upper computer system** on *Twisted*, completed frame parsing, data storage, command distributing, etc.; *3)* Developed **web back-end system** (*Django*), supplied REST interface (*DRF*), implemented **back-end &hArr; front-end** communication on **WebSocket** (*Channels*); *4)* Based on **Redis MQ** middleware, developed **back-end &hArr; upper computer** part of communication of control tasks and results, and built an exclusive lock for tasks; *5)* Supervised interns to make math models.

    Achievements: *1)* One Chinese patent (pending) and four software copyrights; *2)* [An app for fisherman](http://yubb123.com) and two monitoring and management system for the insurance company (Business-end); *3)* [Presented our landing work to Chunqing Yuan, vice director of the Office of Central Rural Work Leading Group](http://www.sohu.com/a/255487326_100165300) (news page in Chinese).

* **Baidu hot-query ranking &nbsp;&nbsp;&nbsp;&nbsp; R&D &nbsp;&nbsp;&nbsp;&nbsp; 2017.08 - 2018.04**
  
    Improve the click raito of recommended hot queries on Baidu search result page, enhance Baidu Fengyunbang's influence.

    Resonsibilities: *1)* Crawled down news title from news web, filtered and deduplicated for the source of hot queries; *2)* **Devised a new ranking algorithm** to improve the click ratio of recommended hot queries; *3)* Cooperated with PM to upgrade other products, such as [Baidu mobile Doodle landing page](https://m.baidu.com/s?word=%E4%BB%8A%E6%97%A5%E6%96%B0%E9%B2%9C%E4%BA%8B&from=1020853c&sa=ire_dl_gh_logo_ws); *4)* Maintained <http://top.baidu.com> and expanded hot queris inlets and outlets.

    Achievements: *1)* **Increased the click ratio** on Baidu PC search result page from 0.6% to 0.85%, **by 40%**; *2)* [2017 Baidu Feidian data](http://top.baidu.com/2017) (annual hot searches).


* **SendCats&nbsp;&nbsp;&nbsp;Co-founder/Front-end&nbsp;&nbsp;&nbsp;2015.05 - 2016.09**
  
    An entrepreneurship project was aiming at building a platform for the sharing of graduates' study resources, experience, and valuable own-service.

    Responsibilities: *1)* Established front-end technology route, constructed front-end system (*AngularJS & BootStrap*); *2)* Systemsized auto-test (*Karma*) and auto-deploy (Gulp) of front-end; *3)* Completed file upload/download based on *Qiniu* cloud storage; *4)* Participated in talks and meetings of product, future planning, and other business of a start-up.    

<!-- 
* **Manage and Analysis of Indoor Moving Objects on Hadoop, Hase&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Subject/Designer/Developer&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Dec. 2015 - Present**

	*Description:* Taking advantage of **HBase** to store massive data of indoor moving objects, build a **Spatial-
	Temporal Index** mainly by designing a resonable **row-key** of hbase, then make some data mining work on **Spark**.
	
	*Responsibilities:* ***a.*** **Setting up basic environment** such as *Hadoop, Hbase, Spark* on a seven-nodes cluster, ***b.*** **design the row-key composition** based on the analysis of feature of *IMO*s , ***c.*** *TODO*:**provide API of data query** and do some **data-mining** work(expected in scala).
	
	
* **HER &nbsp;&nbsp;&nbsp;Business Project/Developer&nbsp;&nbsp;Oct. 2014 - Mar. 2015**

	*Descripiton:* *HER* is short for Hazard, Exposure, Risk. It utilizes historical hazard data, exposure data, and insurance policy data to predict risk probability and whether a new policy is worth to take. Launched by a Dr. of Structure who resigned from a reinsurance company.
	
	*Responsibilities:* ***a.*** Find, analyze and **crawl down** accessible hazard, exposure data, coded in Python, ***b.*** **design table structure** for GIS data on *PostGIS*, maintain datatbase, ***c.*** provide **data query API** for business staff in *Java*.
	
* **A web campus map for Henan Polytechnic University based on Baidu Map JS-API&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Student Quality Training Program/Team leader/Developer&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Oct. 2012 - Jan. 2013**

	*Description:* Build a ***web campus map*** for my own university based on free accessible map API.
	
	*Responibilities:* ***a.*** act as **team leader** of a six-people group, including data collectors and developers, ***b.*** **design and develop** system, *ASP.NET* for server side and *JS* for map showing and manipulation. ***c.*** establish and maintain *SQL Server* database.
-->
	
## Interns, Honors, etc.
* Allenaya, LLC. Beijing, China.&nbsp;&nbsp;&nbsp;&nbsp;  Developer&nbsp;&nbsp;&nbsp;&nbsp;2014.10 - 2015.01



* Key Lab. of Mine Spaital Information Technic, National Administration of Surving, Mapping and GeoInformation, Jiaozuo, China&nbsp;&nbsp;&nbsp;&nbsp;  Developer&nbsp;&nbsp;&nbsp;&nbsp; 2012.10 - 2013.05



* National Encouragement Scholarship, First-class Scholarship (twice), etc. 2011-2013


* National Computer Rank Examination, 4th grade, Database Engineer, 2013


* 2015 Beijing Marathon, Dr. Chorus, Annual Conference of *CSNR*, 2015, etc.&nbsp;&nbsp;&nbsp;&nbsp; Volunteer&nbsp;&nbsp;&nbsp;&nbsp; 2014 - 2015
