
> Try Azure Speech-To-Text [Speech APIs](https://gallery.azureml.net/MachineLearningAPI/89d229231a72471ebf7280fb5bd3e18c) via Node.js

## Install

0. Install the latest stable version of [Node.js](https://nodejs.org/) (version 0.10.x).

1. `$ git clone https://github.com/swells/text-to-speech.git`

2. `$ cd text-to-search`

3. `$ npm install`

## Configure

Before you run the example you must add your credentials here in `tts.js`:

```
CLIENT_ID    = '{{ PUT YOUR USER ID HERE }}'
SUBSCRIPTION = '{{ PUT YOUR SpeechAPI Subscription HERE }}'
```

I not confident that the `CLIENT_ID` is needed or not? The `SUBSCRIPTION` 
however is a must. You can can your subscription key by:

1. [Sign up](http://www.projectoxford.ai/speech) to use the Speech APIs
2. Login into the Azure portal
3. Navigate to: `MARKETPLACE-->SpeechAPIs-->Dashboard-->Subscription`

## Usage

```
$ node tts.js
```

This will write out a file called `speech.wav`. Open `speech.wav` and you should
hear the speech 'Is JavaScript a Functional Programming Language?' in English.

## License

The MIT License (MIT)

Copyright (c) 2015 Sean Wells

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
