# glher_test_pkg
GLHER package for import testing

Notes:

9/6/2018
 - Moved "ID" column to last position
 - Renamed "MonID" to "ResourceID"
 - Sorted file by "ResourceID"
 - Loads succesfully using this command:
        `python manage.py packages -o import_business_data -s ../glher_test_pkg/business_data/heritage_asset.csv -ow overwrite -create_concepts create --bulk`
