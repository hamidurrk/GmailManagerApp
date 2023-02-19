# Gmail Manager App
Gmail Manager App is a Java application that uses the Gmail API to manage emails. This app provides a basic implementation to list the user's Gmail labels.

## Installation
1. Clone the repository: git clone https://github.com/hamidurrk/GmailManagerApp.git
2. Navigate to the GmailManagerApp directory: cd GmailManagerApp
3. Build the project using Maven: mvn clean install
## Usage
1. Run the application: java -jar target/GmailManagerApp-1.0-SNAPSHOT.jar
2. Log in to your Gmail account when prompted.
3. The application will list all the labels in your account.
## Configuration
The application requires a credentials.json file to authenticate with the Gmail API. The file should be located in the src/main/resources directory of the project. If you don't have this file, follow these steps to create one:

1. Go to the Google Cloud Console.
2. Create a new project or select an existing one.
3. In the left sidebar, click on APIs & Services > Credentials.
4. Click on Create credentials > OAuth client ID.
5. Select Desktop App as the application type.
6. Give your client ID a name and click Create.
7. Download your client ID as a JSON file and save it as credentials.json in the src/main/resources directory.
## Contributing
We welcome contributions to the Gmail Manager App project. If you would like to contribute, please open a pull request with your changes.
