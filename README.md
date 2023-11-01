# Investigate-Hotel-Business-using-Data-Visualization

<img src="https://img.freepik.com/premium-vector/hotel-building-isolated-city-street-vector-illustration-flat-cartoon_101884-680.jpg" alt="Hotel Business" style="width:600px;height:400px;">

In the ever-evolving landscape of business, the ongoing analysis of performance stands as a cornerstone of success. As we embark on this project, our sights are set on the vibrant hospitality industry of Indonesia. Our primary mission is to explore the intricacies of customer behavior concerning hotel bookings and its direct impact on the rates of cancellations. This endeavor is fueled by the recognition that understanding these patterns is not merely important, but imperative, for businesses operating in the unique context of Indonesia's hotel industry.

The essence of our project lies in decoding the multifaceted relationship between customer choices and the hotel booking cancellation rates within Indonesia. Our objective is to unravel the subtleties that often elude the naked eye, and to translate these revelations into tangible, data-driven insights. We are dedicated to presenting these findings through compelling data visualizations, thus ensuring that our discoveries are not only easily comprehensible but also imbued with the persuasive power needed to drive informed decision-making within the Indonesian hospitality sector.

**The data used for this analysis is data from 2017-2019.**

## Points to Analyze
This project looks at and focuses on the following:
- **Monthly Booking Analysis/Seasonality:** how the number of bookings vary from month to month by each hotel type.
- **Stay Duration Effect on Cancellation Rates:** how cancellation rates vary by duration of stay.
- **Lead Time Effect on Cancellation Rates:** how lead time affects cancellation rates.

## Data Preparation
The dataset contained: 
- 119,390 rows and 29 columns
- 129,425 null values spread across 4 columns
- 1,172 inappropriate “Undefined” values spread across 3 columns

The data was cleaned and prepared accordingly. The final dataset contains: 
- 118,900 rows and 24 columns
- Has 0 null values and 0 inappropriate values
- Is smaller and less complex than the previous one

## Analysis

### Monthly Booking Analysis/Seasonality
****
<img src="https://github.com/farrellwahyudi/Investigate-Hotel-Business-using-Data-Visualization/blob/main/Images/monthly_hotel_booking_analysis_based_on_hotel_type.png" alt="monthly booking visualization" style="width:900px;height:500px;">

**1. Seasonal Fluctuations:**

Both City and Resort Hotels experience fluctuations in bookings throughout the year, which is common in the hospitality industry. It appears that the mid-year months, particularly June and July, have the highest average bookings for both hotel types. Conversely, the early-year months, including January through March, see relatively lower average bookings.

**2. Eid al-Fitr Impact:**

It is essential to consider that Eid al-Fitr, a significant religious holiday in Indonesia, fell in June in the years 2017-2019. The surge in June-July bookings for both hotel types could be attributed to travelers returning to their hometowns to celebrate Eid al-Fitr with their families.

 **3. Year-End Peak:**

There is a noticeable surge in average bookings for both City and Resort Hotels in November and December. This surge suggests increased demand during the holiday season, including Christmas and New Year's, as travelers seek accommodations for festive celebrations and vacations.

 **4. Academic Year:**

Students in Indonesia usually commence their academic year in August or September. The decline in bookings observed in August and September for both hotel types may be associated with students and their families returning to school or work.

**5. City Hotels vs. Resort Hotels:**

Comparing the two types of hotels, City Hotels generally maintain higher average bookings year-round when compared to Resort Hotels. This could be attributed to the urban location and the lower rates offered by City Hotels, making them more accessible and affordable to both business and leisure travelers.

As stated in the above, more travelers book City Hotels in general. This could be the reason as to why the decline in Resort Hotels’ bookings was not as sharp as it was with City Hotels. Since Resort Hotels didn’t attract as many travelers, it didn’t peak as high, thus making the decline in bookings less sharp.

**Overall Insights:**

Overall, the analysis of monthly booking patterns in both City and Resort Hotels in Indonesia reveals several key insights. Seasonal fluctuations are a common occurrence, with the mid-year months, especially June and July, experiencing the highest average bookings, possibly due to Eid al-Fitr celebrations during these months. Notably, November and December see a surge in bookings, indicating heightened demand during the year-end holiday season. The decline in bookings observed in August and September aligns with the commencement of the academic year, impacting both hotel types. City Hotels consistently maintain higher year-round bookings than Resort Hotels, likely due to their urban locations and affordability. This discrepancy in booking levels explains the less pronounced decline in Resort Hotels, as their lower overall bookings result in a milder impact during periods of reduced demand.
****
### Stay Duration Effect on Cancellation Rates
****
<img src="https://github.com/farrellwahyudi/Investigate-Hotel-Business-using-Data-Visualization/blob/main/Images/impact_analysis_of_stay_duration_on%20hotel_bookings_cancellation_rates.png" alt="stay duration effect on cancellation rates visualization" style="width:900px;height:500px;">

**1. General Trends:**

There is a consistent trend across both hotel types (City Hotel and Resort Hotel) where cancellation rates tend to increase as the duration of stay becomes longer. Shorter stays generally had lower cancellation rates, while longer stays had higher cancellation rates.

**2. Short Stay Durations (0 to 5 nights):**

- City Hotel: Cancellation rates increase from 4.94% to 35.54% as stay duration increases from 0 to 5 nights.
- Resort Hotel: Cancellation rates increase from 2.65% to 31.76% as stay duration increases from 0 to 5 nights.
- Short stays have relatively low cancellation rates for both hotel types, but Resort Hotels performs slightly better.

**3. Medium Stay Durations (6 to 10 nights):**

- City Hotel: Cancellation rates increase from 45.80% to 58.29% as stay duration increases from 6 to 10 nights.
- Resort Hotel: Cancellation rates decrease from 33.05% to 25.64% as stay duration increases from 6 to 10 nights.
- For medium-length stays, City Hotels had higher cancellation rates compared to Resort Hotels.

**4. Long Stay Durations (>10 nights):**

- City Hotel: Cancellation rates remain relatively stable and high, ranging from 46.15% to 72.67% for stay durations exceeding 10 nights.
- Resort Hotel: Cancellation rates drop significantly from 43.04% (12 nights) to 22.88% (14 nights) but increase to 45.62% for stays longer than 14 nights.
- Long stays are associated with high cancellation rates for both hotel types, with City Hotels consistently having higher rates.

**5. City Hotels vs. Resort Hotels:**

City Hotels had higher cancellation rates throughout the whole stay duration when compared to Resort Hotels. Resort Hotels’ cancellation rates also tend to be less affected by stay duration, exhibiting a shallower slope in cancellation rate increase throughout the whole stay duration.

**Overall Insights:**

- Short stays are generally associated with lower cancellation rates in both hotel types, suggesting that guests were less likely to cancel shorter bookings.
- Medium stays exhibit varying patterns, with both hotel types experiencing high and fluctuating cancellation rates.
- Long stays consistently had high cancellation rates in both hotel types, indicating a higher risk of cancellations for extended bookings.
- The trend is clear, bookings with higher stay duration carry a higher risk of cancellation.
****
### Lead Time Effect on Cancellation Rates
****
<img src="https://github.com/farrellwahyudi/Investigate-Hotel-Business-using-Data-Visualization/blob/main/Images/impact_analysis_of_lead_time_on_hotel_bookings_cancellation_rate.png" alt="lead time effect on cancellation rates visualization" style="width:800px;height:600px;">

**1. General Trend:**

The chart demonstrates a consistent trend where cancellation rates tend to increase as lead time increases, for both City Hotels and Resort Hotels. In other words, the longer the lead time before the booking, the higher the likelihood of a cancellation.

**2. City Hotels vs. Resort Hotels:**

City Hotels generally exhibit higher cancellation rates compared to Resort Hotels across all lead time categories. This suggests that the type of hotel can significantly influence cancellation behavior, with City Hotels experiencing a greater number of cancellations.

Resort Hotels cancellation rates are more stagnant at higher lead times compared to City Hotels, however Resort Hotels cancellation rates jumped by more than 3.3x between very short and short notice, from having half the rate of City Hotels to having more than 2/3. This did not continue however, as towards the higher lead times City Hotels’ cancellation rates skyrocketed leaving Resort Hotels behind.

**3. Very Short Lead Time:**

Both City Hotels and Resort Hotels experience their lowest cancellation rates in the "Very Short" lead time category. City Hotels have a cancellation rate of 12.12%, while Resort Hotels have a rate of 6.59% in this category. This implies that bookings made on very short notice are less likely to be canceled, possibly because guests have firm plans or limited flexibility.

**4. Effect of Longer Lead Times:**

As lead time increases from "Short" to "Very Long," there is a consistent upward trend in cancellation rates for both hotel types. City Hotels, in particular, show a substantial increase in cancellation rates from 30.91% at "Short" lead time to 64.03% at "Very Long" lead time, indicating that guests booking well in advance are more likely to cancel.

**Overall Insights:**

- Longer Lead Time, Higher Cancellation: Cancellation rates increase as the time between booking and the stay gets longer, applying to both City and Resort Hotels.
- City Hotels Have More Cancellations: City Hotels tend to have higher cancellation rates compared to Resort Hotels, indicating the type of hotel influences cancellation behavior.
- Unpredictable Short Notice Bookings: Both hotel types experience their lowest cancellation rates when guests book on very short notice, suggesting that these last-minute plans are less likely to change.
- Fluctuations in Short Lead Times: Resort Hotels show steadier cancellation rates at longer lead times, but they experience a substantial increase in cancellations when guests book with short notice.
- Advance Bookings and Cancellations: City Hotels' cancellation rates significantly rise for guests booking well in advance, indicating a greater likelihood of cancellations for early reservations.

## Conclusions and Recommendations

**Conclusion:**

The analysis of monthly booking patterns, stay duration effects, and lead time impacts on cancellation rates in both City and Resort Hotels provides valuable insights into the dynamics of the hospitality industry in Indonesia. Seasonal fluctuations are a common occurrence, with mid-year months, particularly June and July, experiencing peak bookings, likely driven by the Eid al-Fitr holiday celebrations. Conversely, November and December witness a surge in demand due to year-end festivities. Understanding these seasonal patterns is vital for effective resource allocation and pricing strategies. Additionally, stay duration significantly influences cancellation rates, with shorter stays generally resulting in fewer cancellations. However, longer stays pose a higher risk of cancellations, calling for tailored management and customer engagement approaches.

**Recommendations:**

- To navigate these seasonal fluctuations, hoteliers should implement dynamic pricing strategies, offering incentives to early bookers and targeted promotions during peak seasons.
- For stay duration, hotels can consider flexible booking policies and tailored packages to encourage longer stays while mitigating the risk of cancellations.
- Moreover, recognizing the type-specific cancellation trends between City and Resort Hotels, businesses can focus on customer relationship management and customer loyalty programs to reduce cancellations and maintain stable revenue streams.
- It is crucial to continuously monitor and adjust strategies based on the interplay of seasonality, stay duration, and lead time, ensuring adaptability in a competitive market.

By proactively addressing these insights, hotels can enhance their revenue management and provide a more satisfying experience to their guests, ultimately improving their competitiveness in the Indonesian hospitality sector.
