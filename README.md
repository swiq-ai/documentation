# SWIQ.AI Plugin Documentation
SWIQ.AI accelerates your software stability journey and frees up developer’s 30% time spent on unit testing.

#

## Dependencies

To successfully run the SWIQ.AI IntelliJ plugin, the following dependencies are required in your project:

### Spring Dependencies

```xml
<!-- Spring Test Utilities (Required for non-spring applications as well) -->
<dependency>
  <groupId>org.springframework</groupId>
  <artifactId>spring-test</artifactId>
  <version>5.3.18</version> <!-- Use the appropriate version -->
</dependency>
```

### Lombork Dependency Update 
```xml
<dependency>
  <groupId>org.projectlombok</groupId>
  <artifactId>lombok</artifactId>
  <version>1.18.24</version>
  <scope>provided</scope>
</dependency>
```

### Mockito Dependencies (Required)

```xml
<!-- Mockito for JUnit Jupiter -->
<dependency>
  <groupId>org.mockito</groupId>
  <artifactId>mockito-junit-jupiter</artifactId>
  <version>5.8.0</version>
  <scope>test</scope>
</dependency>

<!-- Mockito Inline Setup -->
<dependency>
  <groupId>org.mockito</groupId>
  <artifactId>mockito-inline</artifactId>
  <version>3.6.28</version>
</dependency>

<!-- Core Mockito Library -->
<dependency>
  <groupId>org.mockito</groupId>
  <artifactId>mockito-core</artifactId>
  <version>3.4.0</version>
</dependency>
```

### JUnit 5 Dependencies (Required)

```xml
<!-- JUnit Jupiter API -->
<dependency>
  <groupId>org.junit.jupiter</groupId>
  <artifactId>junit-jupiter-api</artifactId>
  <version>5.8.1</version>
  <scope>test</scope>
</dependency>

<!-- JUnit Jupiter Engine -->
<dependency>
  <groupId>org.junit.jupiter</groupId>
  <artifactId>junit-jupiter-engine</artifactId>
  <version>5.8.1</version>
  <scope>test</scope>
</dependency>

<!-- Additional JUnit Platform Components -->
<dependency>
  <groupId>org.junit.platform</groupId>
  <artifactId>junit-platform-launcher</artifactId>
  <version>1.8.1</version>
  <scope>test</scope>
</dependency>

<dependency>
  <groupId>org.junit.platform</groupId>
  <artifactId>junit-platform-suite-api</artifactId>
  <version>1.8.1</version>
  <scope>test</scope>
</dependency>

<dependency>
  <groupId>org.junit.platform</groupId>
  <artifactId>junit-platform-suite-engine</artifactId>
  <version>1.8.1</version>
  <scope>test</scope>
</dependency>

<dependency>
  <groupId>org.junit.jupiter</groupId>
  <artifactId>junit-jupiter-params</artifactId>
  <version>5.8.1</version>
  <scope>test</scope>
</dependency>

<!-- For running JUnit 4 tests with JUnit 5 -->
<dependency>
  <groupId>org.junit.vintage</groupId>
  <artifactId>junit-vintage-engine</artifactId>
  <version>5.8.1</version>
  <scope>test</scope>
</dependency>
```

These dependencies ensure that all necessary components for unit testing with JUnit 5 and Mockito are available, enabling robust testing capabilities. This setup supports a wide range of test scenarios, making your development process more efficient and your software more reliable.
