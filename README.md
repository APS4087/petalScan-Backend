# PetalScan Backend

## Overview
PetalScan is an image recognition application designed to identify various plants and flowers found in the Singapore Botanic Gardens. This backend service is built using FastAPI and utilizes a PyTorch Lightning model for predictions.

> **Note**: This repository contains only the backend API. The frontend can be found [here](https://github.com/APS4087/PetalScan).

## Features
- **Image Prediction**: Upload an image of a plant to receive classification results.
- **Event Retrieval**: Fetch upcoming events from the Singapore Botanic Gardens.
- **Default Image Testing**: Test the model using a default image.

## Technologies Used
- **FastAPI**: A modern, fast web framework for building APIs with Python.
- **PyTorch**: An open-source machine learning library used for building and training deep learning models.
- **Pillow**: A Python Imaging Library used for opening, manipulating, and saving image files.
- **BeautifulSoup**: A library for parsing HTML and XML documents to scrape data.
- **Requests**: A simple HTTP library for making requests to external web services.

## Installation

### Prerequisites
- Python 3.7 or higher
- Pip (Python package installer)

### Steps
1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/petalScan-Backend.git
   cd petalScan-Backend
