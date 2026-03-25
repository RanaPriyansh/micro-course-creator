# AI Micro Course Creator

[![GitHub](https://img.shields.io/badge/GitHub-000000?logo=github)](https://github.com/RanaPriyansh/micro-course-creator)
[![License](https://img.shields.io/github/license/RanaPriyansh/micro-course-creator)](https://github.com/RanaPriyansh/micro-course-creator/blob/main/LICENSE)
[![Last commit](https://img.shields.io/github/last-commit/RanaPriyansh/micro-course-creator)](https://github.com/RanaPriyansh/micro-course-creator/commits/main)

AI-powered micro course creator for iOS.

## Features
- AI generation using Claude API
- Stripe subscription payments ($29/month)
- Freemium model: 1 free generation
- PDF export (coming soon)

## Setup
1. Copy `.env.example` to `.env` and fill in your API keys
2. Run: `pip install -r requirements.txt`
3. Run: `uvicorn main:app --reload`
4. Open http://localhost:8000/docs for API docs

## Deployment
Deploy to Vercel, Railway, or Heroku. Set all environment variables.

## App Store
iOS app template: iOS/MicroCourseCreator/
Configure bundle ID: com.appfactory.microcoursecreator
Set RevenueCat product: AI Micro Course Creator

## Revenue
- Freemium: 1 free generation
- Pro: $29/month
- Target: 100+ subscribers in first month = $2900/mo
