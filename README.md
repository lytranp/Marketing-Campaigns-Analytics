# Marketing-Campaigns-Analytics

1. Dataset: A list of users with language_preferred and age_group. They could choose to subscribe the service via different marketing channels. Our data recorded if they canceled the subscription within 1 month. 

2. Approaches

  a. Clean data:
  
  - Mapping marketing channels to numeric
  
  - Convert date_subscribed from string type to time 

  b. Check how many users are seeing ads by date_served
  
  c. Check what marketing channel attracting users who subscribed the most
  
  d. Check age_group in each marketing channel because one of hypothesis: older people often access to ads via House Ads whereas younger people prefer Instagrams
  
  d. Conversion rate is important, but retention rate is even much more important 
  
  - Compute conversion rate and retention rate to evaluate how marketing campaign performed

  - We also realize that conversion rate is decreasing recently. So, one of hypothesis: language_displayed does not match with language_prefered. Then, we want to compute % of langugage_preferred that was displayed correctly. As a sequence, we will see in the most recent days, the number of language_preferred displayed wrongly was much higher than previous days.
