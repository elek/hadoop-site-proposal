Welcome to Apache™ Hadoop®!
<div class="section">

What Is Apache Hadoop?
The Apache™ Hadoop® project develops open-source software for reliable,
scalable, distributed computing.

The Apache Hadoop software library is a framework that allows for the
distributed processing of large data sets across clusters of computers
using simple programming models. It is designed to scale up from single
servers to thousands of machines, each offering local computation and
storage. Rather than rely on hardware to deliver high-availability, the
library itself is designed to detect and handle failures at the
application layer, so delivering a highly-available service on top of a
cluster of computers, each of which may be prone to failures.

The project includes these modules:

-   **Hadoop Common**: The common utilities that support the other
    Hadoop modules.
-   **Hadoop Distributed File System (HDFS™)**: A distributed file
    system that provides high-throughput access to application data.
-   **Hadoop YARN**: A framework for job scheduling and cluster resource
    management.
-   **Hadoop MapReduce**: A YARN-based system for parallel processing of
    large data sets.

Other Hadoop-related projects at Apache include:

-   [**Ambari™**](ext:ambari): A web-based tool for provisioning,
    managing, and monitoring Apache Hadoop clusters which includes
    support for Hadoop HDFS, Hadoop MapReduce, Hive, HCatalog, HBase,
    ZooKeeper, Oozie, Pig and Sqoop. Ambari also provides a dashboard
    for viewing cluster health such as heatmaps and ability to view
    MapReduce, Pig and Hive applications visually alongwith features to
    diagnose their performance characteristics in a user-friendly
    manner.
-   [**Avro™**](ext:avro): A data serialization system.
-   [**Cassandra™**](ext:cassandra): A scalable multi-master database
    with no single points of failure.
-   [**Chukwa™**](ext:chukwa): A data collection system for managing
    large distributed systems.
-   [**HBase™**](ext:hbase): A scalable, distributed database that
    supports structured data storage for large tables.
-   [**Hive™**](ext:hive): A data warehouse infrastructure that provides
    data summarization and ad hoc querying.
-   [**Mahout™**](ext:mahout): A Scalable machine learning and data
    mining library.
-   [**Pig™**](ext:pig): A high-level data-flow language and execution
    framework for parallel computation.
-   [**Spark™**](ext:spark): A fast and general compute engine for
    Hadoop data. Spark provides a simple and expressive programming
    model that supports a wide range of applications, including ETL,
    machine learning, stream processing, and graph computation.
-   [**Tez™**](ext:tez): A generalized data-flow programming framework,
    built on Hadoop YARN, which provides a powerful and flexible engine
    to execute an arbitrary DAG of tasks to process data for both batch
    and interactive use-cases. Tez is being adopted by Hive™, Pig™ and
    other frameworks in the Hadoop ecosystem, and also by other
    commercial software (e.g. ETL tools), to replace Hadoop™ MapReduce
    as the underlying execution engine.
-   [**ZooKeeper™**](ext:zookeeper): A high-performance coordination
    service for distributed applications.

</div>

<div class="section">

Getting Started
To get started, begin here:

1.  [Learn about](ext:docs/current) Hadoop by reading the documentation.
2.  [Download](releases.html) Hadoop from the release page.
3.  [Discuss](mailing_lists.html) Hadoop on the mailing list.

</div>

<div class="section">

Download Hadoop
Please head to the [releases](releases.html) page to download a release
of Apache Hadoop.

</div>

<div class="section">

Who Uses Hadoop?
A wide variety of companies and organizations use Hadoop for both
research and production. Users are encouraged to add themselves to the
Hadoop [PoweredBy](http://wiki.apache.org/hadoop/PoweredBy) wiki page.

</div>

<div class="section">

News
<div class="section">

25 January, 2017: Release 3.0.0-alpha2 available
This is the second alpha in a series of planned alphas and betas leading
up to a 3.0.0 GA release. The intention is to "release early, release
often" to quickly iterate on feedback collected from downstream users.

Please note that alpha releases come with no guarantees of quality or
API stability, and are not intended for production use.

Users are encouraged to read the [overview of major
changes](http://hadoop.apache.org/docs/r3.0.0-alpha2/index.html) coming
in 3.0.0. The alpha2 [release
notes](http://hadoop.apache.org/docs/r3.0.0-alpha2/hadoop-project-dist/hadoop-common/release/3.0.0-alpha2/RELEASENOTES.3.0.0-alpha2.html)
and
[changelog](http://hadoop.apache.org/docs/r3.0.0-alpha2/hadoop-project-dist/hadoop-common/release/3.0.0-alpha2/CHANGES.3.0.0-alpha2.html)
detail 857 fixes, improvements, and new features since the previous
3.0.0-alpha2 release.

</div>

<div class="section">

08 October, 2016: Release 2.6.5 available
A point release for the 2.6 line.

Please see the [Hadoop 2.6.5 Release
Notes](http://hadoop.apache.org/docs/r2.6.5/hadoop-project-dist/hadoop-common/releasenotes.html)
for the list of 79 critical bug fixes and since the previous release
2.6.4.

</div>

<div class="section">

03 September, 2016: Release 3.0.0-alpha1 available
This is the first alpha in a series of planned alphas and betas leading
up to a 3.0.0 GA release. The intention is to "release early, release
often" to quickly iterate on feedback collected from downstream users.

Please note that alpha releases come with no guarantees of quality or
API stability, and are not intended for production use.

Users are encouraged to read the [overview of major
changes](http://hadoop.apache.org/docs/r3.0.0-alpha1/index.html) coming
in 3.0.0. The [full set of release
notes](http://hadoop.apache.org/docs/r3.0.0-alpha1/hadoop-project-dist/hadoop-common/release/3.0.0-alpha1/RELEASENOTES.3.0.0-alpha1.html)
and
[changelog](http://hadoop.apache.org/docs/r3.0.0-alpha1/hadoop-project-dist/hadoop-common/release/3.0.0-alpha1/CHANGES.3.0.0-alpha1.html)
detail all the changes since the previous minor release 2.7.0.

</div>

<div class="section">

25 August, 2016: Release 2.7.3 available
A point release for the 2.7 line.

Please see the [Hadoop 2.7.3 Release
Notes](http://hadoop.apache.org/docs/r2.7.3/hadoop-project-dist/hadoop-common/releasenotes.html)
for the list of 221 bug fixes and patches since the previous release
2.7.2.

</div>

<div class="section">

11 February, 2016: Release 2.6.4 available
A point release for the 2.6 line.

Please see the [Hadoop 2.6.4 Release
Notes](http://hadoop.apache.org/docs/r2.6.4/hadoop-project-dist/hadoop-common/releasenotes.html)
for the list of 46 critical bug fixes and since the previous release
2.6.3.

</div>

<div class="section">

25 January, 2016: Release 2.7.2 (stable) available
A point release for the 2.7 line.

Please see the [Hadoop 2.7.2 Release
Notes](http://hadoop.apache.org/docs/r2.7.2/hadoop-project-dist/hadoop-common/releasenotes.html)
for the list of 155 bug fixes and patches since the previous release
2.7.1.

</div>

<div class="section">

17 December, 2015: Release 2.6.3 available
A point release for the 2.6 line.

Please see the [Hadoop 2.6.3 Release
Notes](http://hadoop.apache.org/docs/r2.6.3/hadoop-project-dist/hadoop-common/releasenotes.html)
for the list of 35 critical bug fixes and since the previous release
2.6.2.

</div>

<div class="section">

28 October, 2015: Release 2.6.2 available
A point release for the 2.6 line.

Please see the [Hadoop 2.6.2 Release
Notes](http://hadoop.apache.org/docs/r2.6.2/hadoop-project-dist/hadoop-common/releasenotes.html)
for the list of 15 critical bug fixes and since the previous release
2.6.1.

</div>

<div class="section">

23 September, 2015: Release 2.6.1 available
A point release for the 2.6 line.

Please see the [Hadoop 2.6.1 Release
Notes](http://hadoop.apache.org/docs/r2.6.1/hadoop-project-dist/hadoop-common/releasenotes.html)
for the list of 158 critical bug fixes and since the previous release
2.6.0.

</div>

<div class="section">

06 July, 2015: Release 2.7.1 (stable) available
A point release for the 2.7 line. This release is now considered stable.

Please see the [Hadoop 2.7.1 Release
Notes](http://hadoop.apache.org/docs/r2.7.1/hadoop-project-dist/hadoop-common/releasenotes.html)
for the list of 131 bug fixes and patches since the previous release
2.7.0. Please look at the 2.7.0 section below for the list of
enhancements enabled by this first stable release of 2.7.x.

</div>

<div class="section">

21 April 2015: Release 2.7.0 available
Apache Hadoop 2.7.0 contains a number of significant enhancements. A few
of them are noted below.

-   **IMPORTANT notes**
    -   This release drops support for JDK6 runtime and works with JDK
        7+ only.
    -   This release is not yet ready for production use. Critical
        issues are being ironed out via testing and downstream adoption.
        Production users should wait for a 2.7.1/2.7.2 release.
-   Hadoop Common
    -   Support Windows Azure Storage - Blob as a file system in Hadoop.
-   Hadoop HDFS
    -   Support for file truncate
    -   Support for quotas per storage type
    -   Support for files with variable-length blocks
-   Hadoop YARN
    -   Make YARN authorization pluggable
    -   Automatic shared, global caching of YARN localized resources
        (beta)
-   Hadoop MapReduce
    -   Ability to limit running Map/Reduce tasks of a job
    -   Speed up FileOutputCommitter for very large jobs with many
        output files.

Full information about this milestone release is available at [Hadoop
Releases](releases.html#News).

</div>

<div class="section">

18 November, 2014: release 2.6.0 available
Apache Hadoop 2.6.0 contains a number of significant enhancements such
as:

-   Hadoop Common
    -   Key management server (beta)
    -   Credential provider (beta)
-   Hadoop HDFS
    -   Heterogeneous Storage Tiers - Phase 2
        -   Application APIs for heterogeneous storage
        -   SSD storage tier
        -   Memory as a storage tier (beta)
    -   Support for Archival Storage
    -   Transparent data at rest encryption (beta)
    -   Operating secure DataNode without requiring root access
    -   Hot swap drive: support add/remove data node volumes without
        restarting data node (beta)
    -   AES support for faster wire encryption
-   Hadoop YARN
    -   Support for long running services in YARN
        -   Service Registry for applications
    -   Support for rolling upgrades
        -   Work-preserving restarts of ResourceManager
        -   Container-preserving restart of NodeManager
    -   Support node labels during scheduling
    -   Support for time-based resource reservations in Capacity
        Scheduler (beta)
    -   Global, shared cache for application artifacts (beta)
    -   Support running of applications natively in Docker containers
        (alpha)

Full information about this milestone release is available at [Hadoop
Releases](releases.html#News).

</div>

<div class="section">

19 November, 2014: release 2.5.2 available
Full information about this milestone release is available at [Hadoop
Releases](releases.html#News).

</div>

<div class="section">

12 September, 2014: release 2.5.1 available
Full information about this milestone release is available at [Hadoop
Releases](releases.html#News).

</div>

<div class="section">

11 August, 2014: release 2.5.0 available
Full information about this milestone release is available at [Hadoop
Releases](releases.html#News).

</div>

<div class="section">

30 June, 2014: release 2.4.1 available
Full information about this milestone release is available at [Hadoop
Releases](releases.html#News).

</div>

<div class="section">

27 June, 2014: release 0.23.11 available
Full information about this milestone release is available at [Hadoop
Releases](releases.html#News).

</div>

<div class="section">

07 April, 2014: release 2.4.0 available
Full information about this milestone release is available at [Hadoop
Releases](releases.html#News).

</div>

<div class="section">

20 February, 2014: release 2.3.0 available
Full information about this milestone release is available at [Hadoop
Releases](releases.html#News).

</div>

<div class="section">

11 December, 2013: release 0.23.10 available
Full information about this milestone release is available at [Hadoop
Releases](releases.html#News).

</div>

<div class="section">

15 October, 2013: release 2.2.0 available
Apache Hadoop 2.x reaches GA milestone! Full information about this
milestone release is available at [Hadoop Releases](releases.html#News).

</div>

<div class="section">

25 August, 2013: release 2.1.0-beta available
Apache Hadoop 2.x reaches beta milestone! Full information about this
milestone release is available at [Hadoop Releases](releases.html#News).

</div>

<div class="section">

27 December, 2011: release 1.0.0 available
Hadoop reaches 1.0.0! Full information about this milestone release is
available at [Hadoop Releases](releases.html#News).

</div>

<div class="section">

March 2011 - Apache Hadoop takes top prize at Media Guardian Innovation
Awards
Described by the judging panel as a "Swiss army knife of the 21st
century", Apache Hadoop picked up the *innovator of the year* award for
having the potential to change the face of media innovations.

See [The Guardian web
site](http://www.guardian.co.uk/technology/2011/mar/25/media-guardian-innovation-awards-apache-hadoop)

</div>

<div class="section">

January 2011 - ZooKeeper Graduates
Hadoop's ZooKeeper subproject has graduated to become a top-level Apache
project.

Apache ZooKeeper can now be found at <http://zookeeper.apache.org/>

</div>

<div class="section">

September 2010 - Hive and Pig Graduate
Hadoop's Hive and Pig subprojects have graduated to become top-level
Apache projects.

Apache Hive can now be found at <http://hive.apache.org/>

Pig can now be found at <http://pig.apache.org/>

</div>

<div class="section">

May 2010 - Avro and HBase Graduate
Hadoop's Avro and HBase subprojects have graduated to become top-level
Apache projects.

Apache Avro can now be found at <http://avro.apache.org/>

Apache HBase can now be found at <http://hbase.apache.org/>

</div>

<div class="section">

July 2009 - New Hadoop Subprojects
Hadoop is getting bigger!

-   Hadoop Core is renamed Hadoop Common.
-   MapReduce and the Hadoop Distributed File System (HDFS) are now
    separate subprojects.
-   Avro and Chukwa are new Hadoop subprojects.

See the summary descriptions for all subprojects above. Visit the
individual sites for more detailed information.

</div>

<div class="section">

March 2009 - ApacheCon EU
In case you missed it.... [ApacheCon Europe
2009](http://www.eu.apachecon.com/c/aceu2009/)

</div>

<div class="section">

November 2008 - ApacheCon US
In case you missed it.... [ApacheCon US
2008](http://us.apachecon.com/c/acus2008/)

</div>

<div class="section">

July 2008 - Hadoop Wins Terabyte Sort Benchmark
[Hadoop Wins Terabyte Sort
Benchmark](http://developer.yahoo.com/blogs/hadoop/2008/07/apache_hadoop_wins_terabyte_sort_benchmark.html):
One of Yahoo's Hadoop clusters sorted 1 terabyte of data in 209 seconds,
which beat the previous record of 297 seconds in the annual general
purpose (Daytona) [terabyte sort benchmark](http://sortbenchmark.org/).
This is the first time that either a Java or an open source program has
won.

</div>

</div>
