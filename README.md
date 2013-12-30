qAPI_
=====

So you would like to automate your vulnerability management lifecycle?  Good luck.  But if you are motivated hopefully this little bit of powershell will help.  Here are the prereqs:

- Must have powershell v3

- Must user Qualys for vulnerability scanning.

- For added functionality an additional cmdlet has been included to generate tickets with an external ticketing system via email (this format requires Computer Associates Service Desk, but if your's takes an email as input it should just be a formatting change, also if you do set this up submit a pull request to the github project and I will include another cmdlet for your ticketing system)

Once these are met it is quite simple to get up and rolling with this module.  Clone the repo from git and then import the module into your powershell environment.  Once done you will have the following cmdlets at your disposal:

- Create-qTicket

- Get-qAPI

- List-qTickets

- Set-qTickets

- Delete-qTickets

These are relatively self explanatory and they are pipeable as well.  Before you are able to use the all the functions you will have to setup a couple variables to match your own environment.  These are listed in the header of the module under defaults or explicitly mentioned in the comments.  There are examples in the help of the cmdlets.  If you have any feedback feel free to leave a comment or issue a pull request if you would like to make an improvement. 
