# Real Estate Sales Performance Dashboard | Power BI

## Project Overview
An end-to-end Power BI analytics project built to analyze real estate sales performance across the complete lead-to-booking funnel.

The solution transforms raw CRM-style data into an interactive management dashboard covering lead generation, site visits, bookings, revenue, project performance, executive performance, lead sources, and monthly sales trends.

## Business Questions
The dashboard was designed to answer questions such as:

- Which projects generate the highest booking volume and booking value?
- How efficiently are leads converting into site visits and bookings?
- Which lead sources contribute the highest lead volume?
- How do individual sales executives perform across leads, bookings, conversion, and booking value?
- Where are leads dropping within the sales funnel?
- How are leads and bookings changing month over month?

## Data Preparation
Power Query was used to:

- Remove duplicates and clean inconsistent records
- Standardize project and executive codes
- Standardize lead sources and lead statuses
- Handle missing information
- Clean text fields and assign appropriate data types
- Prepare fact and dimension tables for analysis

## Data Model
A star-schema-style model was created using:

### Fact Tables
- Fact Leads
- Fact Bookings

### Dimension Tables
- Dim Projects
- Dim Executives
- Dim Lead Sources
- Dim Date

Shared dimensions filter the fact tables through one-to-many relationships.

## DAX Measures
Key measures include:

- Total Leads
- Total Site Visits
- Total Bookings
- Total Booking Value
- Average Booking Value
- Lead-to-Site-Visit %
- Site-Visit-to-Booking %
- Lead-to-Booking %
- Previous Month Bookings
- Month-over-Month Booking Change %

## Dashboard Pages

### 1. Real Estate Sales Performance Dashboard
Executive overview covering sales funnel KPIs, booking value, project performance, monthly trends, and interactive filters.

### 2. Sales & Lead Performance Analysis
Detailed analysis of project performance, executive performance, lead-source contribution, and lead pipeline status.

## Key Results

- 2,800 total leads analyzed
- 380 site visits
- 305 bookings
- ₹4.77B total booking value
- 10.89% overall lead-to-booking conversion
- Cedar Court recorded the highest booking volume
- Oak & Ivy generated the highest total booking value

## Tools & Skills
Power BI | Power Query | DAX | Data Cleaning | Data Modeling | Star Schema | KPI Development | Funnel Analysis | Sales Analytics | Business Intelligence

## Repository Contents
- Power BI `.pbix` project file
- Dashboard PDF
- Data model image
- Source dataset

## Note
This project uses simulated real estate data and was created as a portfolio analytics project.
