# TodoApi
Minimal APIs are architected to create HTTP APIs with minimal dependencies. They're ideal for microservices and apps that want to include only the minimum files, features, and dependencies in ASP.NET Core.

| **API**                     | **Description**               | **Request body** | **Response body**        |
|-------------------------    |-------------------------------|------------------|--------------------------|
| **GET /todoitems**          | Get all to-do items           | None             | Array of to-do items     |
| **GET /todoitems/complete** | Get completed to-do items     | None             | Array of to-do items     |
| **GET /todoitems/{id}**     | Get an item by ID             | None             | To-do item               |
| **POST /todoitems**         | Add a new item                | To-do item       | To-do item               |
| **PUT /todoitems/{id}**     | Update an existing item       | To-do item       | None                     |
| **DELETE /todoitems/{id}**  | Delete an item                | None             | None                     |

**POST API**
![image](https://github.com/user-attachments/assets/89b66bde-5999-4f71-8ae0-1f1f89083cb2)

**GET API/ Lấy tất cả các mục trong Todo**
![image](https://github.com/user-attachments/assets/aa3767b2-2f33-4abb-a125-543a851c36c8)

**GET API/ Lấy tất cả các mục trong Todo với IsComplete = true**
![image](https://github.com/user-attachments/assets/4f1c8929-c16c-4305-8560-6b42a51ff3d3)

**GET API/ Lấy thông tin với id (trong trường hợp này id cho trước là 5)**
![image](https://github.com/user-attachments/assets/6496a005-673b-43e8-a9ec-ab2ce28499ce)

**PUT API/ Thay đổng thông tin dựa trên id (trong trường hợp này id là 1)**
![image](https://github.com/user-attachments/assets/a09c7e7e-53ed-4198-bf39-4c8ca12b8f49)

**DELETE API/ Xóa thông tin dựa trên id (trong trường hợp này id là 1)**
![image](https://github.com/user-attachments/assets/706cf5c1-30f4-4377-ab13-889842406c9a)

