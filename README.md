# data101-final-project
Data 101 @ COCC Winter 2026 Project

I have chosen to examine data from the Deschutes Public Library, specifically the "item records" which contain catalog information.  My goal is to be able to use a simple model to help classify the items using subject information to assign it to a "Wayfinder" category.  Wayfinder is the in-house categorization system used by DPL, taking into account other data including the Dewey Decimal Classification (DDC).

I started by cleaning the data.  I converted all possible values of the "wayfinder" column to a new curated and accurate list of "true_wayfinder" values given by DPL.  I also cleaned up the unicode and other characters to allow for better character recognition during analysis.
