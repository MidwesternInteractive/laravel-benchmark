# Laravel Benchmark
Build a simple User Auth with relationships to organizations of which have multiple locations. 
The following actions should be available once registered/logged in.

Utilize `laravel/ui` and `php artisan ui vue —auth`  for bootstrapping auth.

### Tasks
- Fork this repository and build off of it
- Update User Account
    - Name
    - Email
    - Password
    - Select Organizations
- Organization CRUD: id, name, timestamps
    - Many to Many Users
    - One to Many Locations
- Location CRUD from within organization, organizations.edit: id, street, city, state, zip, timestamps
- Bonus: Use seeds/factories to populate the db with all models/relationships.

### Notes
- Don’t spend more than 4 hours.
- Only use plain bootstrap classes for simplicity.
- Not too concerned with look/design. 
    - Reference screen shots in this repo

### Please use the following tools
- Laravel [Authentication - Laravel - The PHP Framework For Web Artisans](https://laravel.com/docs/6.x/authentication)
- Mix/Webpack
- Bootstrap
- MySQL|MariaDB|PostgreSQL