# SearchSG Admin Portal: User Onboarding Guide

## Key Concepts

### Tenant (Project)

A tenant is a subscription framework that consolidates all resources / configurations related to your team within a shared environment.

### Sites

A site refers to a website or server-side application that integrates with SearchSG. It acts as a workspace for multiple applications, such as Search and Recommend, requiring only a one-time integration to enable the use of multiple application features.

### Applications

An application encapsulates all configurations for a specific search / recommend feature deployed on your site.

### Indexes

An index serves as a repository for your documents, acting as a searchable knowledge base. It can contain one or more data sources that sync your data with the SearchSG platform.

### Data Sources

Data sources are connectors that facilitate data syncing and indexing, either through web scraping or by connecting to your APIs.

-   **Web Data Source**: Utilize our web crawlers to scrape publicly accessible websites, automatically crawling and re-indexing data on a daily basis.
-   **API Data Source**: Connect to your APIs to poll data, enabling automatic updates and re-indexing on an hourly basis.

## Onboarding to SearchSG to start using Search

### Setting Up Your Tenant

To start using SearchSG, create a subscription tenant project.

1. Access the **Tenant** option in the top navigation bar.
2. Select **Add New Tenant**.
3. Name your tenant according to your project or use case (e.g., "MOM Corporate Website") and provide a description. Choose your billing agency.
4. To add collaborators, select **Add New Tenant Admin** and enter their email addresses.

### Creating Your First Index

Once your tenant is set up, you can create an index.

1. Navigate to the **Indexes** section and select **Add New**.
2. Provide a descriptive name for your index (e.g., "MOM Website Documents").
3. Configure your index by adding new data sources.

    For web data sources, select from a list of websites that SearchSG already crawls. After configuration, you can trigger syncing to begin indexing immediately.

### Configuring Your Search Application

With your knowledge base established, you can create an application that utilizes the index for search functionality.

1. In the **Applications** section, select **Add New**.
2. A new search application will be created with default basic configurations, and a **Client ID** will be generated.
3. You may further configure search configurations with the `Workspace` tab
4. Follow the onboarding steps to integrate the search bar injection script into your website.

Once the integration is complete, your search functionality will be ready for use!
