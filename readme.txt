create config/Database.php
create models/Post.php
create posts/read.php
create posts/read_single.php
create posts/create.php

GET - http://localhost:81/php_rest_api_from_scratch/php_rest_myblog-master/api/post/read.php

GET - http://localhost:81/php_rest_api_from_scratch/php_rest_myblog-master/api/post/read_single.php?id=3

POST - http://localhost:81/php_rest_api_from_scratch/php_rest_myblog-master/api/post/create.php

GET - http://localhost:81/php_rest_api_from_scratch/php_rest_myblog-master/api/post/read.php

PUT - http://localhost:81/php_rest_api_from_scratch/php_rest_myblog-master/api/post/update.php

DELETE - http://localhost:81/php_rest_api_from_scratch/php_rest_myblog-master/api/post/delete.php

create post
Postman/Header/
Key - Content-type
Value - application.json
Body/raw
{
    "title": "My Tech Post",
    "body": "This is a sample post",
    "author": "Tiago Ramos",
    "category_id": "1"
}

edit models/Post.php
create posts/update.php

{
    "title": "My Tech Post",
    "body": "This is a sample post",
    "author": "Tiago Ramos",
    "category_id": "1",
    "id": "4"
}

edit models/Post.php
create posts/delete.php

DELETE - http://localhost:81/php_rest_api_from_scratch/php_rest_myblog-master/api/post/delete.php
{
    "id": "4"
}

create api/Category
       models/Post.php
GET - http://localhost:81/php_rest_api_from_scratch/php_rest_myblog-master/api/category/read.php

GET - http://localhost:81/php_rest_api_from_scratch/php_rest_myblog-master/api/category/read_single.php?id=3

POST - http://localhost:81/php_rest_api_from_scratch/php_rest_myblog-master/api/category/create.php
create post
Postman/Header/
Key - Content-type
Value - application.json
Body/raw

{
    "name": "Technology"
}

GET - http://localhost:81/php_rest_api_from_scratch/php_rest_myblog-master/api/category/read.php

PUT - http://localhost:81/php_rest_api_from_scratch/php_rest_myblog-master/api/category/update.php
{
    "id": "6",
    "name": "Technology web"
}

DELETE - http://localhost:81/php_rest_api_from_scratch/php_rest_myblog-master/api/category/delete.php
{
    "id": "6"
}

https://www.youtube.com/watch?v=OEWXbpUMODk&list=PLillGF-RfqbZ3_Xr8do7Q2R752xYrDRAo
