# GPS/GNSS receiver plug-in Sample for RICOH THETA
This sample plug-in does receives data from the GPS / GNSS receiver and updates the position information inside the camera.<br>
This project is based on [ricohapi/theta-plugin-sdk](https://github.com/ricohapi/theta-plugin-sdk).

## Usage
The wifi lamp shows the state of the GPS / GNSS receiver.
* Magenta: Positioning can not be done
* Green: Positioning is available
* Yellow: Permission error or poor contact
* Red: Equipment is not connected

The movie recording lamp shows the status of whether you can shoot single images or interval shots.  
Unlit is a state in which one image shooting is possible,and lit is a state in which interval shooting is possible.  
The state changes each time you press the mode button.

You can shoot by pressing the shutter button in single shooting mode.  
You can start and stop interval shooting by pressing the shutter button in interval shooting mode.

## Development Environment
### Camera
* RICOH THETA V Firmware ver.2.50.1 and above

### SDK/Library
* RICOH THETA Plug-in SDK ver.1.0.1
* [mik3y/usb-serial-for-android](https://github.com/mik3y/usb-serial-for-android)

### Development Software
* Android Studio ver.3.1
* gradle ver.4.6


## License

```
Copyright 2018 Ricoh Company, Ltd.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```