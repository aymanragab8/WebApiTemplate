# 1) Packages 
 1- Swashbuckle.AspNetCore
 2- Microsoft.EntityFrameworkCore.SqlServer
 3- Microsoft.EntityFrameworkCore.Tools
 4- Microsoft.AspNetCore.Identity.EntityFrameworkCore
 5- Microsoft.AspNetCore.Authentication.JwtBearer
 6- System.IdentityModel.Tokens.Jwt

# 2) Change the launchsettings.json file to make default path of root of the project is swagger
    "launchBrowser": true
    "launchUrl": "swagger"

# 3) Create ApplicationUser class that inherits from IdentityUser class 
# 4) Create ApplicationDbContext class that inherits from IdentityDbContext<ApplicationUser> class 
# 5) Configure Program.cs
  1- Add ConnectionString + Add ConnectionString in appsettings.json
  2- Add Swagger

# 6) Add Migration and Update Database to add the tables of Identity to the database


 

 