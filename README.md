# What is Warden?
Warden is an API wrapper for the [Get IP Intel](https://getipintel.net/) that allows servers to automatically prevent clients with identified proxy IPs from joining.

# How does Warden work?
Warden uses the Get IP Intel API to send the IP address of the joining player and verify that it is not a proxy. If it is, it automatically kicks the player. That's it!

# How do I add Warden to my server?
Download Warden from this GitHub Repo and insert the "warden" folder into your garrysmod/addons folder. This will allow you to configure options such as kick messages, cache timers, and more in the warden/lua/autorun/server/sv_warden.lua file.

# Setting up Warden
As of v2.0, no setup is necessary! If you'd like to edit some configuration variables, you can find the configuration in sv_warden.lua.

# Links
* [Get IP Intel](https://getipintel.net/)
