<html xmlns="http://www.w3.org/1999/xhtml">
<head>
    <title>SOLR Monitoring FastPack</title>
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8"/>
    <meta http-equiv="X-UA-Compatible" content="IE=EmulateIE8" />
    <meta content="Scroll Wiki Publisher" name="generator"/>
    <link type="text/css" rel="stylesheet" href="css/blueprint/liquid.css" media="screen, projection"/>
    <link type="text/css" rel="stylesheet" href="css/blueprint/print.css" media="print"/>
    <link type="text/css" rel="stylesheet" href="css/content-style.css" media="screen, projection, print"/>
    <link type="text/css" rel="stylesheet" href="css/screen.css" media="screen, projection"/>
    <link type="text/css" rel="stylesheet" href="css/print.css" media="print"/>
</head>
<body>
                <h1>SOLR Monitoring FastPack</h1>
    <div class="section-2"  id="73400921_SOLRMonitoringFastPack-Overview"  >
        <h2>Overview</h2>
    <p>
            <img src="images_community/download/attachments/73400921/worddav4a905bafc9120185831d280bde95e843.png" alt="images_community/download/attachments/73400921/worddav4a905bafc9120185831d280bde95e843.png" class="confluence-embedded-image" />
        The dynaTrace FastPack for the SOLR enables easy out-of-the-box monitoring for applications using the SOLR Search Engine. The FastPack consists predefined JMX Measures for SOLR, Sensors for SOLR Server and SOLR Clients, Business Transactions a Template Profile and Dashboards.    </p>
    </div>
    <div class="section-2"  id="73400921_SOLRMonitoringFastPack-FastPackDetails"  >
        <h2>Fast Pack Details</h2>
    <div class="tablewrap">
        <table>
<thead class=" "></thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
Name    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<strong class=" ">SOLR Monitoring FastPack</strong>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Version    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
1.0.0    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
dynaTrace Version    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
4, 4.1    </p>
    <p>
6.x    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Author    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Keith Marshall    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
License    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="attachments_5275722_2_dynaTraceBSD.txt">dynaTrace BSD</a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Support    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="https://community/display/DL/Support+Levels#SupportLevels-Community+Supported">Community Supported</a><br/>For questions:    </p>
<ul class=" "><li class=" ">    <p>
Comment on this page    </p>
</li><li class=" ">    <p>
Use the Forum <a href="https://community/display/DTFORUM/Community+Plugins+and+Extensions">Community Plugins and Extensions</a>    </p>
</li><li class=" ">    <p>
Directly contact the author    </p>
</li></ul>            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
FastPack Contents    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="attachments_174754209_1_SOLRMonitoringFastPack_dynaTrace6.dtp">SOLR Fastpack for dynaTrace 6.x</a>    </p>
    <p>
<a href="attachments_73335114_1_SOLRMonitoringFastPack.dtp">SOLR Fastpack for dynaTrace 4.x</a>    </p>
            </td>
        </tr>
</tbody>        </table>
            </div>
    </div>
    <div class="section-2"  id="73400921_SOLRMonitoringFastPack-SOLREnvironmentalMonitor"  >
        <h2>SOLR Environmental Monitor</h2>
    <p>
            <img src="images_community/download/attachments/73400921/worddav1f88ceb7850349995e8328d6e41656f7.png" alt="images_community/download/attachments/73400921/worddav1f88ceb7850349995e8328d6e41656f7.png" class="confluence-embedded-image" />
            </p>
    <p>
This dashboard looks at the environmental factors related to the SOLR application server. CPU Load is observed with heap and non-heap memory usage. Web request time and counts are included with a failed transaction traffic light alert. This alert may be adjusted to the % preferred. Class and Thread data are also included.    </p>
    </div>
    <div class="section-2"  id="73400921_SOLRMonitoringFastPack-SOLRWebRequests"  >
        <h2>SOLR Web Requests</h2>
    <p>
            <img src="images_community/download/attachments/73400921/worddav672df1377c53bc9cea473c1b98ec9a35.png" alt="images_community/download/attachments/73400921/worddav672df1377c53bc9cea473c1b98ec9a35.png" class="confluence-embedded-image" />
            </p>
    <p>
The SOLR Web Requests Dashboard provides a Business Transaction like view of all the /SOLR requests. Easy drill down to the transaction details from here. To provide a more detailed operational view we have included charting for all web requests, /SEARCH and /UPDATE specific SOLR web requests. To round out this view the Processor, Free/Comitted memory, and Disk Read/Writes are also charted here.    </p>
    </div>
    <div class="section-2"  id="73400921_SOLRMonitoringFastPack-FastPackInformation"  >
        <h2>FastPack Information</h2>
    <p>
The Fastpack contains a Dashboard and a Template System Profile. In addition it contains the two dashboards described above.<br/>The System Profile already contains an Agent Group for SOLR, just add the dynaTrace agent to your JVM_OPTS when starting SOLR (use name=SOLR). This agent group contains some minor modifications to allow optimal monitoring of SOLR.    </p>
    </div>
    <div class="section-2"  id="73400921_SOLRMonitoringFastPack-Installation"  >
        <h2>Installation</h2>
    <p>
Just download and import the FastPack on your dynaTrace Server (see <a href="https://community/display/DOCDT40/Plugin+Management">Plugin Management</a>)<br/>If you start with a fresh system simply copy the provided System profile (to give it an application specific name) and add agent groups for your own application. If you want to use Cassandra in an existing System profile please copy the following items to your system profile.    </p>
<ul class=" "><li class=" ">    <p>
SOLR Business Transactions    </p>
</li><li class=" ">    <p>
the SOLR Agent Group cannot be copied please do the following    </p>
<ul class=" "><li class=" ">    <p>
Create a separate agent group for SOLR    </p>
</li></ul></li></ul>    </div>
            </div>
        </div>
        <div class="footer">
        </div>
    </div>
</body>
</html>
