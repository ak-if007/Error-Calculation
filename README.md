# Error-Calculation
RMSE Error Estimation for Memristive Devices

![RMSE Error](assets/error.png)

## To estimate error we presume that the experimental data is collected from a paper and then the data points are extracted using a WebPlotDigitizer. Two main issues arise when trying to compare simulated and experimental data in such fashion which are:
* WebPlotDigitizer inherently sorts the x-axis points for which the positive and negative sweep are indistinguishable.
* Data points present in experimental and simulated results are not the same

Such discrepencies are dealt with in this script. To tackle the first problem while extracting points from WebPlotDigitizer the points are to be extracted in four chunks instead extracting all at once.


<p align="center">
  <img src="assets/Segment1.jpg" width="300" style="margin-right: 10px;" />
  <img src="assets/Segment2.jpg" width="300" />
</p>
<p align="center">
  <img src="assets/Segment3.jpg" width="300" style="margin-right: 10px;" />
  <img src="assets/Segment4.jpg" width="300" />
</p>
