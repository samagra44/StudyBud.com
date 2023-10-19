# StudyBuddy: A Study-Oriented Social Platform

**StudyBuddy is a web application developed using Django that serves as a study-oriented social platform and chat system, with features akin to a Discord clone, coupled with a study room search engine. This README provides an in-depth description of the project, guiding you through the installation process and offering an extensive overview of its functionalities.**

## Project Description

**StudyBuddy is designed to facilitate collaborative learning and discussions. Here's a comprehensive breakdown of its features:**

### Chat Rooms

- **Create Study Rooms:** *Users can create study rooms focused on specific topics. For instance, if you're studying Django, you can set up a dedicated chat room for it.*     

- **Join Study Rooms:** *Other users can find and join these study rooms to communicate with fellow learners.*   

- **Chat Like Discord:** *Within these rooms, users can engage in real-time text conversations, similar to a Discord server, allowing for a dynamic and interactive learning experience.*       

### Study Room Feed       

- **Study Room Feed:** *Study rooms are displayed in a social networking-style feed. Users can see various study rooms created by the community.*   

- **Room Details:** *The feed provides details about the study rooms, including the number of participants and when the room was created.*   

- **Room Conversations:** *Users can access and participate in the conversations within a room, promoting knowledge sharing and collaboration.* 

## Installation   

**To set up StudyBuddy on your local machine, follow these detailed steps:**    

### Clone the Repository:
```
git clone https://github.com/samagra44/StudyBud.com.git
```

 ### Change the directory:
 ```
 cd StudyBuddy
 ```

### Virtual Environment:

*Create a virtual environment for the project:*

```
python -m venv venv
```

- **Activate the venv Environment:**
```
source venv/bin/activate
```

- **Activate the venv Environment on Windows:**
```
venv\Scripts\activate
```

- **Create the virtual environment using conda command:**
```
conda create -n venv
```
**Activate the venv Environment:**  
```
conda activate venv/
```

**Verify that the virtual environment was activated correctly by running the following command:**
```
conda info
```

### Install Dependencies:

**Install the required Python packages:**
```
pip install -r requirements.txt
```

### Database Setup:

**Apply database migrations to set up the database schema:**
```
python manage.py migrate
```

### Create an Admin User:

**Create an admin superuser to manage the platform:**
```
python manage.py createsuperuser
```

### Launch the Development Server:

**Start the development server:**
```
python manage.py runserver
```

### Access the Application:

**Open a web browser and navigate to http://localhost:8000/ to access StudyBuddy.**


## Configuration      

**StudyBuddy can be configured to meet your specific needs. Key configuration options are found in the settings.py file within the project directory. These settings include database configuration, secret keys, and other parameters that you can modify to suit your requirements.**  

### Usage   

**Once the application is running, users can:**   

- Register for an account or log in.    
- Create their own study rooms.    
- Join existing study rooms to collaborate and learn.   
- Explore the study room feed to discover and join other rooms.    
- Interact in real-time chat within study rooms, similar to Discord.     
- Update their user profiles to personalize their experience.       

**StudyBuddy empowers users to seamlessly engage in collaborative learning and discussions within a social networking-style platform.**

## License      

**This project is licensed under the MIT License, which means you are free to modify and use it according to your requirements. For a more in-depth understanding of the project and detailed usage instructions, consult the project's documentation and explore the codebase. We hope StudyBuddy enhances your study collaboration experience and provides a valuable tool for learners.**
