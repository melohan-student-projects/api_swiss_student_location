![](https://img.shields.io/github/license/melohan/api_swiss_student_location.svg)

# API Swiss Student Location

This project delivers the necessary API to the Swiss Student Location site. It is based on a REST API JSON server.

## Prerequisites

- `npm@8.18.0` or higher 

## Getting started

1. Clone the repository
```shell
git clone git@github.com:melohan/api_swiss_student_location.git
cd api_swiss_student_location/
```

2. Install dependencies
```shell
npm install -g json-server
```

3. Run the server
```shell
json-server --watch data/realestate.json
```

## Project directory

```shell
.
├── assets
│   ├── min
│   └── photos
├── data
│   └── realestate.json
├── LICENSE
└── README.md
```

- `./assets/min` : contains realstate minature
- `./assets/photos`: contains realstate photos
- `./data/realstate.json`: API data file

## Resource
[Create a REST API with JSON server](https://medium.com/codingthesmartway-com-blog/create-a-rest-api-with-json-server-36da8680136d)
