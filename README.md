# express-orm
Capstone Project Express ORM

# project tag: API Backend, MySQL, JWT Token, Postman
# project sitemap:

- Home: 
<!-- GET all image with pagination:  -->
localhost:3000/page/1
<!-- GET image by name (for searching) -->
localhost:3000/search/?name={image-name-to-search}

- Single Image:
<!--GET single image/author information by image id -->
localhost:3000/image/{image-id}
<!-- GET comment by image id -->
localhost:3000/comment/{image-id}
<!-- GET save image in user save list by image id -->
localhost:3000/save/{image-id}
<!-- POST user commnet in single image -->
localhost:3000/comment

- User List Image (for user to manage image they uploaded):
<!-- GET user information -->
localhost:3000/user/{user-id}
<!-- GET image saved by user -->
localhost:3000/save/{user-id}
<!-- GET image created by user -->
localhost:3000/image/{user-id}
<!-- DELETE image created by user -->
localhost:3000/image/{image-id}


- User Add/Edit Image:
<!-- POST add image by user -->
localhost:3000/image

- User Add/Edit Profile:
<!-- PUT edit user profile -->
localhost:3000/user/{user-id}

- Login/Register:
localhost:3000/login
localhost:3000/register