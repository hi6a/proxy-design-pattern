# proxy-design-pattern
# CourseHive: Data Structures project using the proxy design pattern.

## A fully functioning, dynamic course administration website for courses given at LAU

This project will aid instructors in organizing and managing their course material more efficiently. Courses, instructors, sections, lectures can be added. Additionally, there is a "Join" section included on the website where students can join a WhatsApp group with their instructor. After entering their information on the website, the instructor has to approve before an automatic email containing the WhatsApp link will be sent. More specifically, each course will have its own webpage including all the mentioned features.

## How to run the web application

To run our web application download the file of the project and make sure to follow these steps:
1. The virtual environment must be downloaded within the packages 
2. Activate the virtual environment through this command: source dsenv/bin/activate
3. Go to dsweb folder: cd dsweb
4. Run the following command to create a super user so you can test our backend application: python3 manage.py createsuperuser
5. Run the following command to run the server: python3 manage.py run server
6. Go to http://127.0.0.1:8000/admin enter the username and password you have set for your superuser
7. After creating a course and a section you can check your section’s page on  http://127.0.0.1:8000/coursecode/sectioncrn (course code is the code you have filled in code field of the course class, section crn is the CRN you have filled for your course section’s in the CRN field of your section class)
