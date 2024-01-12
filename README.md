# PemuLink
## Detail Description
Pemulink is an innovative solution that combines the MVP (Minimum Viable Product) concept with sustainability principles to improve the waste distribution system. By focusing on scavengers and the MSME sector, Pemulink aims to reduce the gap in waste distribution and provide economic benefits to those involved.
## Team Description
Team Name: Hadehh Team <br> <br>
Member Team: 
 - Hustler
   * Andi Ahmad Fa'il Fudhayl
 - Hipster
   * Muhammad Zoel Ramadhan
 - Hacker
   * Muhammad Adnan Putra Amiruddin
   * Rasyad Bimasatya
---
## Progress Screenshots
### Front-End
sample
### Back-End
#### API Endpoints:
### 1. Register User
- **Endpoint:** `http://localhost:8081/sign-up`
- **Method:** `POST`
- **Description:** Register an User.

### 2. Login User
- **Endpoint:** `http://localhost:8081/sign-in`
- **Method:** `POST`
- **Description:** Login User.

### 3. Create Mission
- **Endpoint:** `http://localhost:8081/`
- **Method:** `POST`
- **Description:** Create a mission by Waste Bank Admin.

### 4. Get All Weekly Missions
- **Endpoint:** `http://localhost:8081/`
- **Method:** `GET`
- **Description:** Displays all missions for the user.

### 5. Get Mission By Id
- **Endpoint:** `http://localhost:8081/{id}`
- **Method:** `GET`
- **Parameters:**
  - `{id}` (path parameter): mission ID.
- **Description:** Displays specific mission based on mission ID.

### 6. Create Mission Acceptance Request
- **Endpoint:** `http://localhost:8081/{id}`
- **Method:** `POST`
- **Parameters:**
  - `{id}` (path parameter): user ID.
- **Description:** Make a request for mission acceptance by the user to the waste bank admin.
