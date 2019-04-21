# rails-module-users
> Rails module for users.


## model
> The users table fileds.

| field           | type   | length | description               |
| --------------- | ------ | ------ | ------------------------- |
| username        | string | -      | unique user name          |
| email           | string | -      | unique user email         |
| password        | string | -      | unique user password(md5) |
| password_digest | string | -      | unique user password(md5) |
| access_token    | string | -      | for login                 |