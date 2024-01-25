# GMM-Segmentation-Dunnhumby

## 🎯 Project Overview 

The primary goal of this analysis is to gain insights into customer segmentation by using the Gaussian Mixture Model (GMM), allowing businesses to understand the diverse needs and preferences of their customer base.

## ✨ Data Sources 
The Dunnhumby dataset has been obtained from [Kaggle](https://www.kaggle.com/datasets/frtgnn/dunnhumby-the-complete-journey/data?select=hh_demographic.csv)

AIC & BIC for selecting the optimal number of clusters and determining a balance between model complexity and goodness of fit can be explained further [here](https://vitalflux.com/aic-vs-bic-for-regression-models-formula-examples/)

## 🌱 Objectives 
The primary objectives of this clustering project are as follows:

- Customer Segmentation: Utilize clustering algorithms to identify distinct customer segments based on their attributes and behaviours.

- Profile Creation: Develop detailed profiles for each identified cluster, outlining the mean attribute values that define them.

- Business Insights: Derive actionable insights from the clusters to inform marketing strategies, product development, and customer engagement approaches.

- Marketing Strategy Recommendations: Provide tailored marketing strategies for each cluster, maximizing the effectiveness of promotional efforts.

- Product Customization Opportunities: Identify opportunities for product customization or development based on the unique preferences and characteristics of each cluster.

- Enhanced Customer Engagement: Propose strategies for enhancing customer engagement and loyalty, considering the specific needs of each cluster.

## ⚡ Tools 
- Google Colab
- Python

## 🔭 Cluster Interpretation
- Cluster 0: "Young Adults"
  
  Age Distribution: Dominated by individuals aged 25-34. Some representation in the 35-44 age group. Negligible representation in the 45-54 and 55-64 age groups. No representation in the 65+ age group.
  
  Marital Status: Predominantly single (Unknown marital status).
  
  Income Distribution: Diverse income distribution with a slight emphasis on the $15-24K range.
  
  Homeownership: Higher probability of being a probable renter.
  
- Cluster 1: "Middle-Age Families"
  
  Age Distribution: Significant representation across age groups, with a focus on 35-54 age group.

  Marital Status: A mix of married and unknown marital statuses.

  Income Distribution: Relatively higher representation in the $150-174K income range.

  Homeownership: Higher probability of being a probable owner.

- Cluster 2: "Young Professionals"

  Age Distribution: Dominated by individuals aged 25-34 and 35-44. No representation in the 55-64 and 65+ age groups.

  Marital Status: A mix of married and unknown marital statuses.

  Income Distribution: Varied income distribution, with emphasis on $125-149K.

  Homeownership: Higher probability of being a probable renter.

- Cluster 3: "Middle-Age Parents"

  Age Distribution: Dominated by individuals aged 45-54. Some representation in the 55-64 age group. No representation in the 25-34, 35-44, and 65+ age groups.

  Marital Status: Predominantly married.

  Income Distribution: Varied income distribution, with emphasis on $150-174K.

  Homeownership: Balanced probability between probable owner and probable renter.

- Cluster 4: "Diverse Household"

  Age Distribution: Spread across various age groups. No representation in the 65+ age group.

  Marital Status: A mix of married and unknown marital statuses.

  Income Distribution: Varied income distribution.

  Homeownership: Higher probability of being a probable renter.

## 📫 Marketing Strategies
- Cluster 0: "Unknown Singles"
  
  Digital Engagement Campaign: Leverage online platforms for marketing campaigns since this cluster has a high likelihood of having unknown marital status and household composition.
  Utilize targeted social media advertisements and email campaigns to engage with individuals in the 25-44 age group.

- Cluster 1: "Middle-Age Family"

  Family-Centric Promotions: Create marketing promotions that appeal to families, emphasizing products or services suitable for various family sizes.
  Offer family discounts or bundled packages to attract and retain customers in the 35-54 age group.

  Multichannel Marketing: Implement a multichannel marketing approach to reach individuals with varying preferences.
  Combine online and offline strategies, including social media campaigns, email newsletters, and targeted print materials to cover a broader audience.

- Cluster 2: "Young Professionals"

  Career Development Events: Organize events or webinars focusing on career development and professional growth.
  Promote products or services that cater to the needs and lifestyles of young professionals, such as career-related tools or lifestyle subscriptions.

  Social Media Influencer Collaborations: Partner with social media influencers popular among the 25-44 age group to endorse products or services.
  Leverage influencer marketing to increase brand awareness and credibility among this tech-savvy cluster.

- Cluster 3: "Middle-Age Parents"

  Family-Focused Loyalty Programs: Introduce loyalty programs that reward middle-aged parents for family-related purchases.
  Offer exclusive discounts, early access to new family-oriented products, and rewards for frequent purchases.
  
  Parenting Workshops and Content: Conduct workshops or provide online content addressing parenting challenges and offering solutions.
  Use content marketing to position the brand as a valuable resource for parenting advice and products.

- Cluster 4: "Diverse Household"

  Targeted Product Bundles: Create diverse product bundles that cater to the varied preferences and needs within this cluster.
  Offer personalized bundles with discounts to encourage cross-category purchases.

  Community Engagement Initiatives: Launch community-focused initiatives to connect with the diverse audience in this cluster.
  Sponsor local events, support community projects, and engage with customers through community forums to build a sense of belonging.
