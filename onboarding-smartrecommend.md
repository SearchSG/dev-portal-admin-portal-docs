## Onboarding for SmartRecommend

`SmartRecommend` provides tailored recommendations to your users through 2 modes:

- **ML-based Recommendations** - Automated predictions powered by a Machine Learning model that learns from user interactions.<br>This model recommends links based on three key factors:
    - User interaction history: Derived from users’ previous activity, including clicks and page views.
    - Popularity of website pages: Pages that receive more user engagement are displayed higher in the recommendations.
    - Relevance score: Pages are shown based on their predicted relevance, with the highest-scoring ones displayed first.

    This approach allows for personalized recommendations without requiring site owners to manually define the recommendation rules.

- **Rule-based Recommendations** - Allows you to define specific rules and deterministic call-to-actions for targeted recommendations.

### Creating your SmartRecommend index

(_Required only for_ `ML-based`)

Navigate to **Index Library** page and refer to [Index Guide](index-recommendation) for detailed steps.

### Setting Up Your SmartRecommend Banner

Follow the user guide for **[Rule-based](application-smartrecommend#how-to-create-a-rule-based-recommendation-banner)** or **[ML-based](application-smartrecommend#how-to-create-a-ml-based-recommendation-banner)** to set up your banner and obtain the **Client ID** required for the next step.

With the **Client ID**, you can now follow the [onboarding steps](https://docs.developer.tech.gov.sg/docs/searchsg-onboarding-guide/onboarding-for-smartrecommend?id=step-3-integrate-smartrecommend-into-your-website) provided to add the integration script into your website to deploy the SmartRecommend banner.

Before launching, preview your banner in staging to confirm it meets all your standards for appearance and functionality then you are ready to go live!