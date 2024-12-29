# MonthlyOvertimeSurveyFlow
This solution contains monthly overtime survey flow which sends out survey for specific month provided as input. Employees has to select dates for which they have to work overtime for a month.
## Few things to be noted:
1. MonthlyOvertimeSurveySolution_1_0_0_1.zip : This is the solution which needs to be imported to Power Automate. This contains 2 flows:
      <ul>
      <li><b>MonthlyOvertimeCalculatorFirstVersion</b> : This cloud flow is the one which we have discussed first where all dates would be available for selecting in survey form.</li>

      <li><b>MonthlyOvertimeCalculatorUpdatedVersion</b>: This is the upgraded cloud flow where we have updated survey form to exclude checking of dates which lies in weekend.</li>    
      </ul>
2. Adaptive Card Design : Under this folder, we will find two subfolders.
<ul>
<li><b>Adaptive Card Design/Version 1</b> : This folder contains the table row and adaptive card design used for MonthlyOvertimeCalculatorFirstVersion cloud flow.</li>

<li><b>Adaptive Card Design/Version 2</b>: This folder contains the table row and adaptive card design used for MonthlyOvertimeCalculatorUpdatedVersion cloud flow.</li>
</ul>
