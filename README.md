# session_06_database_design
## Part 1: Normalization

| Table Name | Primary Key | Foreign Key | Normal Form | Description |
| :--- | :--- | :--- | :--- | :--- |
| users | user_id | None | 3NF | Stores user information |
| posts | post_id | user_id | 3NF | Stores blog posts |
| categories | category_id | None | 3NF | Stores categories |

## Part 2: Relationships

- Users to Posts: One-to-Many (1:N)
- Posts to Categories: Many-to-Many (N:N)
- Doctors to Appointments: One-to-Many (1:N)
- Patients to Appointments: One-to-Many (1:N)
