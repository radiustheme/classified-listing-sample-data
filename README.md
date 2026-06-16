# Classified Listing Sample Data

Sample data files for the [Classified Listing](https://wordpress.org/plugins/classified-listing/) WordPress plugin. This repository contains form builder configurations and listing data for various directory types.

## Available Data

| Directory Type | Form Builder | Listings |
|----------------|--------------|----------|
| Car | `form/car.json` | `listings/car.csv` |
| Classified | `form/classified.json` | `listings/classified.csv` |
| Directory | `form/directory.json` | `listings/directory.csv` |
| Doctors | `form/doctors.json` | `listings/doctors.csv` |
| Hotel | `form/hotel.json` | `listings/hotel.csv` |
| Lawyers | `form/lawyers.json` | `listings/lawyers.csv` |
| Real Estate | `form/real_estate.json` | `listings/real_estate.csv` |
| Restaurants | `form/restaurants.json` | `listings/restaurants.csv` |
| Services | `form/services.json` | `listings/services.csv` |

## Import Instructions

### Step 1: Import Form Builder Data

1. Go to **Classified Listing → Form Builder** in your WordPress dashboard
2. Click **Import Form**
3. Upload the JSON file from the `form/` folder (e.g., `car.json`)
4. Complete the import process

### Step 2: Import Listings

1. Go to **Classified Listing → Export / Import** in your WordPress dashboard
2. Select the **Import** tab
3. Choose **Import Listings**
4. Upload the CSV file from the `listings/` folder (e.g., `car.csv`)
5. Map the fields and complete the import

> **Note:** Import the form builder data first before importing listings to ensure custom fields are properly configured.

## Requirements

- WordPress 6.0+
- [Classified Listing](https://wordpress.org/plugins/classified-listing/) plugin

## License

This sample data is provided for use with the Classified Listing plugin.
