## Teaching how to set up and install the robot on the host (Sipnel)
- Enter BotFather bot [@BotFather](https://t.me/BotFather) and create a new bot with `/new_bot` command and get the token.
- Log in to your host and go to the [`MySQL® Database Wizard'] section and create a new database and activate all the necessary accesses.
- Enter the [`public_html`] folder and create a new folder (any name) in this folder.
- Upload all the files and folders of the bee panel robot accurately and correctly in the folder you created.
- Run the ``install.html'' file, the address example you should run: (in this example, ``Domain.com'' is equal to your domain and ``folder'' is equal to the name of the folder you created)
```bash
https://Domain.com/folder/install/install.html
```
- Enter all the required entries on the page accurately and correctly and finally click on **Register and install the robot** button.
- You can get your numerical ID through the bot [@UserInfoBot](https://t.me/userinfobot).
- After filling all the required fields and pressing the button **register and install the robot**, a successful message will be sent to you in the robot.
- You can enter the robot management panel through the `/panel' or ``panel'' command.

 ## Teaching how to set up and install the bot on the server
- Log in to your server.
- Send the following command to install the robot.
```bash
bash <(curl -s https://raw.githubusercontent.com/ZanborPanel/ZanborPanel/main/zanbor.sh)
```- After executing this command, you have to wait a little until you reach the step of entering the domain.
- Enter your domain without ``http'' and ``https'' (the ``SSL'' domain must be active)
- After entering the domain, you have to wait a little until you reach the stage of creating the database.
- When you reach the database stage, it will ask you for the database information, if you want to create everything by default, press `enter' in both parts of the database stage.
- After the completion of this section, your database will be created, and in the next step, you will be asked three pieces of information that you must enter (`token` | `chat_id` | `domain`)
- After entering this information, the bee robot will be installed on your server.
- After installation, a message will be sent to you stating that the installation is successful in the robot.
- Enter the robot and `/start' the robot.

## Robot update tutorial
- To update the robot to the latest version, just run the following command:
```bash
bash <(curl -s https://raw.githubusercontent.com/ZanborPanel/ZanborPanel/main/update.sh)
```
- After executing this command, send command `1` and then `y` to update

## Frequently asked questions
- **Mandatory Joining**: The bot's mandatory joining lock is set through the robot's management panel, and there is no limit, that is, you can register 5 mandatory joinings.
- **Not registering the panel/server in the robot**: there are many reasons for the robot not logging in to your panel, for example, the ``CURL'' access is not fully open, there is an error in the description text.
- **set and hook error during installation**: This error occurs when the sent token is wrong or your host cannot send a request to the Telegram site to set and hook the robot, and the reason for sending the unsuccessful request is because ``curl'' access is closed or your host is Iranian. is
- **Wrong token error installation successful**: As it is clear from the error text, the token you sent for installation is wrong.
- **Database information error**: This error occurs when the database information you send is wrong (`name`, `username`, `password`).

## Necessary permissions to install on the host
- CURL access is open
- Opening ``curl_exec'' access
- Open the necessary ports, for example `8000`
- Necessary permission to create/delete/edit the file
- Host version should be `7.4` (soon it will work on all versions)

## Important points
- Do not apply any special edits on the source, if you have a special option in mind, you can register your comments in [Telegram group](https://t.me/ZanborPanelGap) ZanborPanelGap.
- Be sure to create a new bot to install the bot, that is, do not use your previous tokens.
- Enter the database information correctly.
- When adding a panel to the robot, if your panel has ssl, enter the input address with `https' and otherwise enter ``http''.
- To run the bot on the host, ssl domain must be active.
- If running on a host, the host must be foreign.
- If running on the server, you must know the ``roor'' password.

## **supported panels in the robot**
- Marzban
```bash
sudo bash -c "$(curl -sL https://github.com/Gozargah/Marzban-scripts/raw/master/marzban.sh)" @ install
```
- Sanaei
```bash
bash <(curl -Ls https://raw.githubusercontent.com/mhsanaei/3x-ui/master/install.sh)
```

## آموزش ساخت ربات در BotFather ( مرحله به مرحله )
- وارد ربات [@BotFather](https://t.me/BotFather) شوید و ربات را `/start` کنید.
- دستور `/newbot` را جهت ساخت ربات جدید ارسال کنید.
- نام ربات خود را ارسال کنید.
- یوزرنیم ربات خود را ارسال کنید ( اخر یوزرنیم باید `bot` باشد ).
- در صورت صحیح بودن یوزرنیم ارسالی ربات شما ساخته خواهد شد.
- نمونه توکن ربات :
```bash
66332901756:AAFsGVqaydeIeQJsqCcVbhSJ9fiyBLtR9VU0s
```

## Features of the panel bee robot
- Stylish design
- Multi panel
- Multiplane
- Add panel
- Support from Senai and Marzban panel
- Adding a plan with desired fields
- Smart subscription
- Complete server/panel status
- Complete user information
- Blocking the user
- Freeing Yazer
- Send a message to the user
- Public posting
- Public forwarding
- Unlimited forced join lock
- "zarinpal" and "idpay" port and card by card
- ``NOWPayments'' portal
- Set bot texts
- Instant report from the robot
- Manage bot statistics
- Complete management of the payment portal
- Complete management of the connection guide section
- Bot anti-spam management
- Test account management
- Smart link
- Creating a Qr code for the service
- Complete management of protocols
- Possibility of full panel/server management
- Possibility of complete management of added plans (remove/rename/change volume, etc.)
- Add unlimited admin
- Remove admin
- View the list of admins
- Full notification of service purchase and. . .
- Online support in the robot
- **Many options will be added to the robot in the next versions.**

## Support
- Bank Meli: `6037998195739130`
- Tron (TRX): `TAwNcAYrHp2SxhchywA6NhUEF4aVwJHufD`
- ETH, BNB, MATIC network (ERC20, BEP20): `0x36c5109885b59Ddd0cA4ea497765d326eb48396F`
- Bitcoin network: `bc1qccunjllf2guca7dhwyw2x3u80yh4k0hg88yvpk`

## Channel and bee panel group**Be sure to join the channel and group of the bee panel.**
- Channel: [@ZanborPanel](https://t.me/ZanborPanel)
- Group: [@ZanborPanelGap](https://t.me/ZanborPanelGap)
- Bot: [@ZanborPanelBot](https://t.me/ZanborPanelBot)
