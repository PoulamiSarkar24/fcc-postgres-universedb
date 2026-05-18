# fcc-postgres-universedb

🌌 *Celestial Bodies Database*

A relational database project built using PostgreSQL as part of the freeCodeCamp Relational Database Certification.

This project models different celestial objects including galaxies, stars, planets, moons, and black holes using SQL tables, constraints, and relationships. The database structure and data are stored in the universe.sql dump file.

🚀 **Features**
Relational database design
Multiple interconnected tables
Primary and Foreign Keys
UNIQUE and NOT NULL constraints
Auto-incrementing IDs using sequences
Sample astronomical data
PostgreSQL database dump for easy import

🛠️ **Technologies Used**
PostgreSQL
SQL
Git
GitHub
Linux Terminal / Bash
🗂️ Database Structure

The database contains the following tables:

*Table	Description*
galaxy	Stores galaxy information
star	Stores stars linked to galaxies
planet	Stores planets linked to stars
moon	Stores moons linked to planets
blackhole	Stores black hole information

🔗 **Entity Relationships**
Galaxy → Star → Planet → Moon
One galaxy can have many stars
One star can have many planets
One planet can have many moons

The database currently includes:

6 galaxies
6 stars
12 planets
20+ moons
3 black holes

📚 **Concepts Practiced**

This project helped practice:

Database normalization
Table relationships
SQL constraints
Foreign key implementation
PostgreSQL commands
Database export/import
Relational schema design


🎯Completed as part of: freeCodeCamp Relational Database Certification
Galaxy: andromeda
Planet: Earth
Star: beatlejuice
