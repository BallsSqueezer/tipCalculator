# Pre-work - *Tip*

**Tip** is a tip calculator application for iOS.

Submitted by: **Hien Quang Tran**

Time spent: **12** hours spent in total

## User Stories

The following **required** functionality is complete:

* [x] User can enter a bill amount, choose a tip percentage, and see the tip and total values.
* [x] Settings page to change the default tip percentage.

The following **optional** features are implemented:
* [x] UI animations
* [ ] Remembering the bill amount across app restarts (if <10mins)
* [x] Using locale-specific currency and currency thousands separators.
* [x] Making sure the keyboard is always visible and the bill amount is always the first responder. This way the user doesn't have to tap anywhere to use this app. Just launch the app and start typing.

The following **additional** features are implemented:

- [x] Customize tint color and button to make the app more attractive
- [x] Automatically split the total amount depending on the number of people (eg. If there are 4 people and total amount is $120, each will have to pay $30)

## Video Walkthrough 

Here's a walkthrough of implemented user stories:

![Video Walkthrough](https://github.com/BallsSqueezer/tipCalculator/blob/master/Tip%20Calculator.gif)

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

I did not locale currency because in my opinion no matter which currency the user uses, it is going to print out the same number. There is no need to switch from $ to any other currencies, this is not a currency coverter app.

It should work perfectly on iPhone 5/5s, I could have made it work for other screen size if  had spent more time.

## License

    Copyright [2016] [Hien Quang Tran]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
