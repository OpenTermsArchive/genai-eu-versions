# Dataset GenGA (ongoing collection)

The dataset GenGA (Generative AI Governance Archive) is part of the [Platform Governance Archive (PGA)](https://www.platformgovernancearchive.org/). It is the result of a continuous data collection of policies of generative AI services since November 2025, performed with the [Open Terms Archive engine](https://docs.opentermsarchive.org/), and hosted and curated by the [Lab Platform Governance, Media And Technology (PGMT)](https://platform-governance.org/) at ZeMKI, University of Bremen. The GenGA dataset contains a selected set of policies of major GenAI providers that usually include Community Guidelines, Privacy Policies and Acceptable Use Policies. There are also additional policies that are tracked for particular providers, depending on how they structure their documentation. 

- Platforms: ChatGPT, Claude.AI, DeepSeek, Google Generative AI Services, Grok, Llama API, Meta AI, Microsoft Copilot, Perplexity, Qwen Chat, Vibe (formerly Le Chat). 
- Time frame: started November 2025
- Project website: https://www.platformgovernancearchive.org
- Weakly releases: [Weekly releases of collected data](https://github.com/OpenTermsArchive/genai-eu-versions/releases) – a weekly export of all changes to tracked terms. 

## Usage

### [🔍 Browse through versions](https://docs.opentermsarchive.org/navigate-history/) straight in this repository

### [🔔 Subscribe by RSS](https://docs.opentermsarchive.org/subscribe-rss/) to be notified of changes

### [🗂️ Download as dataset](https://github.com/OpenTermsArchive/genai-eu-versions/releases) to analyse in depth

## Background

The dataset GenGA is a part of the [Platform Governance Archive (PGA)](https://www.platformgovernancearchive.org/), a data repository and platform that collects and curates policies of major social media platforms and GenAI providers in a long-term perspective. GenGA entails data collected in-real time as changes are made to the policies of GenAI providers. This way, the database remains always up to date allowing access to the data through the Platform Governance Archive even for the most current versions of platform policies.

## Data Collection

The data collection is performed with the [Open Terms Archive engine] (https://docs.opentermsarchive.org/). Open Terms Archive (OTA) is a French NGO focused on making company terms and their changes available to consumers and the public, and offering an almost real-time alert service for such changes. The dataset GenGA utilizes the open source software ‘Open Terms Archive Engine’ to download and archive changes of generative AI services. Two aspects for data collection are important and linked to the OTA. The OTA Engine automatically updates the archive of the English language version of selected platform policies on a regular basis, capturing all meaningful edits in terms and policies. This is done by using an automated web scraper that tracks the changes of each web URL. The relevant parts of platform policies are selected [here](https://github.com/OpenTermsArchive/genai-eu-declarations) with the use of CSS selectors and Javascript filters, to select the correct content, remove insignificant content (e.g. ads, illustrative pictures, internal navigation links…), and filter out noise (e.g. tracker identifiers in links, relative dates…). The engine scrapes through the selected policies multiple times a day, and keeps all HTML snapshots [here](https://github.com/OpenTermsArchive/genai-eu-snapshots). If changes are detected within the HTML snapshots, new versions of the policy are populated to the [GenGA dataset](https://github.com/OpenTermsArchive/genai-eu-versions). Please consult the [documentation](https://docs.opentermsarchive.org/) for more information on the Open Terms Archive Engine.

Even when taking an automated approach, we could not archive all platforms this way. The logic for archiving decisions has largely been based on scale i.e. selecting the services with the largest possible usership. In general, we are interested in Generative AI services that enable communication and not in image or video generating services. A number of these services can be best described as “chat services” although they might have a number of additional features. Another sampling criterion is that the location of the services must be in the jurisdiction of the European Union (at least through a form of representation or agent). We track the European versions of policies wherever possible.

We try to ensure a constant tracking so that even the slightest changes in policies would not be missed. However, due to technical issues and anti-bot protection measures of the platforms we sometimes lose parts of data. For instance, in the beginning of the year 2026 we faced a massive amount of tracking errors presumably caused by the temporary blockings by the platforms' cybersecurity services. In order to maintain full transparency, we are documenting the periods during which the recording of snapshots is interrupted. The detailed information about the data gaps in Platform Governance Archive and GenAI Governance Archive collections can be found [here](https://docs.google.com/spreadsheets/d/1d9obvYX331ppueC7BNVNqfFgdjqr75xYf-fGCPO2a2c/edit?usp=sharing). 

## Explore and Download the Data

The data is organised by the GenAI providers, each having a dedicated folder in this repository. Within this folder, you find a markdown-file for each policy / document of this provider. For each of these files the repository includes the full history of changes.

If you just want to work with the current versions of platform policies you can just click through the services and documents. You can also download the files in their current form by clicking on the green "Code" button on the top right and then "Download ZIP".

If you want to explore the history of changes, open the folder of the service of your choice. You will see the set of documents tracked for that service. Now click on the document of your choice, for example, [Claude.AI Privacy Policy](https://github.com/OpenTermsArchive/genai-eu-versions/blob/main/Claude.ai/Privacy%20Policy.md). The latest version will be displayed. To view the history of changes made to this document, click on "History" at the top right of the document. The changes are ordered ante-chronologically (see [example](https://github.com/OpenTermsArchive/genai-eu-versions/commits/main/Claude.ai/Privacy%20Policy.md)).

Click on a change to see its contents. The red colour shows deleted elements and the green colour shows added elements. For example, here is an interesting change in [Claude’s Privacy Policy](https://github.com/OpenTermsArchive/genai-eu-versions/commit/1fcddb027d3faad9360e30233722d28df70152a7).

You can choose from two types of display with the icons in the grey bar above the document:

- The first one, named source diff (button with chevrons) displays the previous version and the next one side by side.
- The second one, named rich diff (button with a document icon) displays all the changes in a single document. In this view, beyond green and red, the yellow color shows modified paragraphs. Be careful, this display does not show some changes such as hyperlinks and text style changes.

You can download the full repository including all tracked platforms and documents with their complete history under "[Releases](https://github.com/OpenTermsArchive/genai-eu-versions/releases)".

## Using the Data in your Own Projects

We are more than happy if you want to use our dataset in your research, reporting, and explorations.

We are currently preparing a data paper for GenGA and will add the citation as soon as the paper is complete. 

**Recommended Citation for Single Policy Document**: Name of platform. (Date of version). Name of policy. Platform Governance Archive. Direct URL.

In general, GenGA is made available under the [Open Data Commons Attribution License](http://opendatacommons.org/licenses/by/1.0/) (that means what we say above: use it, but reference us).

## Use RSS feed

You can receive notification for a specific service or document by subscribing to RSS feeds.

> An RSS feed is a type of web page that contains information about the latest content published by a website, such as the date of publication and the address where you can view it. When this resource is updated, a feed reader app automatically notifies you and you can see the update.

To find out the address of the RSS feed you want to subscribe to:

1. [Navigate](https://github.com/OpenTermsArchive/genai-eu-versions#exploring-the-versions-history) to the page with the history of changes you are interested in. *In the OpenTermsArchive example above, this would be [this page](https://github.com/OpenTermsArchive/genai-eu-versions/commits/main/OpenTermsArchive/Privacy%20Policy.md).*
2. Copy the address of that page from your browser’s address bar. *In the OpenTermsArchive example, this would be `https://github.com/OpenTermsArchive/genai-eu-versions/commits/main/OpenTermsArchive/Privacy%20Policy.md`.*
3. Append `.atom` at the end of this address. *In the OpenTermsArchive example, this would become `https://github.com/OpenTermsArchive/genai-eu-versions/commits/main/OpenTermsArchive/Privacy%20Policy.md.atom`.*
4. Subscribe your RSS feed reader to the resulting address.

#### Recap of available RSS feeds

| Updated for                    | URL                                                          |
| ------------------------------ | ------------------------------------------------------------ |
| all services and documents     | `http://134.102.58.170/collection-api/v1/feed` |
| all the documents of a service | Replace `$serviceId` with the service ID: `http://134.102.58.170/collection-api/v1/feed/$serviceId` |
| One specific document          | Replace `$serviceId` with the service ID and `$termsType` with the terms type: `http://134.102.58.170/collection-api/v1/feed/$serviceId/$termsType` |

For example:

- To receive all updates of `Claude.AI` documents, the URL is `https://github.com/OpenTermsArchive/genai-eu-versions/commits/main/Claude.ai.atom`.
- To receive all updates of the `Privacy Policy` from `Grok`, the URL is `https://github.com/OpenTermsArchive/pga-versions/commits/main/Grok/Privacy%20Policy.md.atom`.
