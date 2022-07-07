# School District Analysis

## Overview of the School District Analysis

    The purpose of this analysis is correct evidence of academic dishonesty discovered by the school board. The targeted data analyzed is specifically around math and reading for all 9th graders at `Thomas High School`, as it appears those grades have been altered. The objective in the below analysis is to replace the 9th grade reading and math scores, then repeat the district analysis to show a true measure of passing grades through out the district. 

---
## Results

* **How is the district summary affected?**

    The district summary of student data was affected as one of the schools had grades altered for their ninth grade class. The data was altered in a way that skewed the overall data for all schools in the district. You will see the difference between the overall passing scores in comparison to each other is a difference of `0.316608%`

    **Replacing the 9th grade reading and math scores at Thomas High School with NaN**
    
    Before we were able to get to this difference in percentage, we had to select all reading and math scores from Thomas High School and replace those scores with `NaN` so that they would not factore into the new percentage. 

    ![nan-replacement](https://github.com/hastyjr/School_District_Analysis/blob/main/Resources/images/NaN-replacement.png)

    This is a before and after of the district summary:
    
    ![before-data-clean](https://github.com/hastyjr/School_District_Analysis/blob/main/Resources/images/pre-clean-district.png)

    ![after-data-clean](https://github.com/hastyjr/School_District_Analysis/blob/main/Resources/images/post-clean-district.png)


* **How is the school summary affected?**

* **How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?** 

    There is no doubt that the impact on overal passing percentage for Thomas High School was impacted. The difference can be seen down below in the images. After the Thomas High School's 9th grade data was complete, it proved to show a staggering difference of:
    * `26.36%` in math passing scores. 
    * `27.64%` in reading passing scores.
    * `25.87%` in overall passing scores. 

    **school summary header**
![school_summary_header](https://github.com/hastyjr/School_District_Analysis/blob/main/Resources/images/school_summary_header.png)

    **pre data clean**
![ths_pre_clean](https://github.com/hastyjr/School_District_Analysis/blob/main/Resources/images/ths_pre_clean.png)
    
    **post data clean**
![ths_post_clean](https://github.com/hastyjr/School_District_Analysis/blob/main/Resources/images/ths_post_clean.png)

* **How replacing the ninth-grade scores affect the following:**

    * **Math and reading scores by grade**
        You will see that in its finality, math and reading scores by grade didn't change for any of the other high schools in the district as their data was untouched. You will noticed that Thomas High School schools are not factored into the scoring here for either subject as their data had been retracted and replaced with `Nan` or `nan`.
        ![Math and reading scores by grade](https://github.com/hastyjr/School_District_Analysis/blob/main/Resources/images/math_reading_scores_by_grade.png)
    
    * **Scores by school spending**
        One very interesting fact revealed with the scores by school spending is that the lower the spending range per student, the higher the average, percentage passing and overall passing grades were. And on the contrary, the higher the spending range per student, the lower the scores across the board. 

        This is basically saying, that spending less on students is a true testament to having higher scores aross both math and reading. 
        ![Scores by school spending](https://github.com/hastyjr/School_District_Analysis/blob/main/Resources/images/score_by_school_spending.png)

    * **Scores by school size**
        The below table shows that the soft spot for best grades across the board are medium schools sizes from 1000-1999. While small schools als have high scores, in this case it was off by 1% in comparison. Large schools on the other hand suffered in terms of passing scores. 

        ![Scores by school size](https://github.com/hastyjr/School_District_Analysis/blob/main/Resources/images/scores_by_school_size.png)

    * **Scores by school type**
        The schools were also measured by school type, where there were two types of either `Charter` or `District`. The table below shows a clear differentiation of the two. Charter schools had an impressing overall passing percentage in comparison to the District school by `37%`!
        ![Scores by school type](https://github.com/hastyjr/School_District_Analysis/blob/main/Resources/images/scores_by_school_type.png)

---
## Summary

In Summary the data I started with and the data I ended with were a clear differntiation between how the district could have been impacted if they would not have addressed the altered data for Thomas High School 9th graders. 
    
While the post-cleaning of data analysis didn't make much of an overall dent in the district summary data, there was a clear difference when comparing Thomas High School's performance around passing scores. A 25.87% difference at that. 

The rest of the data also provided general insights around the rest of the schools in terms of spending, school type and school size. Extracting this information will be a great way for the board to forward plan and look at how they can optimize their strategic plans to get larger schools better scores and look at possibly cost cutting in schools that high spending averages per student but low passing scores. The data proves that it does not take a lot of money per student for them to be successful.
