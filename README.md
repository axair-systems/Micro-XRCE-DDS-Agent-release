<img src="https://axair-assets.s3.eu-central-1.amazonaws.com/logos/axair_logo_rounded.png" width="90px" style="padding: 10px" align="left">

### `AXAIR System`

Micro-XRCE-DDS-Agent
</br>

## 👀 Overview

This repo build the Micro XRCE DDS Agent for Raspberry ARM64 based on the official [repo](https://github.com/eProsima/Micro-XRCE-DDS-Agent).

## ⬇️ How to install

```shell
curl -fL -o install.tar.gz https://github.com/axair-systems/Micro-XRCE-DDS-Agent-release/releases/download/microxrce-v3.0.1/microxrce-agent-v3.0.1-arm64.tar.gz
tar -xzvf install.tar.gz -C /usr/local/
ldconfig
```

## 📦️ Create a new release

1. Go to Actions > Build Micro XRCE-DDS Agent (ARM64). [link](https://github.com/axair-systems/Micro-XRCE-DDS-Agent-release/actions/workflows/build-agent.yml)
2. Click on `Run Workflow` button.
3. Enter `Git tag to build` which must match the tag from Micro XRCE DDS Agent official repo.
