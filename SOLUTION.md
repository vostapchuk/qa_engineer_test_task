# Solution Vadym Ostapchuk 

Project: https://github.com/vostapchuk/qa_engineer_test_task.git

Task 2
==================
1. Write user story for Customer contact add according to Agile best practice

### User Story

As a manager/Company manager I want to create new customer contact, 
so that I can click Add contact button and fill out New contact form.

**Acceptance criteria**

* access to create new contact
* fill New contact record details
* add a few Email addresses and Phone numbers specifying them with following 
different types
* save New contact record details

2. Write 2 use cases for Customer contact add according to Agile best practice

|Create a contact|
|------------|
|**Brief description:** The actor create customer contact|
|**Actors:** manager, Company manager|
|**Pre-conditions:** The actor is registered as manager or Company manager|
|**Basic flow or events**|
|1. After the actor click **Add contact** button the **New contact** form is available|
|2. The actor fill out all required fields.|
|3. When the actor click button **email** under **Email 1** field or **phone** under **Phone 1** field new email field or phone field is available.|
|4. When the actor click **Submit** button system save new contact and new contact is available in contact list|
|5. When the actor click **Close** button system close **New contact** form without save|
|**Extensions**|
|2a. The actor doesn't fill out all required fields. The system informs the actor|
|2b. The actor enter invalid data in fields. The system informs the actor|

|Delete a contact|
|-------------|
|**Brief description:** The actor delete customer contact|
|**Actors:** manager, Company manager|
|**Pre-conditions:** The actor is registered as manager or Company manager|
|**Basic flow or events**|
|1. After the actor click the Delete button the system displays the pop-up window Delete contact information.|
|2. When the actor click the Confirm button the system delete contact.|
|3. When the actor click the Cancel button the system doesn’t delete contact|

3. Write 3 requirements for Customer contact add

* The fields Email, Phone and Name are required.
* The field Phone should contain only numbers.
* The field Email should contain "@" symbol.
* The field Name should contain only chars.
* The field Zip code should contain only numbers.

Bug report: https://github.com/vostapchuk/qa_engineer_test_task/issues
