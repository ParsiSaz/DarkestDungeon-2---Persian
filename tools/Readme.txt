BuildPotFile - a player-accessible .exe for building iron_crown.pot from English source .txt files to support changes to foreign languages.

Version 1.0

Install Microsoft .NET library:
1) Navigate to ".NET 5.0 Runtime" download: https://aka.ms/dotnet-core-applaunch?missing_runtime=true&arch=x64&rid=win10-x64&apphost_version=5.0.10+
2) Under "Run console apps", choose "Download x64"
3) From your Downloads, run "dotnet-runtime-5.0.10-win-x64.exe"

Usage:
1) Open the Windows terminal and navigate to the folder with BuildPotFile.exe.
2) Run BuildPotFile.exe, either with no parameters which will default the paths to "../Sources/" and "../Poedit/", or with two parameters for the source .txt directory and the destination .pot directory.
