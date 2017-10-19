# TaxiNewYork
My analysis of the data provided on Kaggle.
Link to the competition: https://www.kaggle.com/c/nyc-taxi-trip-duration
The description of the data taken from the Kaggle website
File descriptions

    train.csv - the training set (contains 1458644 trip records)
    test.csv - the testing set (contains 625134 trip records)
    sample_submission.csv - a sample submission file in the correct format

Data fields

    id - a unique identifier for each trip
    vendor_id - a code indicating the provider associated with the trip record
    pickup_datetime - date and time when the meter was engaged
    dropoff_datetime - date and time when the meter was disengaged
    passenger_count - the number of passengers in the vehicle (driver entered value)
    pickup_longitude - the longitude where the meter was engaged
    pickup_latitude - the latitude where the meter was engaged
    dropoff_longitude - the longitude where the meter was disengaged
    dropoff_latitude - the latitude where the meter was disengaged
    store_and_fwd_flag - This flag indicates whether the trip record was held in vehicle memory before sending to the vendor because the vehicle did not have a connection to the server - Y=store and forward; N=not a store and forward trip
    trip_duration - duration of the trip in seconds

