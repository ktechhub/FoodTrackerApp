# FoodTrackerApp
A simple food tracker app with Flask 


# Run the following outside the folder
'''
from foodtracker.models import log_food, Food, Log
from foodtracker.extensions import db
from foodtracker import create_app
db.create_all(app=create_app())
'''
