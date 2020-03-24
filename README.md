# Test Assignment

## 1. Make A Choice 
You can either use *Symfony* as framework or cook your own solution.

## 2. Install Prerequisites
The application needs to use an *SQLite database*, on Linux you can install the necessary tools using *apt*:
```
apt install sqlite3
apt install php-sqlite
```

You also have to make use of *Composer*:
```
apt install composer
```

## 3. Setup Database
If you use Symfony this means setting up *Entities*, *Repositories* and *Migrations".
If you cook your own solution this means creating one or more OOP classes that represent the data and setting up the database. 

The database needs to store the following information per record:
- Date: date/time the record was created
- Infections: amount of currently infected persons
- Fatalities: amount of people that died from it
- Fatality rate: how often it leads to death (fatalities / infections)

## 4. Setup Backend & Frontend
Your backend needs to be controlled through a webinterface and fullfil these functional requirements:
- a new record can be created
- an existing record can be deleted
- all existing records can be viewed (just a simple table, nothing fancy)

You can use Twig for the frontend or pure HTML/CSS/JavaScript, the choice is yours.

# Deliverables
Either a Symfony project with all required files, or the folder of your application in a zip/tar/rar compressed file.

