🎬 Movie Recommendation Website

The Movie Recommendation Website is a web-based application that recommends movies to users based on their preferences. The system uses machine learning techniques and natural language processing to analyze movie data and suggest similar movies. By entering the name of a movie, users can quickly discover other movies that share similar features such as genre, cast, or keywords. This project demonstrates how machine learning models can be integrated with a web application to build an intelligent recommendation platform.


🚀 Features

This application allows users to search for a movie and receive a list of recommended movies that are similar to the searched movie. The recommendation system is built using a content-based filtering approach that analyzes the characteristics of movies in the dataset. The website also includes sentiment analysis, which analyzes user reviews and determines whether the sentiment expressed in the review is positive or negative. The web interface is designed to be simple, interactive, and responsive so that users can easily interact with the system.


🛠 Technologies Used

The project is developed using Python as the main programming language. Machine learning and data processing tasks are implemented using libraries such as Scikit-learn, Pandas, and NumPy. Natural language processing techniques are used for text processing and sentiment analysis. The web application is built using the Flask framework, while the user interface is created with HTML, CSS, JavaScript, and Bootstrap to provide a clean and responsive design.


⚙️ System Working

The system works by first collecting and processing a movie dataset containing information such as movie titles, genres, cast members, and keywords. During preprocessing, the relevant features are combined and converted into numerical form using vectorization techniques. A similarity matrix is then created to measure the similarity between movies. When a user enters a movie name, the system compares it with other movies in the dataset and displays the top recommended movies that are most similar.


📂 Project Structure

The project consists of several folders and files that work together to run the web application. The templates folder contains HTML files that define the layout of the web pages. The static folder stores CSS, JavaScript, and image files used for styling and functionality. The dataset folder contains the movie data used to train the recommendation system. The main application logic is written in main.py, which runs the Flask server and connects the machine learning model with the web interface.


⚙️ Installation

To run this project locally, first clone the repository from GitHub and navigate to the project directory. Then install the required dependencies using the requirements.txt file. After installing the dependencies, run the application using the Python command. Once the server starts successfully, the application can be accessed through a web browser using the local server address.


🌐 Usage

After running the application, open a web browser and navigate to the local server address. The home page will display a search bar where users can enter the name of a movie. Once a movie is entered, the system processes the request and displays a list of recommended movies that are similar to the searched movie. This allows users to quickly explore and discover new movies based on their interests.


📸 Output

When a user enters a movie name such as “Avatar”, the system analyzes the similarity scores and displays a list of recommended movies. The output typically includes several movies that share similar themes, genres, or cast members. For example, the system may recommend movies such as Guardians of the Galaxy, Star Trek, John Carter, Avengers, and Interstellar.

The system also performs sentiment analysis on user reviews. If a review such as “This movie was amazing with great visuals and story” is provided, the system classifies it as Positive Sentiment. Similarly, a review like “The movie was boring and too long” will be classified as Negative Sentiment.


🔮 Future Improvements

In the future, this project can be enhanced by adding user authentication and personalized recommendations, integrating external movie APIs to fetch live movie data, and improving the overall user interface and experience. Advanced recommendation techniques such as collaborative filtering and deep learning models can also be implemented to improve the accuracy of the recommendations
