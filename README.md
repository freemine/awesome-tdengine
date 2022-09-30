<p align="center">
  <br>
  <a href="https://tdengine.com"><img width="240" src="./assets/logo.svg" alt="logo of awesome-tdengine repository"></a>
  <br>
  <br>
</p>

# Awesome TDengine [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> 🎉 A curated list of awesome things related to TDengine.

High-Performance, Scalable, Time-Series Database with SQL support.

Enables efficient, real-time data ingestion, processing and monitoring of TB and even PB scale data per day, generated by billions of sensors and data collectors. TDengine can be widely applied to IoT, Industrial Internet, Connected Vehicles, DevOps, Energy , Finance and many other use-cases.

GitHub Repo: https://github.com/taosdata/TDengine

Offical Website: [tdengine.com](https://tdengine.com)

## Contents

- [GUI](#gui)
- [IoT](#iot)
- [ORM](#orm)
- [Connector](#connector)
- [Stack](#stack)
- [Plugin](#plugin)
- [Data](#data)
- [Algorithm](#algorithm)
- [Observability](#observability)
- [Container](#container)
- [Distribution](#distribution)
- [Dataset](#dataset)
- [Others](#others)

## GUI

- [TDengineGUI](https://github.com/arielyang/TDengineGUI) - A simple TDengine Desktop Manager.
- [Taos.Studio](https://github.com/maikebing/Taos.Studio) - A GUI tool for viewing and editing data for TDengine.
- [balloonfish](https://github.com/xielaoshi99/balloonfish) - Electron + Vue3 + Vite2.0 based TDengine time-series database visualized management tool.
- [tdengine-client](https://github.com/wurong1420/tdengine-client) - A simple TDengine interface.

## IoT

- [Zeus IoT](https://github.com/zmops/zeus-iot) - Zeus IoT is the world's first open source Internet of Things distributed collection platform based on Zabbix, with the ability to collect, analyze, and store data from millions of IoT devices.
- [DG-IoT](https://github.com/dgiot/dgiot-dashboard) - DG-IoT platform industry application extension plugin.
- [dgiot_tdengine](https://github.com/dgiot/dgiot_tdengine) - TDengine adapter plugin.
- [node-red-contrib-tdengine](https://github.com/kp45-tech/node-red-contrib-tdengine) - TDengine connector plugin for Node-RED.
- [IoTSharp](https://github.com/IoTSharp/IoTSharp/blob/master/IoTSharp.Data.TimeSeries/TaosStorage.cs) - IoTSharp is an open-source IoT platform for data collection,It supports storing time series data to TDengine.

## ORM
- [sqli](https://github.com/x-ream/sqli) - ORM SQL Interface, Criteria, CriteriaBuilder, ResultMapBuilder.
- [TDengine ORM Framework](https://github.com/hxshun/TDengineORM) - ORM framework of TAOS Data's time-series database TDengine.
- [IoTSharp.EntityFrameworkCore.Taos](https://github.com/IoTSharp/EntityFrameworkCore.Taos) - Entity, Framework, EF, Core, Data, O/RM, entity-framework-core, TDengine.
- [tdengine-orm](https://github.com/Yurunsoft/tdengine-orm) - TDengine ORM based on tdengine-restful-connector & php-tdengine.<!--lint ignore awesome-list-item-->
- [crown](https://github.com/machine-w/crown) - crown is a simple and small ORM for TDengine.
- [APIJSON](https://github.com/Tencent/APIJSON) - A JSON Transmission Protocol and an ORM Library for providing APIs and Docs without writing any code.
- [ZORM](https://gitee.com/chunanyong/zorm) - ORM support TDenging by Go.
- 
## Connector

- [PDO_TAOS](https://github.com/bearlord/pdo_taos) - TDengine driver for PDO.
- [yii2-tdengine](https://github.com/bearlord/yii2-tdengine) - TDengine for yii2, pdo_taos needed.
- [php-tdengine](https://github.com/Yurunsoft/php-tdengine) - PHP extension of TDengine, supports Swoole.
- [tdengine-restful-connector](https://github.com/Yurunsoft/tdengine-restful-connector) - PHP extension of TDengine, support Swoole.
- [imi-tdengine](https://github.com/imiphp/imi-tdengine) - Encapsulated TDengine connection pools, used in imi framework.
- [pytaos](https://github.com/horennel/pytaos) - Python RESTful API of TDengine.
- [Go Connector for TDengine](https://github.com/wenj91/taos-driver) - Implements internal database interface database/sql/driver of Go-lang.
- [node2tdengine](https://github.com/machine-w/node2tdengine)
- [NestJS TDengine Driver](https://github.com/IricBing/nestjs-tdengine) - NestJS TDengine Driver(RESTful based).
- [taos-rs](https://github.com/yuerrd/taos-rs) - TDengine Java RESTful Client.
- [TDengine Rust bindings](https://github.com/songtianyi/tdengine-rust-bindings) - It's a Rust bindings project for TDengine.
- [TDenginex](https://github.com/lizhaochao/TDenginex) - TDengine Connector for Elixir.
- [DBUtility.TDengine](https://github.com/cockroach888/GSA.MOLLE.ToolKits/tree/main/src/ToolKits.DBUtility) - C# Connector for TDengine. (.NET 6+)
- [IoTSharp.Data.Taos](https://www.nuget.org/packages/IoTSharp.Data.Taos/)  - TDengine's ADO.Net provider. (.Net Framework 4.6+, .Net Standard2.0+,.Net 5.0+)  [more](https://github.com/IoTSharp/EntityFrameworkCore.Taos) 


## Health Checks
- [IoTSharp.HealthChecks.Taos](https://www.nuget.org/packages/IoTSharp.HealthChecks.Taos/) - TDengine's HealthChecks provider. (.Net 5.0+)  [more](https://github.com/IoTSharp/EntityFrameworkCore.Taos) 


## Stack

- [NewLife.Core](https://github.com/NewLifeX/X) - NewLife.Core Database core.
- [NewLife.XCode](https://github.com/NewLifeX/NewLife.XCode) - NewLife.XCode Database Middle-ware.

## Plugin

<!--lint ignore awesome-list-item-->
- [rsyslog plugin for tdengine](https://github.com/mxmkeep/rsyslog-omtaos) - rsyslog plugin for TDengine.
- [HiveMQ TDengine Plugin](https://github.com/huskar-t/hivemq-tdengine-extension) - HiveMQ TDengine Plugin.
- [hivemq-tdengine-jdsl-extension](https://github.com/huskar-t/hivemq-tdengine-jdsl-extension) - HiveMQ TDengine JDSL Plugin.
- [HiveMQ-TDengine-Extension](https://github.com/john-bigz/hivemq-tdengine-extension) - A TDengine extension for HiveMQ.
- [tdengine_hivemq](https://github.com/379547990/tdengine_hivemq) - HiveMQ to TDengine.
- [pulsar-io-tdengine](https://github.com/JueShanCoder/pulsar-io-tdengine) - The TDengine connector connects Pulsar and TDengine.

## Data

- [tsarchive](https://github.com/cenc-cea/tsarchive) - Consume data streams from a Kafka topic, archive the data packets into the TDengine time series database.
- [flink-connector-tdengine](https://github.com/echisan/flink-connector-tdengine)
- [TD-Spark](https://github.com/liuyq-617/TD-Spark) - A java project, read from TDengine and write to TDengine on Spark.
- [Integrate TDengine to YoMo](https://github.com/yomorun/yomo-sink-tdengine-example) - Demonstrates how to integrate TDengine to YoMo and store data to TDengine after stream processing.
- [YoMo x TDengine](https://github.com/fanweixiao/push-stream-logging) - Streaming high frequency logs to TDengine.<!--lint ignore awesome-list-item-->
- [taostd](https://github.com/nzhzds/taostd) - taostd is a simple sql executor for TDengine.

## Algorithm

- [PyODDS](https://github.com/datamllab/pyodds) - An End-to-end Outlier Detection System.
- [PYTSDA-TDengine](https://github.com/Shawshank-Smile/PYTSDA-TDengine) - An End-to-end time series data analysis system with TDengine.

## Observability

- [TDengine interface for n9e transfer](https://github.com/xiangxud/transfer)
- [Business metrics monitoring based on TDengine](https://github.com/gunnerliu/horus) - Highly customized business metrics monitoring with TDengine & Spring Boot

## Container

- [TDengine cluster for kubernetes](https://github.com/wwbgo/tdengine-k8s) - TDengine cluster for kubernetes.
- [TDengine Containers](https://github.com/arktos-venture/docker-tdengine) - TDengine Client, Node, Adapter and Arbitrator Rootless and smallest containers as possible.
- [TDengine-K8S](https://github.com/elihe2011/TDengine-K8S)

## Distribution

- [tdengine-client-macos-unofficial](https://github.com/cybartists/tdengine-client-macos-unofficial) - Unofficial compiled TDengine client for macOS.
- [Unofficial TDengine Windows](https://github.com/GitHubForzhenjiazhao/Soft) - Unofficial TDengine Windows client & server package.

## Dataset

- [seedlink2taos_py](https://github.com/schenton/seedlink2taos_py) - A Python program that fetches seismic waveform data from IRIS and writes to TDengine database.
- [airQuality](https://github.com/233lawliet/airQuality) - 3000+ District air quality metrics: CO2, CO1, PM2.5, PM10 and so on.

## Others

- [auto_taos_cfg](https://github.com/glzhao89/auto_taos_cfg) - Auto generate TDengine log/data/cfg.
- [Sentinel Console](https://github.com/wenhao/sentinel-dashboard-tdengine) - Sentinel-Dashboard with TDengine.
- [Davinci](https://github.com/edp963/davinci) - Davinci is a DVsaaS (Data Visualization as a Service) Platform.
