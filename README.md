My Experience with Large-Scale Data Processing: Power Query & SSIS

I discovered a dataset significantly larger than those I had worked with in my previous projects. Working with this dataset gave me a new perspective on data processing, ETL workflows, and the challenges of handling large volumes of data.

Initially, I discovered the power and simplicity of Power Query. Without using a database, I independently performed the ETL process directly within Power BI using Power Query. This experience helped me understand how accessible and effective data transformation can be, even without a dedicated database infrastructure. I also developed a dashboard that I was genuinely satisfied with, at least from my own perspective.

Later, I decided to implement the same ETL workflow independently using SQL Server and SSIS, this time with a more advanced approach and a database-driven architecture.

This transition helped me recognize how much easier database systems can make certain parts of the ETL process, particularly when it comes to troubleshooting, identifying errors, validating data, and managing transformations. Working directly with SQL Server also gave me a better understanding of the advantages of separating data storage and processing from the reporting layer.

However, the experience was not without limitations. Due to my hardware constraints, particularly limited available memory, I was unable to complete the ETL process for a table containing approximately 32 million records in a single processing stage using my current knowledge and system configuration.

Despite this limitation, the project introduced me to several useful techniques and concepts, including:

BULK INSERT in T-SQL: For loading large volumes of data into SQL Server.

Data Conversion in SSIS: For handling data type inconsistencies and preparing data for subsequent transformations.

Overall, this project was an important learning experience. More than simply building a dashboard or implementing an ETL pipeline, it helped me understand the practical differences between working with data directly in Power BI and building a database-driven ETL architecture using SQL Server and SSIS.

It also taught me that choosing the right tools and architecture is just as important as writing transformations, especially when working with large-scale datasets.
