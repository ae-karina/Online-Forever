# Setting `Playing` status
await client.change_presence(activity=discord.Game(name="a game"))

# Setting `Streaming` status
await client.change_presence(activity=discord.Streaming(name="My Stream", url=my_twitch_url))

# Setting `Listening` status
await client.change_presence(activity=discord.Activity(type=discord.ActivityType.listening, name="a song"))

# Setting `Watching` status
await client.change_presence(activity=discord.Activity(type=discord.ActivityType.watching, name="a movie"))
