# alx_travel_app_0x00

This project is a travel listings application built with Django and Django REST Framework.  
It includes models, serializers, and a database seeding mechanism.

## Features

### 1. Models
Located in: `listings/models.py`
- **Listing**: Represents a travel accommodation.
- **Booking**: Stores booking information linked to a listing.
- **Review**: Stores user reviews and ratings.

### 2. Serializers
Located in: `listings/serializers.py`
- ListingSerializer
- BookingSerializer

### 3. Seeder Command
Located in:  
`listings/management/commands/seed.py`

Run:
```bash
python manage.py seed
