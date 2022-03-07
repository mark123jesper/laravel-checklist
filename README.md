# Markdown for Laravel Checklist

## All refresher tasks for Laravel Framework are as follows.

### Laravel Fundamentals
- [x] Routes
- [x] Controllers
- [x] Views
- [x] Blade Templating Engine ```(optional)```
- [x] Database Migration
- [x] Raw SQL Querying
- [x] Eloquent ORM Querying
- [x] Eloquent ORM Relationships
- [x] Tinker for cli testing ```optional```
### Database Eloquent Relationships - CRUD
- [x] One to One Relationship
- [x] One to Many Relationship
- [x] Many to Many Relationship
> Needs a pivot table migration with foreign keys of each id
- [x] Many to Many (Through) 
> Commonly used for data query where two models/tables are not entirely related and are only in relation with another model/table
- [x] Polymorphic One to Many Relationship
> Commonly used for a morphed model that has relations to many tables/models. With `-able` suffix followed by Class(type) and id(per class) 
- [x] Polymorphic Many to Many Relationship
> best example: User model can relate to Comment model and Post model by polymorphic relation of Likeable(Like migration) so we can Like both Comments and Post dynamically
### Blade Templating ```Optional```
- [ ] Forms - Validations
- [ ] Forms - File Upload
- [ ] Forms - Simple Login Page
### Security
- [x] middleware
- [x] Sessions ```unable to commit the progress along middleware project. sad.```
- [x] Sanctum + Fortify Authentication ```session based with fortify features and minor token-based login/logout```
### Miscellaneous
- [x] Sending Email API ```Used mailtrap for email testing tool and mailgun for email service provider```
- [ ] Sending SMS API ```optional but recommended```
### ...and more. Checklist will be updated if see fit.
