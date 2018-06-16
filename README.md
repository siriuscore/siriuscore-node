# siriuscore-node

A Sirius full node for building applications and services with Node.js. A Sirius node is extensible and can be configured to run additional services.

## Install

```bash
npm install -g siriuscore-node
siriuscore-node start
```

## Configuration

siriuscore includes a Command Line Interface (CLI) for managing, configuring and interfacing with your siriuscore Node.

```bash
siriuscore-node create -d <sirius-data-dir> mynode
cd mynode
siriuscore-node install <service>
siriuscore-node install https://github.com/yourname/helloworld
```

This will create a directory with configuration files for your node and install the necessary dependencies. For more information about (and developing) services, please see the [Service Documentation](docs/services.md).

## Add-on Services

There are several add-on services available to extend the functionality of siriuscore:

- [Sirius Insight API](https://github.com/siriuscore/insight-api)
- [Sirius Explorer](https://github.com/siriuscore/sirius-explorer)
