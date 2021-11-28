 # README

 > **NAME**

                           MySQL Workbench Tutorial: What is, How to Install & Use
 > **DESCRIPTION**
 {
   MySQL supports multiple storage engines each with its own specifications while other systems like SQL server only support a single storage engine. In order to appreciate this statement, let’s look at two of the storage engines supported by MySQL.
     InnoDB: – its default storage engine provided with MySQL as of version 5.5. InnoDB supports foreign keys for referential integrity and also supports ACID-standard transactions.
     MyISAM: – it was the default storage engine for MySQL prior to version 5.5. MyISAM lacks support for transactions. Its advantages over InnoDB include simplicity and high performance.
	 MySQL has high performance compared to other relation database systems. This is due to its simplicity in design and support for multiple-storage engines.
Cost effective, it’s relatively cheaper in terms of cost when compared to other relational databases. In fact, the community edition is free. The commercial edition has a licensing fee which is also cost effective compared to licensing fees for products such as Microsoft SQL Server.
Cross platform – MySQL works on many platforms which means it can be deployed on most machines. Other systems such as MS SQL Server only run on the windows platform.


[Reference](https://www.guru99.com/introduction-to-mysql-workbench.html?fbclid=IwAR3o9I8efS7FIb3GemyHxnNeI-91U2OFWMWxmrnzL4vZkU1-I34UYcMWlNs)


> **VISUAL**
  
![DATABASE](https://www.guru99.com/images/mysql_workbench_administration.png)


![DATABASE](https://www.guru99.com/images/workbench-instance-1.png)

![DATABASE](https://www.guru99.com/images/workbench-instance-2.png)

![DATABASE](https://www.guru99.com/images/mysql_work_bench_home.png)


)

> **INSTALLATION**



{

    Step 1: Install MySQL Community Server

    

}

{

    Step 2:  Install MySQL workbench – You can install the workbench using a zip file or an msi installer (recommended)

    Note: You will require Administrator or Power User Privileges to perform installation.

}
 > **SET UP**
{

    
    1.  Open Home Window
    First step is launching the Workbench MySQL. What you see is called Home Window
    

}

{

    2. Open New Connection Wizard
    Next you need to create your MySQL Server Connection which contains details about target database server including how to connect to it. Click ” + “ in MySQL Workbench Home Window. This will open Setup New Connection. Wizard

}

{

    3. Click Configure Server Management button
    As a beginner you can create a connection for a locally installed server. Click Configure Server Management button in Setup New Connection window to check the cofiguration of the MySQL server.

}

{


     4. Click Next button to continue
     A new window opens named Configure Local Management. Click Next button to continue.

}

{

    5. Enter your password and press OK
     Next the Wizard will test connections to database. If test fails, go back and correct database connection parameters.5. Next it will open a pop up window asking your root password to test your connection with the local mysql server instance. The password is the one you set during installation of MySQL Workbench. Enter your password and press OK

}

{

     6.  Click Next to continue
        Next the Wizard will test connections to database. If test fails, go back and correct database connection parameters. Else if all tests are sucessful click Next to continue.

}

{


    7.  Click Next
       After that a new wizard will open about Local Service Management – It lets you switch between multiple mysql severs installed on one machines. As a beginner you can bypass this and click Next to continue.
  
}

    8. Select MySQL Server Configuration File
    The Wizard will then check ability to access MySQL Server Configuration File, and test start/stop commands.
{
    
    9.  Click Finish to finsh server cofiguration
    Next you can review current configurations. After reviewing the configurations, Click Finish to finsh server cofiguration.


}
{


    10. Click on Test Connection
       Next Step is to setup a connection, which can be used to connect to server. If you have not created a connection already, you can use the default values given. Click on Test Connection [ 2 ] after entering the Connection Name [ 1 ].



}
{


     11. Click OK
      A new dialog box will open asking you password to root/selected user. If your MySQL root user has a password, you can enter that using Store in Vault feature. Click OK.

     If the entered password for the user is correct then the following screen will show. Click on both OK buttons and you will be good to go.
     
     A new instance is shown in the homepage.
}

    


    

> **AUTHOR**

Author Name: Quiem Ayessa Madarcos




![DATABASE](https://scontent.fceb2-2.fna.fbcdn.net/v/t1.18169-9/13567353_717427348399696_2224221166802173146_n.jpg?_nc_cat=110&ccb=1-5&_nc_sid=8bfeb9&_nc_eui2=AeHIble05UHNfUFgIDEJmiPiB_IhGFjdtVcH8iEYWN21VwWWppkUbnWJwKxdDoCKIuSecZXBP6g-hAulGMzrHz0b&_nc_ohc=1EGhgYKCw7YAX8CpZDn&_nc_ht=scontent.fceb2-2.fna&oh=07ff50a78c1df567a0d90896c4a2c5b0&oe=61C9EA7E)


