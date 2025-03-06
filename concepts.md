## Key Concepts - How does SearchSG Admin Portal Work?

### Project (Tenant)

- Projects are designed as a subscription framework that consolidates all resources / configurations related to your tenant within a shared environment.
- Allows you to organise the apps you create into different groups for easier management.
- Add editors into each project to collaborate together. Editors will only be able access the projects they are added to.

### Indexes

- An index serves as a repository for your documents, acting as a searchable knowledge base. It can contain one or more data sources that sync your data with the SearchSG platform.
- Indexes you create for a project can be shared across all the apps within the same project.
For example, if you create an index in the “SearchSG” project, you can test the index on a staging site (e.g. stg.search.gov.sg) then use the same index on a production site (e.g. prod.search.gov.sg).

### Data Sources

- Data sources are the building blocks of a search index, determining what content users can find when they search.
- Data source connectors facilitate data syncing and indexing, either through web scraping or by connecting to your APIs.
    -   **Web Data Source**: Utilize our web crawlers to scrape publicly accessible websites, automatically crawling and re-indexing data on a daily basis.
    -   **API Data Source**: Connect to your APIs to poll for data updates, enabling automatic updates and re-indexing on an hourly basis.

### Sites

- A site refers to a website or server-side application that integrates with SearchSG. 
- It serves as a workspace for multiple applications, such as Search and Recommend, requiring only a one-time integration to enable the use of multiple application features.

### Applications

- An application encapsulates all configurations for a specific search / recommend feature deployed on your site. 
    - Example: search bar settings and filter configurations for your search app are managed under 'Applications'.


