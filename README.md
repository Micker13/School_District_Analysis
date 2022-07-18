# School_District_Analysis
Analysis of school grading for module 4

##Overview of the Work

Our team has been requested to perform an evaluation of an area's reading and math grades across various schools to assess for possible academic integrity issues.  It is suspected that the ninth grade grades for Thomas High School have been altered.  Our analysis will compare with and without this data set to understand if this has impacted overall standing and report back to our employer.

After initial data replacement, a reevaluation will be done of all relevant metrics (district, school type, and school size) to evaluate potential impacts.  

## Initial Findings / Analysis

The first step was to remove all of the ninth grade data from the data set and compare before and after data summaries for just Thomas High School.  It was noted that even with the 9th graders data being completely removed, there was little to no impact on the average scores.  However, there was a large change in overall percent passing.  

###For Thomas High School:
Average math went from 83.41 to 83.35
Average reading went from 83.84 to 83.89
Percent passing math went from 93.3 to 66.9
Percent passing reading went from 97.3 to 65.1

#### Before

![image](https://user-images.githubusercontent.com/107594247/179436141-e9e6c46c-b9c1-4516-8e44-96bee11d0a61.png)

#### After

![image](https://user-images.githubusercontent.com/107594247/179436096-a4c8fd95-56da-4acf-8ced-4868cd6306ff.png)


The large change implies there is likely some incorrect data within the 9th grader information.  The lack of change in the average can be explained as incorrect grades can still be made to average to the same value with little impact.

##For the District

For the district the change is less severe due to the volume of other students and schools to dilute the impact.  

Before
![image](https://user-images.githubusercontent.com/107594247/179436351-b639bebf-f6fa-4911-98bc-20f1f336d1e0.png)

After

![image](https://user-images.githubusercontent.com/107594247/179436379-3822b60b-5bf0-411c-9e7e-21ee479cccdc.png)

Average math decreased from 79.0 to 78.9
Average reading had no impact
Percent passing math decreased by .2% from 75 to 74.8%
Percent passing reading decreased by .3% from 86 to 85.7%


##Summary

Overall, while the impact to the district is very minor, the large impact to the passing percent at Thomas High School warrants a further investigation.  It is highly likely due to the outlier data that some form of academic dishonesty is happening.  This change dropped Thomas out of the top 5 schools by a significant margin.  Further investigation is warranted with school officials.  
