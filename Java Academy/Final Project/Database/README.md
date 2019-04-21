The database was originally intended to be placed on x10hosting, a cloud host service for web domains.
Basically, our team wanted a live version of the website to be available for view without the need
to look at the files on GitHub.

I've had prior experience with x10hosting from my internship at Wilmington University so querying the
MySQL database on the backend wasn't too tricky since I had sample code to work with. The x10Hosting Database 
Access folder constinas the php scripts used to query the database. It's by no means complete. I spent most of my time on the project
making the Plot Four game networkable. I need to integrate prepared statements and look into password salt hashing
to protect users.

I exported the database in its current state as an .sql file and placed a .txt document containing
the queries required to join the tables between their primary and foreign keys. (I haven't figured out
how to get MySQL to export it with the keys intact.) Also, phpmyadmin has a nice feature called designer
view, which lets you drag and drop your tables around for a nice view of the schema. Most of these tables
haven't been implemented yet. They are there however, because our team spent the early part of the project
planning what kinds of features we'd like our product to have.