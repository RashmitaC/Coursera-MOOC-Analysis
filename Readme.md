# Coursera MOOC Data Analysis

## Objective

Coursera has been an integral part of my academic life as being in an engineering college, it is all about the fear-of-mising-out enough skill development. Coursera proved to be a go-to as it has a plethora of different courses from so many different fields and backgrounds. In April 2020, Coursera collaborated with the Entrepreneurship Cell of NIT Agartala to provide access to 4000+ different free courses with certificates for 6 months, making it such a crazy opportunity to grab as much skills and knowledge as possible. Since then, I have grown even more fascinated and attached to this platform, having completed over 35 courses in different areas of interest. Hereby, I decided to make an analysis of this platform regarding the courses, certifications, universities, etc. it has to provide.
Check out the project [here]. (https://github.com/RashmitaC/Coursera-MOOC-Data-Analysis/blob/main/Coursera-MOOC-Data-Analysis.ipynb)


## About the dataset

Coursera is the largest massive open online course (MOOC) provider in the world and hosts many courses from top universities in different subjects. The data has been collected from Kaggle which has been taken from 1.45 million course reviews posted by students and participants on the platform. 
Link to dataset: [Here] (https://github.com/RashmitaC/Coursera-MOOC-Data-Analysis/blob/main/Data/Coursera_MOOC-Dataset.csv)

Course dataset scrapped from Coursera website. This dataset contains mainly 6 columns and 890 course data. The detailed description:

* course_title : Contains the course title.
* course_organization : It tells which organization is conducting the courses.
* courseCertificatetype : It has details about what are the different certifications available in courses.
* course_rating : It has the ratings associated with each course.
* course_difficulty : It tells about how difficult or what is the level of the course.
* coursestudentsenrolled : It has the number of students that are enrolled in the course.


## Conclusion

1. Average course rating is quite higher, compared to lowest and maximum value. So, the cours quality is being maintained.
2. Advanced courses' rating has some ups-and downs; maybe due to low frequency.
3. Beginner course has distribution quite similiar to total rating chart, as big portion of the data is from them, and he number of beginner level courses are high.
4. Intermidiate course's rating top is not as sharp of others, that may say - as the participants has some knowledge on the topic, they can judge better and being critical.
5. Specializations has lower mean value than courses, but the distribution is interesting. specialization has good distribution values on right, but normal courses are on left.
6. No effective coorelation between course_difficulty,course_students_enrolled, course rating.
7. No effective coorelation between course_students_enrolled, course rating per university.
8. Mean number of students enrolled per university has some positive corelation to number of courses offered by the university. The more courses are offered, the more students are enroled in average.