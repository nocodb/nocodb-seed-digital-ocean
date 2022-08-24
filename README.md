# NocoDB seed digital ocean

To create digital ocean snapshot of NocoDB seed, follow the steps below:

1. Install `packer` from digital ocean [here](https://www.packer.io/downloads)
2. Create a digital ocean token [here](https://cloud.digitalocean.com/account/api/tokens)
3. Run `DIGITALOCEAN_TOKEN=${your_token} packer build marketplace-image.json` to create snapshot

This will create a snapshot which can be used to spin up a droplet
