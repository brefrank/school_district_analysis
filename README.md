# School District Analysi

## Overview

The schoolboard has requested a new district analysis, without the data from Thomas High School's 9th graders, due to suspition of academic dishonesty. To complete the analysis as requested, we have replaced the THS 9th grade data with NaN's. With this data removed, the board can be sure that their state-testing stadards hav been upheld.

## Results

Below you will see an explanation of the new results. Each photo referenced will contain data from the updated district summary numbers.

 - How is the district summary affected?
Luckily, the suspected academic dishonesty by the THS students did not make large difference in our results. In comparison to the previous file, both percentages for passing math and reading went down about 0.1-0.2%, rsultinig in an overall passing percentage drop of about 0.3%.

 ![image](https://user-images.githubusercontent.com/90646961/137647899-92926a55-6dec-4b57-bb28-5b77c9cdd350.png)

 - How is the school summary affected?
Because the only data removed belonged to Thmas High Schol, they were the only ones affected in our new anaysis. As you can see below, their overall passing percentage dropped from about 91% to 65%.

![image](https://user-images.githubusercontent.com/90646961/137648568-9b489439-0a53-4c82-92d2-832fe8e837ca.png)

 - How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Since the THS 9th grade math and reading scores were replaced with NaN rather than removing the students entirely, we now have an inaccurate comparison of THS to the rest of the schools. If we would have removed the 9th graders from the dataset entirely, our ratios of passing to total students would have been higher, and therefore more similar to the percentages from the rest of the district.

 - How does replacing the ninth-grade scores affect the following:
 
    - Math and reading scores by grade
    By replacing 9th graded scores with NaN, our results for math and rading scores by grade do not have a number from THS 9th graders. This does not have an affect on the rest     of the data.
    
    - Scores by school spending
    Despite THS being in the $630-644 spending range, our results here were unchanged. We can conclude from this data the the higher the spending range is forn students, the         lower their average scores wil be.
    
    ![image](https://user-images.githubusercontent.com/90646961/137648917-f3de042c-f151-48c0-a915-cf15ac114d4d.png)

    - Scores by school size and type
    As you can see below, scores by school size and type were also not affected. We can come to the same conclusion as we did above.
    
    ![image](https://user-images.githubusercontent.com/90646961/137648958-a6df2cf8-242e-4528-ade2-b0ed6cf68837.png)
    
    ![image](https://user-images.githubusercontent.com/90646961/137648974-6711d8b3-fe37-4e1d-87a1-d9d4951fe7dd.png)


## Summary

Taking all of the new results into consideration, we are able to conclude that our district summary, scores by school spending, school size, and school type calculations will be accurate, despite the mishap with THS 9th graded data. We will, however, need to re-analize our school summary and results by grade when accurate testing scores are obtained. Fortunately, we can use our original analysis file attached to do so, as long as we change the data file. 
