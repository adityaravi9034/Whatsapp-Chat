# Whatsapp-Chat
Do you ever wonder who sends the most messages in your group chat? Or what are the most common words used in your conversations? 
The Whatsapp Analyzer is here to help!
This is a Python-based web application that allows you to analyze your WhatsApp chat data. 
The application takes in a chat file and provides a number of insights and statistics including total messages, total words, media shared, 
links shared, monthly timeline, daily timeline, activity map, most busy users, word cloud, and most common words.



<img width="1225" alt="Screenshot 2023-05-02 at 7 08 20 PM" src="https://user-images.githubusercontent.com/103438753/235741098-5cfe2d31-2e79-4167-b9ac-6a107a2f5bd5.png">
**Getting Started**

To use this application, you need to have the following software installed on your machine:

**Python 3.7 or later**

**Streamlit**

**Matplotlib**

You can install the required libraries by running the following command in your terminal:

**pip install streamlit matplotlib**




**Usage**

To run the application, navigate to the project directory in your terminal and run the following command:



**streamlit run app.py**



This will open the application in your web browser. Once the application is running, follow these steps:


Upload your WhatsApp chat file by clicking on the "Choose a file" button in the sidebar.

Select the user you want to analyze the chat data for.

Click on the "Show Analysis" button to generate the statistics and insights.




**Code Overview**

The application is built using Python and the Streamlit framework. The code is organized as follows:

app.py - This is the main file that contains the Streamlit application code.

helper.py - This file contains helper functions that are used by the main application code to generate the statistics and insights.

preprocessor.py - This file contains functions for preprocessing the raw WhatsApp chat data.



**The main application code is divided into the following sections:**


Sidebar - This section contains the file uploader and user selector.

Top Statistics - This section displays the total number of messages, words, media messages, and links shared.

Monthly Timeline - This section displays a line graph showing the number of messages sent each month.

Daily Timeline - This section displays a line graph showing the number of messages sent each day.

Activity Map - This section displays two bar charts showing the busiest day and month for the selected user.

Most Busy Users - This section displays a bar chart and a table showing the busiest users in the chat.

Word Cloud - This section displays a word cloud based on the selected user's chat data.
![Uploading Screenshot 2023-05-02 at 7.11.22 PM.png…]()

Most Common Words - This section displays a horizontal bar chart showing the most common words used in the chat.



**Limitations**



The application currently only supports WhatsApp chat data.

The chat file must be in plain text format.

The application assumes that the chat data has been exported in the following format: "hh:mm:ss sender_name: message_text".

The application does not currently support analysis of media files, such as images and videos, shared in the chat.
