# 🗺️ gis_pgrouting_docker

This project provides a Docker-based infrastructure for developing and deploying GIS applications using PostgreSQL/PostGIS, pgRouting, Flask, and Nginx. It enables spatial database management, network analysis, and interactive web interfaces with minimal setup.

## 🔧 Features

- PostgreSQL database with PostGIS and pgRouting extensions for spatial and routing capabilities.
- Flask-based web application for interacting with geospatial data.
- Nginx web server to serve the Flask app and manage HTTP requests.
- Docker Compose orchestration for simplified setup and management of services.

## 📁 Project Structure

```
gis_pgrouting_docker/
├── data/                 # Geospatial datasets (e.g. shapefiles)
├── db/                   # Database initialization scripts
├── flask/                # Flask application source code
├── nginx/                # Nginx configuration files
├── web/                  # Static files and HTML templates
├── docker-compose.yml    # Docker Compose service definitions
└── README.md             # Project documentation
```

## 🚀 Quick Start

1. Ensure Docker and Docker Compose are installed on your system.
2. Clone the repository:

   ```bash
   git clone https://github.com/voirinprof/gis_pgrouting_docker.git
   cd gis_pgrouting_docker
   ```

3. Start the services using Docker Compose:

   ```bash
   docker-compose up --build
   ```

4. Access the web application at [http://localhost](http://localhost).

## 🧪 Usage

- Add your spatial data (e.g., shapefiles) to the `data/` directory.
- Use the SQL scripts in `db/` to initialize and populate the database.
- Develop your geospatial API or interface inside the `flask/` directory.
- Customize Nginx as needed in the `nginx/` folder.

## 📚 Additional Resources

- [pgRouting Documentation](https://pgrouting.org/)
- [PostGIS Documentation](https://postgis.net/documentation/)
- [Docker Compose Documentation](https://docs.docker.com/compose/)

## 📝 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.