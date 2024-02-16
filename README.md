# Log-returns-analysis-volume-bars
Resampling over volume bars gives better statistical properties then regular time bars.


![price](https://raw.githubusercontent.com/alexlukekoval/Log-returns-analysis-volume-bars/main/volume_price.png)

![dist](https://raw.githubusercontent.com/alexlukekoval/Log-returns-analysis-volume-bars/main/resampled.png)



Both the time-based and volume-based resampling methods of financial data exhibit high kurtosis values, indicating distributions with heavy tails and a higher likelihood of extreme price movements. Both methods are far from the normal distribution's kurtosis of 3. This tail-heaviness underscores a significant tail risk in the data.  
  
The volume-based resampling shows a lower kurtosis compared to the time-based method, suggesting it is the better option for analysis seeking to minimize the impact of extreme outliers. 
