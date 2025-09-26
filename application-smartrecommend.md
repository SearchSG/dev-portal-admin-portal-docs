## SmartRecommend

### How to create a Rule-based recommendation banner?

1. Login to Admin Portal.

2. Click on “Create app” then “SmartRecommend”.
    ![Create app](images/application/smart_recommend/create_app.png)

3. Choose the site you would like to place the banner then click next.
    ![Create app](images/application/smart_recommend/choose_existing_site.png)
    - If you would like to place the banner on your existing site, select the site from the drop-down list
    - If you would like to place the banner on a new site, select the option “Create a new site” and enter the information such as name, URL and choose the environment

    ![Create app](images/application/smart_recommend/create_new_site.png)
    - If you would like to add the new site into your existing project, select the project from the drop-down list
    - If you would like to add the new site into a new project, select the option “Create a new project” and enter the project name and choose the agency

    ![Create app](images/application/smart_recommend/create_new_project.png)

4. Configure the basic settings then click next. **Note**: These settings can’t be edited after the banner is created.
    ![Create app](images/application/smart_recommend/choose_smartrecommend_model_rule_based.png)
    ![Create app](images/application/smart_recommend/choose_audience_control_settings.png)
    ![Create app](images/application/smart_recommend/choose_banner_layout.png)
    - **Banner Name**: Used for analytics and usage tracking. Once set, it can’t be changed to avoid splitting analytics data.
    - **SmartRecommend Model**: Select the option "Set my own rule".
    - **Audience Control Settings**: Choose one of the following tracking options (applies to all rules in this banner):
        - Track only the most recent page viewed
        - Track all pages viewed in the past 6 months
    - **Banner Layout**: Select one layout (styling can be adjusted later, but the layout can’t be changed):
        - Link Banner (supports up to 6 links)
        - Horizontally-Stacked Card Banner (supports up to 4 cards)
        - Vertically-Stacked Card Banner (supports up to 4 cards)

5. Define your audience targeting rules then click next.
    ![Create app](images/application/smart_recommend/create_new_rule.png)
    ![Create app](images/application/smart_recommend/add_rule_settings.png)
    - **Rule Name**: Used in analytics to track usage. **Note**: Once created, the rule name can’t be edited to prevent splitting analytics data.
    - **Rule Activation Period**: Choose when the rule should be active:
        - Always Active – The rule remains active as long as the banner is enabled.
        - Custom Date Range – Specify start and end dates for the rule’s activation.
    - **Banner Display Title**: This is the visible title users will see on the banner. Filling this field is optional.
    - **Recommendation Links**:
        - When **Link Banner** is selected in the previous step, you can add up to 6 links.
        - When **Card Banner** is selected, you can add up to 4 links.
    - **Audience Control**: Define who can see the banner by setting targeting rules based on:
        - Visitor type (based on browsing activity. e.g., All visitors, First-time visitors only)
        - Location (e.g., Any country, Singapore only)

6. Change rules priority then click next.

    If you have multiple rules, you may reorder them to set their priority (***optional***).
    - Click "Change rules priority"
    - In the pop-up window, reorder the rules to set their priority

    ![Create app](images/application/smart_recommend/reorder_rules.png)

7. Set up banner styling and click next.
    ![Create app](images/application/smart_recommend/banner_style_preview.png)
    ![Create app](images/application/smart_recommend/review_banner_style_settings.png)
    - Click “Edit style“ to open the styling panel
    - In the pop-up window, tailor the banner’s appearance for desktop, tablet, and mobile views.

    ![Create app](images/application/smart_recommend/banner_style_sandbox.png)

8. Set banner placement and click “Add banner”.

    Select the page(s) where your banner should appear and define the HTML marker. **Note**: Each banner requires a distinct marker to ensure proper display.

    ![Create app](images/application/smart_recommend/banner_placement.png)
    ![Create app](images/application/smart_recommend/add_banner_placement.png)
    - Follow the [rules](application-smartrecommend#banner-placement-rules) to specify your banner placement.
    - Follow the options below to define the banner position on your page:
        - Auto-generated HTML marker: choose this option if you don’t have an existing recommendation banner on your webpage. A unique element ID will be generated automatically for you to add to your new html div element.
        - Custom HTML marker: choose this option if you intend to replace an existing banner on your webpage.
        **Note:** The HTML marker must be unique. Validation also applies to banners in `disabled` status.
    - Follow the [steps](https://docs.developer.tech.gov.sg/docs/searchsg-onboarding-guide/onboarding-for-smartrecommend?id=onboarding-for-smartrecommend) for detailed instructions to complete your onboarding.

9. Click on “View my SmartRecommend banners” to access your banner listing page.
    - The banner will be created in an `enabled` status and can be instantly previewed and verified after adding the code snippet to your website.

    ![Create app](images/application/smart_recommend/created_app.png)

### How to create a ML-based recommendation banner?

1. Login to Admin Portal.

2. Click on “Create app” then “SmartRecommend”.
    ![Create app](images/application/smart_recommend/create_app.png)

3. Choose the site you would like to place the banner then click next.
    ![Create app](images/application/smart_recommend/choose_existing_site.png)
    - If you would like to place the banner on your existing site, select the site from the drop-down list
    - If you would like to place the banner on a new site, select the option “Create a new site” and enter the information such as name, URL and choose the environment

    ![Create app](images/application/smart_recommend/create_new_site.png)
    - If you would like to add the new site into your existing project, select the project from the drop-down list
    - If you would like to add the new site into a new project, select the option “Create a new project” and enter the project name and choose the agency

    ![Create app](images/application/smart_recommend/create_new_project.png)

4. Configure the basic settings then click next. **Note**: These settings can’t be edited after the banner is created.
    ![Create app](images/application/smart_recommend/choose_smartrecommend_model_ml_based.png)
    ![Create app](images/application/smart_recommend/choose_banner_layout.png)
    - **Banner Name**: Used for analytics and usage tracking. Once set, it can’t be changed to avoid splitting analytics data.
    - **SmartRecommend Model**: Select the option "Use SearchSG’s machine learning (ML) model".
    - **Banner Layout**: Select one layout (styling can be adjusted later, but the layout can’t be changed):
        - Link Banner (supports up to 6 links)
        - Horizontally-Stacked Card Banner (supports up to 4 cards)
        - Vertically-Stacked Card Banner (supports up to 4 cards)

5. SmartRecommend Index
    ![Create app](images/application/smart_recommend/choose_ml_recommendation_method.png)
    ![Create app](images/application/smart_recommend/choose_ml_banner_content_settings.png)
    - **Recommendation method**: You can choose to display recommended links according to page popularity or similarity.
    - **Banner display title**: This is the visible title users will see on the banner. Filling this field is optional.
    - **Number of recommended links**:
        - When **Link Banner** is selected in the previous step, you can select up to 6 links.
        - When **Card Banner** is selected, you can select up to 4 links.
    - **Source of recommendations**: You can either select an existing SmartRecommend index or follow the [user guide](index-smartrecommend#how-to-create-a-smartrecommend-index) to create a new one.

6. Set up banner styling and click next.
    ![Create app](images/application/smart_recommend/banner_style_preview.png)
    ![Create app](images/application/smart_recommend/review_banner_style_settings.png)
    - Click “Edit style“ to open the styling panel
    - In the pop-up window, tailor the banner’s appearance for desktop, tablet, and mobile views.

    ![Create app](images/application/smart_recommend/banner_style_sandbox.png)

7. Set banner placement and click next.

    Select the page(s) where your banner should appear and define the HTML marker. **Note**: Each banner requires a distinct marker to ensure proper display.

    ![Create app](images/application/smart_recommend/banner_placement.png)
    ![Create app](images/application/smart_recommend/add_banner_placement.png)
    - Follow the [rules](application-smartrecommend#banner-placement-rules) to specify your banner placement.
    - Follow the options below to define the banner position on your page:
        - Auto-generated HTML marker: choose this option if you don’t have an existing recommendation banner on your webpage. A unique element ID will be generated automatically for you to add to your new html div element.
        - Custom HTML marker: choose this option if you intend to replace an existing banner on your webpage.
        **Note:** The HTML marker must be unique. Validation also applies to banners in `disabled` status.
    - Follow the [steps](https://docs.developer.tech.gov.sg/docs/searchsg-onboarding-guide/onboarding-for-smartrecommend?id=onboarding-for-smartrecommend) for detailed instructions to complete your onboarding.

8. Click on “View my SmartRecommend banners” to access your banner listing page.
    - The banner will be created in an `enabled` status and can be instantly previewed and verified after adding the code snippet to your website.

    ![Create app](images/application/smart_recommend/created_app.png)

### Banner Placement Rules

1. **Add banner to these pages:**
    Enter the URLs (within your domain) where the banner should appear. You can:
    - Enter a full URL to display the banner on a specific page (e.g. `https://search.gov.sg/news/press-release-2024`)
    - Use a wildcard pattern to display the banner on all subpages (e.g. `https://search.gov.sg/news/*`)

    **Rules:**
    - Enter one URL per line
    - Duplicate URLs are not allowed
    - The domain of each URL must match your hosting URL

2. **Exclude these pages (_optional_):**

    Specify any URLs where the banner should not appear even if they match the above rules.

### How to delete SmartRecommend banner?

1. Login to Admin Portal

2. Navigate to “Workspace” and select your site from the drop-down list

3. Click on “SmartRecommend”

4. Click on the ![Delete app](images/3dots_icon.png) icon and select “Delete”
    ![Delete app](images/application/smart_recommend/delete_app.png)

5. In the pop-up window, click “Delete SmartRecommend banner”.
    ![Delete app](images/application/smart_recommend/delete_app_popup.png)

6. The banner will be deleted (removed) from the list.
    ![Delete app](images/application/smart_recommend/deleted_app.png)

### How to disable SmartRecommend banner?

1. Login to Admin Portal

2. Navigate to “Workspace” and select your site from the drop-down list

3. Click on “SmartRecommend”

4. Click on the ![Disable app](images/3dots_icon.png) icon and select “Disable”
    ![Disable app](images/application/smart_recommend/disable_app.png)

5. In the pop-up window, click “Disable banner”.
    ![Disable app](images/application/smart_recommend/disable_app_popup.png)

6. The banner will be disabled (deactivated).
    ![Disable app](images/application/smart_recommend/disabled_app.png)

### How to enable SmartRecommend banner?

1. Login to Admin Portal

2. Navigate to “Workspace” and select your site from the drop-down list

3. Click on “SmartRecommend”

4. Click on the ![Enable app](images/3dots_icon.png) icon on the row of the disabled SmartRecommend banner then select “Enable”
    ![Enable app](images/application/smart_recommend/enable_app.png)

5. Click “Enable banner” button in the pop-up window
    ![Enable app](images/application/smart_recommend/enable_app_popup.png)

6. If your banner doesn’t have an existing index, you will be prompted to go through a flow to connect one.
    - Click “Connect an Index”, then either select an existing index or go to the “Index Library” page to create a new one.

    ![Enable app](images/application/smart_recommend/enable_app_missing_index.png)
    ![Enable app](images/application/smart_recommend/enable_app_choose_existing_index.png)
    - If you don’t have any available indexes, you will see the screen below. Simply click “Create an Index in Index Library”.

    ![Enable app](images/application/smart_recommend/enable_app_create_index.png)
    - Click the “Confirm” button to finalize your index selection. **Note**: It will take up to 15 minutes to sync the newly selected index.

    ![Enable app](images/application/smart_recommend/enable_app_confirm.png)
    - “Banner connected to index” will appear at the bottom of the screen. You can now repeat steps 4 and 5 to enable your banner.

    ![Enable app](images/application/smart_recommend/enable_app_with_index.png)

7. “Banner enabled” will appear at the bottom, and the banner status will change to `Enabled`.
    ![Enable app](images/application/smart_recommend/enabled_app.png)

### How to duplicate SmartRecommend banner?

1. Login to Admin Portal

2. Navigate to “Workspace” and select your site from the drop-down list

3. Click on “SmartRecommend”

4. Click on ![Duplicate app](images/3dots_icon.png) icon on the row of the SmartRecommend banner then select “Duplicate”
    ![Duplicate app](images/application/smart_recommend/duplicate_app.png)

5. You can duplicate a banner either within the same site or across different sites/projects.
    - **Within the same site**: Enter all mandatory fields - Banner Name, Banner Placement, and HTML Marker Configuration.
    - **To a different site**: In addition to the above, select the destination site. If the site belongs to a different project, a warning message will appear indicating that connecting to an index is required before enabling the banner.

    ![Duplicate app](images/application/smart_recommend/duplicate_app_settings.png)

6. Click the "Duplicate" button. "Banner created" message will appear at the bottom once the banner has been successfully duplicated. **Note**: The duplicated banner will be set to `Disabled` by default. Follow the [guide](application-smartrecommend#how-to-enable-smartrecommend-banner) to enable the banner.
    ![Duplicate app](images/application/smart_recommend/duplicated_app.png)