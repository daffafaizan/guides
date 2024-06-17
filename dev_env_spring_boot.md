## Creating a Dev Environment for Spring Boot Project and Run on IntelliJ

1. Create a `application-dev.properties` file in the resources folder
2. Navigate to the top right, left of the run button, click the dropdown
3. Click "Edit Configurations"
4. Under "Gradle", find the default run configuration and remember the values
5. Click "Application" and click "Add new run configuration..."
6. Type a name like "DEV", insert the same values from the previous configuration, and add `spring.profiles.active=dev` in the "Environment variables" 
