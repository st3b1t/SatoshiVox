# SatoshiVoice
Donate voice to your Bitcoin full node


## Hardware requirements
![image](https://github.com/st3b1t/SatoshiVoice/assets/113633676/8966aaef-7e24-4618-a841-c649ecfe0262)
![image](https://github.com/st3b1t/SatoshiVoice/assets/113633676/27920e37-91ff-4db3-aa95-6b13228f7c71)

#### how to get it
- https://www.amazon.com/s?k=usb+external+audio
- https://it.aliexpress.com/w/wholesale-external-usb-audio.html

## Software requirements

- Python (usually just installed in a Bitcoin full node machine)
- [Festival](https://github.com/festvox/festival) (apt-get install festival)
- [eSpeak](https://github.com/espeak-ng/espeak-ng) (sudo apt install espeak)

## Features

- alert about Transaction confirmations you've been waiting for(or unespected tx in a certain address)
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

- trigger of the features listed above
- language to speech and audio volume
- voice (male, female and other available voices of the speech synthesis library)
- alert sounds
