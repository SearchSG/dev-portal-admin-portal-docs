## Directory Index

### How to Create a Directory Index

#### Step 1: Access the Index Library

- Navigate to the `Index Library` page using the top navigation menu.

#### Step 2: Add a New Index

- Click on "Add new +" within the project card that you want to add your index to.
- In the pop-up window, enter a title for your index, choose `Directory` as the type, and click "Create" to proceed.
![Create index](images/index/directory_search/create_index.png)

#### Step 3: View Created Index in Index Overview

- The created index will have a status that indicates "Action Required: Add Data Source" on the Index overview page after creation.
![Index overview](images/index/directory_search/index_overview.png)
- **Status Definitions**:
    - `Action required: Add data source`: This status means at least **one data source** must be added before the directory index can start supporting search functionality.
    - `Pending sync`: This status indicates the directory index is queued for syncing and waiting to start.
    - `Syncing`: This status indicates that data syncing is currently in progress. Please wait for it to complete.
    - `Active`: This status indicates that the directory index is now active and serving search results.

#### Step 4: Add a Data Source

- Click "Data Sources" tab and you will be redirected to the data sources page.
![Data sources](images/index/directory_search/index_data_sources.png)

#### Step 4.1. Setup a Web Data Source

- To add a `Web Data Source`, choose "Add new +" within Web data source card and proceed to set up the data source.
![Add web data sources](images/index/directory_search/add_web_data_source.png)
- Select your website domain to index from the list of websites crawled by SearchSG. If your domain is not listed, click on **"Domain is missing"**.
- Whitelisted and blacklisted pages are optional configuration to exclude certain webpages.
- Click on "Save" and then "Proceed" in the confirmation pop-up window.
![Add web data sources confirmation](images/index/directory_search/add_web_data_source_confirmation.png)
- You will be redirected to the previous page, where the newly created data source will appear under the "Web data sources" section.
![Added web data sources](images/index/directory_search/added_web_data_source.png)

#### Step 4.2. Setup an API Data Source

- This API connector allows agencies to index custom API data that may be protected or not publicly available. Our API connector polls your configured endpoints hourly, to process changes in your content and updates your index automatically.
- To add an `API Data Source`, choose "Add new +" within API data source card and proceed to set up the data source.
![API data sources](images/index/directory_search/api_data_source.png)
- Fill up your API information and click on "Next". Refer our docs to understand [how API Data sources work](https://docs.developer.tech.gov.sg/docs/searchsg-onboarding-guide/indexing-features?id=b-api-data-source)
![Add API data sources](images/index/directory_search/add_api_data_source.png)
- Once configured, a data health check will be performed on your API.
![API data sources health check pass](images/index/directory_search/api_data_source_health_check_pass.png)
    - If all required data are present, click "**Add data source**"
    - If any required data are missing, you can choose to "**Fix issues**" or "**Continue with warnings**"
    ![API data sources health check fail](images/index/directory_search/api_data_source_health_check_fail.png)

- Click "Add data source" in the confirmation pop-up.
![Add API data sources confirmation](images/index/directory_search/add_api_data_source_confirmation.png)
- You will be redirected to the previous page, where the newly created data source will appear under the "API data sources" section.
![Added API data sources](images/index/directory_search/added_api_data_source.png)

#### Step 4.3. Setup a Push API Data Source

- The `Push API Data Source` allows you to proactively send updated content and files to SearchSG whenever your data changes. With near real-time synchronization, it bypasses the need for polling, and it’s especially useful for websites with time-sensitive data.
- For enabling the `Push API Data Source`, toggle the switch button. A confirmation toast message - "Push API data source enabled" will appear upon successful activation.
![Enable Push API data sources](images/index/directory_search/push_api_data_source_toggle.png)
- Only the latest 5 pushes within the past 7 days are displayed, including details on the number of documents added or deleted. For example, if only 1 push happened within the past 7 days, just that push will appear.
- "No error detected" indicates a successful API call.
- If errors occur, download the error report using the provided link. **Note**: Error report downloads will be available in an upcoming release.
![Push API data sources error report](images/index/directory_search/push_api_data_source_error_report.png)
- When disabled, previously synced content and files are preserved, so you can re-enable the data source later without data loss.

#### Step 5: Trigger Sync Process to Prepare Index

- Under "Index overview", the status of the index should be updated to "Pending Sync".
![Index overview pending sync](images/index/directory_search/index_overview_pending_sync.png)
- Click on sync icon next to index status to trigger syncing process to start immediately, or wait for the scheduled job to start sync for your index automatically at a later timing.
- Once sync process is complete and your index is ready to be used, the index status will update to be "Active".
![Index overview synced](images/index/directory_search/index_overview_synced.png)

### Optional Configurations for your Search Index

#### Synonyms

1. Access Synonyms
    - Navigate to the "Synonyms" page to set up synonyms.
2. Request Synonyms setup for your Index
    - To add synonyms, reach out to us by clicking on the "Request to add or edit synonyms" button.
    ![Synonyms](images/index/directory_search/synonyms.png)


#### Featured Results

1. Access Featured Results
    - Navigate to the "Featured results" page to configure the featured search result.
    ![Featured results](images/index/directory_search/featured_results.png)

2. Create Featured Results
    - Click "Add new +" in the "Set up featured results" card to create a new featured result.
    - Enter the following details:
        - **Search terms**: The query terms that will trigger the featured result.
        - **Page URL**: The URLs of pages within your index that should be pinned to the top of search results.
        
        Both fields are required. The **Display title** is optional.
        ![Add featured results](images/index/directory_search/add_featured_results.png)
3. Save and Verify
    - After saving, you will be redirected to the previous page, where the newly created featured result(s) will appear under the "**Set up featured results**" section.
    ![Added featured results](images/index/directory_search/added_featured_results.png)

### How to Delete the Directory Index?

***Note: Deleting a directory index will permanently remove all previously collected interaction feedback and incremental learning data associated with it, which may negatively impact search relevance.***
1. Click "**More actions**" and then select "**Delete**".
![Delete index](images/index/directory_search/delete_index.png)

2. Click "Delete" in the confirmation pop-up.
![Delete index confirmation](images/index/directory_search/delete_index_confirmation.png)

3. You will be redirected to the index library page once the index is successfully removed.
![Deleted index](images/index/directory_search/deleted_index.png)
    - Only indexes that are not used in any active sites, or are associated with inactive (soft-deleted) sites, can be deleted.