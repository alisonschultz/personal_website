---
title: "A 500-Billion-Dollar Decision for the World: The Revenue Impacts of Global Unitary Taxation"
date: 2026-08-02
weight: 3
tags: ["corporate tax","unitary taxation","UN tax convention","profit shifting"]
author: ["Alison Schultz","Alex Cobham"]
description: "Report by the Tax Justice Network and Public Services International. Countries would collect US$500 billion more corporate tax a year under global unitary taxation."
venue: "Report by the Tax Justice Network and Public Services International"
summary: "Countries could collect around US$500 billion more in corporate tax each year – 24% more from multinationals, without raising rates – by taxing multinationals where they actually do business rather than where they declare their profits. The report models the design choices at stake in the UN Tax Convention; an interactive explorer lets you examine the country-level estimates under every scenario."
editPost:
    URL: "https://taxjustice.net/reports/a-500-billion-dollar-decision-for-the-world-the-revenue-impacts-of-global-unitary-taxation/"
    Text: "Tax Justice Network"
---

---

##### Download

+ [Report (PDF)](Unitary_Taxation_Report.pdf)
+ [Methodology note (PDF)](Unitary_Taxation_Methodology_Note.pdf)
+ [Country-level results (xlsx)](Unitary_taxation_results.xlsx)
+ [Code and data (GitHub)](https://github.com/Tax-Justice-Network/unitary-taxation)

---

##### Unitary Taxation Explorer

Country-level estimates for all scenarios modelled in the report — pick a country, a formula, and the design choices, and see who gains what.

<iframe id="ut-explorer" src="/unitary-taxation-explorer/"
  title="Unitary Taxation Explorer" loading="lazy"
  style="width:100%;border:1px solid rgba(0,0,0,0.15);border-radius:8px;display:block;min-height:80vh;"></iframe>
<script>
  window.addEventListener("message", function (e) {
    if (e.data && e.data.utExplorerHeight) {
      document.getElementById("ut-explorer").style.height =
        (e.data.utExplorerHeight + 20) + "px";
    }
  });
</script>

<p style="margin-top:0.6rem;font-size:0.85rem;">
  <a href="/unitary-taxation-explorer/">Open the explorer full-page &rarr;</a>
</p>

---

##### About

With a UN Framework Convention on International Tax Cooperation in sight, the world faces a decision that could fundamentally reshape corporate taxation. This report, written with Alex Cobham for the Tax Justice Network and Public Services International (PSI), estimates what is at stake: moving from the 100-year-old "pay where you say" approach – under which multinationals are taxed where they declare their profits – to a "pay where you play" approach that taxes them where they actually employ workers, hold assets, and make and sell their goods and services. In technical terms: from the arm's length principle to unitary taxation with formulary apportionment.

We find that countries altogether would collect around US$500 billion more in corporate tax each year – 24% more from multinational corporations – without raising tax rates. Almost every country gains. Beyond the headline number, the report examines the design choices that determine how the gains are shared: treating resource rights as prior to taxing rights (without which low-income countries gain 35% less), measuring sales at destination rather than origin (which raises low-income countries' gains by more than 40%), the choice of apportionment formula, and the effect of cross-border loss consolidation. It also shows that the small number of likely losers – corporate tax havens and "headquarters-bias" countries – could preserve their current revenues simply by applying ordinary tax rates to the smaller profit base they would keep.

The [methodology note](Unitary_Taxation_Methodology_Note.pdf) documents the data and estimation approach in detail, and all code and non-confidential data are available in the [replication package](https://github.com/Tax-Justice-Network/unitary-taxation).
