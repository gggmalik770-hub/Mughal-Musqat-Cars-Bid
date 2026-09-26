# MUGHAL MUSCAT CAR BID — Android Project

This is a ready-to-open Android Studio project based on the supplied UI reference.

## Demo
- Admin email: `admin@mughal.om`
- Admin password: `admin123`
- New accounts are created as **pending** and must be approved by Admin.
- Cars can be posted and bids can be placed in the demo.
- Vehicle photo picker is wired to Android.

## Build
Open this folder in Android Studio, let Gradle sync, then:
Build → Build APK(s) → Build APK(s)

The current environment did not contain the Android SDK/Gradle toolchain, so a compiled APK could not be produced here. This package is the source project.

## Important for production
The included data layer uses local device storage for a working prototype. For real multi-device online accounts, approvals, chat, bidding, and shared vehicle listings, connect a backend such as Firebase or Supabase and add your own project keys.
