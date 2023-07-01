# DutyBot
DutyBot is a fully interactive **discord** bot that allows you to keep track of who is on duty and who is not. This is done from a panel where the users on duty are shown, with two buttons that allow entry and exit from duty. It uses the latest features in discord such as **timestamps** so you don't have to waste your time with useless cacola!

This bot was designed, initially, for the **GTA V RP Servers** but can be used for other purposes as well.

## Features
- Entering and exiting the duty
- Viewing users in duty
- Authorize only certain roles to enter and exit the duty
- Forced management of entering and exiting the duty
- Manipulation of time spent in duty
- Viewing time spent in duty
- Adding and removing a role when entering and exiting the duty
- Ability to set up a **Manager** role that can manage the duty
- Log of entering and leaving the duty for each user
- Exporting the log in **.csv**, **.json** and **.txt** format

## How it works
First you need to invite the bot to your server. To do this you need to go to [this link](https://discord.com/api/oauth2/authorize?client_id=755202202201733120&permissions=8&scope=bot) and select the server where you want to invite the bot. Once this is done, the bot will send a message in the system channel.

Now the bot needs configuration, which can be done in two ways:
- **Automatic**: via the command `/autoconfig` the bot will explain what it will do and you simply have to confirm its actions, of course with `/settings` you can always change the bot's settings.
- **Manual**: through the command `/settings` the bot will show you a panel where you can configure the bot to your liking.

## Commands
The commands are divided into three categories:
- **User**: these are the commands that can be executed by all users.
- **Manager**: are the commands that can be executed only by users with the **Manager** role.
- **Admin**: are the commands that can be executed only by users with the **Admin** role.

### User
- `/help`: shows information about the bot.
- `/myhours`: shows the time spent in duty.

### Manager
- `/user add <@user>`: adds a user to the list of users on duty.
- `/user remove <@user>`: removes a user from the list of users on duty.
- `/user dutytime <@user>`: shows the time spent on duty of a user.
- `/time add <@user> <time>`: adds a time to a user's time spent on duty (in seconds).
- `/time remove <@user> <time>`: removes a time to the time spent in duty of a user (in seconds).
- `/time set <@user> <time>`: sets the time spent in duty of a user (in seconds).
- `/time reset <@user>`: resets the time spent in duty of a user.
- `/log <@user>`: shows the log of a user's entry and exit from duty.

### Admin
- `/autoconfig`: starts the automatic configuration of the bot.
- `/settings`: shows the bot's configuration panel.
- `/export <csv|json>`: exports the log of entry and exit from the duty of all users.

## ToDo
- [ ] Make the bot multi-language
- [ ] Add the ability to have multiple duty roles and be able to manage them separately.
- [ ] Decide which role to enter and exit the duty with.
- [ ] Create APIs to integrate the bot into other projects. 

## Gallery
![225356523-36905eb7-c9e9-412a-91ab-5ef21d89476e](https://user-images.githubusercontent.com/75610581/227705992-5434f02d-4d58-4935-bda7-9c4da5acfb73.png)
![225356855-c3a43204-df0d-4d8d-ac75-24d9dbb741a0](https://user-images.githubusercontent.com/75610581/227705994-9cc9574f-ef0b-462c-8e45-e076a3d3c8df.png)
![225355123-274d63ce-7bf0-4db8-a553-8b035022e1e0](https://user-images.githubusercontent.com/75610581/227705995-3e2ce513-9fa0-48c6-9a8f-d62a07947cf2.png)
![225356629-65022a1c-43c3-482c-a5b0-7e07044a3b5a](https://user-images.githubusercontent.com/75610581/227705996-36eef64c-f831-4c18-82f5-95a14ae8e59a.png)
![225355442-c5da541b-37f4-4bd6-a737-f3b1e28de357](https://user-images.githubusercontent.com/75610581/227705997-21c407ee-cbb5-496c-9a05-b67803483204.png)

