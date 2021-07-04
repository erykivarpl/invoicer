# invoicer


The project is to be used to issue invoices, store customer and payment data.

I create this project to consolidate and expand knowledge and to publish that knowledge.

The assumption is to implement hexagonal architecture based on DDD:
- Communication between modules will take place only through the modules facades.
- In communication between modules, we can also use the DTO's and Exceptions classes.
  We do not share repositories or entities between modules.
- All facade methods will have tests written.

In code, this translates to 3 main directories
- Application
- Domain
- Infrastructure