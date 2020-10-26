# School_District_Analysis
## Overview
-In this challenge we are to replicate the steps of data cleaning, analysis, and visualization went over during the model with a slightly updated data set and very similar methodology refactored a bit for efficiency.
### Purpose
-The purpose of this challenge is to re-evaluate the statistics put forth because the Freshman student grades at one of the high schools reflected academic dishonesty, so those scores are now considered null and void.

## Results
-The results here are measured not just on their own value, but also in comparison to how the academically dishonest results affected the whole.
### Metrics Affected
1. The district summary was largely unaffected by the small relative portion of data pulled from the set. The percentages of students who passed both math and reading (and thus overall) was reduced. However, none of these metrics was affected by even .30%.
2. The school summary or 'per school summary' was only slightly affected. The data subset removed was entirely from Thomas High School, and it very minimally diminished the passing percentages for both math and reading (and thus also the overall percentage by a slightly wider margin).
3. Thomas High School's relative performance also didn't see much negative effect. They remained one of the top 5 highest performing schools despite the removal of this data.
4. The math and reading scores by grade were affected more greatly, losing one of the top performers amidst the schools analyzed in this dataset. The 461 9th grade students were among some of the better performing in both math and reading, where now the other schools--many of whom had worse-performing students--carried a significantly heavier weight for that arm of statistics.
5. The average scores based on school spending remain mostly unchanged.
6. The average scores based on school size remain mostly  unchanged.
7. The average scores based on school type also remain mostly unchanged.

## Summary
-The 461 9th grade students' records that were removed from the sample constituted approximately 1.177% of the overall number of students whose grades are tallied here, and they weren't a particularly anonymous set of students in regard to the larger trend. Thus, their impact was not very large on the overarching lessons and patterns observed.
### Changes to the Analysis
1. The average scores based on school spending, size, and type seem largely unchanged in terms of performance by the removal of the suspect data.
2. The relative performance of Thomas High School as compared to other schools here remains largely unchanged, if slightly lower. They are still one of the top 5 highest performing in the set.
3. The average scores based on grade level was the most highly affected view of the data, given that a disproportioante impact was felt by a slice of this view--being that all the data removed was from 9th graders at a high-performing school, thus affecting the average performance of 9th graders across the sample.
4. The little-to-no change observed after the removal of the suspect data seems to suggest that there either was no reason to remove it for suspicion in the first place, or that the academic dishoneesty might pertain to a larger portion of the dataset submitte--i.e. all of Thomas High School's student entries.