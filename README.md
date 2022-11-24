# HTV coins
A simple script to claim htv coin rewards remotely. Basically a bash script ported from [here](#credits)

## Running locally
```sh
git clone https://github.com/EverythingSuckz/htv-coins
cd htv-coins
chmod +x coins.sh
./coins.sh
```
## Run as a cron job in workflows

- [Fork](https://github.com/EverythingSuckz/htv-coins/fork) this repo
- Enable workflows in the `Actions` tab in your forked repository
> Using workflow is better because the script will auto run every 3 hours and auto-claim your rewards.

## Credits
- [hanime-auto-coins-collector](https://github.com/WeaveAche/hanime-auto-coins-collector)