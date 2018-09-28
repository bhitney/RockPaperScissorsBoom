# Challenge 2 - Run the app

## Prerequisities

1. [Challenge 1 - Setup](./Setup.md) should be done successfuly.

## Introduction

With this second challenge you will be able to run "locally" in your Azure Cloud Shell the given "Rock Paper Scissors Boom" app.

## Challenges

1. Build and run the app from within Azure Cloud Shell
1. Test the app as an end-user, and play a game

## Success criteria

1. In Azure Cloud Shell, make sure `docker images` is showing you 5 Docker images.
1. In Azure Cloud Shell, make sure `docker ps` is showing you 2 Docker containers.
1. In your web browser, navigate to the app and play a game, make sure it's working without any error.
1. In Azure Cloud Shell, read the `docker-compose.yaml` file and the `Dockerfile*` files. What do you see? What do you understand? Are you able to quote 3 benefits/advantages of using Docker?
1. In Azure DevOps (Boards), from the Boards view, you could now drag and drop this user story associated to this Challenge to the `Resolved` or `Closed` column, congrats! ;)

## Tips

1. .NET Core is not installed in Azure Cloud Shell?! Don't worry, we have something for you: Docker!
  - You could for example run this command `docker-compose up --build -d` from the folder where the `docker-compose.yaml` file is.
1. Your app is deployed on your remote Azure Docker-machine, how to browse the app now, right? Just grab the IP address of your Azure Docker-machine. Give `docker-machine ls` a try ;)
1. To edit or read files from within Azure Cloud Shell, you could run `code .` to graphically browse the current folder and its files and subfolders. FYI, `cat` or `vi` are other alternatives.

## Advanced challenges

Too comfortable? Eager to do more? Here you are:

1. Instead of leveraging Docker via Azure Cloud Shell, you could configure your local machine with Visual Studio Code, or Visual Studio, installed .NET Core and deploy your app locally.

## Learning resources

- [SQL Server on Linux](https://docs.microsoft.com/en-us/sql/linux/sql-server-linux-overview)
- [ASP.NET Core](https://docs.microsoft.com/en-us/aspnet/core)
- [Why Docker?](https://www.docker.com/)

[Next challenge (Move to Azure SQL Database) >](./MoveToAzureSql.md)