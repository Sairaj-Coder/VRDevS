# E-Waste Management Website

A web application for managing electronic waste collection and rewards system. The website features user authentication, e-waste donation tracking, collection point mapping, and a rewards system with unique coupon codes.

## Features

- Dark theme with modern UI
- Animated components and transitions
- User authentication (Sign up/Login)
- Interactive map with OpenStreetMap for collection points
- E-waste donation system with points calculation
- Rewards system with unique coupon codes
- Contact form with Google Forms integration
- Data storage in Excel files

## Prerequisites

- Python 3.7 or higher
- pip (Python package installer)
- Google Forms (for contact form)

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd e-waste-management
```

2. Install required Python packages:
```bash
pip install -r requirements.txt
```

3. Set up Google Forms:
   - Create a Google Form for the contact form
   - Replace the form URL in `contact.html` with your form's embed URL

## Running the Application

1. Start the Flask server:
```bash
python app.py
```

2. Open your web browser and navigate to:
```
http://localhost:5000
```

## Project Structure

- `index.html` - Home page with e-waste information
- `map.html` - Collection points map using OpenStreetMap
- `donate.html` - E-waste donation form
- `rewards.html` - Rewards and coupons page
- `contact.html` - Contact information and form
- `login.html` - User login page
- `signup.html` - User registration page
- `styles.css` - Main stylesheet
- `app.py` - Flask backend application
- `requirements.txt` - Python package dependencies
- `users.xlsx` - User data storage
- `coupons.xlsx` - Coupon data storage

## Data Storage

The application uses Excel files for data storage:
- `users.xlsx`: Stores user information and points
- `coupons.xlsx`: Stores generated coupon codes and their usage

## Security Notes

- Passwords are hashed before storage
- User data is stored locally in Excel files

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details. 