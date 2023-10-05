---
layout: col-sidebar
title: OWASP Chirps
tags: chirps scanner
level: 2
type: tool
pitch: Chirps is an open source, Django-based, Python web application that allows users to scan LLMs for Prompt Injection and search and scan vector databases for sensitive data.
---

[![](https://img.shields.io/badge/owasp-incubator-blue)](https://owasp.org/other_projects/)
<img src="assets/images/chirps_logo.png" width="20%" height="20%" alt="Chirps Logo" align="left" hspace="15" vspace="0" style="margin-bottom: 30px">
[![GitHub contributors](https://img.shields.io/github/contributors/mantiumai/chirps)](https://github.com/mantiumai/chirps/graphs/contributors)
[![GitHub Pulse](https://img.shields.io/github/commit-activity/m/mantiumai/chirps)](https://github.com/badges/shields/pulse)
[![GitHub Workflow Status (with event)](https://img.shields.io/github/actions/workflow/status/mantiumai/chirps/.github%2Fworkflows%2Fdjango-test.yml)](https://github.com/mantiumai/chirps/actions)

## Description

OWASP Chirps is an open source, Django-based, Python web application that allows users to search and scan vector databases for sensitive data, test your LLM API for Prompt injection, and find other Generative AI Vulnerabilities.

The application can connect to LLM API endpoints, vector databases like Redis and Pinecone, and Mantium Chat applications. Users can create and manage scanning policies, execute scans against an asset using a selected plan, and view the results of the scan, including any findings.

<hr style="margin: 32px 0; clear: both;" />

<img src="assets/images/policies.png" alt="Policies" align="left" hspace="15" vspace="0" style="margin-bottom: 30px">

## Policies

Leverage premade or custom rule sets to help identify the information you are looking for in your vector databases.

<hr style="margin: 48px 0; clear: both;" />

<img src="assets/images/scans.png" alt="Scans" align="right" hspace="15" vspace="0" style="margin-bottom: 30px">

## Scans

Manage your scans and their results. Create, execute, and analyze scans using plans with defined rules. And when the scan is complete, review scan findings to see what information you need to remove from your vector database.

<hr style="margin: 32px 0; clear: both;" />

<img src="assets/images/asset.png" alt="Scans" align="left" hspace="15" vspace="0" style="margin-bottom: 30px">

## Assets

Interact with Mantium applications and vector databases like Redis and Pinecone for storing and searching document embeddings. Users can create, edit, and delete asset configurations, which include connection details and authentication credentials.

<hr style="margin: 32px 0; clear: both;" />

<img src="assets/images/github-large.png" alt="GitHub" align="right" hspace="15" vspace="0" style="margin-bottom: 30px">

## Use Github Codespaces

Github’s Codespaces is enabled so you don’t need to fork, pull, merge, or anything else. Just spin up a fully configured dev environment in seconds and start coding.

<a href="https://github.com/mantiumai/chirps#chirps"><i class="fab fa-github">&nbsp;Get Started</i></a>

<hr style="margin: 32px 0; clear: both;" />

## Contributors

![GitHub contributors](https://img.shields.io/github/contributors/mantiumai/chirps)

OWASP Chirps has been created by
<a href="mailto:&#114;&#121;&#097;&#110;+&#111;&#119;&#097;&#115;&#112;&#064;&#109;&#097;&#110;&#116;&#105;&#117;&#109;&#097;&#105;&#046;&#099;&#111;&#109;">Ryan Sevey</a> and is developed, maintained by [these contributors](https://github.com/mantiumai/chirps/graphs/contributors).

<hr style="margin: 32px 0; clear: both;" />

## Licensing

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

This program is free software: You can redistribute it and/or modify it under the terms of the
[GPL 3.0 License](https://github.com/mantiumai/chirps/blob/master/LICENSE).
OWASP Chirps and any contributions are Copyright © by Ryan Sevey & the OWASP Chirps contributors 2023.
