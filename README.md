# MYSQL-project

Project Overview:
🌐 Database:

The project focused on leveraging the World Database in MySQL to explore relational databases, different types of relationships, normalization, and executing diverse queries for insightful data retrieval.
Types of Relationships in Relational Databases:
1. One-to-One Relationship:

    Example: The relationship between a "Country" and its "Capital" in the "City" table. Each country has only one capital.

2. One-to-Many Relationship:

    Example: The relationship between "Country" and "City" tables. One country can have multiple cities.

3. Many-to-Many Relationship:

    Example: The relationship between "Country" and "Language" tables. Multiple countries can share the same language, and a country can have multiple languages.

Normalization in Database Development:
🔄 Definition:

Normalization is the process of organizing data in a database to reduce redundancy and dependency. It involves dividing large tables into smaller, related tables and defining relationships between them.
🔑 Importance:

    Data Integrity: Reduces the risk of data anomalies and ensures consistency.
    Efficiency: Optimizes storage and enhances query performance.
    Flexibility: Easier to modify and extend the database structure.


Foreign Keys:

    City Table: CountryCode (References Country table)
    CountryLanguage Table: CountryCode (References Country table)

Conclusion:

The MySQL project using the World Database successfully explored different types of relationships, normalization, and executed diverse queries for insightful data retrieval. The EER diagram provided clarity on primary and foreign keys, essential for maintaining a well-structured and efficient relational database.

Feel free to explore the repository for detailed documentation and additional insights! 🚀 If you have any questions or feedback, please don't hesitate to reach out. 📧
