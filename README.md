# School District Analysis

## Overview of School District Anaysis

Due to evidence of academic dishonesty, an alternative analysis of the school district data has been requested to demonstrate the impact of excuding the ninth grade reading and match scores at Thomas High School.<br>

For this analysis, Thomas High School math and reading scores have been dropped from the summary totals, and variance from the base data will be presented to quantify the impact of the integrity issues.<br>

Using the previous data as base case, analysis demonstrating impacts will be presented on district and school level metrics in attempt to maintain the state-testing standards.<br>

## Results
  ### How the district summary affected:
  Base Case:<br>
  ![image](https://user-images.githubusercontent.com/100323377/161386949-55e98f22-fc53-4f08-9eb1-77021a5203f6.png)
  
  Revised Data:<br>
  ![image](https://user-images.githubusercontent.com/100323377/161386979-c9da354f-bc2e-46c8-ab77-a7b4e9d96fb9.png)<br>
  
  ### How the school summary is affected:
  Base Case:<br>
  ![image](https://user-images.githubusercontent.com/100323377/161387065-b0a84678-93ec-4798-9cdf-e84c7ec1902e.png)

  Revised Data:<br>
  ![image](https://user-images.githubusercontent.com/100323377/161387072-b1390f31-97ad-4fe5-9af1-b8edd75709bc.png)
  
  ### Replacement of Thomas High's scores impact on relative performance:
  Base Case:<br>
  ![image](https://user-images.githubusercontent.com/100323377/161388446-30e67721-9d9a-4a19-b0d9-6a46fe11ccae.png)

  Revised Data:<br>
  ![image](https://user-images.githubusercontent.com/100323377/161388435-d4c794c1-5bce-450e-b894-7ab633df1781.png)

 ### Impact of replacing ninth grade scores:
 -Math and Reading scores by grade<br>
  Base Case (Math):<br>
  ![image](https://user-images.githubusercontent.com/100323377/161387395-581ba209-dda8-4e12-82c7-b3af04745bdb.png)

  Revised Data (Math):<br>
  ![image](https://user-images.githubusercontent.com/100323377/161387332-c190b66c-4579-46a6-9b77-361bfbd4ca26.png)
    
  Base Case (Reading):<br>
  ![image](https://user-images.githubusercontent.com/100323377/161387462-aa3a0574-19e8-47e5-929e-5012c41f5e6f.png)

  Revised Data (Reading):<br>
  ![image](https://user-images.githubusercontent.com/100323377/161387478-ded12163-526b-4066-a6c2-bae680e5ec0c.png)

  -Scores by school spending size<br>
  Base Case:<br>
  ![image](https://user-images.githubusercontent.com/100323377/161388050-6c7639bd-d5b6-4156-be40-6223e2ab4089.png)

  Revised Data:<br>
  ![image](https://user-images.githubusercontent.com/100323377/161388057-4e1f4eb9-859d-4ebf-8cbf-a24742cfed41.png)

  -Scores by school size<br>
  Base Case:<br>
  ![image](https://user-images.githubusercontent.com/100323377/161388114-cfdc1903-ce21-4023-a9d6-c99af71fe282.png)

  Revised Data:<br>
  ![image](https://user-images.githubusercontent.com/100323377/161388106-147c491a-bd68-46c8-9202-13c5f793a959.png)

  -Scores by school type<br>
  Base Case:<br>
  ![image](https://user-images.githubusercontent.com/100323377/161388151-d62b355e-608a-4112-87e1-1cfbfb3728d2.png)

  Revised Data:<br>
  ![image](https://user-images.githubusercontent.com/100323377/161388164-f91ce4c0-5fbf-4684-9d03-b40deb393639.png)

## Summary
Based on dropping the Thomas High School 9th grade scores, four notable impacts occur:<br>
1. Average Math score drops from 79.0 to 78.9
2. Percent of students passing math drops from 75.9% to 74.8%
3. Percent of students passing reading drops from 86.8% to 85.7%
4. Percent of students passing both reading and math drops from 65.9% to 64.9%

Since this alteration is ony 461 records of 39,170 total students, the impacted records have a significant impact given their proportion of the total scores.  Further, we are still using the total student count as the denominator in the provided code, subtracting the NaN record counts would provide even more impact, and better reflect the integrity issue being studied here.
