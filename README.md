This project focuses on designing a well-structured database schema for a Library Management System using SQL. It involves creating normalized tables such as Author, Publisher, Book, Member, and Loan, each with appropriate primary and foreign key constraints to maintain data integrity and define relationships. Tools like MySQL Workbench or SQLiteStudio were used to implement the schema and optionally visualize it using an ER diagram. The goal is to understand relational database design, table creation, and key relationships like one-to-many and many-to-many. By completing this project, learners gain hands-on experience in building scalable, organized databases suitable for real-world applications and placement interviews.
Author (1) ────< (M) Book (M) >──── (1) Publisher  
                     │  
                    (M)  
                    ↓  
                 Loan >── (1) Member
