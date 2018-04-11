# Lab16 Intro to APIs

## Todo List Api
This is a simple API that contains todo list items. You can get all todo list
items or get item by id. You can also create new todo list items and edit them.
You are also able to delete items.

## Tools Used
Microsoft Visual Studio Community Version 15.5.7

C#

ASP.Net Core

Postman

## Getting Started

Clone this repository to your local machine.
```
$ git clone 
```
Once downloaded, cd into the ```Lab16-Intro-to-APIs``` directory.
```
$ cd Lab16-Intro-to-APIs
```
The cd into ```Lab16-Intro-to-APIs``` directory.
```
$ cd Lab16-Intro-to-APIs
```
The cd into the second ```Lab16Phil``` directory.
```
$ cd Lab16Phil
```
Then run .NET build.
```
$ dotnet build
```
Once that is complete, run the program.
```
$ dotnet run
```

## API Calls

### Get

To get all items:

```http://localhost:XXXXX/api/todo```

To get item by ID:

```http://localhost:XXXXX/api/todo/X```

Create a new item:

```http://localhost:XXXXX/api/todo```

JSON example:

```
    {
        "name": "Take down christmas decorations",
        "isComplete": true
    }
```

Update existing item:

```http://localhost:XXXXX/api/todo/X```

JSON Example:
```
{
    "id": X,
    "name": "Take down christmas decorations",
    "isComplete": false
}
```

Delete an item:

```http://localhost:XXXXX/api/todo/X```