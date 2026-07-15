# Data Transformation Pipeline

## Overview
An end-to-end data transformation pipeline that processes raw 
semi-structured data, applies business rules, and prepares clean 
datasets ready for SQL Server integration and reporting.

## Problem Statement
Raw incoming data contained inconsistencies, formatting issues, 
and structural problems that prevented direct database insertion 
and accurate reporting.

## Tools Used
- Microsoft Excel (transformation and business rule application)
- SQL Server (destination database)
- SQL (post-load validation and integrity checks)

## Process
1. Received and assessed raw semi-structured data
2. Identified data quality issues including nulls, duplicates, 
   formatting inconsistencies and structural mismatches
3. Applied business transformation rules in Excel
4. Standardized data types, formats and naming conventions
5. Validated transformed data before database insertion
6. Executed post-load SQL validation queries to confirm integrity

## Transformation Steps Applied
- Null value handling and default value assignment
- Duplicate record identification and removal
- Date format standardization
- Text field cleaning and trimming
- Numeric field validation and correction
- Column restructuring to match database schema

## Outcome
Delivered clean, validated datasets ready for seamless SQL Server 
integration, significantly improving data quality and reducing 
post-load error rates in ETL workflows.
