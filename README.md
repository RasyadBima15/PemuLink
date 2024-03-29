# PemuLink
![PemuLink Logo](images/pemulink.jpeg)
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
## Progress Report
### Front-End (Screenshots Page)
- Dashboard <br>
![Dashboard](images/dashboard_1.png)
![Dashboard](images/dashboard.png)
![Dashboard](images/dashboard_2.png)
![Dashboard](images/dashboard_3.png)
![Dashboard](images/dashboard_4.png)
- Loading Page <br>
![Loading](images/loading.png)
- Register Page <br>
![Register](images/register.png)
- Login Page <br>
![Login](images/login.png)
- Homepage <br>
![Homepage](images/homepage_3.png)
![Homepage](images/homepage_2.png)
- Certain Mission Page <br>
![Certain Mission](images/mission_detail_2.png)
![Certain Mission](images/mission_detail.png)
- Mission Acceptance Request <br>
![Mission Acceptance](images/upload_mission.png)
- Join Event <br>
![Join Event](images/join_event.png)
- Create Team <br>
![Create Team](images/create_team.png)
- Join Team <br>
![Join Team](images/join_team.png)
- Team Page <br>
![Team Page](images/team_page.png)


### Back-End (API Documentation)
#### API Endpoints:
#### 1. Register User
- **Endpoint:** `http://localhost:8081/api/sign-up`
- **Method:** `POST`
- **Description:** Register user for households.

#### 2. Login User
- **Endpoint:** `http://localhost:8081/api/sign-in`
- **Method:** `POST`
- **Description:** Login user for households.

#### 3. Create Mission
- **Endpoint:** `http://localhost:8081/api`
- **Method:** `POST`
- **Description:** Create a mission by Waste Bank Admin.

#### 4. Get All Weekly Missions
- **Endpoint:** `http://localhost:8081/api`
- **Method:** `GET`
- **Description:** Displays all missions for the user.

#### 5. Get Mission By Id
- **Endpoint:** `http://localhost:8081/api/{id}`
- **Method:** `GET`
- **Parameters:**
  - `{id}` (path parameter): mission ID.
- **Description:** Displays specific mission based on mission ID.

#### 6. Create Mission Acceptance Request
- **Endpoint:** `http://localhost:8081/api/{id}`
- **Method:** `POST`
- **Parameters:**
  - `{id}` (path parameter): user ID.
- **Description:** Make a request for mission acceptance by the user to the waste bank admin.

#### Error Handlings:
#### 1. Bad Request (400)
- **Description:** This error occurs when the request is malformed or invalid.
- **Example Response**:
```json
{
  "status": 400,
  "message": "Invalid data. Please check your request."
}
```
#### 2. Unauthorized (401)
- **Description:** This error occurs when the user is not authorized to access a protected resource.
- **Example Response**:
```json
{
  "status": 401,
  "message": "Unauthorized"
}
```
#### 3. Forbidden (403)
- **Description:** This error occurs when the user does not have permission to access a specific resource.
- **Example Response**:
```json
{
  "status": 403,
  "message": "Forbidden"
}
```
#### 4. Not Found (404)
- **Description:** This error occurs when the requested resource is not found.
- **Example Response**:
```json
{
  "status": 404,
  "message": "Cannot Find It"
}
```
#### 5. Internal Server Error (500)
- **Description:** This error occurs when an unexpected internal server error happens.
- **Example Response**:
```json
{
  "status": 500,
  "message": "Waduh! There is Something Wrong"
}
```
