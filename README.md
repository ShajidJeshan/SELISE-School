# SELISE-School
Imagine your school name is SELISE School. Under this school/organization there are some students and teachers who you are associated with. In your school few of the admin personnel maintain all administrative tasks. Here we have 3 kinds of users (Admin, Teacher, Student); 

1. You have to make an authentication and authorization api endpoint that will be responsible for login to access some private api(2 and 3). (Built login registration that support 3 level role) 

2. Build 2-3 api that is accessible from the public users, who may or may not be part of this organization. 

3. Try to build one api that will be accessible for only the admin that will store personal details about the teachers and the details editable by the admin only visible by the teacher. Your model_name, serializer, viewset_name whatever you want(should be followed pep8/9). Personal details should be foreign key of your user models could be stored(NID, maritul_status, date of birth, joining_date, so on)

4. There will be an api for declaring teachers class schedule which will be edited, updated and deletable by the teacher but only visible by students.
