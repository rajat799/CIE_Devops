Git commads lab 2

<!-- fjggslkgjkfld -->

cd Desktop
mkdir student-management-system
cd student-management-system
git init

notepad Student.java

git add .
git commit -m "Added Student class"

git branch -M main
git remote add origin https://github.com/yourusername/student-management-system.git
git push -u origin main

git checkout -b student_course_information

notepad StudentCourses.java

git add .
git commit -m "Added StudentCourses class"
git push -u origin student_course_information

git checkout main

git merge student_course_information

git push origin main
