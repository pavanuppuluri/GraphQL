# GraphQL
GraphQL is a data query and manipulation language for APIs that allows a client to specify what data it needs. 
A GraphQL server can fetch data from separate sources for a single client query and present the results in a unified graph. 
It is not tied to any specific database or storage engine.

It tackles the drawbacks of regular REST APIs. With GraphQL, we can pinpoint the exact data we need, 
avoiding the hassles of getting too much or too little. 

It’s all about efficiency and delivering just what’s necessary.

In our Spring Boot project, we’ll harness the power of GraphQL. By combining it with Spring Boot, we’ll create an intuitive and seamless integration. We’ll begin by crafting a GraphQL schema — a masterpiece that defines data types and governs queries and mutations. We’ll use GraphQL Schema Definition Language (SDL) to orchestrate this process.

**Key terms in GraphQL**
<br/><br/>
**Schema**<br/>
- The schema is the core of GraphQL, serving as an essential blueprint that shapes your API’s structure.
- It defines the data types and showcases the API’s capabilities.
- Acts as a friendly agreement between the client and server.
- Lays out which data can be requested and what will be provided in return.
- Enhances usability and maintainability of your GraphQL API.

<img width="182" alt="image" src="https://github.com/user-attachments/assets/2e0328ad-6f7f-4df3-b6ed-6f31fd03572c">

**Type**<br/>
- Strict typing in GraphQL ensures that data is well-defined and consistent
- This makes it easier for developers to understand and work with the API

<img width="151" alt="image" src="https://github.com/user-attachments/assets/400a035e-a137-4192-8aa3-70e85cb1a8d6">

**Field**<br/>
- In GraphQL, a field is a crucial element found within a Type.
- Represents a specific piece of data that the Type holds, similar to properties in a Java class.
- For example, in a “User” Type:
  - Fields like “name” and “email” define the user’s identity.
 
**Query**<br/>
- In GraphQL, a query is a powerful tool for fetching data from the API endpoint.
- Acts as a gateway to access information, like a key unlocking the treasures of the GraphQL universe.
- Queries are meant only for reading data, not for updating or creating it.

<img width="235" alt="image" src="https://github.com/user-attachments/assets/ab9554bf-6200-4b6c-aa8f-25eea4943e0f">

<br/>
<br/>

<img width="483" alt="image" src="https://github.com/user-attachments/assets/3e6e6a20-f20e-4724-ac71-88d37cfffee3">

<br/>
<br/>

**Mutation**<br/>
- In GraphQL, a mutation is a specialized tool designed for data manipulation.
- Unlike queries, which are used for reading data, mutations act as guardians of change.
- Provide a controlled and elegant way to perform insert or update operations within the GraphQL universe.

<img width="249" alt="image" src="https://github.com/user-attachments/assets/a9d57fa9-f91c-4aa1-a01b-b65f81326afa">







