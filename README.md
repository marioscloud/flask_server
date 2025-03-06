# Flask Development Lab

This repository contains the hands-on lab for creating and running a Flask server in development mode and understanding the request object. This lab is part of the course **Developing AI Applications with Python and Flask** within the **IBM DevOps and Software Engineering Professional Certificate**.

## Learning Objectives

After completing this lab, you will be able to:
- Create and run a Flask server in development mode.
- Understand the request object.

## Getting Started

### Prerequisites

Before you begin, ensure you have the following installed:
- Python (version 3.6 or higher)
- Flask

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/flask-development-lab.git
    ```
2. Change into the lab directory:
   cd flask_server
   
3. Check Python version and install Flask
    ```bash
    python3 --version
    ```
4. Install Flask:
    ```bash
    pip install "Flask==2.2.2"
    ```

## Running the Flask Server

1. Set the environment variable for Flask development mode:
    ```bash
    export FLASK_ENV=development
    ```
2. Run the Flask server:
    ```bash
    flask run
    ```

## Understanding the Request Object

In this lab, you will learn how to:
- Access request data (query parameters, form data, JSON payloads).
- Handle different types of HTTP requests (GET, POST, etc.).
- Extract information from the request object (headers, URL, method).

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request for review.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

This lab is part of the **Developing AI Applications with Python and Flask** course within the **IBM DevOps and Software Engineering Professional Certificate**.
