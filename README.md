The CLI companion for dbman

Create a config file like this:

		{
			"uri": "http://db.example.com",
			"email": "myusername@example.com",
			"password": "your-secret-password"
		}

And save it as .dbman or any other file, the cli will search in your home directory for that file, you can always override it by passing -c=/path/to/config/file