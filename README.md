# customer Management
# Data Engineering Project

## Week 1: Data Management and Database Design

### Entity-Relationship Diagram (ERD)

![ERD Diagram](https://github.com/osama1hatem2abdelkreem3/customer-Management-/blob/main/pics/week%201/image%20(2).png)

In **Week 1**, we focused on designing the **Entity-Relationship Diagram (ERD)** for the project. The main goal was to identify the entities, their attributes, and the relationships between them.

Key **entities** identified:
- **Customer**: Stores customer details such as name, date of birth, email, gender, phone, address, etc.
- **Transaction**: Includes transaction-related information like transaction ID, amount, currency, type, status, and transaction date.
- **Interaction**: Tracks customer interactions, including the interaction outcome, type, channel, follow-up requirements, etc.
- **Agent**: Represents agents handling customer interactions.

The **relationships** between these entities are as follows:
- **Customers** can have multiple **transactions**.
- **Customers** can participate in multiple **interactions**, each managed by an **agent**.
- **Customers** have associated **addresses** and **phone numbers**.

---

### Relational Mapping

![Relational Mapping](https://github.com/osama1hatem2abdelkreem3/customer-Management-/blob/main/pics/week%201/image%20(3).png)

In **Week 1**, we also created the relational model, mapping the ERD to a database schema. This step involved defining the structure for each table and specifying primary and foreign key relationships.

Key elements in the relational model:
- The **Customer** table includes attributes such as `customer_id`, `first_name`, `last_name`, `email`, `phone`, and others.
- The **Transaction** table has a foreign key linking to the **Customer** table (`customer_id`).
- The **Interaction** table links to both the **Customer** and **Agent** tables using foreign keys (`customer_id` and `agent_id`).
- The **Agent** table stores information about agents managing customer interactions.

Each table has been carefully designed to ensure data integrity and support efficient queries for transaction history, customer interaction tracking, and more.

---

## Week 2: Data Integration and Transformation

### Task 1: Data Integration

![Data Flow Diagram](https://github.com/osama1hatem2abdelkreem3/customer-Management-/blob/main/pics/week2/Screenshot%20(78).png)

![](https://github.com/osama1hatem2abdelkreem3/customer-Management-/blob/main/pics/week2/Screenshot%20(77).png)

In **Week 2**, we worked on integrating data from various sources into a centralized system for easier analysis and reporting.

The key steps included:
- **Extracting** data from multiple systems (e.g., CRM, Transaction databases).
- **Transforming** the data into a unified format, ensuring consistency and accuracy.
- **Loading** the data into a data warehouse or database for efficient querying.

The **Data Flow Diagram (DFD)** below illustrates the movement of data through the system and the interaction between various components.

Key components in the data flow:
- Data is extracted from the **Customer**, **Transaction**, and **Interaction** systems.
- Data is processed and transformed to ensure it meets business requirements before being loaded into the central **Data Warehouse**.
- Various tools like **ETL** (Extract, Transform, Load) processes are used to ensure smooth data integration.

---

## Week 3: Predictive Analysis and Azure Integration
![Data Analysis with python](https://github.com/osama1hatem2abdelkreem3/customer-Management-/blob/main/pics/week%203/WhatsApp%20Image%202024-10-22%20at%206.27.48%20PM.jpeg)

![](https://github.com/osama1hatem2abdelkreem3/customer-Management-/blob/main/pics/week%203/WhatsApp%20Image%202024-10-22%20at%206.26.22%20PM.jpeg)

![*ML_flow*](https://github.com/osama1hatem2abdelkreem3/customer-Management-/blob/main/pics/week%203/WhatsApp%20Image%202024-10-22%20at%206.26.06%20PM.jpeg)

![](https://github.com/osama1hatem2abdelkreem3/customer-Management-/blob/main/pics/week%203/WhatsApp%20Image%202024-10-22%20at%205.06.16%20PM.jpeg)

Details for **Week 3** tasks will include:
- Performing predictive analysis based on the data integrated in Week 2.
- Leveraging **ML Flow** services to manage our pridiction modules .

---

## Week 4: Final Integration and Reporting

![Azure Data Flow](https://github.com/osama1hatem2abdelkreem3/customer-Management-/blob/main/pics/week%204/DataFlow.png)

![Azure pipeline](https://github.com/osama1hatem2abdelkreem3/customer-Management-/blob/main/pics/week%204/Pipline.png)

![](https://github.com/osama1hatem2abdelkreem3/customer-Management-/blob/main/pics/week%204/DATA.png)

![Lake Database](https://github.com/osama1hatem2abdelkreem3/customer-Management-/blob/main/pics/week%204/DATA.png)

![Pipeline Run](https://github.com/osama1hatem2abdelkreem3/customer-Management-/blob/main/pics/week%204/DATA.png)

In **Week 4**, the focus will shift to:
- **Integrating** the predictive models and data pipelines.
- **Building reporting tools** to visualize key business metrics, using **Power BI** or similar tools.
- Finalizing the **system architecture** and ensuring data integrity for ongoing reporting.

---

## Conclusion

The project will involve multiple stages of data management, integration, and analysis, ultimately creating a comprehensive data system that supports reporting, predictive analysis, and customer insights. The first two weeks have set a solid foundation for the overall design and integration of data sources.
