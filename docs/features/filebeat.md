---
id: filebeat
title: Filebeat
sidebar_label: Filebeat
---

Canarytrace live logging all activities during life cycle of Canarytrace runner on [WDIO](https://webdriver.io/). [Filebeat](https://www.elastic.co/beats/filebeat) provides live logging all events before start of Canarytrace runner, during lifecycle (from git pull repository,  Canarytrace runner start to stop and all post-end events. Filebeat logging all stdout and stderr streams from all Canarytrace docker containers in your cluster e.g. Canarytrace runner, container with a browser and Canarytrace Listener.

> - If you have a problem with Canarytrace, you won't know about it without filebeat.



---

- Do you find mistake or have any questions? Please [create issue](https://github.com/canarytrace/documentation/issues/new/choose), thanks 👍
- Have more questions? [Contact us](/docs/support/contactus).