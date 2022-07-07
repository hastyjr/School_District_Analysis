# School District Analysis

## Overview of the School District Analysis

The purpose of this analysis is correct evidence of academic dishonesty discovered by the school board. The targeted data analyzed is specifically around math and reading for all 9th graders at `Thomas High School`, as it appears those grades have been altered. The objective in the below analysis is to replace the 9th grade reading and math scores, then repeat the district analysis to show a true measure of passing grades through out the district. 

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
        ![Math and reading scores by grade](https://github.com/hastyjr/School_District_Analysis/blob/main/Resources/images/math_reading_scores_by_grade.png)
    * **Scores by school spending**
        ![Scores by school spending](https://github.com/hastyjr/School_District_Analysis/blob/main/Resources/images/score_by_school_spending.png)
    * **Scores by school size**
        ![Scores by school size](https://github.com/hastyjr/School_District_Analysis/blob/main/Resources/images/scores_by_school_size.png)
    * **Scores by school type**
        ![Scores by school type](https://github.com/hastyjr/School_District_Analysis/blob/main/Resources/images/scores_by_school_type.png)

fsdfsd
## Summary
Write a statement statement summarizing four changes to the school district analysis after reading and math scores have been replaced (5 pt).

