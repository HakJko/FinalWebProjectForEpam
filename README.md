# Final Web Project For Epam - Library Management System
-------------------
> The repository is compiled by ___Ihar Koshman___ for __EPAM TRAINING CENTER__
***

## Final Task. Web Project

> ___Library___. The reader has the opportunity to search and order Books in the Catalog. The librarian gives the 
>                   Reader a Book by subscription or in the reading room. The book can be present in the Library 
>                   in one or more copies. The Administrator manages Librarians, Readers, and Books.

- The application must be implemented using Servlet and JSP technologies.
- The application architecture must conform to the _Layered architecture_ and _MVC_ patterns. A controller can only 
    be of two types: a role controller or an application controller.
    
***

### DB requirements:

- Information about the subject area should be stored in the database.
- If the data in the database is stored in Cyrillic, it is recommended to use utf-8 encoding
- Database access technology JDBC only.
- To work with the database, a thread-safe connection pool must be implemented in the application, the use of 
    synchronized and volatile is prohibited.
- When designing a database, it is recommended to use no more than 6-8 tables.
- Work with the data in the application using the DAO template.

***

### Basic application requirements:

- The application interface must be localized; the choice of languages: EN|BE|RU etc.

- The application must correctly handle exceptional situations that arise, including logging them. Use Log4J2/SLF4J 
    as a logger
    
- Classes and other entities of the application must be competently structured by packages and have a name reflecting 
    their functionality.
    
- When implementing the business logic of the application, design patterns should be used if necessary 
    (for example, GoF templates: Factory Method, Command, Builder, Strategy, State, Observer, Singleton, Proxy, etc.).
    
- Use a session to store user information between requests.

- To intercept and correct request and response objects (response) apply filters.

- It is allowed, but by no means necessary, to use AspectJ and Web-services technologies 
    (these topics are not considered in the framework of external training).

- When implementing JSP pages, you should use the tags of the JSTL library, it is forbidden to use scriptlets.

- When implementing the user interface, it is allowed to use any front-end development technologies (js, AJAX).

- Implement protection against repeated execution of the request by pressing F5 and from js injection.

- Implement custom tags.

- It is advisable to organize the viewing of “long lists" in page-by-page mode.

- Validation of input data is performed on the client and on the server.

- Documentation for the project must be issued according to the requirements of javadoc.

- The design of the code must comply with the Java Code Convention.

- When deploying the application, it is allowed to use Maven technology.

- The application must contain JUnit, (TestNG, Mockito or EasyMock can be used by the student at will, 
    these topics are not covered in the course).

- The application must be hosted on a remote git repository.

***

### Minimum requirements for application functionality:

- Authorization (sign in) and exit (sign out) to/from the system.
- User registration and/or adding an artifact of the subject area of the system.
- View information (for example: view all betting odds, order statistics, invoices, etc.)
- Deletion of information (for example: cancellation of an order, deletion of an entity, etc.)
- Adding and modifying information (for example: create and edit a product, create and edit an order, etc.)

***