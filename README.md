crc8js
======

CRC-8 checksum generation in javascript


usage
======

```javascript
  var sample_text = "Hi. I need a checksum."

  // convert sample text to array of bytes
  var byte_array = sample_text.split('').map(function(x){return x.charCodeAt(0)})

  var crc8 = new CRC8()
  
  var checksum = crc8.checksum(byte_array)

```
