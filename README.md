=w[p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial explains the journey of a ticket from submission to resolution within the open-source help desk system, osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- Windows App (macOS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)
- macOS Sonama 14.6.1

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>
1 http://localhost/osTicket/scp/login.php (Admin/Analyst Login Page)
  http://localhost/osTicket (End Users osTicket URL)
  Open up both of these links and sign into the Admin/Analyst Login Page.
<p>
<img <img width="1440" alt="TTL_1" src="https://github.com/user-attachments/assets/77c020bf-7241-463e-ada9-7e3dfc3f18cc" />
</p>
<p>
2 Go into the "Admin Panel"
<p>
<img <img width="1440" alt="TTL_2" src="https://github.com/user-attachments/assets/d0e3af9e-a6e4-440a-9e59-6d16efd8a47d" />
</p>
<p>
3 From there click the "Agents Tab".
<p>
<img <img width="1440" alt="TTL_3" src="https://github.com/user-attachments/assets/5c75f0b5-e14e-43ed-a402-a459d4ff3c61" />
</p>
<p>
4 Click "Departments"
<p>
<img <img width="1440" alt="TTL_4" src="https://github.com/user-attachments/assets/7f03db73-b4bd-4a13-b24a-34eea812b070" />
</p>
<p>
6 Check the box for Maintenance.
<p>
<img <img width="1440" alt="TTL_6" src="https://github.com/user-attachments/assets/479924b0-32ef-4a07-acf4-7a368fc8b7ba" />
</p>
<p>
7 On the right click the drop down arrow next to more and then "delete".
<p>
<img <img width="1440" alt="TTL_7" src="https://github.com/user-attachments/assets/f37f3f9a-2e4c-482f-9360-5296b58ec4b4" />
</p>
<p>
8 With the maintenance department deleted your created tickets will go to the correct departments. 
  Now click Support / SysAdmins
<p>
<img <img width="1440" alt="TTL_8" src="https://github.com/user-attachments/assets/a8546eb1-255a-47a8-9deb-75153a0c25f5" />
</p>
<p>
9 Now set the parent to Top level Department.
<p>
<img <img width="1440" alt="TTL_9" src="https://github.com/user-attachments/assets/2237b5b4-f765-4dd9-9020-61d62daacadd" />
</p>
<p>
10 Scroll down and Save changes. 
<p>
<img <img width="1440" alt="TTL_10" src="https://github.com/user-attachments/assets/cfd1482e-10b6-49ea-ac8a-0e8d381f4306" />
</p>
<p>
11 On another webpage go to the End user link.
<p>
<img <img width="1440" alt="TTL_11" src="https://github.com/user-attachments/assets/7f551a61-d95b-4c1c-bf32-df67305aaa37" />
</p>
<p>
13  Under "Open a New Ticket"
    Now fill out the form as seen below with the email address and name of a client that you created earlier. 
<p>
<img <img width="1440" alt="TTL_13" src="https://github.com/user-attachments/assets/0991caf7-2d36-405f-9622-cfe61b8d0811" />
</p>
<p>
14 This is an example of what a Ticket could be for a bank. 
   After you have filled out everything click "Create Ticket" at the bottom.
<p>
<img <img width="1440" alt="TTL_14" src="https://github.com/user-attachments/assets/b98dd63e-83c1-45c9-8cac-633126356cc1" />
</p>
<p>
15 The screen will change to this notifying you the ticket was created and sent to the support team. 
   We will now go back as a Help Desk Agent and review this ticket. 
<p>
<img <img width="1440" alt="TTL_15" src="https://github.com/user-attachments/assets/cf40919c-a072-46d9-b874-ba2434e156f6" />
</p>
<p>
16 From the other link (Admin/Analyst Login Page) Sign in as the help desk agent you created earlier. Then go to the tickets Panel. 
<p>
<img <img width="1440" alt="TTL_16" src="https://github.com/user-attachments/assets/3b5ea308-e2df-4155-aea4-31b86058d5fb" />
</p>
<p>
17 Now you can see the ticket that we created from the client. Now click on the ticket number. 
<p>
<img <img width="1440" alt="TTL_17" src="https://github.com/user-attachments/assets/455949c5-11c5-4018-b76a-120779f54944" />
</p>
<p>
18 While signed in as the help desk agent and observe this tickets properties. 
   Priority 
   Department 
   SLA 
   Assigned To
<p>
<img <img width="1440" alt="TTL_18" src="https://github.com/user-attachments/assets/84bd9519-bb0d-44c8-8367-b00bb2704a90" />
</p>
<p>
20 Quick setting change (Error on my part) Sign out as the agent and back in as yourself. Then go to the "Agents" tab. 
<p>
<img <img width="1440" alt="TTL_20" src="https://github.com/user-attachments/assets/81503c06-49f3-48cc-a724-f70796f14a08" />
</p>
<p>
21 Click on the agent that you were using to look at the ticket. 
<p>
<img <img width="1440" alt="TTL_21" src="https://github.com/user-attachments/assets/b02b7f43-be5f-4ab8-ae8b-9588f502673f" />
</p>
<p>
22 For access change from "View only" to "All Access". Now as that agent we can make changes to the ticket. 
<p>
<img <img width="1440" alt="TTL_22" src="https://github.com/user-attachments/assets/3ba1ce76-77de-48b3-adef-5b001b26c34b" />
</p>
<p>
23 Click "Save Changes" at the bottom. Then sign back in as the Help Desk Agent.
<p>
<img <img width="1440" alt="TTL_23" src="https://github.com/user-attachments/assets/e9431d78-404d-47cb-a24b-e2d10f59030c" />
</p>
<p>
24 Go back to the ticket we were looking at prior. 
   Sometimes clients don't choose the best information when submitting the ticket and when that happens we need to make changes to both better understand the issue and get it to the right department if necessary. 
   First, next to SLA Plan click "Default SLA".
<p>
<img <img width="1440" alt="TTL_24" src="https://github.com/user-attachments/assets/e0857b60-5722-4921-b484-fae22b045eb4" />
</p>
<p>
25 Here you would update the SLA to better meet the circumstances of the ticket like this. I change the Plan and and provided a reason for the update. Then click update. 
<p>
<img <img width="1440" alt="TTL_25" src="https://github.com/user-attachments/assets/20659c1b-55bb-4b95-98d2-b7244058d877" />
</p>
<p>
26 Next to Help Topic click "Report a Problem".
<p>
<img <img width="1440" alt="TTL_26" src="https://github.com/user-attachments/assets/7a67c9b3-775b-4058-9e30-1c45d991726d" />
</p>
<p>
27 A more appropriate topic for this situation would be "Report a Problem/Business Critical Outage". 
   Then give a reason for the update. Then click update. 
<p>
<img <img width="1440" alt="TTL_27" src="https://github.com/user-attachments/assets/e0016ed3-0586-40ba-92eb-5fb30a0b956d" />
</p>
<p>
28 Now refresh the page. 
<p>
<img <img width="1440" alt="TTL_28" src="https://github.com/user-attachments/assets/5314c5d4-449a-4c66-8e32-ccbabe158789" />
</p>
<p>
29 After the page refreshes scroll down and you can see all the updates you made. 
<p>
<img <img width="1440" alt="TTL_29" src="https://github.com/user-attachments/assets/675939ca-67b6-47aa-bfc3-d6fd7250a0fd" />
</p>
<p>
30 This ticket hasn't been assigned to anyone yet so now we will assign it to the correct team. 
   To do that you would click "Unassigned". Before that however another correction (My apologies). 
<p>
<img <img width="1440" alt="TTL_30" src="https://github.com/user-attachments/assets/f6498169-4018-4bfd-91f7-eaf0765fe459" />
</p>
<p>
31 Sign back in as yourself, click on "Agents" tab and then "Teams".
<p>
<img <img width="1440" alt="TTL_31" src="https://github.com/user-attachments/assets/da680dc8-33f0-497a-b6a3-6109905b9e8f" />
</p>
<p>
32 Click "Online Banking".
<p>
<img <img width="1440" alt="TTL_32" src="https://github.com/user-attachments/assets/33642892-f1c9-418c-acf3-bf7e829a12be" />
</p>
<p>
33 Go to the Members tab.
<p>
<img <img width="1440" alt="TTL_33" src="https://github.com/user-attachments/assets/cfb5291a-b303-4066-aa0d-011ec26e648f" />
</p>
<p>
34 Under select agent click the Sysadmin agent you created earlier. 
<p>
<img <img width="1440" alt="TTL_34" src="https://github.com/user-attachments/assets/95f502e0-6bcd-41af-817e-27ae637f3a18" />
</p>
<p>
35  Do this for the other two as well. Then click "Save Changes". 
    (The reason behind this is to see the changes regardless when you are signed in as.)
<p>
<img <img width="1440" alt="TTL_35" src="https://github.com/user-attachments/assets/a17435fb-da6b-446f-b175-4e2a535999f4" />
</p>
<p>
36 Now sign back in as the Help Desk Agent, go back to the ticket and click "Unassigned". 
<p>
<img <img width="1440" alt="TTL_36" src="https://github.com/user-attachments/assets/f32d9354-4bc9-49cf-9892-7b5fba235f64" />
</p>
<p>
37 Select "Online Banking" and copy the reason for the assignment in the image. Then click "Assign".
<p>
<img <img width="1440" alt="TTL_37" src="https://github.com/user-attachments/assets/092b0c76-6113-458d-ae35-0922c9b09d27" />
</p>
<p>
39 Now that we have made the necessary changes to the ticket we are going to sign out as the Help Desk Agent and sign in as the Sysadmin to work the ticke to completion.
<p>
<img <img width="1440" alt="TTL_39" src="https://github.com/user-attachments/assets/ad3d695c-2ab4-479e-882b-795ef1a270ce" />
</p>
<p>
40 After you are signed in as the Sysadmin go to Tickets and click on the ticket assigned to Online Banking. 
<p>
<img <img width="1440" alt="TTL_40" src="https://github.com/user-attachments/assets/47bc0e8d-7b3b-4447-a775-99a0e43fea24" />
</p>
<p>
41 Next to click "Online Banking". 
<p>
<img <img width="1440" alt="TTL_41" src="https://github.com/user-attachments/assets/af2a50d0-f335-4358-82f3-a4bff341a667" />
</p>
<p>
42 For this scenario lets say this person wants to take care of the ticket themself so they will reassign the ticket to them. 
   Just change the assign, your reason for assigning it to your self and click "Assign".
<p>
<img <img width="1440" alt="TTL_42" src="https://github.com/user-attachments/assets/e633bc83-e4b3-404f-bfbd-dbea0ab310f5" />
</p>
<p>
43 Now you can see its assigned to that specific person. In this case Jane Doe. 
<p>
<img <img width="1440" alt="TTL_43" src="https://github.com/user-attachments/assets/00b405e0-fd64-4e8b-8893-e0db70ce845b" />
</p>
<p>
44 In the bottom of the ticket page you can post replies to update the ticket status. 
<p>
<img <img width="1440" alt="TTL_44" src="https://github.com/user-attachments/assets/213f8e4d-59c1-407a-90de-669975fbe0a8" />
</p>
<p>
45 Now its added to the thread where any people involved will be notified of updates. 
<p>
<img <img width="1440" alt="TTL_45" src="https://github.com/user-attachments/assets/921e34c6-d68b-4603-874c-579312c0742d" />
</p>
<p>
46 Next lets say Jane looked into the issue with online banking and addressed it. They would post a reply to update the ticket status. 
<p>
<img <img width="1440" alt="TTL_46" src="https://github.com/user-attachments/assets/ebdfe384-24af-465f-b8a8-e8fb4d413aa5" />
</p>
<p>
47 After posting that everyone can see that the root cause was the recent update. It was rolled back and the vendor was notified pending a proper fix. 
<p>
<img <img width="1440" alt="TTL_47" src="https://github.com/user-attachments/assets/67e88f55-befd-4e1d-92cf-cda78f8bfa81" />
</p>
<p>
48 Now scroll up to the top and click the Priority: "status". In this kind of scenario it would have been changed to Emergency. For practice change that status. 
<p>
<img <img width="1440" alt="TTL_48" src="https://github.com/user-attachments/assets/f2da4570-3625-4e85-bd7d-e11af9cdcd4c" />
</p>
<p>
49 With everything fixed Next to status click "Open". 
<p>
<img <img width="1440" alt="TTL_49" src="https://github.com/user-attachments/assets/7863c402-a621-40c9-8219-6bc643689b94" />
</p>
<p>
50 Click "Resolved".
<p>
<img <img width="1440" alt="TTL_50" src="https://github.com/user-attachments/assets/53954b29-0f10-46e3-8074-9a016a10eb9b" />
</p>
<p>
51 Click "Close" effectively closing down the ticket.
<p>
<img <img width="1440" alt="TTL_51" src="https://github.com/user-attachments/assets/4969f828-005e-4fe9-a416-2e6ad93339d6" />
</p>
<p>
52 Back on the tickets page you can see there aren't any tickets to view. 
   Resolved tickets can still be viewed its just a matter of who has the permissions to do so.
<p>
<img <img width="1440" alt="TTL_52" src="https://github.com/user-attachments/assets/41122571-ebb4-49d4-b602-07dee0c31a29" />
</p>
<p>
53 Now go back to the enduser portal for creating tickets.
<p>
<img <img width="1440" alt="TTL_53" src="https://github.com/user-attachments/assets/253c56be-2d70-418b-a89c-3721a17d1c78" />
</p>
<p>
54 Open up a new ticket.
<p>
<img <img width="1440" alt="TTL_54" src="https://github.com/user-attachments/assets/4373adef-0fbc-43bb-94d6-78e2b77acd33" />
</p>
<p>
55 Then fill out the information like this. 
   You can use either user created I just chose to use the same one. 
<p>
<img <img width="1440" alt="TTL_55" src="https://github.com/user-attachments/assets/e13069ea-c9f2-4c90-9f88-fee6e61076e0" />
</p>
<p>
56 This is just an example scenario but generally submitted tickets aren't going to be perfectly explained when submitted. 
   When you are done click "Create Ticket" at the bottom and we will process this new ticket. 
<p>
<img <img width="1440" alt="TTL_56" src="https://github.com/user-attachments/assets/f997369d-fdc8-4380-9000-23dd2bc2d337" />
</p>
<p>
57 Go back to the osTicket site and sign in as the other Help Desk Agent.
<p>
<img <img width="1440" alt="TTL_57" src="https://github.com/user-attachments/assets/014f06f7-c08e-4528-96ba-adcb1743a613" />
</p>
<p>
58 After you are signed in click on the ticket created by the accounting department. 
<p>
<img <img width="1440" alt="TTL_58" src="https://github.com/user-attachments/assets/9273e099-abd3-4884-b319-44058afd01db" />
</p>
<p>
59 After inspecting the ticket the description isn't the best so ideally you would reach out to the user for more details. 
<p>
<img <img width="1440" alt="TTL_59" src="https://github.com/user-attachments/assets/736976c0-16a7-4c71-8dc3-f39c5795a77e" />
</p>
<p>
60 Lets say you contact the user and actually its only two people that are having issues opening adobe. You recomend a restart and they will call you back after lunch with an update. 
   With this information we can make some changes. 
   Click on the SLA Plan and set it to Sev-C with for this reason. 
<p>
<img <img width="1440" alt="TTL_60" src="https://github.com/user-attachments/assets/f148094d-7e41-4a1a-8540-40827804215d" />
</p>
<p>
62 Now we are going to assigne the ticket to ourselves. Click "Unassigned" 
<p>
<img <img width="1440" alt="TTL_62" src="https://github.com/user-attachments/assets/6849d501-ae37-4b1b-abdd-d2f7066906ed" />
</p>
<p>
63 Add your reasoning and click "Assign". 
<p>
<img <img width="1440" alt="TTL_63" src="https://github.com/user-attachments/assets/72d5a4ea-f6f7-4347-8d50-596c12ef87f1" />
</p>
<p>
64 Now post a reply (like this one) letting everyone know the current status. 
<p>
<img <img width="1440" alt="TTL_64" src="https://github.com/user-attachments/assets/d17a60e7-c7ca-4d49-b40c-786c6215e5ed" />
</p>
<p>
65 With that anyone who needs to can see the thread so far as we "wait' for the return call. 
<p>
<img <img width="1440" alt="TTL_65" src="https://github.com/user-attachments/assets/913a4f86-a70c-4e67-bd4f-0aa7fc66f26e" />
</p>
<p>
66 We get the call back and the restart was successful. Make another post notifying the issue is resolved.
<p>
<img <img width="1440" alt="TTL_66" src="https://github.com/user-attachments/assets/30fb6199-03b6-47b1-8904-ffae35a0eb84" />
</p>
<p>
67 Now anyone who needs to can see the update. 
<p>
<img <img width="1440" alt="TTL_67" src="https://github.com/user-attachments/assets/12b162f6-938e-415f-846a-e83795c8bbe9" />
</p>
<p>
68 Just like the first ticket click on the status and change it to Resolved. 
<p>
<img <img width="1440" alt="TTL_68" src="https://github.com/user-attachments/assets/e95c6acb-22f0-4249-b273-428baccb92f4" />
</p>
<p>
69 State the the reset was succcessful and click "Close".
<p>
<img <img width="1440" alt="TTL_69" src="https://github.com/user-attachments/assets/b923ae34-da71-4e8f-b272-d69320e9b775" />
</p>
<p>
70 We are going to run through one more example ticket involving the CFO's laptop. 
   Fill out the ticket accordingly and click "Create Ticket".
<p>
<img <img width="1440" alt="TTL_70" src="https://github.com/user-attachments/assets/6873ad10-662c-460d-8bb0-b02f41fa91c1" />
</p>
<p>
72 Click on the CFO's ticket (If it isn't there click the refresh symbol next to Open).
<p>
<img <img width="1440" alt="TTL_72" src="https://github.com/user-attachments/assets/d0e6c44b-0d85-4a02-bfa5-e1640a042fdd" />
</p>
<p>
73 Observe the ticket details.
   We are going to change the Priority first. 
<p>
<img <img width="1440" alt="TTL_73" src="https://github.com/user-attachments/assets/45292a84-1a35-4256-abe6-b95b2c9fb0e8" />
</p>
<p>
74 Just like before click the priority, set it to Emergency, and click "Update". 
<p> 
<img <img width="1440" alt="TTL_74" src="https://github.com/user-attachments/assets/9ee95f05-75cb-4801-bd1b-e0e8f1e09f8d" />
</p>
<p>
75 Next change the SLA. Sev-B(4 hours, 24/7) is the most appropriate considering even though it is the CFO its still just one persons laptop and not a major business impact. 
   Also add the reasoning that may change later with more information then click "Update".
<p>
<img <img width="1440" alt="TTL_75" src="https://github.com/user-attachments/assets/c1d3cf82-addb-4f1b-8956-c274b5fe3185" />
</p>
<p>
76 Assign the ticket to yourself. 
<p>
<img <img width="1440" alt="TTL_76" src="https://github.com/user-attachments/assets/b3855423-701f-431f-a6e3-a6453ee44e8d" />
</p>
<p>
78 You contact Karen to see if you can get eyes on the laptop. Its arranged and you determine that the cause was a bad charger. You replace it and it is charging. 
   Make a thread to close out the ticket.
<p>
<img <img width="1440" alt="TTL_78" src="https://github.com/user-attachments/assets/d7703856-16d4-4dc1-ac8b-64555c4b531b" />
</p>
<p>
79 Scroll back up and change the status to "Resolved".
<p>
<img <img width="1440" alt="TTL_79" src="https://github.com/user-attachments/assets/427ae8af-1070-4a50-bb7f-bbaf2517479a" />
</p>
<p>
80 Change the status, provide the reason, and click "Close". 
<p>
<img <img width="1440" alt="TTL_80" src="https://github.com/user-attachments/assets/0750c4f1-a577-47bb-8648-2704e7f2a6fc" />
</p>
<p>
