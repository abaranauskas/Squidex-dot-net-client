# C# Blog Sample

You can create an app with prepulated schemas directly in Squidex.

## How to run it?

Just press F5 in Visual Studio, thats it.

- OR -

    dotnet start

## How to run it with a custom app?

Have a look to the configuration first: [appsettings.json](Sample.Blog/appsettings.json)

You have to change the following settings:

* `appName`: The name of your app.
* `clientId`: The client id, usually: '`appName`:default'
* `clientSecret`: The secret for your client. You can get it from the Squidex UI.

Optionally:

* `url`: The url to your squidex instance, e.g. `http://localhost:5000` if you run it locally.