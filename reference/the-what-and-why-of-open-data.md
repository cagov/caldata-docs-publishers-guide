# The What and Why of Open Data

## :white\_check\_mark: What is open data?

The Open Knowledge Foundation has a standard definition of open data in both short and detailed form. We've sumarized the key components and modified the definition to be specific to California standards where appropriate.

**Open data is data that can be freely used, shared and built-on by anyone, anywhere, for any purpose.**

Building on this, open data:

1. **Is openly licensed.** In California, data _must_ be in the Public Domain.
2. **Is accessible.** In California, data _must_ be published to an official State open data portal without restrictions. Any additional information necessary for attribution or citation _must_ also accompany the data.
3. **Is machine readable.** Data _must_ be provided in a form readily processable by a computer and where the individual elements of the work can be easily accessed and modified.
4. **Is in an open format.** Data _must_ be provided in an open format. An open format is one which places no restrictions, monetary or otherwise, upon its use and can be fully processed with at least one free/libre/open-source software tool.

The Open Knowledge Foundation provides [additional detail about open works in their open definition](https://opendefinition.org/od/2.1/en/).

## :x: What is NOT open data?

There are many things the State does to share data or reports about data. You can consider these "data products," but they don't constitute open data by the definition above. The table below describes several data products that are sometimes confused with open data, a reason why they aren't, and ways to leverage your data product to open data.

| Data Product and Description                                                                                                                 | Why this is not open data                                                                                                                                                                                                                                                                                                                                                                                                        | How to upgrade to open data                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| -------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Web application.** _A public-facing application that allows users to search for specific data and potentially generate reports_            | <p>While these applications are useful and can meet specific user needs, they require the user to run queries and generate reports and often limit bulk access to data. <br><br>If a user wanted to do an analysis, they would need to run multiple queries. More savvy users will write scripts to automate this, which can burden the application. This limits the accessibility to the data by putting burden on its use.</p> | <p>Develop an automated process from your backend system with IT to extract the raw data in the application and load to the open data portal. Once there, users can access as a single download or through an Application Programming Interface.<br><br>Provide a link from your application to enable discovery of raw and bulk data, which will take burden off of your application. You can also link to your application from the published open data.</p> |
| **Dashboard.** _An interactive application that allows users to visualize data in pre-created reports_                                       | Contextualizing data is useful, but if a user wanted to do additional analysis outside of the pre-created visuals and filters, they wouldn't be able to. This limits the accessibility and machine readability of the data. Data would also not be considered published in an open format.                                                                                                                                       | <p>Provide the underlying data in raw and bulk forms through the open data portal. <br><br>Provide a link to your dashboard from the open data portal and to the published open data from your dashboard. This enables discovery of your resources.</p>                                                                                                                                                                                                        |
| **Report.** _A document providing both data and context often published as a PDF and to satisfy an administrative or legislated requirement_ | <p>Reports are just snapshots in time and are highly curated. Users cannot do any additional analysis so they cannot build on the work. <br><br>Even if tables are provided in the report, extracting data from PDFs is prone to error and does not satisfy data being machine readable. It also limits accessibility of data.</p>                                                                                               | <p>Publish the data behind the report on the open data portal. If the report is based on administrative data that is collected more regularly than the reporting period, publish the underlying data on a more frequent and automated basis.<br><br>Provide a link in your report to the published data and link to reports from your published data enable discovery of your resources.</p>                                                                   |

## Why open data?

Open data is not just something we do for the sake of open data. There are real benefits including:

* **Stimulating new ideas and services.** By releasing open data, State organizations may help to stimulate new and innovative ideas from Californians. There is great potential for open data to act as the fuel for new solutions and even new businesses that can address common problems or challenges facing those that live in, work in, or travel to the State of California. For example, see [projects developed](https://waterdatacollaborative.github.io/project/) as part of the [California Water Data Challenge](https://waterchallenge.data.ca.gov).
* **Increasing cross-organizational data sharing.** If data can be shared in the open, you can leverage the open data portal as an interface to data between departments and agencies and other external organizations. This can also save from additional costly investments in data infrastructure. Combining information from different State departments and agencies can also provide valuable insights into important areas that many organizations touch including health equity, climate change, and drought response to name just a few.
* **Simplifying Public Records Act (PRA) Requests.** Open data releases can be an effective way of responding to requests for data made under the Public Records Act. One open data release may address multiple requests for information than can be repetitive and costly to respond to if addressed on an individual basis.
* **Improving data quality.** Having more eyes on data helps improve the quality over time. Open data publishing allows and encourages users to provide feedback on accuracy, consistency, and other quality measures, important feedback that can help departments get better results from their own internal data uses.&#x20;
* **Reducing unwanted web traffic.** Publishing open data can also help reduce unwanted web traffic on department and Agency websites, which is often the result of “data scraping” by individuals seeking to obtain data in bulk from the State through public applications. This puts unnecessary stress on the State's technology infrastructure and unneeded burden on IT staff.
* **Changing how we use data.** Ultimately, open data can serve as a platform to change how we use, share, and consume our data externally and internally, transform data into services, and foster continuous improvement in decision making and the business of government. Ultimately, open data is about enabling use of data to help support a range of positive outcomes.
