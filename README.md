# WordPress Hotel Booking Plugin

WordPress plugin for hotel room bookings with Beds24 API integration and Stripe payments.

**Live Demo:** [https://dev-bookingroom.pantheonsite.io/](https://dev-bookingroom.pantheonsite.io/)

## Features

- Beds24 API v2 integration
- Stripe payment processing  
- Test mode for development
- Duplicate booking prevention
- Email notifications
- Responsive design
- Elementor widget support

## Requirements

- WordPress 5.0+
- PHP 7.4+
- Beds24 account
- Stripe account

## Installation

1. **Install Plugin**
   - Download and upload to WordPress
   - Activate plugin

2. **Configure Beds24**
   - Get API token from Beds24.com
   - Go to Beds Options → Paste token

3. **Add Rooms**
   - Beds Options → Room Configuration
   - Add room names and Beds24 IDs

4. **Setup Payments**
   - Add Stripe API keys
   - Configure success/error pages

## Test Mode

Perfect for development:
- Enable in Beds Options → Test Mode
- Bookings saved locally (not in Beds24)
- Use Stripe test cards

**Test Cards:**
- Success: `4242 4242 4242 4242`
- Declined: `4000 0000 0000 0002`

## Troubleshooting

**API Token Invalid**
- Check for extra spaces
- Verify in Beds24 dashboard

**Duplicate Booking Error**
- System prevents double bookings
- Check existing reservations

**Payment Issues**
- Verify Stripe API keys
- Check SSL certificate
- Test with Stripe test cards
