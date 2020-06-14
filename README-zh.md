
# Table of Contents

1.  [programming languages](#org75e1c4a)
2.  [基础知识](#org3f19ce0)
    1.  [SuperCowPowers/data\_hacking: Data Hacking Project](#orgc081cbb)
    2.  [infosec-jupyterthon/docs at master · OTRF/infosec-jupyterthon](#orgbe523c9)
    3.  [hunters-forge/ThreatHunter-Playbook: A Threat hunter's playbook to aid the development of techniques and hypothesis for hunting campaigns.](#orga552efb)
3.  [Network](#orgbab0596)
4.  [研究](#org1c7447b)
    1.  [JohnLaTwC/Shared: Shared Blogs and Notebooks](#orgde57970):research:windows:
5.  [Osuqery](#orgbdb0ae2)
6.  [Sysmon/syslog/or any system's logs](#org6dd2cbd)
7.  [Zeek](#org0a19fb1)
    1.  [SuperCowPowers/zat: Zeek Analysis Tools (ZAT): Processing and analysis of Zeek network data with Pandas, scikit-learn, and Spark](#org40cc4ce)
    2.  [tenzir/threatbus: 🚌 The missing link to connect open-source threat intelligence tools.](#org7b52160)
    3.  [mitre-attack/bzar: A set of Zeek scripts to detect ATT&CK techniques.](#orgb9f9ac3)
8.  [搜索和展示平台](#org791a4f6)
    1.  [Elk](#org1fd7d40)
    2.  [Grafana: The open observability platform | Grafana Labs](#org329137c)



<a id="org75e1c4a"></a>

# programming languages

-   Python
    -   Numpy

-   tensorflow

-   scipy

-   matplotlib

-   pandas

-   &#x2026;

-   Julia
    -   flux

-   cudaArray..

-   Haskell
    -   Data parse/query

-   &#x2026;

-   R
    -   data plot

-   &#x2026;


<a id="org3f19ce0"></a>

# 基础知识

-   须知
    这里不仅仅为 `logs 日志作为分析源头` 可以使用脚本分析 PDF binary 任何分析可以使用机器学习相关的库。如 [Maldoc Analysis With xlm-deobfuscator - YouTube](https://www.youtube.com/watch?v=Y7IP0pksEb8) 可以利用任何脚本 进行安全相关的 `数值` 分析。这里不单一局限在日志。
    -   [Didier Stevens | (blog 'DidierStevens)](https://blog.didierstevens.com/) 分析脚本模范展示

1.  相关输出脚本以 jupyter notebook 为展示页面

2.  Notebook 要有相关分析的说明


<a id="orgc081cbb"></a>

## ✰ Important [SuperCowPowers/data\_hacking: Data Hacking Project](https://github.com/SuperCowPowers/data_hacking)

-   可任选一个主题作为当前的分析主题。提交内容结构如上 repo 一样
    1.  data logs

1.  scripts

1.  environment requirements

1.  Notebook overview


<a id="orgbe523c9"></a>

## [infosec-jupyterthon/docs at master · OTRF/infosec-jupyterthon](https://github.com/OTRF/infosec-jupyterthon/tree/master/docs)


<a id="orga552efb"></a>

## [hunters-forge/ThreatHunter-Playbook: A Threat hunter's playbook to aid the development of techniques and hypothesis for hunting campaigns.](https://github.com/hunters-forge/ThreatHunter-Playbook)


<a id="orgbab0596"></a>

# Network

-   [https://tools.netsa.cert.org/silk/analysis-handbook.pdf](https://tools.netsa.cert.org/silk/analysis-handbook.pdf) [基础]


<a id="org1c7447b"></a>

# 研究


<a id="orgde57970"></a>

## [JohnLaTwC/Shared: Shared Blogs and Notebooks](https://github.com/JohnLaTwC/Shared)     :research:windows:


<a id="orgbdb0ae2"></a>

# Osuqery

提交说明：

1.  osquery logs

1.  osquery config files

1.  notebook

1.  environment requirements(Python or R or something else)


<a id="org6dd2cbd"></a>

# Sysmon/syslog/or any system's logs

提交要求：

可以分析任何日志相关的安全数值的分析。

1.  data logs

1.  notebook

1.  environment requirements(Python or R or something else)
    -   parsing script

-   query rules


<a id="org0a19fb1"></a>

# Zeek

zeek 分析提交规范样例 [stratosphereips/IRC-Behavioral-Analysis](https://github.com/stratosphereips/IRC-Behavioral-Analysis)

1.  Zeek script

1.  environment dependences

1.  analysis Notebook


<a id="org40cc4ce"></a>

## ☞ TODO [SuperCowPowers/zat: Zeek Analysis Tools (ZAT): Processing and analysis of Zeek network data with Pandas, scikit-learn, and Spark](https://github.com/SuperCowPowers/zat)

-   目的： 利用 zat 实现各种 zeek logs 的分析和解析


<a id="org7b52160"></a>

## ☞ TODO [tenzir/threatbus: 🚌 The missing link to connect open-source threat intelligence tools.](https://github.com/tenzir/threatbus)


<a id="orgb9f9ac3"></a>

## [mitre-attack/bzar: A set of Zeek scripts to detect ATT&CK techniques.](https://github.com/mitre-attack/bzar)


<a id="org791a4f6"></a>

# 搜索和展示平台


<a id="org1fd7d40"></a>

## Elk

提交需求：

1.  解析日志的 elk config files

1.  dashboard json (import output)

1.  dashboard plugin
    能够编写 kibana 的图表插件

1.  [Yelp/elastalert: Easy & Flexible Alerting With ElasticSearch](https://github.com/Yelp/elastalert)
    提供基于 alert 实现的部分事件报警。给相关数值说明

-   [HASecuritySolutions/VulnWhisperer: Create actionable data from your Vulnerability Scans](https://github.com/HASecuritySolutions/VulnWhisperer)

可脱离 Kibana 实现展示功能


<a id="org329137c"></a>

## [Grafana: The open observability platform | Grafana Labs](https://grafana.com/)

提交需求：

1.  解析日志的 config files

1.  dashboard json (import output)

1.  dashboard plugin
    能够编写 grafana 的图表插件

