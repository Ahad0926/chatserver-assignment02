# Chat Application
Welcome to the Chat Application! This application allows users to create and join chat rooms to communicate with other users in real-time.

## Prerequisites
Before running this application, you will need to have the following installed:

- Java Development Kit (JDK) 1.8 or later
- Maven
- Glassfish server

## Running the Application
To run the ChatResourceAPI, deploy it on a remote Glassfish server. To deploy, navigate to the root directory of the project and run the following command:
```
mvn clean install
```

This will build the project and create a war file in the target directory. Deploy the war file on a remote Glassfish server.

To run the ChatServer, deploy it on a local Glassfish server. To deploy, navigate to the root directory of the project and run the following command:
```
mvn clean install
```

This will build the project and create a war file in the target directory. Deploy the war file on a local Glassfish server.

Once the ChatServer is open, you can open two instances of the tab to create new rooms or join existing ones. Currently, the rooms list doesn't update, but you can manually create and join rooms from the input bar on the sidebar.
