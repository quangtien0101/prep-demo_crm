### Flow demo

**Context**:
- User: bao gồm administrator và người dùng bình thường
- Company: 1 company
- Sales team: có nhiều team khác nhau, user có thể ở nhiều team khác nhau
- email campaign: có 1 campaign
- mailings: có nhiều mailings trong 1 campaign
- mailing list: tái sử dụng mailing list cho nhiều campaign/mailing 
- template: hiện tại chỉ sử dụng được trong context của CRM và Contacts
- Pipeline stage: dọn dẹp lại theo yêu cầu
- filters: cách chọn và bỏ chọn filter cơ bản
- Kanban view: nhấn mạnh, thể hiện sự vượt trội về tính năng  
- List view: có nhiều tính năng hơn, tốt cho các thao tác như xóa, chỉnh sửa

**Content**:
- Login (as a normal user)
- Introduce the navigation menu
	- Filters 
	- Create/Import
	- Views

- Overview contacts
	- Contacts is like a phonebook, storing contacts information of employees
	- Demo:
		- See the contact information of an Individual, Company
		- Create a new contact
		- Search using filter or group
		- Switch different views for different features


- Overview CRM
	- Purposes: manage sales team, opportunities
	- Demo:
		- Filter Company/Sales team
		- Create a new sale team
		- Create opportunities
		- **Import opportunities** ([tài liệu](https://docs.google.com/document/d/1ENY5P7gjBctQf0rYLNGJBLauQNFkLoYB/edit))
		- Basics operations on opportunities (drag and drop on Kanban View, mark Won/Lost)
		- Switch to lists view
			- Select multi opportunities -> actions -> send email / delete / export ...
			- Showing some filters 

> nên giải thích rõ về mục đích của module này, tránh gây nhầm lẫn là đây là công cụ "chỉ để gửi email" vì thế mục gửi email ở bên CRM hoàn toàn không liên quan gì đến Email marketing 
- Overview Email Marketing
	- purposes: manage campaign and mailings
	- Definitions:
		- campaign: consists of many mailings. A campaign can go through different stages - which can be fully customized
		- mailing: a mailing can belong to a campaign. Mailings can be scheduled to be sent in later time and we can observe the stages of all the mailings in the "Mailings" tab
	- demo:
		- Create a new campaign
		- Moving the campaign through different stages (drag and drop in Kanban view)
		- Create a new mailing:
			- Choose recipient as Lead/Opportunity -> show how many records
			- then apply a filter `Sex = Male` -> show records again
			- then compose the rest of the `Mail Body` 
			- go to `settings` and briefly explain the fields
			- choose the `mailing campaign`
			- and click `sent`
			- observe the mailing state in Kanban view in `mailings` tab 
		- Create a new `mailing list`:
			- create a new `mailing lists` entry
			- then click on that empty entry -> import an excel file
			- go back to create a new `mailings` and use the new mailing list as Recipients.