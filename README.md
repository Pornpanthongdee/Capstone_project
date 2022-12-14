# Project Nurse Salary Prediction in San Francisco

Welcome to the nursing industry!


### [Presentation Deck](https://docs.google.com/presentation/d/1Bx1pUgvK1AhBNoxpyS6QjJyM7I4gajOwSlwokChLMks/edit#slide=id.g19f66822c77_0_57)

### Dataset and Competition
[Employee-Compensation in SF](https://data.sfgov.org/City-Management-and-Ethics/Employee-Compensation/88g8-5mnd/data)

### Problem Statement

1. A new hospital wanting to hire nurses wishes to know the industry standard for salaries.
2. HR wants to know how much they should offer candidates.
 
### EDA
1. Filter only target nurses
2. Check duplicated employee name
3. Filter only those who have 2019 salary
4. Filter only those who have same job title
5. Create feature columns such as Total year, Job Title, Start salary, 2018 salary,Increase Rate : (2018-start)/start,2019 salary

### Final Model
1. Top 2 features ['Start Salary', 'Job Title']
2. dummy_jobtitle = ['REGISTERED NURSE', 'LICENSED VOCATIONAL NURSE', 'NURSING ASSISTANT', 'NURSE MANAGER', 'PUBLIC HEALTH NURSE']
3. Y (Salary 2019)

### Business Recommendation
If you are considering hiring nurses in San Francisco, you can use this model to efficiently predict salaries
You can target salaries in ranges given a few parameters to ensure your offers are competitive

### Contributors:
This model can be extended to other markets and employment categories.
Additional degrees could be added as well, such as degrees, skills and industry experience.


And a special thanks to *James Larkin*, *Yamada Nozomi*, and *Apiwat Jaroonpol* for their support.
