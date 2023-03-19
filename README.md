Objective
---------
Predict whether a fatal/serious casualty occurs using road traffic data about the casualty, accident, and vehicles involved.

Relevance
---------
LV= wants to identify fatal/serious casualties early to ensure a quick response is given to those affected.
Further to this, LV= wants to know the most important characteristics of serious casualties to help customers stay safe on the road.

Data
----
> Casualty (primary)
	Description: Data on the person(s) involved in the casualty
	Found as casualty_train.csv
> Accident (secondary)
	Description: Data on the accident itself, including time, location, and police response
	Found as accident_train.csv
	NOTE - This dataset is only for the advanced participants.
> Vehicle (secondary)
	Description: Data on the vehicles involved in the casualty
	Found as vehicle_train.csv
> Data Dictionary (reference)
	Description: Field descriptions and value mappings
	Found as DatathonReference

Target
------
Whether `casualty_severity` in the casualty dataset is fatal (1) or serious (2), where (3) is slight. 
Note: will need to map target to binary 1 (fatal, serious) and 0 (slight).
