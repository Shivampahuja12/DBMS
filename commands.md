<!-- 
    ALTER COMMANDS:

    ```1. alter table <tablename> alter <column_name> set default <value> 
    when we want to set a default value to a record then we can set with this command (by default it is null) 

    2. alter table <tablename> alter <column_name> drop default
    when we want to drop the set default value;
    (while doing the drop default it will also remove the default null constraint so if we want it then we have to set it again)

    3. alter table <tablename> alter <column_name> set default null;

    4. alter table <tablename> add <column_name> datatype;
    this command is used to add a column in the table

    5. alter table <tablename> modify column <column_name> enum(val1, val2, val3, ...)
    here we are using enumerator means only one of the enums values can be selected

    6. alter table <tablename> rename column <column_name> to <new_column_name>;
    this command is used to rename a column.

    7. alter table <tablename> drop column <column_name>;
    this command is used to delete the column 

    ```
-->