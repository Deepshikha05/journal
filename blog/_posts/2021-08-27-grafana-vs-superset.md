---
layout: post
title: Grafana VS Apache Superset
image: /assets/img/blog/jeremy-bishop@0,5x.jpg
description: >
  Grafana VS Apache Superset which is better for what problem?
---

### Grafana vs Superset: What are the differences?

* toc
{:toc}

What is **Grafana**? Open source Graphite & InfluxDB Dashboard and Graph Editor. Grafana is a general purpose dashboard and graph composer. It's focused on providing rich ways to visualize time series metrics, mainly though graphs but supports other ways to visualize data through a pluggable panel architecture. It currently has rich support for for Graphite, InfluxDB and OpenTSDB. But supports other data sources via plugins.

What is **Superset**? Data exploration and visualization platform, by Airbnb. Superset's main goal is to make it easy to slice, dice and visualize data. It empowers users to perform analytics at the speed of thought.

Grafana can be classified as a tool in the "Monitoring Tools" category, while Superset is grouped under "Business Intelligence".

#### Some of the features offered by Grafana are:
- Create, edit, save & search dashboards
- Change column spans and row heights
- Drag and drop panels to rearrange

#### On the other hand, Superset provides the following key features:
- A rich set of visualizations to analyze your data, as well as a flexible way to extend the capabilities
- An extensible, high granularity security model allowing intricate rules on who can access which features, and integration with major authentication providers (database, OpenID, LDAP, OAuth & REMOTE_USER through Flask AppBuiler)
- A simple semantic layer, allowing to control how data sources are displayed in the UI, by defining which fields should show up in which dropdown and which aggregation and function (metrics) are made available to the user