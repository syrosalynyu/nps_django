# Digital Ecosystem for National Park Service Annual Passholder Program
#### Capstone Project - Evelynn Kaplan - Ada Developers' Academy

## Introduction

**The problem**: 

The National Park Service of the United States has no database or other digital system storing records of annual passes sold to park visitors. Park rangers cannot look up visitors' annual passes at the gate, so passholders must have a physical pass to be admitted without paying an entrance fee.

**The solution**: 

A three-part digital ecosystem:
  * Database, custom REST API, interfaces for park rangers and passholders
    * [Deployed webapp](https://mynpspass.herokuapp.com/)
    * Built with: Django 2, Python 3, PostgreSQL 11
    * Stored in this repository
    
  * Data visualization dashboard
    * [Deployed site](https://npspassdashboard.herokuapp.com/)
    * Built with Python 3 and Plotly 4/Dash 1
    * Data from the custom Django REST API
    * [Github repository](https://github.com/evelynnkaplan/nps_dashboard)
    
  * Mobile app with digital annual pass 
    * [Expo build of app](https://expo.io/@ekaplan/nps_app)
    * Built with React Native 0.59 and Expo 3
    * Data from the custom Django REST API
    * [Github repository](https://github.com/evelynnkaplan/nps_app)
