# OnlineVotingSystem
A simple secure web app for online voting using **ASP.NET Core MVC**.

### Features
- Admin: Add/manage elections + candidates, see live results
- Voter: Register, login, vote once per election
- No multiple voting allowed
- Responsive design

### Tech Used
- ASP.NET Core MVC
- Entity Framework Core + SQL Server
- Bootstrap

### How to Run
1. Clone the repo  
2. Update connection string in `appsettings.json`  
3. Run `dotnet ef database update` (or use the SQL script)  
4. Start the project (`dotnet run` or F5 in Visual Studio)

**Default Admin** → Email: admin@example.com | Password: Admin@123
