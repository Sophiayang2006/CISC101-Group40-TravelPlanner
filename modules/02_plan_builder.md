### **Module 2 — Plan Builder (Options → Days)**

Change log (2025-11-18):
   > – Clarified inputs and outputs.
   > – Improved activity selection steps.
   > – Added basic handling for missing or limited data.

Create a short list of candidate activities (e.g., attractions, restaurants, parks) and each activity includes type, estimated duration, cost range, and distance.

Use a simple loop to build days:

for each day:
    pick Morning activity (near lodging)
    pick Midday activity (close by)
    pick Afternoon activity (different theme)
    pick Evening restaurant or optional event
