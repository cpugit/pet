**ID:** ETSY-6  
**Type:** Functional  
**Severity:** Minor  
**Priority:** Medium    
**Reporter:** roman m.  
**Assignee:** roman m.  
**Status:** New  
**Environment:** Ubuntu 20.04.6 LTS Google Chrome Version: the latest version.  

---

## Summary:
**The system allows entering an asterisk (*) in the City field on the “Your shipping addresses” tab.**

---

## Pre-conditions:					
1. The user is logged into the system.				
2. The page https://www.etsy.com/your/account/addresses is open in the browser.											

---
## Steps to reproduce:

1. Click the "Add a new address" button.				
2. Fill in all fields with valid data except for the "City" field.				
3. Enter an asterisk (*) in the "City" field.				
4. Click the "Save" button.									

---

## Actual result:					
**The pop-up closes, and the data is saved.**		

---			
					
## Expected result:					
**The system displays the message "Please enter a city."**					

----

## Attachments:			

[br4-1.png](https://drive.google.com/file/d/189zUeTY0EAWHCMPv5OJ2mnegvrU66Xk3/view)
[br4-2.png](https://drive.google.com/file/d/1lY0MKp6O6o1jZ80osH20gkx6maTOboGK/view?usp=drive_link)