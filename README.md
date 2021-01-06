# TestAPI
Fake API for testing

Install JSON Server

npm install -g json-server
Create a db.json file with some data

{
    "lookbook": [
        {
            "Id": "1",
            "Timestamp": "2019-10-15T18:04:24.528595",
            "User": null,
            "LogbookCategory": "Management",
            "ObjectType": "Undefined",
            "LogbookEvent": "",
            "LogbookSource": "",
            "Content": "The user group 'OverallManagers' has been created.",
            "ToBeConfirmed": false,
            "AffectedDevices": [],
            "AffectedEndoscopes": []
        },
        {
            "Id": "2",
            "Timestamp": "2019-10-15T18:04:24.811347",
            "User": null,
            "LogbookCategory": "Management",
            "ObjectType": "Undefined",
            "LogbookEvent": "",
            "LogbookSource": "",
            "Content": "The role 1 has been assigned to user group 4.",
            "ToBeConfirmed": false,
            "AffectedDevices": [],
            "AffectedEndoscopes": []
        }
    ]
}




Start JSON Server

json-server --watch db.json
Now if you go to http://localhost:3000/lookbook you see the data


