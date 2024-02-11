# College Event Database System

This is a database system designed to store the details and requisites of college events efficiently. The database is implemented using SQL and utilizes normalization concepts to overcome data inconsistency and improve data integrity.

## Features

- **Storage of Event Details**: The database allows for the storage of various details related to college events, including event name, date, venue, description, organizers, attendees, etc.
- **Requisites Management**: The system enables tracking of requisites for each event, such as equipment, resources, permissions, budget, etc.
- **Normalization**: Efficient normalization techniques are employed to organize the database schema, reduce redundancy, and improve data integrity.
- **Data Consistency**: By employing normalization, the database minimizes data redundancy and inconsistencies, ensuring that each piece of data is stored in only one place, reducing the likelihood of errors and ensuring data consistency.

## Database Schema

The database schema is designed to efficiently organize event details and requisites. It consists of multiple tables that are normalized to reduce redundancy and improve data integrity. Here's an overview of the main tables:

1. **Events Table**: Stores general details of each event such as event ID, name, date, venue, description, etc.
2. **Organizers Table**: Contains information about the organizers of each event, linked to the Events table through foreign keys.
3. **Attendees Table**: Tracks attendees for each event, linked to the Events table through foreign keys.
## SQL Scripts

The repository includes SQL scripts for creating the database schema, populating sample data, and querying information from the database. These scripts are organized for easy setup and usage.

## Usage

1. **Setup Database**: Execute the SQL script to create the database schema.
2. **Populate Data**: Run the script to populate sample data into the database.
3. **Query Information**: Use SQL queries to retrieve event details, requisites, organizers, attendees, etc.

## Contributing

Contributions are welcome! If you have suggestions for improvements, additional features, or find any issues, please feel free to open an issue or submit a pull request.
