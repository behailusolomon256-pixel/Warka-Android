# Warka News

Bilingual English and Amharic Flutter news app for Ethiopia.

## Build Android APK

GitHub Actions builds a release APK on every push to `main`.

1. Open the **Actions** tab.
2. Select **Build Warka Android APK**.
3. Download the `warka-news-release-apk` artifact after a successful run.

## Backend

The app supports Supabase configuration through the `SUPABASE_URL` and `SUPABASE_PUBLISHABLE_KEY` Dart compile-time environment variables. Configure a Supabase project and apply `schema.sql` before enabling live backend features.

This repository contains the Flutter source and build workflow. A successful APK build does not by itself configure a production backend.
