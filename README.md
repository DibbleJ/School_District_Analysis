# Python School District Analysis

## Overview
Overview of the school district analysis: 
- The Original anaylsis was made to help the school board identify performance trends and patterns in standardized math and reading scores. By aggregating the data, school performance and trends will be analyzed to assist the school board and superintendants with budget prioritization.
- After the original analysis was performed, suspicions of academic dishonesty regarding the results of Thomas High School 9th Graders resulted in replacing the THS 9th graders math and reading scores with NaNs. Once this was performed, the initial analysis was reperformed to compare results. 
## Results

Results: 
- How is the district summary affected?
  - There is little impact to the district summary. The total number of students decreased by 461, the number of THS 9th graders. There is also a 0.1% reduction in the Average Math Score. This is likely due to the fact that the THS 9th grade class accounts for just over 1% of the total student population, so removal of those grades has little affect.

Before:![District Summary Before](https://user-images.githubusercontent.com/40553064/119241438-ef67cb00-bb1b-11eb-8081-5c343f380b8e.PNG)
After:![District Summary After](https://user-images.githubusercontent.com/40553064/119241467-24741d80-bb1c-11eb-8e0a-3191edefb1f3.PNG)

- How is the school summary affected?
  - As expected the only changes to the school summary is the THS Row. The average math scores were slightly increased and the average reading scores were slightly decreased as a result of dropping the 9th grade class.

Before:![School Summary Before](https://user-images.githubusercontent.com/40553064/119241777-977e9380-bb1e-11eb-914e-f17a52222a71.PNG)
After:![School Summary After](https://user-images.githubusercontent.com/40553064/119241774-95b4d000-bb1e-11eb-85d0-ddd966b8f385.PNG)


- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  - THS stays 2nd overall; THS drop 0.31% Overall Passing, which is not enough to be overtaken by Griffin High School

Before: ![Best-Before](https://user-images.githubusercontent.com/40553064/119244072-509a9900-bb32-11eb-93ed-d908b4366857.PNG)
After: ![Best-After](https://user-images.githubusercontent.com/40553064/119244075-542e2000-bb32-11eb-94d8-169f7b5c7b6d.PNG)

- How does replacing the ninth-grade scores affect the following:
  - Math and reading scores by grade
    - There is no change to any outcomes to any of the other grades or schools. This is expected as only the THS 9th graders scores were replaced with NaN. 
    
  Before: Math: ![Average-math-before](https://user-images.githubusercontent.com/40553064/119244133-fe0dac80-bb32-11eb-8d40-7ae8bb070fba.PNG) 
  Reading:![Average-reading-before](https://user-images.githubusercontent.com/40553064/119244134-00700680-bb33-11eb-855c-2c11ea7d4a45.PNG)

  After: Math: ![Average-math-after](https://user-images.githubusercontent.com/40553064/119244156-301f0e80-bb33-11eb-8fa3-b47dc5c265a8.PNG)
  Reading: ![Average-reading-after](https://user-images.githubusercontent.com/40553064/119244159-34e3c280-bb33-11eb-8e94-3b620bd4bc21.PNG)
  
  - Scores by school spending
   
  Before: ![Performance-Spending-Before](https://user-images.githubusercontent.com/40553064/119244181-85f3b680-bb33-11eb-995b-84524394b97f.PNG)

  After: ![Performance-Spending-After](https://user-images.githubusercontent.com/40553064/119244183-88561080-bb33-11eb-9b4c-e8b135531b3c.PNG)
  
  - Scores by school size
  
  Before: ![Performance-Size-Before](https://user-images.githubusercontent.com/40553064/119244192-9ad04a00-bb33-11eb-8e6b-6fd544097a66.PNG)

  After: ![Performance-Size-After](https://user-images.githubusercontent.com/40553064/119244215-d66b1400-bb33-11eb-9647-493d59e22347.PNG)
  
  - Scores by school type
  
  Before:![Performance-Type-Before](https://user-images.githubusercontent.com/40553064/119244189-9146e200-bb33-11eb-80f0-68f371bed5b5.PNG)

  After: ![Performance-Type-After](https://user-images.githubusercontent.com/40553064/119244219-dcf98b80-bb33-11eb-8b05-7da2d0785621.PNG)
  
## Summary
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
