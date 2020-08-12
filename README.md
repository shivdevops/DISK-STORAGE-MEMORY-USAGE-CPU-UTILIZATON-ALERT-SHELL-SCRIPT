# Disk Storage,Memory Used and CPU Utilization Alert Shell Script through Mail .

  * Download the script.
  * Change the script permission to 777

    ` ` ` sudo chmod 777 alert.sh ` ` `   

  * Run the script with sudo.

    ` ` ` sudo ./alert.sh ` ` `  


  * Scripts actually calculates on percentage basis so the output will be  in percentage wise.

  * You can set the Disk Memory and CPU limit value by changing the default values according to your wish for mail alert in corresponding variables.


# Note: Limit value is nothing but minimum value where mail alert occurs when it exceeds the minimum value.
 
 * For Disk storage set the limit value in DLIMIT="your limit value"
 * For Memory limit  set the limit value in MLIMIT="your limit value"
 * For CPU limit set the limit value in CLIMIT="your limit value"

# Prerequisite:

  * Ubuntu OS
  * Mail Server
