# gozwave
An opensource golang lib for zwave-controller communication thru serial-api. Tested and developed with a usb connected AEOTEC Z-Stick Gen5

Sigmadesigns have released some of the zwave documentation and it can be found here http://z-wave.sigmadesigns.com/design-z-wave/z-wave-public-specification/

## Can I use this library in production?
This library is in the early development state and is not ready for production in any way. The api is subject to changes and we will probably redesign it a couple of times before its ready.

## Contribute
We love any help we can get! If you are interested just fork the lib, make changes and send ous a pull request. 

## TODO
- [x] Basic communication between controller and lib (serial-api)
- [x] Get a list of nodes
- [ ] Identify each node and look them up in a device database
- [ ] Save/Load the identified nodes in a file
- [ ] List, get and set parameters in a node
- [ ] Implement commands to send to the nodes
- [ ] Receive and decode events from sensors
