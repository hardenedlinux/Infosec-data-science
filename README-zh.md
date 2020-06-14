
# Table of Contents

1.  [programming languages](#orgf967f91)
2.  [基础知识](#org08afe60)
    1.  [SuperCowPowers/data\_hacking: Data Hacking Project](#org34a1e9c)
    2.  [机器学习库](#orgea9c3c4)
3.  [相关学习和教程](#org462cdfa)
4.  [研究](#orgcf723c7)
    1.  [JohnLaTwC/Shared: Shared Blogs and Notebooks](#org6c54c28):research:windows:
    2.  [lbnl-cybersecurity/ddos-detection](#orgad75342):DDOS:
5.  [Osuqery](#org740ed40)
6.  [Sysmon/syslog/or any system's logs](#orgee69060)
7.  [Zeek](#orga622085)
    1.  [SuperCowPowers/zat: Zeek Analysis Tools (ZAT): Processing and analysis of Zeek network data with Pandas, scikit-learn, and Spark](#orge0dcd1e)
    2.  [tenzir/threatbus: 🚌 The missing link to connect open-source threat intelligence tools.](#org727acfc)
    3.  [mitre-attack/bzar: A set of Zeek scripts to detect ATT&CK techniques.](#orgf975e0c)
8.  [搜索和展示平台](#org0e92733)
    1.  [Elk](#org5632b2b)
    2.  [Grafana: The open observability platform | Grafana Labs](#org14538c9)



<a id="orgf967f91"></a>

# programming languages

-   Python

<table border="2" cellspacing="0" cellpadding="6" rules="groups" frame="hsides">


<colgroup>
<col  class="org-left" />

<col  class="org-left" />
</colgroup>
<thead>
<tr>
<th scope="col" class="org-left">machine learn</th>
<th scope="col" class="org-left">&#xa0;</th>
</tr>
</thead>

<tbody>
<tr>
<td class="org-left">scipy</td>
<td class="org-left">&#xa0;</td>
</tr>


<tr>
<td class="org-left">Numpy</td>
<td class="org-left">&#xa0;</td>
</tr>


<tr>
<td class="org-left">tensorflow</td>
<td class="org-left">&#xa0;</td>
</tr>


<tr>
<td class="org-left">pandas</td>
<td class="org-left">&#xa0;</td>
</tr>


<tr>
<td class="org-left">matplotlib</td>
<td class="org-left">plot</td>
</tr>


<tr>
<td class="org-left">clx</td>
<td class="org-left">Important</td>
</tr>


<tr>
<td class="org-left">fastai</td>
<td class="org-left">&#xa0;</td>
</tr>
</tbody>
</table>

-   Julia

<table border="2" cellspacing="0" cellpadding="6" rules="groups" frame="hsides">


<colgroup>
<col  class="org-left" />

<col  class="org-left" />
</colgroup>
<thead>
<tr>
<th scope="col" class="org-left">machine learn</th>
<th scope="col" class="org-left">&#xa0;</th>
</tr>
</thead>

<tbody>
<tr>
<td class="org-left">flux</td>
<td class="org-left">&#xa0;</td>
</tr>


<tr>
<td class="org-left">cudaArray</td>
<td class="org-left">GPU</td>
</tr>
</tbody>
</table>

-   Haskell
    -   Data parse/query

-   R

<table border="2" cellspacing="0" cellpadding="6" rules="groups" frame="hsides">


<colgroup>
<col  class="org-left" />

<col  class="org-left" />
</colgroup>
<thead>
<tr>
<th scope="col" class="org-left">package name</th>
<th scope="col" class="org-left">role</th>
</tr>
</thead>

<tbody>
<tr>
<td class="org-left">ggplot2</td>
<td class="org-left">plot</td>
</tr>


<tr>
<td class="org-left">tidyverse</td>
<td class="org-left">&#xa0;</td>
</tr>


<tr>
<td class="org-left">xts</td>
<td class="org-left">timeline</td>
</tr>


<tr>
<td class="org-left">timetk</td>
<td class="org-left">timeline</td>
</tr>
</tbody>
</table>


<a id="org08afe60"></a>

# 基础知识

-   须知
    这里不仅仅为 `logs 日志作为分析源头` 可以使用脚本分析 PDF binary 任何分析可以使用机器学习相关的库。如 [Maldoc Analysis With xlm-deobfuscator - YouTube](https://www.youtube.com/watch?v=Y7IP0pksEb8) 可以利用任何脚本 进行安全相关的 `数值` 分析。这里不单一局限在日志。
    -   [Didier Stevens | (blog 'DidierStevens)](https://blog.didierstevens.com/) 分析脚本模范展示

1.  相关输出脚本以 jupyter notebook 为展示页面

1.  Notebook 要有相关分析的说明

-   数据范畴不限 SIEM 支持的。可以参考 SIEM 要求数据分析范围类型
    -   [TonyPhipps/SIEM: SIEM Tactics, Techiques, and Procedures](https://github.com/TonyPhipps/SIEM)


<a id="org34a1e9c"></a>

## ✰ Important [SuperCowPowers/data\_hacking: Data Hacking Project](https://github.com/SuperCowPowers/data_hacking)

可任选一个主题作为当前的分析主题。提交内容结构如上 repo 一样

1.  data logs

1.  scripts

1.  environment requirements

1.  Notebook overview

阅读掌握:

-   [infosec-jupyterthon/docs at master · OTRF/infosec-jupyterthon](https://github.com/OTRF/infosec-jupyterthon/tree/master/docs)

-   [hunters-forge/ThreatHunter-Playbook: A Threat hunter's playbook to aid the development of techniques and hypothesis for hunting campaigns.](https://github.com/hunters-forge/ThreatHunter-Playbook)


<a id="orgea9c3c4"></a>

## 机器学习库

-   [rapidsacademy/tutorials/security/tour at master · RAPIDSAcademy/rapidsacademy](https://github.com/RAPIDSAcademy/rapidsacademy/tree/master/tutorials/security/tour) :ML:GPU:

-   [frapidsai/clx: A collection of RAPIDS examples for security analysts, data scientists, and engineers to quickly get started applying RAPIDS and GPU acceleration to real-world cybersecurity use cases.](https://github.com/rapidsai/clx)

基于 GPU 的攻击安全分析，建议使用的库

-   [clx/notebooks at branch-0.15 · rapidsai/clx](https://github.com/rapidsai/clx/tree/branch-0.15/notebooks)

提交标准参考 notebooks


<a id="org462cdfa"></a>

# ✰ Important 相关学习和教程

不限如下：

-   [Kayzaks/HackingNeuralNetworks: A small course on exploiting and defending neural networks](https://github.com/Kayzaks/HackingNeuralNetworks)

-   [course-v4/nbs at master · fastai/course-v4](https://github.com/fastai/course-v4/tree/master/nbs)

-   [ogrisel/parallel\_ml\_tutorial: Tutorial on scikit-learn and IPython for parallel machine learning](https://github.com/ogrisel/parallel_ml_tutorial)

-   [fastai/courses/dl1 at master · fastai/fastai](https://github.com/fastai/fastai/tree/master/courses/dl1)

-   [https://tools.netsa.cert.org/silk/analysis-handbook.pdf](https://tools.netsa.cert.org/silk/analysis-handbook.pdf) [网络分析基础]


<a id="orgcf723c7"></a>

# 研究


<a id="org6c54c28"></a>

## [JohnLaTwC/Shared: Shared Blogs and Notebooks](https://github.com/JohnLaTwC/Shared)     :research:windows:


<a id="orgad75342"></a>

## [lbnl-cybersecurity/ddos-detection](https://github.com/lbnl-cybersecurity/ddos-detection)     :DDOS:


<a id="org740ed40"></a>

# Osuqery

提交说明：

1.  osquery logs

1.  osquery config files

1.  notebook

1.  environment requirements(Python or R or something else)


<a id="orgee69060"></a>

# Sysmon/syslog/or any system's logs

提交要求：

可以分析任何日志相关的安全数值的分析。

1.  data logs

1.  notebook

1.  environment requirements(Python or R or something else)
    -   parsing script

-   query rules


<a id="orga622085"></a>

# Zeek

zeek 分析提交规范样例 [stratosphereips/IRC-Behavioral-Analysis](https://github.com/stratosphereips/IRC-Behavioral-Analysis)

1.  Zeek script

1.  environment dependences

1.  analysis Notebook


<a id="orge0dcd1e"></a>

## ☞ TODO [SuperCowPowers/zat: Zeek Analysis Tools (ZAT): Processing and analysis of Zeek network data with Pandas, scikit-learn, and Spark](https://github.com/SuperCowPowers/zat)

-   目的： 利用 zat 实现各种 zeek logs 的分析和解析


<a id="org727acfc"></a>

## ☞ TODO [tenzir/threatbus: 🚌 The missing link to connect open-source threat intelligence tools.](https://github.com/tenzir/threatbus)


<a id="orgf975e0c"></a>

## [mitre-attack/bzar: A set of Zeek scripts to detect ATT&CK techniques.](https://github.com/mitre-attack/bzar)


<a id="org0e92733"></a>

# 搜索和展示平台


<a id="org5632b2b"></a>

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


<a id="org14538c9"></a>

## [Grafana: The open observability platform | Grafana Labs](https://grafana.com/)

提交需求：

1.  解析日志的 config files

1.  dashboard json (import output)

1.  dashboard plugin
    能够编写 grafana 的图表插件

