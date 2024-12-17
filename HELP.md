# News Paper Platform
## Install instruction
1. Clone repository
    ```
    git clone https://github.com/bakhtiiartashbolotov/newspaper.git
    ```
2. Create environment
   ```
   virtualenv .env
   ```
3. Intall requirements
   ```
   pip3 install -r requirements.txt
   ```
4. Run
   ```
    python3 manage.py runserver
    ```

## API
1. Article CRUD
   ```
   Create / Read
   articles/api/posts/

   Update / Delete
   articles/api/posts/<id>
   ```
2. Comment CRUD
   ```
   Create / Read
   articles/api/posts/<id>/comments/

   Update / Delete
   articles/ api/comments/<id>/

   ```
3. JWT
   ```
   api/token/
   api/token/refresh/
   ```
4. Swagger / Redoc
   ```
   swagger/
   redoc/
   ```