# go_web_service_gin

An installation of Go 1.16 or later. For installation instructions, see Installing Go.
A tool to edit your code. Any text editor you have will work fine. 
A command terminal. Go works well using any terminal on Linux and Mac, and on PowerShell or cmd in Windows.
The curl tool. On Linux and Mac, this should already be installed. On Windows, it’s included on Windows 10 Insider build 17063 and later. For earlier Windows versions, you might need to install it. For more, see Tar and Curl Come to Windows.

Design API endpoints
You’ll build an API that provides access to a store selling vintage recordings on vinyl. So you’ll need to provide endpoints through which a client can get and add albums for users.

When developing an API, you typically begin by designing the endpoints. Your API’s users will have more success if the endpoints are easy to understand.

Here are the endpoints you’ll create in this tutorial.

/albums

GET – Get a list of all albums, returned as JSON.
POST – Add a new album from request data sent as JSON.
/albums/:id

GET – Get an album by its ID, returning the album data as JSON.
Next, you’ll create a folder for your code.