# django-models4-cw_b

### Exercise 1
Create a model called ```State``` with ```state_name```.

Create a model called ```Citizen``` with ```citizen_first_name```, ```citizen_last_name```. and ```citizen_state``` that is a ForeignKey that references ```State``` (deleting a Citizen should NOT delete corresponding state)

Add KY, TN, and MS to states using the Django Admin console.

Add 3 citizens using the Django Admin console and assign your first Citizen to ```TN``` and the other 2 Citizens to ```KY```

Add an endpoint ```citizens/``` that will list all Citizens and their States

Add an endpoint ```chgstate/``` that will change the State of the last Citizen from ```KY``` to ```MS```

Confirm changes by using the ```citizens/``` endpoint
