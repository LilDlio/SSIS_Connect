# Distributed Database Project: SQL Server to MySQL Data Transfer

## Overview
This project aims to transfer data from Microsoft SQL Server to MySQL using a Windows Form application built in C#. It leverages SSIS (SQL Server Integration Services), SSIS+, C#, MSSQL, and MySQL technologies to achieve seamless database migration.

## Technologies Used
- **C#**: Used for developing the Windows Form application and managing the user interface.
- **SSIS (SQL Server Integration Services)**: Used for extracting data from Microsoft SQL Server.
- **SSIS+**: Extended functionalities for SSIS to facilitate complex data transformations and migrations.
- **Microsoft SQL Server**: Source database from which data is extracted.
- **MySQL (MySQL Workbench)**: Target database where data is loaded after transformation.

## Features
- **Windows Form Application**: Provides a user-friendly interface for initiating and monitoring data transfers.
- **Automated Data Extraction**: Utilizes SSIS to extract data from Microsoft SQL Server tables.
- **Data Transformation**: SSIS+ is employed to transform data as per MySQL schema requirements.
- **Direct MySQL Load**: Transformed data is loaded into MySQL using MySQL Workbench connectivity.
