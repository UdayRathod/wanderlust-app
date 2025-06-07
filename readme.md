# Wanderlust Application

A containerized Flask web application showcasing travel destinations, hotels, and packages with wishlist and payment features.

## Features

- Browse popular travel destinations with detailed information  
- View hotels and travel packages with prices  
- User wishlist to save favorite destinations  
- Simple payment flow for booking packages  
- Responsive design with uniform destination cards  

## Tech Stack

- Python 3.12  
- Flask Web Framework  
- Docker for containerization with distroless image.

## Getting Started

### Prerequisites

- Docker installed on your machine  
- Git installed  

### Clone the repo

```bash
git clone https://github.com/UdayRathod/wanderlust-app.git
cd wanderlust-app 
```

### To run the app locally without Docker:

### Create a virtual environment and activate it, install the dependencies
pip install -r requirements.txt

### Run the Flask app
python app.py


### To run with Docker

```bash
docker build -t wanderlust-app .
docker run -p 5000:5000 wanderlust-app
```

### Project Structure

```
/wanderlust-docker-app
│
├── app.py                  # Main Flask application
├── requirements.txt        # Python dependencies
├── templates/              # HTML templates
├── static/                 # CSS, JS, images
├── Dockerfile              # Docker multi-stage build
└── README.md
```

## Contributing

Contributions are welcome!  
To contribute, please fork the repository, create a new branch for your feature or bugfix, and submit a pull request.  
For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

This project is licensed under the [MIT License](LICENSE).