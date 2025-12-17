## Index

- `Index` - An index serves as a repository for your documents, acting as a searchable knowledge base. It can contain one or more data sources that sync your data with the SearchSG platform.

- `Index Deactivation Policy` -
    - For Indexes Not Connected to Any Apps: If an index hasn't been updated in over 30 days
    - For Indexes Connected to Apps:
        - None of the connected apps are currently active, and
        - None of these apps have been updated in over 30 days
        - Note: Once an index is deactivated, all contents and files sent through the PushAPI data source will be permanently removed. 

- `Data Sources` - Data sources are connectors that facilitate data syncing and indexing, either through web scraping or by connecting to your APIs.
    - **Web Data Source**: Utilize our web crawlers to scrape publicly accessible websites, automatically crawling and re-indexing data on a daily basis.
    - **API Data Source**: Connect to your APIs to poll for data updates, enabling automatic updates and re-indexing on an hourly basis.
    - **Push API Data Source**: Push your updated content and files by sending data to our API endpoints at your preferred timing.

## Available Features & Compatibility

Use this table to understand which features are currently supported and the corresponding data sources required for setup.

<table>
    <th>Feature</th>
    <th>Index Type</th>
    <th>Web Data Source</th>
    <th>API Data Source</th>
    <th>Push API Data Source</th>
    <th>
        Platform Data Source<br>
        <span style="font-weight: normal"><i>(Coming soon)</i></span>
    </th>
    <tr>
        <td>Website Search</td>
        <td>Public Web Index</td>
        <td>Yes</td>
        <td>Yes</td>
        <td>Yes</td>
        <td>No</td>
    </tr>
    <tr>
        <td>SmartRecommend</td>
        <td>Recommendation Index</td>
        <td>Yes</td>
        <td>Yes</td>
        <td>No</td>
        <td>No</td>
    </tr>
    <tr>
        <td>Directory Search</td>
        <td>Directory Index</td>
        <td>Yes</td>
        <td>Yes</td>
        <td>Yes</td>
        <td>No</td>
    </tr>
    <tr>
        <td>OneGov Enterprise Search<br><i>(Coming Soon)</i></td>
        <td>Enterprise Index</td>
        <td>Yes</td>
        <td>Yes</td>
        <td>Yes</td>
        <td>Yes</td>
    </tr>
</table>