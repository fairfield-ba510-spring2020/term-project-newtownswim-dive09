# Step By Step Walk-Through

## 1. We looked through the data in order to figure out what tables we would need for this database.
    - We found that Cataloge Courses and Section would be the most important and largest entities
    - As for other tables we settled on Location, Term, Section Mettings, intructors and programs
    - With this in mind we normalized the database and created an ERD
    
## 2. Next we created and populated the Database
    - Each table was created and primary and forgien keys wetre specified
    - Utilizing Python we were able to create import tables in order to more effciently import the data
    - Before importing we checked the counts of each table to make sure it was accurate
    - Lastly, using the import tables we were able to fully populate the database
    
## 3. Once the Database was created we checked for intergirty
    - Did a few tests to check for relational, entity, and domain integrity
    
## 4. Next we contructed the Data Warehouse
    - Using the Star Schema model we chose Section Meetings to be our fact table
    - The Dimension tables chosen were Programs, Terms, Locations, TimeCodes and Intsructors
    - The tables were all created and PK and FK laid out
    - Using the Attach database function we were able to take the CourseDB and use it to populate the warehouse
    
## 5. Next we needed to test the Warehouse for intergirty 
    - Utilized similar tests to verify relation, domain and entity integrity

## 6. Once the Integerity was verfified we put together a Demo to demonstrate its usefulness
    - Showed specific queries for certain classes that can be found and counts that can be used