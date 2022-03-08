# Module 4 | Assignment - PyCitySchools

Use Python and the Pandas library to analyze school district data and showcase trends in school performance.

## Overview of the School District Analysis
### **Purpose**
<br> In this project, we are aiming to remove Thomas High School 9th graders' scores from the entire dataset, and process the analysis with the rest of the data regarding the academic performance from different schools, in order to maintain the honesty and accuracy of the academic performance.

## Results: 
### **How is the district summary affected?**
<br>After removing the Thomas High School - 9th graders' scores, we can see all the average math/reading scores are lower than before. The math/reading and overall passing rates are also lower than before.

### **How is the school summary affected?**
<br>After removing the Thomas High School -9th graders' scores, and calculate the new average math/reading scores, as well as the passing rates correctly, all the results are slightly lowered than before.

### **How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**
<br>By comparing before/after of Thomas High School Summary, with before/after of entire school district summary, we can see the removal of Thomas High School - 9th graders' scores have more impact on the Thomas High School Summary's average math/reading score, than that to the entire school district summary. 

### **How does replacing the ninth-grade scores affect the following:**
  - **Math and reading scores by grade**
    <br>As it's only 1 grade in 1 school, it won't affect the math/reading scores in 10th-12th grade in Thomas High School; Nor does it affect the other schools' math/reading scores by grade.

  - **Scores by school spending**
    <br> Please refer to the ![Spending_range_by_school](Spending_range_by_school.png) for the result.
    <br> For those schools which are not competitive on math/reading scores, tend to spend more money per student.

  - **Scores by school size**
    <br> Please refer to the ![size_range_by_school](size_range_by_school.png) for the result.
    <br> The more students the schools have, the less competitive the students tend to be in the math/reading subjects, the passing rate is lower;

  - **Scores by school type**
    <br> Please refer to the ![school_type](school_type.png) for the result.
    <br> Students in Charter schools tend to have better performance than those in District Schools.

## Summary: 
<br> After removing the Thomas High School - 9th graders' scores, we can see following changes to the school district analysis:
     <br> - Overall school district - average math/reading scores become lower than before, which means the dishonesty of the data from Thomas High School - 9th graders' score did damage the data integrity;
     <br> - We can also see the average math/reading scores of the Charter school become lower;
     <br> - The average math/reading scores in the medium size (1000 to 2000 students) schools get lower;
     <br> - The average math/reading scores in the "$630 - $644" spending group schools are also getting lower.
