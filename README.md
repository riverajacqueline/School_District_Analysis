# School District Analysis

## Overview of the school district analysis

The purpose of this school district analysis is to analyze the data on student funding and student standardized test scores. There are various pieces of data that will be analyzed such as math and reading scores across grade levels, school budget, school size, and school type. This analysis will showcase the trends in school performance.

After going over the data given, it has been brought up that there shows evidence of academic dishonesty with the reading and math grades for Thomas High School ninth graders. Given this information, the school district analysis had to be repeated while also replacing the Thomas High School ninth grade reading and math scores. This report will describe how these changes affected the overall analysis.

## Results

By refactoring the code of the orginal analysis, the math and reading scores of ninth graders at Thomas High School have been removed and replaced with NaN.

![image](https://user-images.githubusercontent.com/103764279/169098658-aeae514a-7244-47b7-88b2-de33048e825f.png)

- **How is the district summary affected?**

In the district summary that was previously analyzed with the Thomas High School ninth graders, the average math score was 79.0 with a passing percentage of 75% and the reading score was 81.9 with a passing percentage of 86%. The overall passing percentage for both math and reading was 65%. In the new report, the average math score was 78.9 with a passing percentage of 74.8% and the average reading score was 81.9 with a passing percentage of 85.7%. The new overall passing pecentage was 64.9%. The data showed that by removing the 461 Thomas High School ninth graders, the math and reading averages, percentage passing math and reading, and the overall passing percantage has decreased, but not by a significant amount.

- **How is the school summary affected?**

In the school summary, the average math score and average reading score do not show a significant change. However after removing the Thomas High School ninth graders, the percentage passing math dropped from 93.2% to 66.9% and the percentage passing reading dropped from 97.3% to 69.6%.

- **How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**

In the school summary based on overall passing percentage that included the Thomas High School ninth graders, Thomas High School is second with an overall passing percentage of 90.0%.

In the school summary based on overall passing percentage that removed that Thomas High School ninth graders, Thomas High School dropped to eighth with an overall passing percentage of 65.0%.

****Figure 1: Shows the image of the analysis that included all students.****
![image](https://user-images.githubusercontent.com/103764279/168496430-5746ef22-7b92-4d22-81b1-eacc4029af8b.png)

****Figure 2: Shows the image of the analysis of that removed all Thomas High School ninth graders.****

![image](https://user-images.githubusercontent.com/103764279/168496396-c5711368-dd92-41d0-82ba-71e9a8717307.png)

- **How does replacing the ninth-grade scores affect the following:**
   - ****Math and reading scores by grade****
     -- Replacing the ninth grade math and reading scores only affected the ninth             graders at Thomas High School. The math and reading scored that were                 previously there were replaced with NaN. All other grades were unaffected by         the changes.

****Figure 3: The before and after of replacing the ninth grade math scores.****
![image](https://user-images.githubusercontent.com/103764279/169150227-ff82cb04-e5de-4229-ac4a-f93d14e1bb6c.png)
![image](https://user-images.githubusercontent.com/103764279/169150314-d42ef41f-b75e-43f4-8373-271b7abbae16.png)

****Figure 4: The before and after of replacing the ninth grade reading scores.****
![image](https://user-images.githubusercontent.com/103764279/169150678-966e514c-831f-4604-9e45-e0f521390d1d.png)
![image](https://user-images.githubusercontent.com/103764279/169150736-fba194a2-21f4-4837-b1d4-b8eb01c2dbab.png)
          
   - ****Scores by school spending****
     -- Replacing the ninth grade scores has no affect on school spending.
     
   - ****Scores by school size****
     -- Replacing the math and reading scores didn't have any affect on school size           except for Thomas High School. When caluculating the overall passing                 percentage for reading and math, the percentage dropped when ninth graders           were replaced.
     
   - ****Scores by school type****
     -- Replacing the ninth grade math and reading scores has no affect on school             type, whether being a charter or district school.

## Summary

- The overall passing percentage for Thomas High School drastically dropped when the ninth graders were removed.
- The average math and reading scores did not see much of a change across the district when the ninth graders were removed. 
- When analyzing the data comparing spending per student to the overall passing percentage, the data shows that schools that are spending less than $586 per student have a higher overall passing percentage than schools who are spending the most in the spending range of $646-$675 per student.
- When analyzing the data comparing school size and overall passing percentage, the data shows that small and medium sized schools have a higher overall passing percentage compaared to the large schools. This could be due to factors such as small and medium sized schools having smaller class sizes and being able to give more individualized attention to students.
