# Antlia :sparkles:
Antlia Explorer for RNS Solutions Pvt Ltd

## Projects running on mainnets
[Antlia Explorer with RNS Solutions Pvt Ltd](http://ec2-3-15-152-52.us-east-2.compute.amazonaws.com:3000/)


## How to run Antlia

1. Copy `settings.json.default` to `settings.json`.
2. Update the RPC and LCD URLs.
3. Update Bech32 address prefixes.
4. Update genesis file location.

### Run in local

```
meteor npm install
meteor update
meteor --settings settings.json
```

### Run in production

```
./build.sh
```

It will create a packaged Node JS tarball at `../output`. Deploy that packaged Node JS project with process manager like [forever](https://www.npmjs.com/package/forever) or [Phusion Passenger](https://www.phusionpassenger.com/library/walkthroughs/basics/nodejs/fundamental_concepts.html).

---
## Donations :pray:

Antlia is always free and open. Anyone can use to monitor available Antlia hub or zones, or port to your own chain built with Antlia SDK. We welcome any supports to help us improve this project.

ATOM: `colors1p9nck20mlgf7nn9yg7rpf5mg0uuztn4skv4q6d`\
BTC: `1HrTuvS83VoUVA79wTifko69ziWTjEXzQS`\
ETH: `0xec3AaC5023E0C9E2a76A223E4e312f275c76Cd77`

And by downloading and using [Brave](https://brave.com/big517).
