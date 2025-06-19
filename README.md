![](https://img.shields.io/badge/build-1.0.0+1-brightgreen)

<!-- PROJECT LOGO -->
<br />
<div align="center">
 <img alt='logo_design' src='https://firebasestorage.googleapis.com/v0/b/weddinghallbooking-2ba28.appspot.com/o/protiflio_images%2Fmunasab_design.png?alt=media&token=22e96739-867a-4d4b-bee8-870fc2c2fdf0'/>
<h2 align="center"></h2>

  <p align="center">
Munasab is a comprehensive app for booking events with all their details.
    <br />
    <br />
    <p>      
      <a href='https://play.google.com/store/apps/details?id=najeeb.aslan.wedding_hall_booking_client&pcampaignid=web_share'>
        <img alt='Get it on Google Play' src='https://play.google.com/intl/en_us/badges/static/images/badges/en_badge_web_generic.png' height="80"/>
      </a>
    </p>
  </p>
</div>

## About The Project
Munasab is an innovative application designed to streamline the management and booking of services related to events and occasions. Whether you are planning a wedding, corporate event, or any special occasion, A comprehensive app for booking and managing all event services - Event halls, Audio equipment, Koshat, Fashion, Meals services, and Photography studios.

<img src="line-gradient.svg" alt="line break" width="100%" height="3px">

# Application Screens:(Screens 50+)

  <td><img src="https://firebasestorage.googleapis.com/v0/b/weddinghallbooking-2ba28.appspot.com/o/protiflio_images%2Fmunaab-client_github1.jpg?alt=media&token=b07914c8-83e3-4619-9b17-960aa08e72a1" alt="Image 2"></td>
  <td><img src="https://firebasestorage.googleapis.com/v0/b/weddinghallbooking-2ba28.appspot.com/o/protiflio_images%2Fmunaab-client_github2.webp?alt=media&token=44b6cfd7-2561-4596-8477-34a9a3d00370" alt="Image 2"></td>

<img src="line-gradient.svg" alt="line break" width="100%" height="3px">


# Quick Links
- [About The Project](#about-the-project)
- [Project Overview](#project-overview)
- [Application Screens](#application-screens)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Technical Architecture](#technical-architecture)
- [Platform Support](#platform-support)
- [Application Structure](#application-structure)
- [Libraries and tools used ](#libraries-and-tools-used)


## Project Overview
  - 🏛 Event halls.
  - 🎤 Audio equipment.
  - 👗 Fashion rentals.
  - 🎨 Decor services (Koshat).
  - 🍽 Meals services
  - 📸 Photography studios

## ✨Features

### Core Platform Features
✔ **Multi-service Booking System**  
✔ **Location-based Discovery**  
✔ **Bilingual UI (Arabic/English)**  
✔ **Rating & Review System**  

### Communication Features
💬 **Real-Time Messaging**  
- Instant text communication
- Image/document sharing
- Read receipts & typing indicators

🔔 **Notification System**  
- Push notifications
- Unread message counters
- Booking status alerts

🛡 **Security Features**  
- End-to-End Encryption
- User Verification  
- Report/Block Functionality  

### More Details
- ✔ Intuitive Booking System - Date selection, guest management.
- ✔ Smart Discovery - Location-based search with filters (price, capacity, ratings).
- ✔ Personalization - Favorite items and personalized recommendations.
- ✔ Transparent Reviews - Verified customer ratings and feedback.
- ✔ Real-Time Chatting between owner service and client 💬.
- ✔ Search - Filter - Sort Details 🔍.
- ✔ Support two languages Arabic - English (🇸🇦,🇺🇸).
- ✔ Support Dark and Light Mode (☽,☀️).
- ✔ Account Signin - SignUp - Reset Password and Account delete.

<img src="line-gradient.svg" alt="line break" width="100%" height="3px">


## Core Technical Features
- 📱 Responsive UI Support (Mobile & Tablet)
- 🔒 Secure Authentication - Email, Google Sign-In .
- 🌍 Localization - Full RTL support for Arabic and ENglish with locale-aware formatting.
- 📱 Cross-Platform - Built with Flutter for iOS and Android.
- 💬 Chat: Firebase Realtime Database + Firestore
- 🔔 Real-Time Updates - Firebase-powered notifications.


## Technologies Used
- Frontend: Flutter (Bloc state management)
- Backend: Firebase (Auth, Firestore, Cloud Functions)
- Maps: Google Maps Platform

## Technical Architecture
```graph TD  
    A[Flutter Client] --> B[Firebase]  
    B --> C[Authentication]  
    B --> D[Firestore Database]  
    B --> E[Cloud Storage]  
    B --> F[Realtime Database]  
    A --> G[Google Maps API]  
    A --> H[Cached Network Images] 
  ```

# Platform Support
| Android | iOS |
| :-----: | :-: |
|   ✔️    | ✔️  |

<img src="line-gradient.svg" alt="line break" width="100%" height="3px">

## Application structure

After successful build, your application structure should look like this:

```
├── android
├── assets
├── ios
├── lib
├── main.dart
├── core
│   ├── constants
│   ├── extensions
│   ├── helper
│   ├── networking
│   ├── router
│   ├── services
│   ├── theme
│   ├── widgets
├── features
│   ├─── auth feature
│   ├─── audio feature
│   ├─── bookings feature
│   ├─── chat feature
│   ├─── home feature
│   ├─── fashion feature
│   ├─── favorite feature
│   ├─── hall feature
│   ├─── koshat feature
│   ├─── studio feature
│   ├─── meals feature
│   ├─── offers feature
│   ├─── onboarding feature
│   ├─── settings feature
│   ├─── notifications feature
└── app.dart
```

<img src="line-gradient.svg" alt="line break" width="100%" height="3px">

## 📚 Libraries and Tools Used

### Core Architecture
- **flutter_bloc** ^9.1.0 - State management
- **equatable** ^2.0.7 - Value equality comparison
- **get_it** ^8.0.3 - Dependency injection

### Firebase Services
- **firebase_core** ^3.13.0 - Firebase core
- **firebase_auth** ^5.5.2 - Authentication
- **cloud_firestore** ^5.6.6 - Cloud database
- **firebase_storage** ^12.4.5 - File storage
- **firebase_messaging** ^15.2.5 - Push notifications
- **firebase_ui_firestore** ^1.7.1 - Firestore UI components

### UI Components
- **timelines** - Custom timeline widgets
- **custom_google_map** - Enhanced map components
- **flutter_svg** ^2.0.17 - SVG rendering
- **carousel_slider** ^5.0.0 - Image carousels
- **flutter_rating_bar** ^4.0.1 - Rating widgets
- **wolt_modal_sheet** ^0.11.0 - Animated modals
- **table_calendar** ^3.1.3 - Calendar widgets
- **smooth_page_indicator** ^1.2.1 - Page indicators
- **flutter_staggered_grid_view** ^0.7.0 - Staggered grids
- **animations** ^2.0.11 - Pre-built animations
- **coupon_uikit** ^0.2.1 - Coupon UI components
- **local_hero_transform** ^0.0.7 - Hero animations

### Maps & Location
- **google_maps_flutter** ^2.12.1 - Google Maps integration
- **google_maps_flutter_android** ^2.16.0 - Android maps
- **google_maps_flutter_platform_interface** ^2.11.0 - Maps platform

### Media Handling
- **cached_network_image** ^3.4.1 - Image caching
- **image_picker** ^1.1.2 - Image selection
- **flutter_image_compress** ^2.4.0 - Image compression
- **saver_gallery** ^4.0.1 - Media saving

### Chat & Messaging
- **flutter_chat_types** ^3.6.2 - Chat data models
- **chat_bubbles** - Custom chat bubbles
- **flutter_link_previewer** - Link previews in chat

### Authentication
- **google_sign_in** ^6.3.0 - Google Sign-In
- **sign_in_with_apple** ^7.0.1 - Apple Sign-In
- **intl_phone_field** ^3.2.0 - Phone number input

### Localization & Internationalization
- **easy_localization** ^3.0.7+1 - Multi-language support
- **intl** ^0.19.0 - Internationalization

### Networking
- **http** ^1.3.0 - HTTP requests
- **dio** ^5.8.0+1 - Advanced HTTP client
- **pretty_dio_logger** ^1.4.0 - Network logging

### Utilities
- **flutter_screenutil** ^5.9.3 - Responsive design
- **url_launcher** ^6.3.1 - URL handling
- **uuid** ^4.5.1 - Unique ID generation
- **timeago** ^3.7.0 - Relative time formatting
- **rxdart** ^0.28.0 - Reactive extensions
- **device_info_plus** ^11.3.3 - Device information

### Storage & Persistence
- **shared_preferences** ^2.5.3 - Local storage
- **path_provider** ^2.1.5 - File system access

### Testing & Debugging
- **device_preview** ^1.2.0 - App preview
- **flutter_native_splash** ^2.4.6 - Splash screen

### Permissions
- **permission_handler** ^12.0.0+1 - Runtime permissions

### App Features
- **upgrader** ^11.3.1 - App update prompts
- **external_app_launcher** ^4.0.3 - External app integration
- **flutter_local_notifications** ^18.0.1 - Local notifications
