# AI-Based Plant Identification System 🌿

## About the Project

The AI-Based Plant Identification System is a web-based application that helps users identify plants by uploading images. It provides information about plants, including their medicinal uses, soil requirements, sunlight needs, watering schedules, and growing conditions.

The application also includes an AI-powered chatbot that supports English and Tamil to help users learn more about plants.

## Features

- **HerbalScan:** Identify plants by uploading a plant image.
- **Growth Guide:** Explore plant-care information, including soil, sunlight, watering, and growing conditions.
- **Botanist Chat:** Ask plant-related questions in English and Tamil.
- **Plant Information:** Learn about medicinal uses and other plant details.
- **Bilingual Support:** Access chatbot assistance in English and Tamil.

## Technologies Used

- **Frontend:** HTML, CSS, JavaScript, Bootstrap
- **Backend:** Python, Django
- **Database:** SQLite
- **AI Integration:** Pre-trained AI model for plant identification
- **Dependency Management:** Python pip and `requirements.txt`

## Installation and Setup

### Prerequisites

Make sure you have the following installed:

- Python
- Git
- pip (Python package installer)

### 1. Clone the Repository

```bash
git clone https://github.com/Dhamayanthi-Sony-K/Plant_Identification.git
```

### 2. Navigate to the Project Directory

```bash
cd Plant_Identification
```

### 3. Create and Activate a Virtual Environment (Recommended)

Create a virtual environment:

```bash
python -m venv venv
```

On Windows, activate it using:

```bash
venv\Scripts\activate
```

### 4. Install Dependencies

```bash
python -m pip install -r requirements.txt
```

### 5. Apply Database Migrations

```bash
python manage.py migrate
```

### 6. Start the Development Server

```bash
python manage.py runserver
```

Open the local development URL displayed in your terminal, usually `http://127.0.0.1:8000/`, in your web browser.

## How to Use

1. Start the application using the instructions above.
2. Open the application in your browser.
3. Upload an image of a plant using HerbalScan.
4. View the identification result and available plant information.
5. Explore the Growth Guide for plant-care recommendations.
6. Use Botanist Chat to ask plant-related questions in English or Tamil.

## Project Structure

The project follows the Django web application structure. The main files and directories include:

- `manage.py` — Django management utility.
- `requirements.txt` — Python package dependencies.
- `README.md` — Project documentation.
- `db.sqlite3` — SQLite database file, if included in the project.

Other application folders contain the project's views, templates, static files, configuration, and related functionality.

## Project Purpose

The goal of this project is to make plant identification and plant-care information more accessible through an AI-powered web application.

## Future Enhancements

- Expand the range of supported plant species.
- Improve plant identification accuracy.
- Provide more detailed plant-care recommendations.
- Add support for additional regional languages.

## Author

Developed as a final-year academic project in Artificial Intelligence and Data Science.