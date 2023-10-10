Hello! 

This is my submission to the GenAI challenge of building a chatbot to answering questions on a CSV based dataset

To give a brief overview of my solution, I developed a chatbot using both back-end and front-end technologies.
On the back-end, I used langchain with a GPT-4 model. Essentially, with the help of a prompt, the model produces
a SQL query based on what the user has entered and then that query is applied onto the dataframe (of the CSV)

The result of the queries are displayed on the frontend, which I used NextJS to develop.,

Instructions:
1. Set up a Python enviornment and install all required libraries by performing  "pip install -r requirements.txt" in the backend directory
2. Ensure that the details of the model are defined in the .env 
3. Run the backend by running "python app.py"
4. Then once it's running, open up a separate terminal and head over to the backend directory
5. Run "npm i" to install all required node modules
6. Run the frontend using "npm run dev" and make sure you go to "localhost:3000/chatbot"

You can ask it queries such as "fetch me customers that have a degree" or "how many customers have spent x amount on wine"