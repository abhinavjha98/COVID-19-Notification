# Covid-19 Notification System


Covid -19 Notification System will detect and tell the corona patents across various states.

  - Type some Markdown on the left
  - See HTML in the right
  - Magic
---
###  Features!
- The notification will tell us the folowing features
    * Number of States
    * Number of Indian Patients
    * Number of Foreign Patients
    * Cured Patients
    * Death Patients

---
###  Libraries Used!

  - Plyer is used for Windows Notifications
  ```sh
$ from plyer import notification
$ def notifyMe(title,message):
	notification.notify(
			title = title,
			message = message,
			app_icon = "images\\corona_icon.ico",
			timeout = 15
		)
```
  - Beautiful Soup is used for data extraction from the website https://www.mohfw.gov.in/
   ```sh
$ from bs4 import BeautifulSoup
$ myHtmlData = getData("https://www.mohfw.gov.in/")
$ soup = BeautifulSoup(myHtmlData, 'html.parser')
```
---
### Author Info
- Abhinav Jha
	* Junior Software Developer and Data Engineer
	* LinkedIn - [Abhinav Jha](https://www.linkedin.com/in/abhinavjha98/)
	* For any doubts contact : Abhinav Jha (abhinavjha98ald@gmail.com)

[Back To The Top](#read-me-template)


