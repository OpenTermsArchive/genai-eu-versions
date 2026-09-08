# Versions of terms from the *genai-eu* collection

The terms in this collection are tracked by the members of the Lab Platform Governance, Media and Technology of the Centre for Media, Communication and Information (ZeMKI), University of Bremen, namely Prof. Dr. Christian Katzenbach, Kim Lisa Ermler, Zenobio De Almeida Ramos Neto, Ayse Darakçi and Gleb Tomashevskii, ✍️ using [Open Terms Archive](https://opentermsarchive.org).

## Usage

### [🔍 Browse through versions](https://docs.opentermsarchive.org/navigate-history/) straight in this repository

### [🔔 Subscribe by RSS](https://docs.opentermsarchive.org/subscribe-rss/) to be notified of changes

### [🗂️ Download as dataset](https://github.com/OpenTermsArchive/genai-eu-versions/releases) to analyse in depth

## Context

[Open Terms Archive](https://opentermsarchive.org) is free and open source software that publicly records every version of the terms of digital services, increasing their readability and highlighting their changes to [enable democratic oversight](https://opentermsarchive.org/impact). In its [vocabulary](https://docs.opentermsarchive.org/#main-concepts):

- A **version** is a record of a service’s terms cleaned of the legally irrelevant parts (e.g. menus, ads…) of an online document. Each version represents the state of the terms at a specific point in time. They are publicly recorded to provide a history of how the terms evolved over time.
- A **collection** is a group of terms characterised by their language, jurisdiction and industry.

Detailed information about this specific collection, including how to request or contribute terms, can be found in its [declarations repository](https://github.com/OpenTermsArchive/genai-eu-declarations).

## Data Collection

The data collection is performed with the [Open Terms Archive engine](https://docs.opentermsarchive.org/). Open Terms Archive (OTA) is a French NGO focussed on making company terms and their changes available to consumers and the public, and offering an almost real-time alert service for such changes. The dataset "genai-eu" utilizes the open source software, the Open Terms Archive Engine to download and archive changes of 11 generative AI services. Two aspects for data collection are important and linked to the OTA. The OTA Engine automatically updates the archive of the English language version of selected platform policies on a regular basis, capturing all meaningful edits in terms and policies. This is done by using an automated web scraper that tracks the changes of each web URL. The relevant parts of platform policies are selected [here](https://github.com/OpenTermsArchive/genai-eu-declarations) with the use of CSS selectors and Javascript filters, to select the correct content, remove insignificant content (e.g. ads, illustrative pictures, internal navigation links…), and filter out noise (e.g. tracker identifiers in links, relative dates…). The engine scrapes through the selected policies multiple times a day, and keeps all HTML snapshots [here](https://github.com/OpenTermsArchive/genai-eu-snapshots). If changes are detected within the HTML snapshots, new versions of the policy are populated to [PGA v2 dataset](https://github.com/OpenTermsArchive/genai-eu-versions). Please consult the [documentation](https://docs.opentermsarchive.org/) for more information on the Open Terms Archive Engine.

We try to ensure a constant tracking so that even the slightest changes in policies would not be missed. However, due to technical issues and anti-bot protection measures of the platforms we sometimes lose parts of data. For instance, in the beginning of the year 2026 we faced a massive amount of tracking errors presumably caused by the temporary blockings by the platforms' cybersecurity services. In order to maintain full transparency, we are documenting the periods during which the recording of snapshots is interrupted. The detailed information about the data gaps in Platform Governance Archive and GenAI Governance Archive collections can be found [here](https://docs.google.com/spreadsheets/d/1d9obvYX331ppueC7BNVNqfFgdjqr75xYf-fGCPO2a2c/edit?usp=sharing). 

## Missing terms

Each collection has a specific scope, and its maintainers might or might not have the intention to track the terms you are interested in.

If some versions are missing, the maintainers of this collection might benefit from your help: check [open issues](https://github.com/OpenTermsArchive/genai-eu-declarations/issues) for known necessary corrections or open a new one.

If specific services, or specific terms for a service, are missing from this collection, they may be available in other [public Open Terms Archive collections](https://opentermsarchive.org/#collections).

If not, you may just be the best person to add them by [following the documentation](https://docs.opentermsarchive.org/contributing-terms)!

- - -

# License

Any database in this repository is distributed under an [ODC-BY 1.0](https://opendatacommons.org/licenses/by/1-0/) license. That means you are free to share, modify, or transform the database and produce works from it as long as you attribute the resulting works to *_ _ _ _ _ ✍️ and Open Terms Archive contributors*.
