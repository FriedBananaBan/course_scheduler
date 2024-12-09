# Course Scheduler

[![CI / CD](https://github.com/software-students-fall2024/5-final-swe_switching_with_econ/actions/workflows/build.yml/badge.svg)](https://github.com/software-students-fall2024/5-final-swe_switching_with_econ/actions/workflows/build.yml)

## Description

A flask web app for scheduling courses, allowing you to add courses and generate potential schedules that align with your target range of credits and course priorities.

## Container Image
[Docker Hub Container Image](https://hub.docker.com/repository/docker/leannelu/schedule-gen-web-app/general)

## Configuration
1. Clone the repository:
```
git clone https://github.com/software-students-fall2024/5-final-swe_switching_with_econ.git
```
2. Create a `.env` file in the root directory, following this format:

```
MONGO_URI=your_mongo_uri
SECRET_KEY=your_secret_key
MONGO_DB_NAME=your_db_name
MONGO_USERNAME=your_username
MONGO_PASSWORD=your_password
MONGO_HOST=your_host
```

## Running the App
1. Download and run [Docker Desktop](https://www.docker.com/products/docker-desktop/)
2. Run the app:
```
docker compose up
```
3. Once the build finishes, follow the link to [localhost:3000](http://localhost:3000/).

## Team
- [Terry Cao](https://github.com/cao-exe)
- [Leanne Lu](https://github.com/leannelu)
- [Samuel Tang](https://github.com/stango1234556)
- [William Cao](https://github.com/FriedBananaBan)