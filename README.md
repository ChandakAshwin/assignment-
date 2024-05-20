# assignment-
using Java, SpringBoot and Postman for a user management system
# User Management API

## Endpoints

1. **Create User**
   - **URL**: `/api/create_user`
   - **Method**: `POST`
   - **Body**:
     ```json
     {
       "full_name": "John Doe",
       "mob_num": "919876543210",
       "pan_num": "AABCP1234C",
       "manager_id": "manager_uuid"
     }
     ```

2. **Get Users**
   - **URL**: `/api/get_users`
   - **Method**: `POST`
   - **Body** (Optional):
     ```json
     {
       "user_id": "user_uuid",
       "mob_num": "9876543210",
       "manager_id": "manager_uuid"
     }
     ```

3. **Delete User**
   - **URL**: `/api/delete_user`
   - **Method**: `POST`
   - **Body**:
     ```json
     {
       "user_id": "user_uuid"
     }
     ```

4. **Update User**
   - **URL**: `/api/update_user`
   - **Method**: `POST`
   - **Body**:
     ```json
     {
       "user_ids": ["user_uuid1


versions:
Java 17
Spring Boot 3.2.6 (SNAPSHOT)
Apache Maven 3.9.6
