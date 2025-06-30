WHAT DOES IT MEAN: 1-IN-200 or 1-IN-1000 EVENT?


Dotcom, GFC, COVID — all within 25 years, and all worse than the 99.9% VaR.

![image](https://github.com/user-attachments/assets/36edd51f-2c81-42d9-bfe5-12354a56d8dc)

 
The month-end liquidity reports I worked on recently were generated based on Historical VaR, using a group portfolio with a default confidence level setting of 99.5%. As part of stress testing exercises, I was asked to derive an implementation based on a 99% confidence level as an alternative metric.
Given the number of month-end reports for business units and the number of scenarios underpinning these results, it can often be overwhelming to interpret the key aggregated nominal VaR results, MTM values, and stressed results. The default and reported VaR was adopted to be Historical VaR because of calibration possibilities to actual market stresses since the 2007/2008 financial crisis—although MC VaR was available only as a benchmark, it also lacked up-to-date calibration of VaR-coverage data.
The Group owned a licence of SS&C Algorithmics Workspace Analyzer (known as AWA) for all risk aggregations — a powerhouse tool for risk aggregation and reporting, which was flexible and allowed our team to enhance it for internal use. Basically, we wrote our own code and deployed it to improve its capabilities. For example, its interface had a risk parameter setting that allows users to view the default VaR confidence level setting. Furthermore, depending on the business unit’s request, we implemented several enhancements to this reporting tool. However, as users interact with SS&C’s AWA reporting tool, it’s easy to spot various features in the settings, such as the scenarios, VaR confidence level, horizon, etc. In my experience, most often users tried to experiment with the confidence level setting. 
Despite the complexity in the underlying models and the process for scenario generation, I would sometimes hear simple questions such as: What is a 1-in-200 event anyway? And what does this mean to the business unit’s month-end VaR?

see attached PDF to continue reading..
