# Setup .Net core 2.2 in Ubuntu Server

>Register Microsoft key and feed

wget -q https://packages.microsoft.com/config/ubuntu/18.10/packages-microsoft-prod.deb

sudo dpkg -i packages-microsoft-prod.deb

> Install the .NET Runtime

sudo apt-get install apt-transport-https

sudo apt-get update

sudo apt-get install dotnet-sdk-2.2

sudo apt-get update

> Create .Net core console application

mkdire DotNetExercises
cd DotNetExercises

dotnet new console -o MyFirstApp

ls -l

cd MyFirstApp

dotnet run



>References
https://dotnet.microsoft.com/download/linux-package-manager/ubuntu18-10/sdk-2.2.102

