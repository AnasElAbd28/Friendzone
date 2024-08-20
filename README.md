
# Social Networking Project

This PHP project is a social networking platform that allows users to sign up, create profiles, post status updates, comment on posts, and manage photos. It includes functionalities for user authentication, profile editing, and social interactions among users.

## Features

- User authentication (sign in, sign out, sign up)
- Profile creation and editing
- Posting status updates
- Commenting on posts
- Photo uploads and management
- Timeline view of posts

## Installation

### Prerequisites

- PHP 7.x or newer
- MySQL 
- Apache 

### Database Setup

1. Create a database for the project.
2. Import the `sourcecodester_friend_zone.sql` file into your database to set up the required tables.

### Configuration

1. Clone or download this repository to your server's web directory.
2. Modify the `includes/db.php` (you may need to create this file based on your environment) to include your database connection details:
    ```php
    <?php
    $servername = "your_server_name";
    $password = "your_db_password";
    $dbname = "your_db_name";

    // Create connection
    $conn = new mysqli($servername, $password, $dbname);
    // Check connection
    if ($conn->connect_error) {
      die("Connection failed: " . $conn->connect_error);
    }
    ?>
    ```
3. Adjust the `.htaccess` file (if using Apache) or server configuration (if using Nginx) as needed to point to the `index.php` as the default document.

## Usage

- Navigate to the project's URL on your web server to access the home page.
- Sign up for an account or sign in if you already have one.
- Once logged in, you can create posts, upload photos, edit your profile, and interact with other users' posts.

## Testing accounts

- test1@gmail.com - 1234
- test2@gmail.com - 12345

