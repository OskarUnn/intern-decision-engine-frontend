# TICKET-101 conclusion

## Positive aspects
- Simple and clean form design
- Checking the National ID code length before making an API call to reduce requests

## Places for improvement
- An API call is made on even the slightest movement of the slider resulting in hundreds of API calls when moving the slider, this can be fixed by making an api call only on the release of the slider
- API url is hard-coded, this should be given via environment variable and leaving the default value to the current hard-coded value
- Loan period slider minimum and maximum do not respond to the constraints set in the requirements
- Constraints are hard-coded, these should be decleared in a config file (like in the backend repo)

## Most important shortcoming
An API call is made on even the slightest movement of the slider resulting in hundreds of API calls when moving the slider
