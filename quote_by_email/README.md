# Template payload

```json
{
    "from": {
        "email": "v.simonin@redspher.com",
        "name": "Vincent Simonin"
    },
    "quotation": {
        "pickup_date": "{{timestamp_start_g}}",
        "pickup_date_till": "{{timestamp_start_till_g}}",
        "delivery_date": "{{timestamp_end_g}}",
        "delivery_date_till": "{{timestamp_end_till_g}}",
        "ship_from": {
            "name": "Mr Laurent Venier",
            "street": "34, rue du couvents",
            "street_other": "près de la chambre",
            "zip_code": "57365",
            "city": "Ennery",
            "country_code": "FR",
            "lat": 43.34,
            "lng": 23.32
        },
        "ship_to": {
            "name": "Mr Laurent Venier",
            "street": "34, rue du couvent",
            "zip_code": "28001",
            "city": "Madrid",
            "country_code": "ES",
            "lat": 43.34,
            "lng": 23.32
        },
        "package_type": "parcel",
        "packages": [
            {
                "width": 1,
                "length": 10,
                "height": 1,
                "weight": 12.5,
                "quantity": 1,
                "stackable": true,
                "adr": {
                    "class": "1.4",
                    "un_code": "Code 14",
                    "packing_group": "III"
                },
                "reference": "#883864982"
            },
            {
                "width": 2,
                "length": 8,
                "height": 2,
                "weight": 8.5,
                "stackable": false,
                "quantity": 2,
                "reference": ""
            }
        ],
        "vehicle_type": "{{vehicle-type}}",
        "distance": "{{distance}}"
    }
}
```
