# SatoshiVox
Donate voice to your node.

*This repository is for now a container of proposals and specifications..*

## Mission
Toward a home automation of the Bitcoin full nodes.

## Use Case

Anyone of you who has a full node working there in the living room or bedroom or bathroom and doesn't want to open ssh/https/rpc/tor to check if it works can be informed from time to time with voice messages from the node itself:
*"Heila' I'm still alive and validating blocks!"*

## Hardware requirements
usually a machine used for bitcoin full node does not include an audio output or a network card, for this I suggest devices of this kind for operation

![image](https://github.com/st3b1t/SatoshiVox/assets/113633676/68472cb6-e7b6-49c6-a34a-250f4176e02f)


#### how to get it
- https://www.amazon.com/s?k=usb+external+audio
- https://it.aliexpress.com/w/wholesale-external-usb-audio.html

## Software requirements

Text to Speech engine:

- Python (usually just installed in a Bitcoin full node machine)
- [Festival](https://github.com/festvox/festival) OR [eSpeak](https://github.com/espeak-ng/espeak-ng)
- Bitcoin node with RPC and ZMQ enabled

## Features
Each of the following alerts is Text to Speech (TTS) technology that converts text into spoken audio, the content is entirely configurable.

- alert about Transaction confirmations you've been waiting for(or unespected tx for certain address or label in watchonly wallet)
- alert about new Block reads height, transactions count, mining-pool name
- alert about Fees de/increase
- alert about Watch-only Wallet(transactions, check amount)
- alert about Memory/Disk critical usage
- alert about dis/connected new peers (ip or Tor nickname)
- alert about Whales transactions
- alert abount Halving Countdown (with nice ending music)
- reads texts found in new OP_RETURN
- reads random Satoshi quotes

## Configurations

- trigger or disable each features listed above
- language to speech and audio volume
- voice (male, female and other available voices of the speech synthesis library)
- alert sounds
