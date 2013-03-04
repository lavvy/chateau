Chateau - Another data explorer for RethinkDB
====

RethinkDB already comes with a "data explorer", which is more like a query buider.  
Chateau is a data explorer where you can manage your data without writing a single query.  
It's still an alpha version so many features are missing, but it's enough if you want to bootstrap a new application and use Chateau as a panel admin for you data.

Install
----
Install node.js amd the following node libraries
```
npm install express
npm install coffee-script
npm install handlebars
npm install stylus
npm install rethinkdb
```
Build with
```
make
```


Run
----
```
node build/app.js
```


Versions
----
- 2013.03.03 - Alpha:  
    * Cool stuff: Infer the schema
    * Other cool stuff: Order keys in a smart way
    * List databases, tables, documents
    * Add/update/delete document  


License
----
MIT License

Contact
----
Michel Tu - orphee@gmail.com


Things to do
----
- Fix some css edges cases
- Do the TODOs in the code
- Refactor the code for add/update a document
- Implement/test all errors handling
- Fix Makefile
- Add loading for logout
- Sort the documents
- Filter documents
- Support joins
- Add custom actions
- Add custom views
- Support https
- Get a dog (a golden retriever)

Note
----
I am working at RethinkDB, but this project is a personal one.
