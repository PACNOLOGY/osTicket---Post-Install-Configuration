# osTicket---Post-Install-Configuration
osTicket - Post-Install Configuration
osTicket logo

# osTicket
## Post-Install Configuration
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.
### Environments and Technologies Used
Microsoft Azure (Virtual Machines/Compute)
Remote Desktop
Internet Information Services (IIS)
### Operating Systems Used
Windows 10 (21H2)
Post-Install Configuration Objectives


### Now that we have successfully installed osTicket,
now we have to make accounts for our staff.  FYI, and I recommend this as well, I enabled the "home" button in "edge browser" and set the osTicket login page to home. 
   <img src=https://i.imgur.com/mh9vzbs.png>
  
  We will have agents, as well as their teams.  We will also be setting the application up for customers in this tutorial.[IMAGE]

  Start by clicking where it says "Admin Panel".  We will be doing our configuring from here. 
  <img src=https://i.imgur.com/ripaPY9.png>
  
  From the roles screen, we will click "Add New Role", and make a Supreme Admin role.
  <img src=https://i.imgur.com/U4o9RXY.png>
  
  We will enable all permissions for this role.  Agents assigned this role will be given full run of the system, usually Managers or General Managers
  <img src=https://i.imgur.com/Er1PsU7.png>
  
  We will make a new department.  In this case I'll name it "System Admin"
  <img src=https://i.imgur.com/gc08jYK.png>
  
  Now we are going to make a team name for what we've made so far.  This way, we can give the team any level of Roles we choose, and we can select agents to be in said teams.  This will create a situation where there is less work involved in putting new hires in our system.  We will call this "Level II Support".  I'm adding myself to the team and making myself leader.
  
  Now we are going to enable the software to allow any user to create tickets, whether they are in the system or not.  This will allow for an operation in which a customer can create and submit a ticket for their products, and we can recieve, delegate, and respond accordingly.  Upon inspection, it seems "Require registration and login to create tickets" was already unchecked.  This is what we want to achieve this end.
  <img src=https://i.imgur.com/zzVzZ6c.png>
 
  
  now we return to the dashboard, then we click agents, then we're going to "add new agent".  This is where we have the new hires give us their contact information.  We can set passwords for them here as well.  for the sake of demonstration, everyone is Password1
  
  You can see here "Don Joe" is being given responsibility for 2 departments.  As Supreme Admin, I was able to assign these issues to different departments, both of which he is head of, and the application auto notifies him as it's his responsibility now.
  <img src=https://i.imgur.com/JwFvWB1.png>
  
  <img src=https://i.imgur.com/ZOdaoIn.png>
  
  We go back to the "Agent Panel" and now, as support agents, we have a tab, "users".  Go there.  Make some new users.  They'll all be registered as guests, and they can reach your support team through osTicket now so long as they register with your system.  If not, you can create tickets on their behalf.  Potentially best use as a receptionist or some type of front counter role.
  
  <img src=https://i.imgur.com/OXVbZbf.png>
  
  ## CONFIGURING SLA 
  ### (urgencies for tickets)
  Service Level Agreement (SLA).  We will make selectable SLAs for our tickets.  Go to "Admin Panel" then "manage", "SLA", "Add new SLA plan". The setup is pretty self-explanatory here.  Your users will be able to set urgency to their tickets.
  <img src=https://i.imgur.com/M8gQqUB.png>
  
  ## CONFIGURING HELP TOPICS
  ### (you'll be glad you did)
  There's really nothing to explain here.  You make help topics you can refer other users to for common issues, and managers or whoever has clearance to update can do so.  This is where daily reports become an important part of the job.
  <img src=https://i.imgur.com/23yp728.png>

Now that we've done all that, let's move on to the next section and try this new system out.
[osTicket: Ticket Lifecycle Examples(WIP)](https://github.com/PACNOLOGY/osTicket-Ticket-Lifecycle-Examples)
