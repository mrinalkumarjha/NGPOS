# APOS

# Some vscode extension useful for this project:
Docker
C#
sqlserver
Nuget Gallary
c# Dev Kit


# Important command :

dotnet tool install --global dotnet-ef --version 8.0.8 : To install migration tool globally
dotnet ef database update -s API -p Infrastructure  : To update db based on migration
dotnet ef migrations add InitialCreate -s API -p Infrastructure : To create migration based on your entity
dotnet ef migrations remove -s API -p Infrastructure : To remove migration 


