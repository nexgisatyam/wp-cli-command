


# WP-CLI Commands


- **Display WP-CLI Environment Information**
  ```bash
  wp --info
  ```

- **Show Installed WordPress Version**
  ```bash
  wp core version
  ```

## Installation and Updates

- **Download WordPress Core Files**
  ```bash
  wp core download
  ```

- **Install WordPress**
  ```bash
  wp core install --url=<url> --title=<title> --admin_user=<username> --admin_password=<password> --admin_email=<email>
  ```

- **Update WordPress Core Files**
  ```bash
  wp core update
  ```

- **Update Database to the Latest Version**
  ```bash
  wp core update-db
  ```

## Plugin and Theme Management

- **List Installed Plugins**
  ```bash
  wp plugin list
  ```

- **Install a Plugin**
  ```bash
  wp plugin install <plugin-slug>
  ```

- **Activate a Plugin**
  ```bash
  wp plugin activate <plugin-slug>
  ```

- **Deactivate a Plugin**
  ```bash
  wp plugin deactivate <plugin-slug>
  ```

- **Delete a Plugin**
  ```bash
  wp plugin delete <plugin-slug>
  ```
  
## User Management

- **List All Users**
  ```bash
  wp user list
  ```

- **Create a New User**
  ```bash
  wp user create <username> <email> --role=<role>
  ```

- **Update a User's Password**
  ```bash
  wp user update <user-id> --user_pass=<new-password>
  ```

## Configuration and Debugging

- **Create a New `wp-config.php` File**
  ```bash
  wp config create
  ```

- **Get a Value from `wp-config.php`**
  ```bash
  wp config get <key>
  ```

- **Set a Value in `wp-config.php`**
  ```bash
  wp config set <key> <value>
  ```



