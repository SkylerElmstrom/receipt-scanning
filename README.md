# Receipt Scanning Using R

## Overview
At it's conception these tools will parse an image of a receipt into text. Later iterations of these tools will train machine models to parse, organize, label, and tag receipts for tracking grocery prices over time and by location. I set out to do this with R but there may be occassions where Python is necessary.

## Process

-  Scan receipt by taking an image with a smartphone.
-  Upload image to server that runs analysis script
-  Machine model dumps results of analysis into a temporary form
-  User checks form and submits data to database

## To-do

-  Simple Process Server (run locally?)
-  Analysis script
-  Build a form
-  Build DB, data tables
