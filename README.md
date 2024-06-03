# How to run the files
You need to use the www.draw.io to read these files.

# # Requirements of the entities

# 1. Library Management System:
  • Entities: Book (ISBN, Title, Author, Genre), Member (MemberID, Name, 
  Address), Loan (LoanID, BookID, MemberID, DueDate)
  • Relationships: A Book can be loaned to many Members (one-to-many). A 
  Member can borrow many Books (one-to-many). A Loan connects a Book 
  and a Member (many-to-many).

# 2. E-commerce Website:
  • Entities: Product (ProductID, Name, Description, Price, Stock), Order 
  (OrderID, CustomerID, Date), OrderItem (OrderItemID, OrderID, ProductID, 
  Quantity)
  • Relationships: A Product can be included in many Orders (one-to-many). An 
  Order contains many OrderItems (one-to-many). An OrderItem links a 
  Product to a specific Order (many-to-many).

# 3. University Course Registration:
  • Entities: Student (StudentID, Name, Major), Course (CourseID, Name, 
  Department), Registration (RegistrationID, StudentID, CourseID, Semester)
  • Relationships: A Student can register for many Courses (one-to-many). A 
  Course can have many Students registered (one-to-many). A Registration 
  connects a Student to a specific Course offered in a Semester (many-tomany).

# 4. Hospital Patient Management:
  • Entities: Patient (PatientID, Name, DOB), Doctor (DoctorID, Name, 
  Specialization), Appointment (AppointmentID, PatientID, DoctorID, Date)
  • Relationships: A Patient can have many Appointments (one-to-many). A 
  Doctor can have many Appointments (one-to-many). An Appointment 
  connects a Patient with a Doctor on a specific Date (many-to-many).

# 5. Music Streaming Service:
  • Entities: Artist (ArtistID, Name, Genre), Song (SongID, Title, ArtistID), User 
  (UserID, Name, Email), Playlist (PlaylistID, UserID, Name)
  • Relationships: An Artist can have many Songs (one-to-many). A Song belongs 
  to one Artist (many-to-one). A User can create many Playlists (one-to-many). 
  A Playlist can contain many Songs (one-to-many).

# 6. Social Media Platform:
  • Entities: User (UserID, Name, Email), Post (PostID, UserID, Content, Date), 
  Comment (CommentID, PostID, UserID, Content, Date)
  • Relationships: A User can create many Posts (one-to-many). A Post can have 
  many Comments (one-to-many). A Comment is created by a User on a 
  specific Post (many-to-many).

# 7. Movie Theater Booking System:
  • Entities: Movie (MovieID, Title, Genre, ReleaseDate), Show (ShowID, 
  MovieID, TheaterID, Date, Time), Seat (SeatID, TheaterID, Row, Number)
  • Relationships: A Movie can have many Shows (one-to-many). A Show is for 
  one Movie (many-to-one). A Show takes place in a specific Theater on a Date 
  and Time (many-to-many). A Seat belongs to one Theater (one-to-many).

# 8. Inventory Management System:
  • Entities: Product (ProductID, Name, Description), Warehouse 
  (WarehouseID, Location), Stock (StockID, ProductID, WarehouseID, 
  Quantity)
  • Relationships: A Product can be stored in many Warehouses (one-to-many). 
  A Warehouse can store many Products (one-to-many). Stock represents the 
  quantity of a Product in a specific Warehouse (many-to-many).

# 9. Hotel Reservation System:
  • Entities: Room (RoomID, Type, Price), Guest (GuestID, Name, Contact), 
  Reservation (ReservationID, GuestID, RoomID, CheckIn, CheckOut)
  • Relationships: A Room can have many Reservations (one-to-many). A Guest 
  can make many Reservations (one-to-many). A Reservation is for one Room 
  by a Guest on specific CheckIn and CheckOut dates (many-to-many).

# 10.Car Rental Service:
  • Entities: Car (CarID, Model, Year), Customer (CustomerID, Name, License), 
  Rental (RentalID, CarID, CustomerID, StartDate, EndDate)
  • Relationships: A Car can be rented in many Rentals (one-to-many). A 
  Customer can rent many Cars (one-to-many). A Rental involves a Car rented 
  by a Customer for a specific StartDate and EndDate (many-to-many).



# Misc

In this basic definitions and techniques are also documented.
