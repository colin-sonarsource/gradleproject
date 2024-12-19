# My Gradle Project

This project is a simple Java application that demonstrates the use of Gradle for building and testing. It also integrates with SonarQube for code quality analysis.

## Project Structure

```
my-gradle-project
├── src
│   ├── main
│   │   ├── java
│   │   │   └── App.java
│   │   └── resources
│   └── test
│       ├── java
│       │   └── AppTest.java
│       └── resources
├── build.gradle
├── settings.gradle
└── README.md
```

## Building the Project

To build the project, navigate to the project directory and run:

```
./gradlew build
```

## Running the Application

To run the application, use the following command:

```
./gradlew run
```

## Running Tests

To execute the tests, use:

```
./gradlew test
```

## SonarQube Analysis

To perform SonarQube analysis, ensure you have a SonarQube server running and configured. Then, run the following command:

```
./gradlew sonarqube
```

Make sure to configure the necessary properties in your `build.gradle` file for SonarQube, such as `sonar.projectKey`, `sonar.host.url`, and any authentication details if required.

## License

This project is licensed under the MIT License.