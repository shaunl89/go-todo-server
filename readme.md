This application is meant to serve as API endpoints for https://github.com/shaunloh89/vue-todo-list

# Quickstart

The following steps are needed to be done before you can begin to use this codebase locally.

Run the following script

```bash
# Depending on your usage practice Golang - either following advice of Go authors or create folders
# Assuming you want to put your code in your own code structures, you can use the following folder structure
# go-todo-server >> src >> {cloned folder}
mkdir go-todo-server
mkdir go-todo-server/src
export GOPATH=$(pwd)
cd go-todo-server/src

# Clone the repository
git clone https://github.com/shaunloh89/go-todo-server.git

# Install all packages
go get

# Start the application
go run main.go
```

# Starting the Server

Initialize the MySQL driver from System Preferences and create a database in your db application of choice.

The server currently uses "mysql" as our database driver, "root" as the database username, "password" as password and "todos" as database name. Please change these information as your needs.