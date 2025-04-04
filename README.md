###🏞️ PetParksApp

PetParksApp is a backend Java application designed to manage pet-friendly park data. Users can create and update park listings, manage contributors, and store geolocation and amenity details. The app is built using Spring Boot and Spring Data JPA.

---

##📌 Features

###Pet Park Management
  - Add a new pet park
  - Retrieve a single park or all parks
  - Update park details
  
###Contributor Management
  - Full CRUD (Create, Read, Update, Delete) operations on contributors
  
###Amenities & Geolocation
  - Track amenities available at each pet park
  - Store geolocation details for accurate mapping
  
---  
  
##🧱 Entities

###🌳 PetPark
  Represents a dog park or pet-friendly area.
  Fields include:

   - Name
   - Directions
   - State or Province & Country
   - List of amenities
   - Coordinates (via Geolocation)
   
###👤 Contributor
  Represents a user who adds or updates information about a pet park.
  Includes:

   - Name
   - Email
   - Parks they've contributed
   
###📍 Geolocation
  Stores latitude and longitude data for a pet park.

###🛝 Amenity
 Represents a feature at the park (e.g., water fountain, agility course, shaded area).

---

##⚙️ Tech Stack

  - Java
  - Spring Boot
  - Spring Data JPA
  - Maven
  
---  
  
##▶️ Getting Started

1. Clone the repository
    - git clone https://github.com/yourusername/PetParksApp.git
    - cd PetParksApp
    
2. Run the application
    - ./mvnw spring-boot:run
    
3. Access the API
    - Base URL: http://localhost:8080
    
---    
    
##📬 API Endpoints Overview

##Pet Park
- POST /parks – Add a new pet park
- GET /parks – Retrieve all parks
- GET /parks/{id} – Get a specific park by ID
- PUT /parks/{id} – Update park details

##Contributor
- POST /contributors – Add a new contributor
- GET /contributors – Retrieve all contributors
- GET /contributors/{id} – View a single contributor
- PUT /contributors/{id} – Update contributor info
- DELETE /contributors/{id} – Remove a contributor

---

##🚀 Future Enhancements

- Add full CRUD for PetPark, Amenity, and Geolocation
- Associate parks with multiple contributors
- Allow contributors to rate or review parks
- Enable amenity filtering (e.g., show parks with shaded areas and water fountains)

---

Developed by Silas Flugum ⚜️  
Contact: https://github.com/sflugum
