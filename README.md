# HandsMen Threads — Salesforce Project

A Salesforce project focused on supporting retail operations for a fashion business through CRM data modelling, order and inventory workflows, and customer communications.

## Project Areas

Based on the included documentation, Apex trigger files, and screenshots, the project covers:

- **Custom data objects:** product, order, inventory, and related business records
- **Order total calculation:** an Apex trigger calculates an order total from product price and quantity before insert or update
- **Inventory updates:** a trigger reduces inventory quantities when an order is confirmed
- **Customer and product workflows:** screenshots document product creation, order creation, customer validation, and inventory management
- **Notifications and process flows:** supporting screenshots show low-stock alerts, loyalty updates, and order-confirmation flows/emails

## Technologies and Salesforce Concepts

- Salesforce platform
- Apex triggers
- Custom objects and fields
- Record automation and data relationships
- Order and inventory process design
- Email templates and workflow documentation

## Repository Contents

- `HandsMen Threads Project Docs.pdf` — project documentation
- `Source Code/Stock Reduction Trigger.txt` — Apex trigger for stock reduction on confirmed orders
- `Source Code/Update Order Total.txt` — Apex trigger for calculating order totals
- `Screenshots/` — screenshots of the UI, objects, inventory, order workflows, and email templates
- `Readme.md` — original project demo link

## Demo

[Watch the project demo](https://drive.google.com/file/d/1ftul1apugi_M1m-v9yGwsl_nwCor16Wu/view?usp=sharing)

## Important Implementation Notes

The trigger files are provided as source-code examples. Before using similar logic in a production org, test bulk orders, repeated updates, inventory edge cases, and transaction behaviour. In particular, inventory deductions should avoid subtracting stock repeatedly when an existing order is updated while it remains confirmed.

## Learning Outcomes

This project demonstrates how Salesforce automation can support common retail operations, connect related records, calculate order values, and help keep inventory data current.

## Author

Aditi Khare