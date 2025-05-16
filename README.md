The Library Information System project aims to provide a digital platform for managing library operations efficiently. It facilitates efficient management of library resources, members, and staff, providing librarians and administrators with a reliable tool to streamline library operations and enhance user experience. 

Key features and functionalities:

Primary user will be the library admin 
	Username: admin
	Password: 123
1.	Book Management:
•	User can add new books to the library data by providing book’s ISBN, title, author, publisher, publication year, quantity, and availability.
•	Existing books can be edited to update their information or deleted from the database.
•	The system allows users to search for books by their ISBN to retrieve detailed information.
•	Also allows to view all existing book data.
2.	Member Management:
•	Members can be registered into the system by providing their ID, name, email, and phone number.
•	Existing member records can be edited to update their information or deleted from the database.
•	Users can view all member data and search for members by their ID to view their details.
3.	Staff Management:
•	Staff members associated with the library can be added to the system by providing their ID, name, email, phone number, hire date, and salary.
•	Staff records can be edited to update their information or deleted from the database.
•	The system allows users view staff data and to search for staff members by their ID to view their details. 
4.	Data Persistence:
•	  File handling techniques are utilized to store all library data, including books, members, and staff records, ensuring that changes made by users are saved and can be retrieved across different sessions.
•	ArrayLists are used to maintain in-memory representations of data during program execution, enabling quick access and manipulation without frequent disk reads and writes.
