# Photos

A self-hosted photo gallery app with ML image search written in React.

- Display photos by time, album and map view.
- Search photos based on their content.
- Self-host on Docker, total control of privacy.

## Roadmap

See [project board](https://github.com/Ivaneres/Photos/projects/1).

## Getting Started

### Docker

Using Docker is recommended for this project. `docker` and `docker-compose` are required. Clone the repository, then run
```
cd Photos
sudo docker-compose up -d
```

The app will be default listen on port 8098, accessible via http://localhost:8098/

### Development

Requirements:
 - React.js 16
 - npm
 - Python 3.9
 - PostgreSQL 13.4

Setup:
```
pip install -r requirements.txt
npm i
```

Running:
```
python -m backend.api
npm run start
```

