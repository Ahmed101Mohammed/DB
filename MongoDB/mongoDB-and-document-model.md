# MongoDB and the Document Model

## MongoDB is a general purpose document database
- MongoDB has a wide variety of use cases
  - Small personal educational projects.
  - Start-ups.
  - Enterprise applications.
- Common example of applications that used MongoDB:
  - E-commerce.
  - Content management.
  - IoT and time-series data.
  - Trading and Payments.
  - Gaming.
  - Mobile Apps.
  - Real time analytics and AI.

## MongoDB structure
- MongoDB structured data on documents, which similar to JSON objects.
- Document is a basic unit of data in MongoDB.
- Acollection is a grouping of those documents.
- While documents in collection are typically similar, They don't have to have the exact same structure. 
- DataBase: is a container for collections

## Documents
- MongoDB structured data on documents, which similar to JSON objects.
- Documents are displayed in JSON format and stored in BSON format.
- Documents offer a flexible and developer-friendly way to work with app data.
- Documents correspond to objects in code, It match how we think in code, which makes them intuitive to work with.
- Document Model make it easier to plan how application data will correspond to data in the database.
- Document Model let you model data of any shape or structure.
- Documents can model everything:
  - Simple key value pairs.
  - text.
  - Geospatial indexes.
  - Time series.
  - Graph data.
- Flexibility of documents means: We can use on format to both model and query data for any application: thats mean that we can use documents to represent the model of the data. And the same time we used documents to create MongoDB queries.
- The flexibility make development more easier and productive: Because there no migration when the data schema change, because MongoDB don't furce you to use fixed document schema, you can have multiple documents with different fields in the same collection.

### BSON
- BSON is a short for: binary json: It is an extension of JSON providing aditional features that MongoDB can leverage.
- BSON add support for additional data types that unavilable in standared JSON.

#### Data types BSON support
- All JSON data types:
  - String.
  - Object.
  - Boolean.
  - Number.
  - Array.
  - null.
- Dates.
- Different types of numbers.
- Object ID's.
- and more...

##### ObjectID
- Is special data type, used in MongoDB to create unique identifier in the database.
- Every document require and ID field. That acts as a primary key.

## Can I use MongoDB with my programming language?
- MongoDB provides drivers in all major programming languages, so it easy to connect MongoDB to your app. without concernec of the availability of MongoDB driver for your language.

## MongoDB charactrects that make is popular across all use cases:
- Scalability.
- Resilience.
- Speed of development.
- High levels of data privacy and security.

## Atlas
- The MongoDB database is at the core of Atlas, which is a developer data platform.
- Atlas features:
  - Full text search.
  - Data visualization.