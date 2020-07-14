# Tools for media and communication research

A list of digital tools and resources for journalism, media and communication research, and computational social science.

## Find datasets

Search engines:

- [Google Dataset Search](https://toolbox.google.com/datasetsearch) - search engine for datasets.
- [re3data.org](http://www.re3data.org/)
- [Metadata Search](http://search.datacite.org/ui)

Archives and lists:

- [A dataset with political datasets](https://github.com/erikgahner/PolData) - Cabinets, citizens, constitutions, political institutions, parties and politicians, democracy, economics, elections, international relations, media, policy, political elites (.xlsx, .csv, .Rdata, .sav).
- [Consortium of European Social Science Data Archives (CESSDA)](http://cessda.net/)
- [Inter-university Consortium for Political and Social Research (ICPSR)](http://www.icpsr.umich.edu/icpsrweb/ICPSR/index.jsp)
- [Open Stats Lab](https://sites.trinity.edu/osl) data from psychological studies that is intended to be used in education.
- [Awesome Public Datasets](https://github.com/vnijs/awesome-public-datasets) - awesome list of (large-scale) public datasets on the Internet (on-going collection).
- [Common Crawl](http://commoncrawl.org/) - download a copy of the web, several billion web pages (250+ terabyte of data), updated regularly.
- [Öppna Data](https://oppnadata.se/) - open data in Sweden (from Riksarkivet).

Survey data:

- [European Social Survey](http://www.europeansocialsurvey.org/) - survey conducted across Europe since 2001. Face-to-face interviews every two years on new cross-sectional samples.
- [European Values Study](https://europeanvaluesstudy.eu/) - large-scale, cross-national survey since 1981 about basic human values (e.g., ideas, beliefs, preferences, attitudes). New surveys every nine years.
- [The General Social Survey 1972–](http://gss.norc.org/) (USA)
- [Latin American Public Opinion Project](https://www.vanderbilt.edu/lapop/raw-data.php) (North and South America)
- [SOM Institute 1986–](https://snd.gu.se/sv/catalogue/search/SOM) (Sweden)

Media data:

- [IMDB Ratings for TV/Streaming Series](https://github.com/nazareno/imdb-series/) - dataset of ratings given in IMDB to episodes of popular TV and Streaming series (includes R code).

## Content analysis, text analysis, text mining

- [Text Mining for Social Scientists and Digital Humanists](https://tm4ss.github.io/docs/) ([GitHub](https://github.com/tm4ss/tm4ss.github.io)) (R)
- [Lexicoder](http://www.lexicoder.com/) - multi-platform software for automated content analysis of text (Java).
- [SentimentAnalysis](https://github.com/sfeuerriegel/SentimentAnalysis) - sentiment analysis of text (R).
- [Topic Models Learning and R Resources](https://github.com/trinker/topicmodels_learning)
- [Count Words in a PDF Document](https://leeper.shinyapps.io/pdfcount/) (online tool).

## Compare differences between texts, find duplicate files

- [Diff Checker](https://www.diffchecker.com/) - compare two texts for differences (online tool).
- [Online LaTeX diff tool](https://3142.nl/latex-diff/) - to compare text differences in LaTeX documents using [latexdiff](https://ctan.org/pkg/latexdiff) (online tool).
- [Auslogics Duplicate File Finder](https://www.auslogics.com/en/software/duplicate-file-finder/) - finds duplicate files regardless of their filenames (Windows app).
- [comparefiles](https://github.com/peterdalle/comparefiles) - scans a directory for identical files or similar text files (Python).

## Social networking sites and specific sites

### Facebook

- [Facepager](https://github.com/strohne/Facepager) - fetches publicly available data from Facebook, Twitter and other JSON-based API:s (Python).
- [facebook-page-post-scraper](https://github.com/minimaxir/facebook-page-post-scraper) - data scraper for Facebook Pages (Python).
- [PolitEcho](http://politecho.org ) ([GitHub](https://github.com/politecho/politecho)) - shows you the political biases of your Facebook friends and news feed (Chrome extension).
- [netvizz](https://github.com/bernorieder/netvizz) - collection of scripts that help with downloading data from the Facebook platform for research purposes (important about Facebook API changes, read [Facebook’s app review and how independent research just got a lot harder](http://thepoliticsofsystems.net/2018/08/facebooks-app-review-and-how-independent-research-just-got-a-lot-harder/)).
- [Facebook API](https://developers.facebook.com/).

### Twitter

- [twarc](https://github.com/DocNow/twarc) - command line tool for archiving Twitter JSON (Python).
- [tweetbotornot](https://github.com/mkearney/tweetbotornot) - detect Twitter bots via machine learning (R).
- [Twint](https://github.com/twintproject/twint) - Twitter scraping and open source intelligens (OSINT) tool that doesn't use Twitter's API, allowing you to scrape a user's followers, following, Tweets and more while evading most API limitations (Python).
- [Tinfoleak](http://www.vicenteaguileradiaz.com/tools/) ([GitHub](https://github.com/vaguileradiaz/tinfoleak)) - open-source tool for Twitter intelligence analysis (Python).
- [Tweetbeaver](https://tweetbeaver.com/) - convert @name to ID, check if two accounts follow each other, download a user's favorites, search within a user's favorites, download a user's timeline etc (online tool).
- [scrape-twitter](https://github.com/sebinsua/scrape-twitter) - Command line interfaces to scrape profiles, timelines, connections, likes, search and conversations with the use of API (Node.js).
- [Chorus](http://chorusanalytics.co.uk/) - free Twitter harvesting and visual analytics suite for social science research (Windows).
- [Twitter API](https://developer.twitter.com/).
- [Twitter - helpful tools](https://developer.twitter.com/en/use-cases/academic-researchers/helpful-tools) - Twitter lists helpful tools for data access, data analysis, data visualization, and hosting.

### Wikipedia

- [Pageviews Analysis tool for Wikimedia Foundation wikis](https://tools.wmflabs.org/pageviews/?project=en.wikipedia.org&platform=all-access&agent=user&range=latest-20&pages=Echo_chamber_(media)|Filter_bubble) ([GitHub](https://github.com/MusikAnimal/pageviews)) - number of page views for any Wikipedia page (online tool, PHP).
- [WikiMedia REST API](https://www.mediawiki.org/wiki/REST_API) - access to Wikipedia content, data, and statistics (online API).
- [WikiShark](https://www.wikishark.com/) - Wikipedia article traffic (page views) since 2008, updated every hour or so.
- [Page view statistics for Wikimedia projects 2008-2016](https://dumps.wikimedia.org/other/pagecounts-raw/) - download all dumps from Wikipedia with page views for all projects from 2008 to 2016.
- [Analytics Datasets: Pageviews 2016 onwards](https://dumps.wikimedia.org/other/pageviews/readme.html) - download all dumps from Wikipedia with page views for all projects from 2016 onwards. Don't forget that you can use the API instead for easier access, but note that the API only has data from year 2015 onwards.

### Google

- [Google Trends](https://trends.google.com/trends/) - number of searches for a specific search query (online tool).
- [Google Ngram Viewer](https://books.google.com/ngrams) - shows number of times a phrase have occurred in a books from year 1800 to 2000 (online tool).
- [GoogleScraper](https://github.com/NikolaiT/GoogleScraper) - scrape search engines (e.g., Google, Yandex, Bing, Duckduckgo, Baidu) by using proxies (socks4/5, http proxy) and many IP's, including asynchronous networking support (Python).
- [Lumen database](https://lumendatabase.org/) - collects and analyzes legal complaints and requests for removal of online materials such as Google search results (online tool).
- [Google Books](https://developers.google.com/books/docs/v1/getting_started) - search for books (online API).
- [YouTube comment scraper](http://ytcomments.klostermann.ca/scrape) - scrape comments from YouTube videos, download comments as JSON or CSV (online tool).
- [youtube-dl](https://github.com/ytdl-org/youtube-dl) - download YouTube videos or videos from other sites (Python).

### Reddit

- [PRAW](https://praw.readthedocs.io/en/latest/) - Library for API access to Reddit (Python).
- [RedditExtractoR](https://www.rdocumentation.org/packages/RedditExtractoR) - Package for API access to Reddit (R).

### Misc sites

- [Creepy](http://www.geocreepy.com) ([GitHub](https://github.com/ilektrojohn/creepy)) - a geolocation OSINT tool. Offers geolocation information gathering through social networking platforms (Python). 
- [flashback](https://github.com/miroli/flashback) - scrapes Swedish Flashback forum https://www.flashback.org/ (Python).
- [Instagram API](https://instagram.com/developer) (online API).
- [New York Times API](http://developer.nytimes.com/) - latest articles, top articles, book bestsellers, search articles from year 1851, and more (online API).
- [OMDb API](http://www.omdbapi.com/) - obtain movie information, content and images mainted by users (online API).
- [Rotten Tomatoes API](http://developer.rottentomatoes.com/io-docs/docs) - movie reviews (online API).
- See also [any-api.com](https://any-api.com/).

## Scrape and extract news articles

- [GDELT Project](http://gdeltproject.org/) - archives all news media events around the globe.
- [The Social, Political and Economic Event Database Project (SPEED)](https://clinecenter.illinois.edu/project/human-loop-event-data-projects/SPEED) - comprehensive news sources from 1945 onwards, crawls over 5,000 news feeds in 120 countries several times each day, scraping news reports, totalling over 40 million news reports.
- [mediacloud](https://github.com/berkmancenter/mediacloud) - open source, open data platform that allows researchers to answer quantitative questions about the content of online media (Perl/Python).
- [Trove](https://trove.nla.gov.au/) - Find and get Australian and online resources: books, images, historic newspapers, maps, music, archives and more.
- [newsdiffs](https://github.com/ecprice/newsdiffs) - automatic scraper that tracks changes in news articles over time (Python).
- [newsflash](https://github.com/hrbrmstr/newsflash) - tools to work with the Internet Archive and GDELT Television Explorer (R).
- [newspaper](https://github.com/codelucas/newspaper) - news, full-text, and article metadata extraction, based on [python-goose](https://github.com/grangier/python-goose) (Python).
- [news-please](https://github.com/fhamborg/news-please) - integrated web crawler and information extractor for news that just works  (Python).
- [Newsmap](https://github.com/koheiw/newsmap) - semi-supervised geographical news classifier (R). [Journal article](https://doi.org/10.1080/21670811.2017.1293487).
- [Scrapy](https://github.com/scrapy/scrapy) - fast high-level web crawling and web scraping framework (Python).

## Online archives and archiving

- [Internet Archive](https://archive.org/) - non-profit digital library offering free universal access to books, movies & music (online tool).
- [Wayback Machine](https://archive.org/web/) - 343 billion archived web pages from Internet Archive (online tool).
- [archive.is](https://archive.is/) - take a snapshot of a webpage that will always be online even if the original page disappears (online tool).

## Journal articles, citations, bibliometrics

- [journal-spider](https://github.com/chartgerink/journal-spiders) - tools to spider journal websites for links to articles (Python).
- [Claim Extraction for Scientific Publications](https://github.com/titipata/detecting-scientific-claim) - detect claims (e.g. "background", "conclusion") from scientific publication using discourse and sentence embedding (Python).
- [scholar.py](https://github.com/ckreibich/scholar.py) - parser for Google Scholar (Python).
- [OpenCitations](http://opencitations.net/) - search and browse OpenCitations Corpus (OCC) of open downloadable bibliographic and citation data recorded in RDF (online API).
- [metaknowledge](http://networkslab.org/metaknowledge/) - computational research in bibliometrics, scientometrics, and network analysis (Python).
- [pdfx](https://github.com/metachris/pdfx) - extract references (pdf, url, doi, arxiv) and metadata from a PDF. Download all referenced PDFs (Python).

Retractions:

- https://retractionwatch.com/
- http://retractiondatabase.org/
- http://openretractions.com/

## Behavioral and cognitive experiments

- [jsPsych](http://www.jspsych.org) ([GitHub](https://github.com/jspsych/jsPsych/)) - library for creating and running behavioral experiments in a web browser (JavaScript).
- [OpenSeasme](http://osdoc.cogsci.nl/about/) - graphical, open-source experiment builder for social sciences. Build complex experiments with minimal effort, create a wide range of experiments. Plug-in framework and Python scripting allows you to incorporate external devices, such as eye trackers, response boxes, and parallel port devices (Windows/Mac/Linux).
- [PlanOut](https://facebook.github.io/planout/) - framework for online field experiments. Makes it easy to run and iterate on sophisticated experiments in a statistically sound manner while satisfying the constraints of deployed Internet services (Python/JS/Java/PHP/Go/Lua/Ruby).
- [PsychoPy](http://www.psychopy.org/) - allow presentation of stimuli and collection of data for a wide range of neuroscience, psychology and psychophysics experiments (Python).
- [WebExp](http://groups.inf.ed.ac.uk/webexp/) - system for conducting psychological experiments over the web (Java).
- [conjoint-example](https://github.com/leeper/conjoint-example) - example conjoint experimental design in Qualtrics.
- [PsyToolkit](https://www.psytoolkit.org/) - free toolkit for demonstrating, programming, and running cognitive-psychological experiments and surveys, including personality tests (online tool).
- [Empirica](https://empirica.ly/) - framework for running multiplayer interactive experiments and games in the browser (JavaScript).

## Graphics, network visualizations and maps

- [Dia](http://dia-installer.de/) - app to draw structured diagrams (Windows/Mac/Linux).
- [Gephi](https://gephi.org/) - visualization and exploration app for all kinds of graphs and networks (Windows/Mac/Linux).
- [QGIS](http://www.qgis.org/) - free and open source geographic information system app (Windows/Mac/Linux).
- [Inkscape](https://inkscape.org/) - free and open source desktop program to draw vector graphics like Adobe Illustrator (Windows/Mac/Linux).
- [From Data to Viz](https://www.data-to-viz.com/) - leads you to the most appropriate graph for your data, links to the code to build it and lists common caveats you should avoid (online tool).

## Convert and clean data

- [OpenRefine](http://openrefine.org/) - powerful tool for working with messy data: cleaning it; transforming it from one format into another; and extending it with web services and external data, formerly called Google Refine (Windows/Mac/Linux).
- [Mr. Data Converter](https://shancarter.github.io/mr-data-converter/) - convert Excel data into web-friendly formats such as HTML, JSON and XML (online tool).
- [PSPP File Conversion Service](https://pspp.benpfaff.org/) - convert SPSS (.sav) files to CSV or text format (online tool).

## Survey scales and measures

- [Media Exposure Measures](https://mediaexposuremeasures.org/) from Amsterdam School of Communication Research (ASCoR).
- [The Semantic Scale Network](https://rosenbusch.shinyapps.io/semantic_net/) - online app that detect semantically related scales. Input a scale item and get a similar scales/items back (contains 2,300 scales and 30,000 items).
- [Measurement Instrument Database for the Social Sciences (MIDSS)](http://www.midss.org/)
- [Decision Making Individual Differences Inventory (DMIDI)](http://www.sjdm.org/dmidi/)
- [PsycTESTS - psychological measures, scales, and instrumentation tools](http://www.apa.org/pubs/databases/psyctests/)

## Survey software

- [qualtRics](https://github.com/ropensci/qualtRics) - Download and import qualtrics survey data directly (R).

## Statistics and questionable research practices (QRP's)

- [GRIM Test](https://medium.com/@jamesheathers/the-grim-test-a-method-for-evaluating-published-research-9a4e5f05e870) checks if the reported means match with number of items and type of scale (see also [GRIMMER test](https://peerj.com/preprints/2400/)).
- [SPRITE](https://hackernoon.com/introducing-sprite-and-the-case-of-the-carthorse-child-58683c2bfeb) check the type of distributions that could have produced the reported descriptive statistics.
- [statcheck](http://statcheck.io/) checks if p-values match reported statistics.
- [Test of Insufficient Variance (TIVA)](https://replicationindex.wordpress.com/2014/12/30/the-test-of-insufficient-variance-tiva-a-new-tool-for-the-detection-of-questionable-research-practices/) checks wether reported p-values was obtained using questionable research practices.

## Statistical software

Programs such as [SPSS](https://www.ibm.com/analytics/se/sv/technology/spss/), [Stata](http://www.stata.com/), [SAS](http://www.sas.com/), and [Comprehensive Meta analysis](https://www.meta-analysis.com/) costs money.

Free data analysis and exploration software:

- [Data Explorer](http://www.data-explorer.com/)
- [Tableau](http://www.tableau.com/) - free version for academic use.
- [GNU PSPP](http://www.gnu.org/software/pspp/) - free alternative to SPSS, looks the same and have all basic SPSS functions.
- [R](https://www.r-project.org/) - programming language for statistics.
- [JASP](https://jasp-stats.org/download/) - built on top of R.
- [Jamovi](https://www.jamovi.org/) - developed from JASP.
- [G\*Power](http://www.gpower.hhu.de/) - statistical power analysis.
- [ESCI (Exploratory Software for Confidence Intervals)](http://www.latrobe.edu.au/psychology/research/research-areas/cognitive-and-developmental-psychology/esci/2001-to-2010) - simulate confidence intervals using Microsoft Excel.
- [Process macro for SPSS and SAS](http://processmacro.org/download.html) - plugin for moderator and mediator analysis.
- [Power and N Computations for Mediation](https://davidakenny.shinyapps.io/MedPower/) - online tool by David A. Kenny to calculate power or sample size.
- [Calculator for false positive risk (FPR)](http://fpr-calc.ucl.ac.uk/) - If you observe a significant p-value after a single experiment, what's the probability that your result is a false positive? By Colin Longstaff, David Colquhoun, Brendan Halpin.

Convert effect sizes:

- [Effect Size Calculator](https://www.campbellcollaboration.org/this-is-a-web-based-effect-size-calculator/explore/this-is-a-web-based-effect-size-calculator)
- [Web Pages that Perform Statistical Calculations!](http://statpages.info/)
- [Free Statistics Calculator](http://www.danielsoper.com/statcalc/default.aspx)
- [VassarStats: Website for Statistical Computation](http://vassarstats.net/)
- [Equivalent Statistics](http://psych.purdue.edu/~gfrancis/EquivalentStatistics/)
- [Practical Meta-Analysis Effect Size Calculator](https://www.campbellcollaboration.org/escalc/html/EffectSizeCalculator-SMD-main.php)

## Organize photos, citations and references

- [EndNote](http://endnote.com/) - bibliography reference manager.
- [JabRef](http://www.jabref.org/) - bibliography reference manager using BibTeX (free).
- [Mendeley](https://www.mendeley.com/) - bibliography reference manager (free).
- [ReadCube Papers](https://www.readcube.com/) - bibliography reference manager.
- [Zotero](https://www.zotero.org/) - bibliography reference manager (free).
- [Tropy](https://tropy.org/) - organize research photos and images (free).

## Education

- [Data Journalism Courses](https://github.com/jwyg/data-journalism-courses) - list of data journalism courses and programmes from universities and higher education institutions around the world.

## Organizations

- [Digital Methods Initiative](https://wiki.digitalmethods.net/Dmi/) ([GitHub](https://github.com/digitalmethodsinitiative)) - contribution to doing research into the "natively digital".
- [DocNow](https://www.docnow.io/) - tool/community that supports ethical collection, use, and preservation of social media content.

## Open science, preregistration, code/data sharing

- [Open Science Framework (OSF)](https://osf.io/) - add your research project and collaborate, store data, preregister (see [Prereg Challenge](https://osf.io/prereg/)) and more.
- [As predicted](https://aspredicted.org/) - preregister your hypothesis test.
- [figshare](https://figshare.com/) - upload your data and get more citations.
- [Dataverse](https://dataverse.org/) - open source web app to share, preserve, cite, explore, and analyze research data.
- [SocArxiv](https://osf.io/preprints/socarxiv) - share your manuscript and get feedback as a pre-print before journal publication.
- [Collection of preregistered studies](https://www.zotero.org/groups/479248/osf/items/collectionKey/VKXUAZM7) from OSF. See also [Registered Protocols](https://www.zotero.org/groups/479248/osf/items/collectionKey/G64VMW96) and [Registered Reports](https://www.zotero.org/groups/479248/osf/items/collectionKey/KEJP68G9).
- [Top factor](https://cos.io/top/) - ranking of scientific journals based on open science practices.

## See also

More lists:

- [Awesome Web Archiving Awesome](https://github.com/iipc/awesome-web-archiving) - awesome list for getting started with web archiving.
- [Awesome R](https://awesome-r.com/) - curated list of awesome R packages and tools, find packages by category. 
- [awesome-r](https://github.com/uhub/awesome-r) - yet another list of awesome R frameworks, libraries and software.
- [Social media collection tools](http://socialmediadata.wikidot.com/) - by Deen Freelon.
- [Social media methodologies](https://socialmediamethodologies.wordpress.com/)

Tutorials:

- [Using Twitter as a data source: an overview of social media research tools (updated for 2017)](http://blogs.lse.ac.uk/impactofsocialsciences/2017/05/08/using-twitter-as-a-data-source-an-overview-of-social-media-research-tools-updated-for-2017/)
- [Using Google Trends data for research? Here are 6 questions to ask](https://medium.com/@pewresearch/using-google-trends-data-for-research-here-are-6-questions-to-ask-a7097f5fb526)
- [Introduction to data management best practices](https://mattiheino.com/2017/09/09/intro-data-management/)
- [Getting Started in Open Source: A Primer for Data Scientists](http://blog.districtdatalabs.com/getting-started-in-open-source)
- [Introductory guide to Open Source media network analysis for beginners](https://medium.com/@kesterratcliff/easy-osint-open-source-intelligence-techniques-for-beginners-and-some-links-to-intermediate-and-413f41580b8d)

Literature:

- Boumans, J. W., & Trilling, D. (2016). Taking Stock of the Toolkit: An overview of relevant automated content analysis approaches and techniques for digital journalism scholars. Digital Journalism, 4(1), 8–23. https://doi.org/10.1080/21670811.2015.1096598
- Burscher, B., Odijk, D., Vliegenthart, R., de Rijke, M., & de Vreese, C. H. (2014). Teaching the Computer to Code Frames in News: Comparing Two Supervised Machine Learning Approaches to Frame Analysis. Communication Methods and Measures, 8(3), 190–206. https://doi.org/10.1080/19312458.2014.937527
- Freelon, D. (2015). On the cutting edge of Big Data: Digital politics research in the social computing literature. In S. Coleman & D. Freelon (Eds.), Handbook of Digital Politics (p. 448). Northampton, MA: Edward Elgar.
- Jacobi, C., van Atteveldt, W., & Welbers, K. (2016). Quantitative analysis of large amounts of journalistic texts using topic modelling. Digital Journalism, 4(1), 89–106. https://doi.org/10.1080/21670811.2015.1093271
- Lazer, D., & Radford, J. (2017). Data ex Machina: Introduction to Big Data. Annual Review of Sociology, 43(1). https://doi.org/10.1146/annurev-soc-060116-053457
- Wilkerson, J., & Casas, A. (2017). Large-Scale Computerized Text Analysis in Political Science: Opportunities and Challenges. Annual Review of Political Science, 20(1), 529–544. https://doi.org/10.1146/annurev-polisci-052615-025542

Podcast episodes:

- Social Media and Politics (August, 2018) [#53: Computational Social Science and Digital Methods in the Post-API Age, with Dr. Deen Freelon](https://socialmediaandpolitics.simplecast.fm/digital-methods-post-api-era)

Facebook groups:

- [Association of Internet Researchers (AoIR)](https://www.facebook.com/groups/aoirlist/) (3,400+ members)
- [OpenCOMM: Open/Replicable/Reproducible Methods/Analyses in Communication](https://www.facebook.com/groups/OpenCOMMResearch/) (280+ members)
- [Political Communication](https://www.facebook.com/groups/politicalcommunication.org) (3,800+ members)
