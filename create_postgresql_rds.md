## Create a PostgreSQL DB Instance using RDS

1. Go to the Amazon RDS console and click on Databases on the left navigation pane. Choose what region you'd like to create this database in on the right of the top menu bar.
2. Click on the Create Database button.
<div>
<img src="img/postgres1.png">
</div>
3. Select PostgreSQL on the Select Engine page.
<div>
<img src="img/postgres2.png">
</div>
4. Since this is for demonstration purposes, select Dev/Test under Use case.
<div>
<img src="img/postgres3.png">
</div>
5. Next, is a long Specify DB details page. You can leave the default values (shown below) for most of these settings. Just make the following choices:
For DB instance class, select `db.t2.small`
<div>
<img src="img/postgres4.png">
</div>
* For DB instance identifier, enter `postgreSQL-test` or another name of your choice
* Enter a master username and password
<div>
<img src="img/postgres5.png">
</div>
* Leave the default values for the next few sections.
<div>
<img src="img/postgres6.png">
</div>
<div>
<img src="img/postgres7.png">
</div>
* In the Backup section and select `1 day` since this is for demonstration purposes.
<div>
<img src="img/postgres8.png">
</div>
* Leave the default values for the rest and click on Create database on the bottom right.
<div>
<img src="img/postgres9.png">
</div>
You should land on a confirmation page.
<div>
<img src="img/postgres10.png">
</div>
6. Click Databases on the left navigation pane to return to your list of databases. You should see your newly created database with the status Creating.
<div>
<img src="img/postgres11.png">
</div>
7. Wait a few minutes for this to change to the status Available.
<div>
<img src="img/postgres12.png">
</div>
