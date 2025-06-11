# Crane Service Order System

A Next.js application for managing crane service orders with email notifications.

## Features

- Save and schedule crane service orders
- Email notifications for new orders
- Customer and contact management
- Location picking with map integration
- Job specifications calculator
- Time and date scheduling

## Setup

1. Install dependencies:
```bash
npm install
```

2. Configure email settings:
Create a `.env.local` file in the project root with the following variables:
```
EMAIL_HOST=smtp.gmail.com
EMAIL_PORT=587
EMAIL_USER=your-email@gmail.com
EMAIL_APP_PASSWORD=your-app-specific-password
EMAIL_TO=recipient@example.com
```

Note: If using Gmail, you'll need to:
1. Enable 2-Step Verification
2. Generate an App Password:
   - Go to Google Account settings
   - Security
   - 2-Step Verification
   - App passwords
   - Generate a new app password

3. Run the development server:
```bash
npm run dev
```

## Usage

1. Fill out the order form with:
   - Customer details
   - Contact information
   - Crane specifications
   - Job location
   - Schedule dates and times

2. Choose to either:
   - Save Order: Stores basic order information
   - Schedule Order: Creates a complete order with all details

3. Email notifications will be sent automatically when orders are saved or scheduled.

## Environment Variables

- `EMAIL_HOST`: SMTP server host (e.g., smtp.gmail.com)
- `EMAIL_PORT`: SMTP server port (typically 587 for TLS)
- `EMAIL_USER`: Your email address
- `EMAIL_APP_PASSWORD`: Your email app-specific password
- `EMAIL_TO`: Recipient email address for order notifications
