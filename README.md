# University-Student-Data-Dashboard

## Overview

A comprehensive dashboard for university student data management, providing insights into key datasets such as Student Information, Class Enrollment, and Book Borrowing. This tool empowers users to efficiently visualize and analyze data related to university students.

## Set Up Steps

Follow these steps to set up the dashboard:

1. **Download FineReport**: Start by downloading FineReport, a powerful reporting tool.

2. **Project Structure**: Open 'dashboard.frm' and place the '/excel' directory inside './reportlets'.

3. **Create MySQL database**: Set up a MySQL database and execute 'data.sql' to deploy the datasets.

4. **Connect Database**: In FineReport, follow these steps:
    - Go to `Template` > `Define Data Connection` > `JDBC MySQL Database`.
    - Connect to the created MySQL database.

5. **Modify Template Dataset**: Adapt the Template Dataset to use the defined Data Connection.

6. **Data Query Validation**: Ensure that each data query in the Template Dataset works correctly.

7. **Preview**: Run the dashboard to preview it on the browser.
 <img src="https://github.com/YutongGGG/University-Student-Data-Dashboard/blob/main/demo.jpg" alt="demo" width="600"/>
 
