# manipal-mit-proxy
Quick Linux bash script to access internet from MIT via their proxy

## Current version
Tested on Archlinux with Gnome 3, should work on any others ditributions with a Gnome based graphic environment, git user configuration is also updated with the proxy settings

## Usage
```
$> ./internet-mit
Setting global proxy settings using 'gsettings'...
Setting user proxy settings for 'git'...
Manual proxy enabled, redirecting http, https, and ftp requests to 172.16.19.10:80
Be careful, a ^C doesn't reset the proxy settings !
Type 'q' or 'quit' for a clean exit
q
Unsetting global proxy settings using 'gsettings'...
Unsetting user proxy settings for 'git'...
Manual proxy disabled, default routes re-setted. Exiting...
$>
```

## Contribution
Don't hesitate to fork and make a pull-request if you want to contribute
