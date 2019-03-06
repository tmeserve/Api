# Api

Uses flask, flask_cors, dotenv, python_jose, functools, flask_cors, six, flask_pymongo

endpoints:
  test:
    http://0.0.0.0:3010/api/public
    http://0.0.0.0:3010/api/private
    http://0.0.0.0:3010/api/private-scoped
  real:
    http://0.0.0.0:3010/api/usernames/<name> - get
    http://0.0.0.0:3010/api/usernames/<name> - post
    http://0.0.0.0:3010/api/usernames/ - get
