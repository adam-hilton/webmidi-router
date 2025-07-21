# webmidi-router
bare bones many-to-one midi device router for webmidi

For browsers with web midi support. Run site on localhost from main folder.

Choose input midi device(s) from multi-select list, choose single output.

Any midi signal channels on an input will mirror one-to-one to the output. For example, an incoming signal on Ch 9 will send to the output on Ch 9 only. By design it does not force input signal on specific channels to all channels at the output, which is common for available web midi devices with routing capabilities.

### To Do
* Add support for multiple outputs
* Add support for channel filtering
* Add channel matrix for re-mapping
