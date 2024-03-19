
### Getting Started
##### CSV to JSON convertor
This is a Node.js application which efficiently converts large CSV files into JSON format. It leverages streaming to process files without overloading the system and uses batch processing for quick database insertion into PostgreSQL. Ideal for managing extensive datasets with complex structures.



```markdown
###Features

1. Streaming CSV Parsing: Handles large CSV files without overwhelming memory resources.
2. Nested Property Support: Parses CSV columns with infinite depth nested properties (e.g., a.b.c...z).
3. Efficient Database Upload: Utilizes batch inserts for better performance with large datasets.
4. Flexible Data Handling: Supports a mix of flat and nested data, suitable for a variety of CSV formats.


###Prerequisites

- Node.js (Version 14 or later recommended)
- PostgreSQL (Version 10 or later recommended) 
- A PostgreSQL database setup and accessible
- CSV files conforming to the application's expected format
```

Setup

1. Clone the Repository
```bash
git clone https://github.com/your-repository/large-csv-parser.git
cd large-csv-parser
```

2. Install Dependencies
```bash
npm install
```
3. Configure Environment

   Create a .env file in the root of the project with the following content, adjusted to match your database configuration:
```bash
DB_HOST=localhost
DB_USER=your_username
DB_PASS=your_password
DB_NAME=your_database
DB_PORT=5432
CSV_FILE_PATH=./path_to_your_csv_file.csv
```

4. Database Setup
```bash
   Ensure your PostgreSQL database is set up and running. Create the necessary table(s) as per your application schema. 
```



5. Usage

   To run the application and upload data from your CSV file to the database:

```bash
node app.js
```



6. Screenshots
   1.Query to display users
   ![image](https://github.com/Dishi2003Jain/Kelp-global/assets/82431854/1c351163-7619-4d8f-88ed-cadf89098684)


   ![image](https://github.com/Dishi2003Jain/Kelp-global/assets/82431854/222bc11a-e5ae-4731-a926-c1914a20d27a)

   2.Console

   ![image](https://github.com/Dishi2003Jain/Kelp-global/assets/82431854/8169a76a-c9b6-4a1a-9c71-23e9debaf7c3)

   3.Postman

   ![image](https://github.com/Dishi2003Jain/Kelp-global/assets/82431854/4094c7e7-1152-41f7-bf4e-7eacc957c9c0)

   

   
