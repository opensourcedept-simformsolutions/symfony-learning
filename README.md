# Basic Practice

## Modules
1. Country
2. City

### Country
Create CRUD for country.

Database fields are:
  - id
  - name
  - createdAt (datetime)
  - updatedAt (datetime)

### City
Create CRUD layout for City. Require to implement Listing, Add, Edit and Delete action.

Database fields are:
  - id  (primary)
  - name   (string, not null)
  - country_id (foreign key of country, not null)
  - active (boolean, by default true)
  - isDeleted (boolean, by default false)
  - createdAt (datetime)
  - updatedAt (datetime)

###### Listing page should like this:

ID | Name    | Country          | Status     | Action
--- |--------|------------------|------------| ----------
1 | Ahmedabad | India            | Active     | Edit Delete 
2 | Surat     | India | Not Active | Edit Delete 

* Search by Name should have like query. And user can search by status dropdown too.
* Search by Country dropdown
* In form, Name field must be required with server side validation
* Only display isDeleted = false records in listing page.


