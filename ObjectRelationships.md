# Object Relationship

1. Ralationships are used to establish connection between two or more objects.
2. Salesforce provides different types of relationships
- Master-Detail relationship
- Many - Many relationship
- Lookup relationship
- Hiearchial relationship
- External lookup
- Internal lookup


### Importance of creating relationship among objects

1. To avoid data redundancy
2. To Cascade-Delete - Data Integrity
3. To refer the related info in the same data.

##### Master-Detail relationship

- It is one to many relationshipts between 2 objects
- The field type Master-Detail relation can be created only on the custom objects
- Master Detail field can only be created on the custom objects.
- Master Detail field can be created on the many side of the relationship.It means the child object
Eg : Department is Master field and Employee is child field.
- Master Detail field is a required field.
- Object on which Master Detail field is created is called Child Object/Detail Object/Related Object.
- In one to many relation of master detail parent object is also called Master Object.
- If master record is deleted then the child records are also deleted, but the deleted child records will not be shown in the recycle bin
- If we undelete the master record then the corresponding child records are also undeleted.
- Owner of the master record will be the owner of the corresponding child records.
- In the master object, there is a field type called roll up summary, which is used to summarize the child records like the total no. of child records, 

#### Junction Object

1. Junction object is a custom object.
2. Junction object has 2 master detail fields
3. Junction object maintains many to many relationships.
4. First Master detail field created on the junction object is called Primary master.
5. Second Master detail field on which junction object is called is called secondary master.
6. Look and Feel and Ownership is inherited from Primary master.
7. If you delete any master then corresponding child records are deleted.



