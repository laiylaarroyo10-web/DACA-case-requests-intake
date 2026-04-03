# DACA-case-requests-intake
Dataset and methodology for consideration of case intake of DACA

# Project Overview
Studying the case intake of DACA reciprients, looking for any spikes or drops. Leading question is: How has the number of DACA case intakes changed between 2016 compared to 2024? 

# Dataset Overview
Collected by the U.S. government, specifically by Citizen and Immigration Services. This dataset spans between 2012 to third quarter of 2025. 
Link to original source: https://www.uscis.gov/tools/reports-and-studies/immigration-and-citizenship-data?topic_id%5B%5D=33602&ddt_mon=&ddt_yr=&query=&items_per_page=1

# Methodology
The dataset is very detailed and required little cleaning, which makes it useful but also somewhat complex. It includes multiple sheets that break down DACA cases by status, state, and country of origin. I only made the decision to double check for any extra white-space and trimmed. I also made pivot tables to help me compare the case intakes.

One key pattern is that 2016 had the highest number of both accepted and rejected DACA cases between 2014–2025, showing a major spike in overall applications. In contrast, 2024 had the lowest numbers for both accepted and rejected cases.

To make a fair comparison across years, I analyzed the data using percentage rates rather than raw totals. This showed that although 2016 had a much higher number of rejected cases, the acceptance rate was consistent with other years overall.

# Limitations
The dataset can be confusing at first. It doesn’t actually show how many people have DACA each year—it only shows how many cases were processed (case intake). So it doesn’t give a clear total number of active recipients over time.

Some of the labels are also unclear. In the country section, only 31 countries are listed, while all others are grouped into an “all others” category, which hides details. In the state section, there’s a “not reported” category, but it’s unclear why those cases are included if the information wasn’t reported.

Overall, the data can still be useful, but it leaves some important questions unanswered.
