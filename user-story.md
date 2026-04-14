---
name: User Story
about: Create a user story
title: ''
labels: ''
assignees: ''
---

As a user  
I need to manage accounts in the service  
So that I can create, read, update, and delete customer accounts  

### Acceptance Criteria:

```gherkin
Given a user wants to create an account
When valid account details are entered
Then the account should be created successfully

Given a user wants to retrieve an account
When a valid account ID is provided
Then the account details should be displayed

Given a user wants to update an account
When updated account details are submitted
Then the account should be updated successfully

Given a user wants to delete an account
When a valid account ID is selected
Then the account should be deleted successfully
