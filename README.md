## To get your Go Todo List application running, follow these steps:

### Prerequisites
Go: Ensure you have Go installed. You can download and install it from golang.org.
MongoDB: Ensure MongoDB is installed and running. You can find installation instructions on the MongoDB website.

### Steps to Run the Application
#### Clone the Repository:

##### Open your terminal or command prompt.
Run the following command to clone your repository:
git clone https://github.com/vedantPankar/go-todo.git
cd go-todo

##### Install Dependencies:
Install the necessary Go packages by running:
go get -u github.com/go-chi/chi
go get -u github.com/go-chi/chi/middleware
go get -u github.com/thedevsaddam/renderer
go get -u gopkg.in/mgo.v2

##### Ensure MongoDB is Running:
Make sure your MongoDB server is running on 127.0.0.1:21017 or change the hostName constant in the code to match your MongoDB server configuration.

#### Run the Application:

In your terminal, navigate to the directory where the main.go file is located.

#### Run the application with the following command:

go run main.go
The server should start running on port 9000. You should see a message indicating that the server is running.
