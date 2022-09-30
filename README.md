# KnovatorTest
i have create user and categories using seeder or you can create user using laravel registration.
i have use sanctum token for user 
http://127.0.0.1:8000/api/login  => enter email and password and send request so you can get Bearer Token
=> pass the Bearer Token in below all request if you have use new tab

http://127.0.0.1:8000/api/add => create post fill form-data like title,description,category_id,is_active.

http://127.0.0.1:8000/api/update/3 => PUT method fill data in x-www-form-urlncoded like title,description,category_id,is_active.

http://127.0.0.1:8000/api/delete/6 => DELETE Method 

http://127.0.0.1:8000/api/post-list =>display user's post list

http://127.0.0.1:8000/api/search-post?title=abc => for searching enter Query Params = title and value then send request

http://127.0.0.1:8000/api/logout => logot user


=> i also use pagination in list of posts and searchin api

