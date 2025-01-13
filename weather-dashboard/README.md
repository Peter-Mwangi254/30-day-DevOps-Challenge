# 30 Days DevOps Challenge - Weather Dashboard

Day 1: Building a weather data collection system using AWS S3 and OpenWeather API

# Weather Data Collection System - DevOps Day 1 Challenge

## Project Overview
This project is a Weather Data Collection System that demonstrates core DevOps principles by combining:
- External API Integration (OpenWeather API): Fetching real-time weather data via the OpenWeather API.
- Cloud Storage (AWS S3): Using AWS S3 to store and manage weather data.
- Infrastructure as Code
- Version Control (Git): Manage the project lifecycle with Git.
- Python Development
- Error Handling
- Environment Management: Secure and manage API keys using environment variables.

## Features
- Fetches real-time weather data for multiple cities
- Displays temperature (°F), humidity, and weather conditions
- Automatically stores weather data in AWS S3
- Supports multiple cities tracking
- Timestamps all data for historical tracking
- Error handling for API and cloud interactions.

## Technical Architecture
- **Language:** Python 3.x
- **Cloud Provider:** AWS (S3)
- **External API:** OpenWeather API
- **Dependencies:** 
  - `boto3` (AWS SDK for Python)
  - `python-dotenv`- (Environment variable management)
  - `requests` - (HTTP library)

```markdown
## Project Structure
weather-dashboard/
  src/
    __init__.py
    weather_dashboard.py
  tests/
  data/
  .env
  .gitignore
  requirements.txt

## Setup Instructions
1. Clone the repository:
```bash
git clone https://github.com/Peter-Mwangi254/30-day-DevOps-Challenge.git
cd weather-dashboard
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Configure Environment Variables
Create a `.env` file and add your credentials:
```plaintext
OPENWEATHER_API_KEY=your_openweather_api_key
AWS_BUCKET_NAME=your_s3_bucket_name
```

### 4. Configure AWS CLI
Set up your AWS CLI credentials:
```bash
aws configure
```

### 5. Run the Application
```bash
python src/weather_dashboard.py
```

---

## Key Learnings

- AWS S3 bucket creation and management.
- Secure handling of API keys using environment variables.
- Best practices for Python API integrations.
- Effective Git workflows for development.
- Error handling in cloud-based systems.

---

## Future Enhancements

- Add weather forecasting capabilities.
- Implement data visualization dashboards.
- Support tracking for more cities.
- Create automated unit tests.
- Set up CI/CD pipelines for deployment.

---

## Screenshots

### Weather Dashboard Output:
![Weather Dashboard Example]()

### AWS S3 Bucket:
![AWS S3 Example](https://via.placeholder.com/600x400.png?text=AWS+S3+Example)

---

## Deployment

This project can be deployed using [Vercel](https://vercel.com):

1. Set up a Vercel account and link your repository.
2. Define environment variables for the project.
3. Configure build settings for Python applications.

---

Feel free to contribute to the project by raising issues or submitting pull requests!
