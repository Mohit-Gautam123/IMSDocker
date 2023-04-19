# IMSDocker
{
	"info": {
		"_postman_id": "68414c53-c2f3-4fa3-951a-bbb30b5346a2",
		"name": "API TESTING",
		"schema": "https://schema.getpostman.com/json/collection/v2.1.0/collection.json",
		"_exporter_id": "26946989"
	},
	"item": [
		{
			"name": "New Request",
			"request": {
				"method": "GET",
				"header": []
			},
			"response": []
		},
		{
			"name": "New Request",
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "{\r\n\r\n\"data\": {\r\n\r\n\"email\": \"smitha@test.in\",\r\n\r\n\"first_name\": \"Smitha\",\r\n\r\n\"last_name\": \"Menon\"\r\n\r\n}\r\n\r\n} ",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "https://reqres.in/api/users",
					"protocol": "https",
					"host": [
						"reqres",
						"in"
					],
					"path": [
						"api",
						"users"
					]
				}
			},
			"response": []
		},
		{
			"name": "New Request",
			"request": {
				"method": "PUT",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "{\r\n\r\n\"data\": {\r\n\r\n\"id\": 5,\r\n\r\n\"email\": \"smitha@test.in\",\r\n\r\n\"first_name\": \"Test\",\r\n\r\n\"last_name\": \"Name\"\r\n\r\n}\r\n\r\n}"
				},
				"url": {
					"raw": "https://reqres.in/api/users/5",
					"protocol": "https",
					"host": [
						"reqres",
						"in"
					],
					"path": [
						"api",
						"users",
						"5"
					]
				}
			},
			"response": []
		},
		{
			"name": "New Request",
			"request": {
				"method": "DELETE",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "{\r\n\r\n\"id\": 5\r\n\r\n}"
				},
				"url": {
					"raw": "https://reqres.in/api/users",
					"protocol": "https",
					"host": [
						"reqres",
						"in"
					],
					"path": [
						"api",
						"users"
					]
				}
			},
			"response": []
		}
	]
}
