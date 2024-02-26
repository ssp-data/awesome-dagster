Awesome Dagster
==========================

> Please visit the offical [awesome-dagster](https://github.com/dagster-io/awesome-dagster) repo by dagster. I moved the relevant content over there.

A curated list of dagster code snippets for data engineers [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

List of content

1. [Resources](#resources)
2. [Solids](#solids)
3. [Hooks](#hooks)
4. [Types](#types)
5. [Docker Images](#docker-images)

# Resources
- Data Warehouse
	* [Apache Druid](https://github.com/sspaeti-com/dagster-data-pipelines/blob/main/src/pipelines/real-estate/realestate/common/resources.py#L43) Connector resource to send GET/POST REST-Requests
- Relational
	* [MySQL](https://github.com/mitodl/ol-data-pipelines/blob/main/src/ol_data_pipelines/resources/mysql_db.py) Instantiate a connection to a MySQL database and run queries
- Monitoring
	* [HealthcheckIO](https://github.com/mitodl/ol-data-pipelines/blob/main/src/ol_data_pipelines/resources/healthchecks.py) Send updates to Cron job monitoring HealthcheckIO

# Solids
- Spark & Delta-Lake
	* [Spark and Delta Lake](https://github.com/sspaeti-com/dagster-data-pipelines/blob/main/src/pipelines/real-estate/realestate/common/solids_spark_delta.py) Solids to create Delta-Table ` create_delta_table`, load data from a Delta-Table into a Spark-df ` create_delta_table`
- Scrapting
	* [Web-Scraping and Caching](https://github.com/sspaeti-com/dagster-data-pipelines/blob/main/src/pipelines/real-estate/realestate/common/solids_scraping.py) Web-scraping with BeautifulSoup

# Hooks
* [Success and Failure Hook](https://github.com/mitodl/ol-data-pipelines/blob/main/src/ol_data_pipelines/lib/hooks.py) and [Pipeline Example](https://github.com/mitodl/ol-data-pipelines/blob/main/src/ol_data_pipelines/edx/solids.py#L585) How to use Hooks on failure or on error
# Types
* [JsonType](https://github.com/sspaeti-com/dagster-data-pipelines/blob/main/src/pipelines/real-estate/realestate/common/types_realestate.py#L46) A valid representation of a JSON, validated with json.loads()

# Docker Images
* [Everything but the Kitchen Sink Image](https://github.com/dagster-io/dagster/blob/b0d8d485182b94a6f3cbfa2bdc81a67996763275/python_modules/automation/automation/docker/images/buildkite-integration-base/Dockerfile) Image to run Spark and a whole lot more
* [Spark](TBD) Image to run Spark and Delta-Lake

# Community

## Forums
* [GitHub Discussions](https://www.reddit.com/r/dataengineering/) News, ideas, Q&A and more about Dagster
* [Slack Channel](https://dagster-slackin.herokuapp.com/) Questions and Discussions

## Podcasts
* [Data Engineering Podcast - Build Maintainable And Testable Data Applications With Dagster - Episode 104](https://www.dataengineeringpodcast.com/dagster-data-applications-episode-104/) _October 28, 2019_: Fist podcast about Dagster where Nick Schrock the founder explains the motivation and the story behind Dagster.
* [Software Engineering Daily - Dagster with Nick Schrock](https://softwareengineeringdaily.com/2019/11/15/dagster-with-nick-schrock/) _November 15, 2019_: Second podcast with different insight from the software engineering perspective
* [Python Podcast - Digging Into Dagster: An Opinionated Open Source Framework For Data Orchestration - Episode 279](https://www.pythonpodcast.com/dagster-data-orchestration-episode-279/) _September 7, 2020_: Update on Dagster after a year.

## Slides
* [Running Pipelines In Production](https://docs.google.com/presentation/d/1TKL9kem6SDyPr0MADOQIRqwvFgHOF7_gJ9Hqdubiuhs/edit?usp=sharing) Using Dagster to replace a homegrown Cron job
* [Bestplaces and their Journey](https://drive.google.com/file/d/1BSaQmSc9szcKTT16-B_HzwPIYUKuxe81/view) A journey from various heterogeneous Tools to integrated Dagster Environment
* [Dagster Migration At Prezi](https://prezi.com/view/kveaLi8KasReSs4pyP5l/) From JSON based homegrown orchestrator to Dagster

Inspired by the [Awesome](https://github.com/sindresorhus/awesome) list of [Data Engineering](https://github.com/igorbarinov/awesome-data-engineering) by [Igor Barinov](https://github.com/igorbarinov/).

## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Simon Späti](https://www.sspaeti.com/blog/#about) has waived all copyright and related or neighboring rights to this work.
