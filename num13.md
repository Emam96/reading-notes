# Related Resources and Integration Testing

## Relationships in Spring Data REST

### Adding Spring Data REST to a Spring Boot Project

The simplest way to get to started is to build a Spring Boot application because Spring Boot has a starter for Spring Data REST and uses auto-configuration.

To add Spring Data REST to a Gradle-based project, add the `spring-data-rest-webmvc` artifact to your compile-time dependencies.

### The Repositories

Spring Data REST uses a RepositoryDetectionStrategy to determine whether a repository is exported as a REST resource. The RepositoryDiscoveryStrategies enumeration includes the following values:

* DEFAULT :Exposes all public repository interfaces but considers the exported flag of @(Repository)RestResource.

* ALL :Exposes all repositories independently of type visibility and annotations.

* ANNOTATED :Only repositories annotated with @(Repository)RestResource are exposed, unless their exported flag is set to false.

* VISIBILITY :Only public repositories annotated are exposed.

### Repository resources

The core functionality of Spring Data REST is to export resources for Spring Data repositories. Thus, the core artifact to look at and potentially customize the way the exporting works is the repository interface.

### One-to-Many Relationship

>In a relational database, a one-to-many relationship exists when one row in table A may be linked with many rows in table B, but one row in table B is linked to only one row in table A. It is important to note that a one-to-many relationship is not a property of the data, but rather of the relationship itself.

### many-to-many Relationship

Multiple records in one table are related to multiple records in another table.
<hr>

## Integration Testing in Spring

Spring-Boot provides `an@SpringBootTest` annotation which provides spring-boot features over and above of the spring-test module. This annotation works by creating the ApplicationContext used in our tests through SpringApplication. It starts the embedded server, creates a web environment and then enables @Test methods to do integration testing.

By default, @SpringBootTest  does not start a server. We need to add attribute webEnvironment to further refine how your tests run. It has several options:

* MOCK(Default): Loads a web ApplicationContext and provides a mock web environment

* RANDOM_PORT: Loads a WebServerApplicationContext and provides a real web environment. The embedded server is started and listen on a random port. This is the one should be used for the integration test

* DEFINED_PORT: Loads a WebServerApplicationContext and provides a real web environment.

* NONE: Loads an ApplicationContext by using SpringApplication but does not provide any web environment


<hr>
&nbsp;
&nbsp;

Get back to [EMAM'S HOMEPAGE](https://emam96.github.io/reading-notes/)

 I have created this page as a part of my project using Github, Please visit my [profile](https://github.com/Emam96), I will be more than happy to hear from you all.      &nbsp;        &nbsp;       &nbsp;   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;      © Emam Shararah 2021