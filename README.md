## DjangoCRM
This CRM I have build to practice my Django skills.
I have performed CRUD operations and used django jinja templated
To run this project locally on your computer

# create vevn using command and activate it
 python -m vevn yourVenvName
 source/yourVenvName/Script/Activate

# Clone the repo
# Install requirements.txt and set database variable according to you setup
# Create SuperUser
 python manage.py createsuperuser
# Make migration
python manage.py makemigration
python manage.py migrate
# Run project
python manage.py runserver
