### Setup MySQL using Docker
```
docker run --name mysql -e MYSQL_ROOT_PASSWORD=<password> -p 127.0.0.1:3306:3306 -d mysql
```

### How to build
```bash
./gradlew :coffee-shop:build
```

### How to run
```bash
./gradlew :coffee-shop:bootRun
```

### Api document
http://localhost:8080/swagger-ui/index.html


[![CI](https://github.com/thachlp/second-brain/actions/workflows/action_build.yml/badge.svg)](https://github.com/thachlp/second-brain/actions/workflows/action_build.yml)
[![codecov](https://codecov.io/gh/thachlp/second-brain/branch/main/graph/badge.svg?token=EO2GT1S5TB)](https://codecov.io/gh/thachlp/second-brain)
