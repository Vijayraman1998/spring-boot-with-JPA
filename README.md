------------------- User Rest API'S details -----------------------------
Add Collector - http://localhost:8080/springbootcrudrest/api/v1/users

Method : POST

Sample Request Json : 
{
	"key": 123456,
	"logKey": 1234568,
	"latitude": "sample latitude",
	"longitude": "sample longitude"
}
	
Sample Response Json :
{
    "id": 1,
    "key": 123456,
    "logKey": 1234568,
    "latitude": "sample latitude",
    "longitude": "sample longitude",
    "createdAt": 1516197019198,
    "createdBy": "sm_user",
    "updatedAt": 1516197019198,
    "updatedby": "sm_user"
}
--------------------------------------------------------------------------
Update Collector - http://localhost:8080/springbootcrudrest/api/v1/users/1

Method : PUT

Sample Request Json : 

{
	"key": 123456,
	"logKey": 54321,
	"latitude": "update latitude",
	"longitude": "update longitude "
}
Sample Response Json :
{
    "id": 1,
    "key": 123456,
    "logKey": 123456,
    "latitude": "update latitude",
    "longitude": "update longitude ",
    "createdAt": 1516195877000,
    "createdBy": "sm_user",
    "updatedAt": 1516196212491,
    "updatedby": "sm_user"
}
--------------------------------------------------------------------------
Get Collector - http://localhost:8080/springbootcrudrest/api/v1/users/1

Method : GET

Sample Request Json : 
Sample Response Json :
{
    "id": 1,
    "key": 123456,
    "logKey": 123456,
    "latitude": "update latitude",
    "longitude": "update longitude ",
    "createdAt": 1516195877000,
    "createdBy": "sm_user",
    "updatedAt": 1516196212000,
    "updatedby": "sm_user"
}

--------------------------------------------------------------------------
Get Collectors - http://localhost:8080/springbootcrudrest/api/v1/users

Method : GET

Sample Request Json : 
Sample Response Json :
[
    {
        "id": 1,
        "key": 123456,
        "logKey": 123456,
        "latitude": "update latitude",
        "longitude": "update longitude ",
        "createdAt": 1516197019000,
        "createdBy": "sm_user",
        "updatedAt": 1516197078000,
        "updatedby": "sm_user"
    },
    {
        "id": 2,
        "key": 123456,
        "logKey": 1234568,
        "latitude": "sample latitude",
        "longitude": "sample longitude",
        "createdAt": 1516197065000,
        "createdBy": "sm_user",
        "updatedAt": 1516197065000,
        "updatedby": "sm_user"
    }
]
--------------------------------------------------------------------------
Delete Collector - http://localhost:8080/springbootcrudrest/api/v1/users/1

Method : DELETE

Sample Request Json : 
Sample Response Json :{deleted : true}
