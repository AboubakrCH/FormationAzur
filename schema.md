{
        "namespace": "nifi",
        "name": "people",
        "type": "record",
        "fields": [
            { "name": "_id", "type": "string" },
            { "name": "last_name", "type": "string" },
            { "name": "first_name", "type": "string" },
            { "name": "job", "type": "string" },
            { "name": "birthdate", "type": ["string", "null"], "default": null},
            { "name": "email", "type": "string" },
            { "name": "employer", "type": "string"}  
        ]
    }
