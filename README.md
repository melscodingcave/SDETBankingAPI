# SDETBankingAPI
A sample RESTful API built in C# to support typical banking operations — suited for SDET practice and automation testing.

## 🧠 Overview
This project exposes endpoints for:
- Account creation
- Balance inquiry
- Transaction posting
- Account statements

Ideal for QA engineers and SDETs to write tests against a realistic API.

## 🚀 Tech Stack
- ASP.NET Core Web API
- C# 10
- Swagger/OpenAPI

## 📦 Run Locally
```bash
git clone https://github.com/melscodingcave/SDETBankingAPI.git
cd SDETBankingAPI
dotnet run
```
Swagger UI will be available at:
```
http://localhost:5000/swagger
```
## 📌 Endpoints Overview
| Method | Endpoint | Description |
| ------ | --------- | ----------- |
| GET | /health | API health |
| POST	| /accounts |	Create account |
| GET |	/accounts/{id} |	Get account |
| POST |	/transactions |	Post transaction |

## 🧪 Testing
Write functional and integration tests using RestSharp or HttpClient.
