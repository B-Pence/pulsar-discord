# Pulsar-Discord

<p align="center">
  
  This is a fork of [HelloWorld017/atom-discord](https://github.com/HelloWorld017/atom-discord). \
  The purpose of this fork is to update the package to better fit Pulsar. \
  Currently, I only plan to change rich presence features to list Pulsar instead of Atom, and to imporve documentation.
</p>

----

# Installation

### Dependencies:

To install pulsar-discord you will need to download the following dependencies:

- Git
- Node.js
- NPM

You can find download links, and install instructions for Git [here](https://git-scm.com). \
You can use the [Node.js installer](https://nodejs.org/en/download/) to install Node.js, and NPM, or you can follow [this guide](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm) for other options.

### Installing from Source (Windows):

Navigate to an empty directory, right click, \
(by default on windows 11 you need to select `Show more options`), \
then select `Open Git Bash Here`.

Now enter the following commands into the terminal:

```
git clone https://github.com/B-Pence/pulsar-discord.git
```
```
cd pulsar-discord
```
```
npm i
```
```
apm link
```

Then add pulsar to the registered games list under activity settings, and restart Pulsar.  

----

# Rich Presence Troubleshooting

* Check if Pulsar has been added in the registered games list under activity settings.  
* Check if the option `Share your activity with others` in activity privacy under activity settings is turned on.  
* Restart Pulsar, then Discord.
* Please follow the [steps from FAQ](https://github.com/B-Pence/pulsar-discord/blob/master/FAQ.md#not-showing).  
* Check if there are some outputs in developer tools `(ctrl + shift + i)`.

# FAQ / Known Errors

Please visit [here](https://github.com/B-Pence/pulsar-discord/blob/master/FAQ.md#faq) to see the FAQ

# License

Released under the [MIT](https://en.wikipedia.org/wiki/MIT_License) License.

>MIT License
>
>Copyright (c) 2018 HelloWorld017
>
>Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:
>
> The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
>
> THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
