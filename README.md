# Developer Screening Process & React Native Assessment
This task is designed to evaluate your React Native expertise, coding style, testing and ability to create UI.

## Overview
We are working on creating dynamic forms and would like to recreate this interface using React Native.

You are free to use any existing UI libraries.

## Datasource
Sample data will look like below:
```
[
    {
        "key": "7d5a2af7-51c9-4915-a362-82dad827dff7",
        "label": "Text fields",
        "type": "input",
        "info_message": "",
        "validation_message": "",
        "addition_text": "",
        "attrs": {
            "required": false
        },
        "short_key": "",
        "deleted": false,
        "name": "text",
        "type_ref": "text",
        "icon": "bi-type",
        "display": true,
        "column": {
            "width": 120
        },
        "visibility": {
            "table": true,
            "form": true,
            "board": true
        }
    },
    {
        "key": "e8a78403-97d9-4d23-9221-9e4b6dff1d7c",
        "label": "Select list",
        "type": "select",
        "info_message": "",
        "validation_message": "",
        "addition_text": "",
        "attrs": {
            "required": false
        },
        "short_key": "",
        "deleted": false,
        "name": "select",
        "type_ref": "dropdown",
        "icon": "bi-list-check",
        "display": true,
        "column": {
            "width": 120
        },
        "options": {
            "list": [
                {
                    "label": "Option 1",
                    "value": "option1"
                },
                {
                    "label": "Option 2",
                    "value": "option2"
                },
                {
                    "label": "Option 3",
                    "value": "option3"
                }                
            ]
        },
        "visibility": {
            "table": true,
            "form": true,
            "board": true
        }
    },
    {
        "key": "c1fb2b56-a5f7-496e-88cb-3684d2628ee9",
        "label": "Checkbox",
        "type": "checkbox",
        "info_message": "",
        "validation_message": "",
        "addition_text": "",
        "attrs": {
            "required": false
        },
        "short_key": "",
        "deleted": false,
        "name": "checkbox",
        "type_ref": "boolean",
        "icon": "bi-check-square",
        "display": true,
        "column": {
            "width": 120
        },
        "visibility": {
            "table": true,
            "form": true,
            "board": true
        }
    },
    {
        "key": "1eefb041-2f8e-4438-bbe0-18cdc717ccd8",
        "label": "Date field",
        "type": "input",
        "info_message": "",
        "validation_message": "",
        "addition_text": "",
        "attrs": {
            "required": false
        },
        "short_key": "",
        "deleted": false,
        "name": "date",
        "type_ref": "date",
        "icon": "bi-calendar-date",
        "default_value": "+0d",
        "display": true,
        "column": {
            "width": 120
        },
        "visibility": {
            "table": true,
            "form": true,
            "board": true
        }
    },
    {
        "key": "6492fcb7-caca-43cf-ad6b-0c3e531524fc",
        "label": "Time",
        "type": "input",
        "info_message": "",
        "validation_message": "",
        "addition_text": "",
        "attrs": {
            "required": false
        },
        "short_key": "",
        "deleted": false,
        "name": "time",
        "type_ref": "time",
        "icon": "bi-clock",
        "default_value": "+0h",
        "column": {
            "width": 120
        },
        "display": true,
        "visibility": {
            "table": true,
            "form": true,
            "board": true
        }
    },
    {
        "key": "d721549e-e6c6-474f-a362-edd24d3df599",
        "label": "Photo",
        "type": "photo",
        "info_message": "",
        "validation_message": "",
        "addition_text": "",
        "attrs": {
            "required": false
        },
        "short_key": "",
        "deleted": false,
        "name": "photo",
        "type_ref": "photo",
        "icon": "bi-camera",
        "display": true,
        "column": {
            "width": 120
        },
        "options": {
            "size": 800,
            "settings": [
                {
                    "label": "x-large",
                    "value": 1200
                },
                {
                    "label": "large",
                    "value": 1000
                },
                {
                    "label": "medium",
                    "value": 800
                },
                {
                    "label": "small",
                    "value": 600
                }
            ]
        },
        "visibility": {
            "form": true
        }
    },
    {
        "key": "d722696b-6150-46a9-bf1e-10266a05a554",
        "label": "Signature",
        "type": "signature",
        "info_message": "",
        "validation_message": "",
        "addition_text": "",
        "attrs": {
            "required": false
        },
        "short_key": "",
        "deleted": false,
        "name": "signature",
        "type_ref": "signature",
        "icon": "bi-pen",
        "display": true,
        "column": {
            "width": 120
        },
        "visibility": {
            "form": true
        }
    }
]
```

## Saving
Form data can be saved either in memory or using native storage.

Please store the form data as an object, either in memory or in native storage. An example format would be:

```
{
    "id": "unique_id",
    "created_at": "date_time",
     “7d5a2af7-51c9-4915-a362-82dad827dff7“:”Record 1”,
    "1eefb041-2f8e-4438-bbe0-18cdc717ccd8":"2021-10-10",
    ...
}
```
## UI

![screen_1](https://github.com/user-attachments/assets/ef4c74e6-0cf7-4e2a-843a-689d86860d67)

![screen_2](https://github.com/user-attachments/assets/dc26cf9c-2b61-47be-9638-c364a40d5c09)

![screen_3](https://github.com/user-attachments/assets/9d197c56-42bb-4c5c-9ef5-5ed64e936b4a)

![screen_4](https://github.com/user-attachments/assets/3d012bc6-7351-4ef9-a5be-3085bf2d6fc2)

![screen_5](https://github.com/user-attachments/assets/54d829ce-60d3-41dc-95f8-da649ac97201)

![screen_6](https://github.com/user-attachments/assets/cab53d85-c0ee-49da-83ce-6c8c75cfc72f)








