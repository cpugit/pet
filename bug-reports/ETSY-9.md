**ID:** ETSY-9    
**Type:** Functional  
**Severity:** Minor  
**Priority:** Medium    
**Reporter:** roman m.  
**Assignee:** roman m.  
**Status:** New  
**Environment:** Ubuntu 20.04.6 LTS Google Chrome Version: the latest version.  

---

## Summary:
**Incorrect message is displayed when attempting to register a shop without specifying a country.**

---

## Pre-conditions:					
1. The page https://www.etsy.com/your/shops/me/onboarding/name is open in the browser.				
2. The user is logged in.																					

---
## Steps to reproduce:

1. Fill in the "Shop language" field.				
2. Fill in the "Shop currency" field.				
3. Leave the "Shop country" field unselected.																			

---

## Actual result:					
**The system displays the warning: "Expected int value for 'country_id' (got string)."**		

---			
					
## Expected result:					
**The system displays the warning: "Please select a country."**					

----

## Attachments:			

[br6.png](https://drive.google.com/file/d/1UwJ9BPfaZPUpouhT7Putg2JqKf2lz0ya/view)  
