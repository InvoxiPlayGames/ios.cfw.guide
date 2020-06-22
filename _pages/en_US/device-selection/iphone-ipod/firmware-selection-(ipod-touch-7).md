---
title: Firmware Selection (iPod Touch 7)
permalink: /firmware-selection-(ipod-touch-7)
excerpt: Find out what jailbreaks you can use on your iPod Touch 7th Generation
---

{% include toc title="Table of Contents" %}

## Required Reading

Different firmware versions will require different steps to jailbreak your iOS device. This page will help you find where to start.

Select the appropriate page for your version from the chart below. Note that the "from" and "to" fields are inclusive. This means that, for example, the "from 13.0 to {% include latestfw %}" row includes version 13.0, version {% include latestfw %}, and all versions in-between.

Your device version can be found in the Settings application in `General` -> `About`.

## Version Table

<table class="version_table">
  <colgroup>
    <col span="1" style="width: 15%;">
    <col span="1" style="width: 15%;">
    <col span="1" style="width: 35%;">
    <col span="1" style="width: 35%;">
  </colgroup>
  <thead>
    <tr>
      <th>From</th>
      <th>To</th>
      <th>macOS / Linux</th>
      <th>All</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>12.3</td>
      <td>12.3.1</td>
      <td><a href="installing-checkra1n">Installing checkra1n</a></td>
      <td>--</td>
    </tr>
    <tr>
      <td>12.4</td>
      <td>12.4</td>
      <td colspan="2"><a href="installing-chimera">Installing Chimera</a></td>
    </tr>
    <tr>
      <td>12.4.1</td>
      <td>12.4.1</td>
      <td><a href="installing-checkra1n">Installing checkra1n</a></td>
      <td><a href="blocking-updates">Blocking Updates</a></td>
    </tr>
    <tr>
      <td>12.4</td>
      <td>{% include latestfw %}</td>
      <td><a href="installing-checkra1n">Installing checkra1n</a></td>
      <td>--</td>
    </tr>
  </tbody>
</table>

---

unc0ver is also compatible with firmware version 12.4 however we recommend use Chimera instead due to it being easier to use.
{: .notice--primary}

checkra1n is compatible with every firmware
{: .notice-primary}

unc0ver is also compatible with firmware versions 13.0 - 13.5.5 if you prefer a semi-untethered jailbreak.
{: .notice--primary}

In boxes marked `--`, there is no jailbreak for that firmware version.
{: .notice--info}

---

{% capture find-ios-version %}{% include_relative find-ios-version.md %}{% endcapture %}
<div id="find-ios-version">{{ find-ios-version | markdownify }}</div>

<div class="notice">{{ notice-2 | markdownify }}</div>