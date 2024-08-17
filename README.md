# Indian Tourism Analysis

Tourism is a key pillar of India's economy, serving as one of the largest sectors within the service industry. It has been experiencing rapid growth and is crucial to the country's economic health. According to the World Travel and Tourism Council, in 2018, tourism contributed ₹16.91 lakh crore (approximately US$220 billion) to India's GDP, accounting for 9.2% of it. The industry also supported 42.673 million jobs, representing 8.1% of total employment. In the 2019-20 period, tourism was estimated to contribute directly 2.7% to the GDP and 6.7% to total employment in the country.

India's status as a top tourist destination is due to its wide range of attractions spread across the nation. Each state in India offers its own distinct tourism experiences. From thrilling wildlife and desert safaris to peaceful nature retreats, India caters to everyone. It's a perfect destination for honeymooners, adventure seekers, spiritual explorers, and history enthusiasts interested in India's rich historical sites.

This project is focused on analyzing India's tourism, particularly concerning foreign tourists, using data obtained from [data.gov.in](https://data.gov.in/).

## Datasets Used:

- **India-Tourism-Statistics-1981-2020-fta_nri_ita.csv**: This dataset provides statistics on foreign tourist arrivals in India from 1981 to 2020. It differentiates between international tourists (ITAs), foreign tourist arrivals (FTAs), and non-resident Indians (NRIs), and includes the percentage change between consecutive values.
  
- **India-Tourism-Statistics-2001-2019-agegroup.csv**: This dataset presents the distribution of FTAs in India by age group from 2001 to 2019, expressed in percentages.
  
- **India-Tourism-Statistics-2001-2019-quarterly.csv**: This dataset contains quarterly distribution statistics, showing the percentage of foreign tourists visiting India from 2001 to 2019.
  
- **India-Tourism-Statistics-2001-2019-worldvsindia.csv**: This dataset compares global tourism with Indian tourism, including world rankings from 2001 to 2021.
  
- **India-Tourism-Statistics-2019_region-and-reason.csv**: This dataset includes 2019 statistics on ITAs in India, showing the percentage distribution of international tourist visits by specific factors, grouped by countries and regions.
  
- **India-Tourism-Statistics-2021-monuments.csv**: This dataset provides statistics on the number of domestic and foreign tourists visiting popular Indian monuments during 2019, 2020, and 2021, along with regional data.
  
- **India-Tourism-Statistics-region-2017-2019.csv**: This dataset provides statistics on the share market contribution of Indian tourism from 2017 to 2019, expressed in percentages.
  
- **India-Tourism-Statistics-statewise_2019-2020_domestic_foreign.csv**: This dataset includes state-wise statistics of domestic and foreign tourists visiting India in 2019 and 2020.

## Required Python Libraries:
```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

%matplotlib inline
