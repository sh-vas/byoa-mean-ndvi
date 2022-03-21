# Mean NDVI: Bring Your Own Algorithm Repository
Mean NDVI repository for EDC BYOA example


```## Parameters 

[
    {
        "description": "Area of interest",
        "id": "aoi",
        "name": "Area of interest",
        "optional": false,
        "type": "bbox"
    },
    {
        "description": "Spatial Resolution. The following values are allowed: 10m, 20m and 60m",
        "id": "spatial_res",
        "name": "Spatial Resolution",
        "optional": true,
        "restriction": {
            "type": "choice",
            "value": [
                0.00001,
                0.00002,
                0.00006
            ]
        },
        "type": "float"
    },
    {
        "description": "Time Range",
        "id": "time_range",
        "name": "Time Range",
        "optional": false,
        "type": "daterange"
    }
]
