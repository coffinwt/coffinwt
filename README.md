@@ -1,14 +1,14 @@
name: Build
on: [push, pull_request]
jobs:
  build:
    runs-on: ubuntu-latest
        strategy:
      matrix:
        python-version: ['3.8', '3.9', '3.10', '3.11']
        python-version: ['3.8', '3.9', '3.10', '3.11', '3.12']
        celery-version: ['5.2', '5.3']
        tornado-version: ['6.0']
