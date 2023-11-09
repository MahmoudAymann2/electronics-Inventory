
<center><img src="source/logo.png"></center>

# <center> Electronics Inventory Database Project <center>

## <center> CNC-314 Database Systems Project - Group Members </center>

<div align="center">

|NAME | ID | E-MAIL | MAJOR | SECTION |
|:-----:|:----:|:--------:|:-------:|:---------:|
|Hazem Mohamed Ibrahim|320210159|hazem.mohamed@ejust.edu.eg|AID|3|
|Yousef Ibrahim Gomaa Mahmoud|320210207|yousef.gomaa@ejust.edu.eg|AID|3
|Seif Eldin Ahmed Diaa|320210163|seifeldin.zakaria@ejust.edu.eg|AID|3
|Mahmoud Ayman El Shaarawy|320210152|Mahmoud.ayman@ejust.edu.eg|AID|3
|Mohamed Ibrahim Mohamed Eldagla|320210177|mohamed.eldagla@ejust.edu.eg|AID|3
|Mohamed Ashraf Mohamed Selima|320210135|mohamed.selima@ejust.edu.eg|AID|2

</div>

## Table of Contents:
- [ Electronics Inventory Database Project ](#-electronics-inventory-database-project-)
  - [ CNC-314 Database Systems Project - Group Members ](#-cnc-314-database-systems-project---group-members-)
  - [Table of Contents:](#table-of-contents)
  - [Business Requirements Specification (BRS) ](#business-requirements-specification-brs-)
    - [1. Introduction:](#1-introduction)
    - [2. Scope:](#2-scope)
    - [3. Functional Requirements:](#3-functional-requirements)
      - [3.1 Product Management:](#31-product-management)
      - [3.2 Manufacturer Management:](#32-manufacturer-management)
      - [3.3 Order Management:](#33-order-management)
      - [3.4 Customer Management:](#34-customer-management)
      - [3.5 Reporting and Analytics:](#35-reporting-and-analytics)
    - [4. Non-Functional Requirements:](#4-non-functional-requirements)
    - [5. Constraints:](#5-constraints)
    - [6. Assumptions:](#6-assumptions)
  - [System Operational Concept (OpsCon) ](#system-operational-concept-opscon-)
    - [1. User Roles:](#1-user-roles)
    - [2. System Components:](#2-system-components)
    - [3. System Workflow:](#3-system-workflow)
    - [4. System Integration:](#4-system-integration)
    - [5. Security and Maintenance:](#5-security-and-maintenance)
  - [Stakeholder Requirements Specification (StRS) ](#stakeholder-requirements-specification-strs-)
    - [Stakeholders:](#stakeholders)
    - [1. Stakeholder Requirements](#1-stakeholder-requirements)
      - [Store Managers](#store-managers)
      - [Sales Staff](#sales-staff)
      - [Warehouse Workers](#warehouse-workers)
      - [Accounting Personnel](#accounting-personnel)
      - [Executives](#executives)
    - [2. Prioritized Requirements](#2-prioritized-requirements)
  - [System Requirements Specification (SyRS) ](#system-requirements-specification-syrs-)
    - [1. Introduction](#1-introduction-1)
    - [2. Functional Requirements](#2-functional-requirements)
    - [3. Non-Functional Requirements](#3-non-functional-requirements)
    - [4. Use Cases](#4-use-cases)
    - [4. Acceptance Criteria](#4-acceptance-criteria)
  - [Diagrams](#diagrams)
    - [Level 0 - Context Diagram (CD)](#level-0---context-diagram-cd)
    - [Level 1 - Data Flow Diagram (DFD)](#level-1---data-flow-diagram-dfd)

<div style="page-break-after: always;"></div>

## Business Requirements Specification (BRS) <a name="BRS"></a>
<b> Assigned: </b> Seif Diaa

### 1. Introduction:
The purpose of this project is to develop a comprehensive inventory management system for an authorized distributor in the electronics industry. The system will enable efficient tracking and management of inventory, including products, stock levels, and related information. The database will store relevant data about products, manufacturers, orders, and customers, facilitating streamlined inventory operations.

### 2. Scope:
<b> The database system will cover the following functionalities: </b>
- Product Management: The system should store detailed information about the products in the inventory, including their specifications, pricing, stock levels, and availability.
- Manufacturer Management: The system should maintain a database of manufacturers, including their contact details, product catalog, and any relevant agreements or contracts.
- Order Management: The system should support order processing, tracking, and fulfillment. It should capture order details, including order date, products ordered, quantities, delivery addresses, and order status.
- Customer Management: The system should store information about customers, including their contact details, order history, and any specific requirements or preferences.
- Reporting and Analytics: The system should provide reporting capabilities to generate inventory reports, sales reports, order history, and other relevant analytics.

### 3. Functional Requirements:
#### 3.1 Product Management:
- The system should allow the distributor to add new products to the inventory, including their specifications, pricing, and stock levels.
- The system should provide the ability to update and delete existing product information.
- The system should track the current stock levels of each product and provide notifications when stock levels fall below a predefined threshold.
- The system should support categorization and searching of products based on various attributes such as brand, category, and features.

#### 3.2 Manufacturer Management:
- The system should allow the distributor to maintain a database of manufacturers, including their contact information, product catalog, and any relevant agreements or contracts.
- The system should provide the ability to add, update, and delete manufacturer records.
- The system should support searching and filtering of manufacturers based on various criteria such as location, product category, and business relationship.

#### 3.3 Order Management:
- The system should enable the distributor to process and track orders from customers.
- The system should capture order details, including order date, products ordered, quantities, delivery addresses, and order status.
- The system should support order fulfillment, including picking, packing, and shipping operations.
- The system should provide reporting capabilities to generate order history, track order status, and analyze order-related data.

#### 3.4 Customer Management:
- The system should maintain a database of customers, including their contact details, order history, and any specific requirements or preferences.
- The system should allow the distributor to add, update, and delete customer records.
- The system should support searching and filtering of customers based on various criteria such as location, order history, and customer preferences.

#### 3.5 Reporting and Analytics:
- The system should provide reporting capabilities to generate inventory reports, sales reports, order history, and other relevant analytics.
- The system should support data visualization and graphical representations of inventory and sales data.
- The system should allow users to customize and generate ad-hoc reports based on specific criteria and parameters.

### 4. Non-Functional Requirements:
- The system should be scalable to handle a large volume of products, manufacturers, orders, and customers.
- The system should have robust security measures to protect sensitive data, such as customer information and order details.
- The system should have a user-friendly interface for easy navigation and efficient data entry.
- The system should be highly available and reliable, minimizing downtime and data loss.
- The system should be easily maintainable and support regular backups and system updates.

### 5. Constraints:
- The system should comply with any relevant industry regulations and standards.
- The system should be compatible with commonly used web browsers and operating systems.
- The project should be completed within the allocated budget and timeline.

### 6. Assumptions:
- The authorized distributor has an existing inventory management system and wants to upgrade it.
- The distributor has a team responsible for managing the database and related operations.
- The distributor has access to necessary data from manufacturers and customers.
<div style="page-break-after: always;"></div>

## System Operational Concept (OpsCon) <a name="OpsCon"></a>
<b> Assigned: </b> Seif Diaa

<p> The system operational concept outlines how the proposed electronics inventory database system will function and interact with different users and components. It describes the core operations and interactions within the system to provide a comprehensive understanding of its functionality. The following is a high-level overview of the system operational concept: </p>

### 1. User Roles:
<b> The system will support different user roles with varying levels of access and privileges. The key user roles include: </b>
- Distributor: Responsible for managing the inventory, manufacturers, orders, and customers.
- Manufacturers: Provide product information, catalog, and updates to the distributor.
- Customers: Browse products, place orders, and track order status through the distributor's website.

### 2. System Components:
<b> The system will consist of the following main components: </b>
- Database: Stores and manages all data related to products, manufacturers, orders, and customers.
- Website Integration: Provides a user-friendly interface for customers to browse products, place orders, and track their order status.
- Reporting and Analytics: Generates various reports, including inventory reports, sales reports, and order history, to support decision-making and analysis.

### 3. System Workflow:
<b> The operational workflow of the system can be summarized as follows: </b>
- Product Management: The distributor adds new products to the inventory database, including specifications, pricing, and stock levels. They can update or delete existing product information as needed. The system tracks stock levels and sends notifications when inventory falls below a predefined threshold.
- Manufacturer Management: The distributor maintains a database of manufacturers, including their contact information and product catalog. Manufacturers provide updates to the distributor regarding product changes, availability, and other relevant information.
- Order Management: Customers place orders through the distributor's website. The system captures order details, including products ordered, quantities, delivery addresses, and order status. The distributor processes the orders, including picking, packing, and shipping operations. The system generates order confirmations and invoices. Customers can track their order status through the website.
- Customer Management: The distributor maintains a customer database, including contact details, order history, and preferences. They can add, update, or delete customer records as needed. The system allows searching and filtering of customer information based on various criteria.
- Reporting and Analytics: The system provides reporting capabilities to generate inventory reports, sales reports, and order history. Users can customize reports based on specific criteria and parameters. Data visualization and graphical representations help analyze inventory and sales data.

### 4. System Integration:
The system integrates with the distributor's website seamlessly. The website provides customers with a user-friendly interface to browse products, view details, place orders, and track order status. The system synchronizes product information, stock levels, and order data between the database and the website in real-time.

### 5. Security and Maintenance:
The system implements robust security measures to protect sensitive data, ensuring customer information and order details are securely stored and transmitted. Regular maintenance activities, including backups and system updates, are performed to ensure system availability, reliability, and data integrity.
<div style="page-break-after: always;"></div>

## Stakeholder Requirements Specification (StRS) <a name="StRS"></a>
<b> Assigned: </b> Mohamed Ashraf

### Stakeholders:
<b> The following are the stakeholders for the electronics inventory management system: </b>
- Store managers
- Sales staff
- Warehouse workers
- Accounting personnel
- Executives

### 1. Stakeholder Requirements
#### Store Managers
- Track inventory levels in real time, both at the store level and across all stores.
- Manage orders, including creating new orders, tracking order status, and receiving orders.
- Generate reports on sales, inventory, and other metrics.
- Set alerts for low inventory levels and other important events.

#### Sales Staff
- Access inventory information in real time, including product availability, pricing, and product specifications.
- Create and manage customer orders.
- Track the status of customer orders and notify customers of any changes.
- Generate reports on customer orders and sales.

#### Warehouse Workers
- Manage incoming and outgoing shipments, including receiving shipments, putaway, picking, and packing.
- Track inventory levels in real time.
- Generate reports on inventory levels, shipments, and picking and packing activity.

#### Accounting Personnel
- Track inventory costs and generate financial reports.
- Reconcile inventory records with financial records.
- Generate reports on inventory shrinkage and other financial losses.

#### Executives
- Track the overall performance of the business, including inventory levels, sales, and profitability.
- Drill down into specific areas of the business to identify areas for improvement.
- Generate reports on the business performance and trends.

### 2. Prioritized Requirements
<b> The following are the highest priority requirements for the electronics inventory management system: </b>
- The system must be able to track inventory levels in real time, with an accuracy of at least 99%.
- The system must be able to process orders within 24 hours of receipt.
- The system must be able to generate reports within 1 hour of request.
- The system must be able to support 100 concurrent users.
<div style="page-break-after: always;"></div>

## System Requirements Specification (SyRS) <a name="SyRS"></a>
<b> Assigned: </b> Mohamed Ashraf

### 1. Introduction

<p> This System Requirements Specification (SyRS) describes the functional and non-functional requirements of an electronics inventory management system. The system will be used by store managers, sales staff, warehouse workers, accounting personnel, and executives to track inventory levels, manage orders, generate reports, and make informed decisions about the business.

### 2. Functional Requirements

<b> It must have the following functionality: </b>

- Track inventory levels in real time, both at the store level and across all stores.
- Manage orders, including creating new orders, tracking order status, and receiving orders.
- Generate reports on sales, inventory, and other metrics.
- Set alerts for low inventory levels and other important events.
- Allow sales staff to access inventory information in real time, including product availability, pricing, and product specifications.
- Allow sales staff to create and manage customer orders, and track the status of customer orders and notify customers of any changes.
- Allow sales staff to generate reports on customer orders and sales.
- Allow warehouse workers to manage incoming and outgoing shipments, including receiving shipments, putaway, picking, and packing.
Track inventory levels in real time for warehouse workers.
- Allow warehouse workers to generate reports on inventory levels, shipments, and picking and packing activity.
- Track inventory costs and generate financial reports for accounting personnel.
Reconcile inventory records with financial records for accounting personnel.
- Generate reports on inventory shrinkage and other financial losses for accounting personnel.
- Track the overall performance of the business, including inventory levels, sales, and profitability for executives.
- Allow executives to drill down into specific areas of the business to identify areas for improvement.
- Generate reports on the business performance and trends for executives.

### 3. Non-Functional Requirements

<b> The Non-functional Requirements: </b>

- The system must be able to track inventory levels in real time, with an accuracy of at least 99%.
- The system must be able to process orders within 24 hours of receipt.
- The system must be able to generate reports within 1 hour of request.
- The system must be able to support 100 concurrent users.
- The system must be secure and protect sensitive data, such as customer information and inventory costs.
- The system must be scalable to handle growth in the business.
- The system must be easy to use for all stakeholders, including store managers, sales staff, warehouse workers, accounting personnel, and executives.

### 4. Use Cases

- A store manager creates a new order for products that are running low in stock.
- A salesperson checks the inventory levels for a product before quoting a price to a customer.
- A warehouse worker receives a shipment of new products and scans them into the system.
- An accounting personnel generates a report on inventory costs at the end of the month.
- An executive reviews a report on the overall performance of the business.

### 4. Acceptance Criteria

<b> The electronics inventory management system must meet the following acceptance criteria: </b>

- The system must be able to track inventory levels in real time, with an accuracy of at least 99%.
- The system must be able to process orders within 24 hours of receipt.
- The system must be able to generate reports within 1 hour of request.
- The system must be able to support 100 concurrent users.
- The system must be able to integrate with the point-of-sale system and the accounting system.

## Diagrams
### Level 0 - Context Diagram (CD)
<b> Assigned: </b> Mohamed Eldagla
![Context Diagram - Level 0](<diagrams/Context Diagram.jpg>)

### Level 1 - Data Flow Diagram (DFD)
<b> Assigned: </b> Hazem Mohamed
![Data Flow Diagram - Level 1](diagrams/DFD1.jpeg)
<!-- <object data="diagrams/DFD Level 1.pdf" type="application/pdf" width="700px" height="700px"> </object> -->