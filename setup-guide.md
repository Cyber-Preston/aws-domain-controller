1. Launch a Windows Server EC2 instance
2. Click Launch Instance
3. Choose Windows Server 2025
4. Choose t2.medium or higher
5. Add key pair so you can connect to the vm later
6. Then click Launch an Instance
7. Wait 1 to 5 mins to Initialize
8. Now should show running
9. Now download the RDP file
10. Open the RDP file
11. Enter the Password if you cant find this password
12. At the bottom of the RDP client it will say get password
13. Now upload your key
14. Then click decrypt
15. Should show your password
16. Now Login in to the RDP
17. Click the windows key
18. Type in Server Manager
19. Now go to Manage at the top
20. You will click add roles and features
21. Click onto the Server it should auto populate
22. Click Next
23. Click the one that says Active Directory Domain Services
24. Click Next
25. Click Install
26. Click Close
27. IF you want to check on your install
28. Click the flag at the top
29. Once its done installing
30. In Server Manager, click Promote this server to a domain controller
31. Select Add a new forest
32. Enter a root domain name
33. Set DSRM passsword
34. Click through defaults and complete setup
35. Once you do that it will ask to reboot
36. Log in using domain admin (e.g., MYDOMAIN\Administrator)
37. Open Server Manager 
38. Open Active Directory Users and Computers
39. You now have a working Active Directory Domain Controller running in AWS!
