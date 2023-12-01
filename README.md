# Exercise 1 - Apex Triggers
Use Case
In the scenario above, the customer who wants the contacts can easily get in touch with the primary contact. In order to facilitate this, the Primary Contact Phone should be stored in all secondary contacts.

Requirements
1.  Create a custom field on the Contact object: Primary Contact Phone(Phone);

2.  Validation should be added so that if the Account already has a Primary Contact set a new one cannot be added;

3.  When contact is set as primary, the Primary Contact Phone should be updated to all Contacts related to the same account. This should be an asynchronous process. Make sure that if one Contact update fails, it doesn’t roll back the changes for the others.


![Error while duplicating primary contatc ](https://github.com/felipeportugalll/OSF-Exercises/assets/108902942/206f72a3-2d3d-4eb0-a775-8a42ab6e473a)
![Apex Trigger Exercise ERROR ](https://github.com/felipeportugalll/OSF-Exercises/assets/108902942/38824747-247b-4acb-894b-2c37d8a1df86)
[Apex trigger.webm](https://github.com/felipeportugalll/OSF-Exercises/assets/108902942/6a026cd9-a96b-4136-b58c-6b203a4d088d)
