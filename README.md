# Price Comparison

Android app for comparing product prices across stores using barcode scanning.

Built as a university group project (2019). I led the Android development - barcode scanner, price comparison engine, product database, and UI/UX design.

## Features

- **Barcode Scanner** - scan product barcodes using ZXing library, with persistent ListView that survives screen rotation
- **Price Comparison** - compare prices of the same product across different stores
- **Product Database** - local product storage with name, barcode, price, and store information
- **Store API** - backend API integration for retrieving product and store data
- **GPS Integration** - attempted GPS-based store location (experimental)

## Tech

- Android SDK (Java)
- ZXing barcode scanner integration
- Custom ListView with dialog-based editing
- `onSaveInstanceState` / `onRestoreInstanceState` for rotation handling
- REST API client for price data
- Material Design with FloatingActionButton and Toolbar

## My Contributions

Looking at the commit history: I built the core application from March to June 2019:
- Barcode scanner activity and integration
- Price comparison logic (`FindCheapest`)
- Product model and database layer
- Screen rotation state preservation
- Dialog boxes for product editing
- UI layout and styling

Other team members contributed the API layer and documentation.

## Screenshots

See `DOKUMENTACJA FINAL VERSION.pdf` for full documentation with screenshots and architecture diagrams.
