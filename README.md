# Perform the following actions for Docker Container Creation:
Create Sample console .NET App and Test
Create Dockerfile
Create Image
Create Container, Run & Test
Stop Container
Remove Container

## Create Sample console .NET App and Test
Step 1: 

dotnet new console -o App -n DotNet.Docker

Step 2:

cd App

Step 3:

dotnet build

Step 4: To check the result "Hello, World!"

dotnet run 

Step 5: To open visual studio code editor

code . 

Step 6: check Program.cs to verify the Hellow World Message!

open Program.cs

Step 7:

dotnet publish -c Release

## Create Docker Container
docker build -t hw-image -f Dockerfile .

docker run -it hw-image

docker ps -a

docker start <generated-container-name>

docker stop <generated-container-name>

docker rm <generated-container-name>

docker rmi <image-name>

docker image
