# HTV coins
A simple script to claim htv coin rewards remotely. Basically a bash script ported from [here](#credits)

## Running locally
```sh
git clone https://github.com/EverythingSuckz/htv-coins
cd htv-coins
chmod +x coins.sh "your-hanime-email" "your-hanime-password"
./coins.sh
```
## Run as a cron job in workflows

- [Fork](https://github.com/EverythingSuckz/htv-coins/fork) this repo
![fork image](https://i.imgur.com/i3FGwOv.png)
- Goto `Settings` of your forked repository > `Secrets` which can be found on the side bar > `Actions`> `New Repository Secrets`.
![settings image](https://i.imgur.com/n9XvGGv.png)
![secrets tab image](https://i.imgur.com/aANpibr.png)
- Set `HTV_EMAIL` and `HTV_PASSWORD` as secrets.
![email image](https://i.imgur.com/JKbRJvl.png)
![password image](https://i.imgur.com/Gtoedo0.png)
- Enable workflows in the `Actions` tab in your forked repository.
![actions tab image](https://i.imgur.com/UUo8Dkr.png)
![accept actions image](https://i.imgur.com/bf8W44x.png)
![enable workflow image](https://i.imgur.com/09bDt6C.png)
> Using workflow is better because the script will auto run every 3 hours and auto-claim your rewards.

## Credits
- [hanime-auto-coins-collector](https://github.com/WeaveAche/hanime-auto-coins-collector)