# Eggdrop Management Console (1.3)
Allows you to manage your Eggdrop bot with a text based GUI - 
Official support sites: [Official Github Repo](https://github.com/fstltna/EggdropManagementConsole) - [Official Forum](https://eggdrop.retro-os.live/index.php/forum/our-eggdrop-utilities)


---

Edit "emc" and change the settings at the top if your Eggdrop bot is not in /home/eggdrop/eggdrop.

You will need to run cpan (as root) and install these modules:

- cpan -i UI::Dialog
- cpan -i Term::ReadKey
- cpan -i Term::ANSIScreen

Then run:

apt install mc

You also need to have my Eggdrop Startup Script installed.

I suggest you then add this to your /home/eggdrop/.bashrc file:
	export PATH=/home/eggdrop/bin:/home/eggdrop/EggdropManagementConsole:$PATH

After that you should log out and back in and now "emc" should work.
