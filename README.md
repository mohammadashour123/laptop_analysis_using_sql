# laptop_analysis_using_sql

## Find the ave of each company and sort is dessending oeder 
SELECT Company , round(AVG(Price)) as average_price
from laptop_data 
GROUP by Company
ORDER BY average_price DESC;
