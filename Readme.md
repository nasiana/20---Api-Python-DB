# 20. Creating a simple hairdressers appointment booking system

For this lesson, we will need to connect to our MySQL server from Python.

To get our database ready, we are going to:
1. Execute the script `create_nano_db_script.sql`
2. Call the 'filldates' stored procedure to add some appointment slots:
```
CALL`nano`.`filldates`(20210701,20210705,'Peter');
CALL`nano`.`filldates`(20210703,20210707,'Maddie');
```
