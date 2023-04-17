# photo-album

This is a Django project that aims to create photo-album Web-Application.

## Installation

To install and run the project, follow these steps:

1. Clone the repository: `git clone https://github.com/raj-bhatodra/photo-album.git`
2. Create a virtual environment: `python3 -m venv .env`
3. Activate the virtual environment: `source .env/bin/activate`
4. Install the dependencies: `pip install -r requirements.txt`
5. Create the database: `python manage.py migrate`
6. Run the development server: `python manage.py runserver`

## Using Docker

To run the project using Docker, follow these steps:

1. Clone the repository: `git clone https://github.com/raj-bhatodra/photo-album.git`
2. Build the Docker image: `docker build -t photo-album .`
3. Run the Docker container: `docker run -d -p 8000:8000 photo-album`

## Contributing

Contributions are welcome! If you find any bugs or issues with the project, please submit an issue or a pull request.

## License

raj-bhatodra
