# Hytopia Node Github Runner

The ultimate Hytopia node setup using Github actions. It is completely free. You set it up once and forget it.

If you like it, donate TOPIA to me: 0xa0e87A8d2e5775263d408065af196AfF93ebFD6a

## How to set up

Set up wallet delegation following instructions [here](https://discord.com/channels/889939924655169616/1224774876628521165/1224775886562398298)

Fork this repo, and go in `Settings -> Secrets and variables -> Actions -> New repository secret`. Add `NODE_WALLET_KEY` and set the value to the private key exported from Metamask.

You're all set!

## How do I know if the setup is working

Go in `Actions -> Run node`, you will see that it runs every day at 0 am and 12 am UTC. If you want to run it manually, click `workflow_dispatch -> Run workflow`.

Click on the action history to see its logs.

## Is my private key safe?

It's [reasonably safe](https://docs.github.com/en/actions/security-guides/using-secrets-in-github-actions#limits-for-secrets) and your secret is only known to Github.
