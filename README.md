#Detect the language From Very Short Strings [langBot]

[![Build Status][build-badge]][build-status]
[![Coverage Status][coverage-badge]][coverage-status]


## What’s so cool about it?

1.  **langBot** is packaged with support for [17][standard] or [56][extended]
2.  **langBot** can detect the language from very short string.
3.  **langBot** is TfLite convertible so it is supported on mobile devices. 

(*) Based on the [Dataset](https://www.kaggle.com/wahabjawed/text-dataset-for-63-langauges) extracted from TedTalks

Text data extracted from TED Talks in 56 languages was converted
 into its binary representation of 4 byte for each letter, utf-8 encoding. 
Using Tensorflow, I trained a deep neural network to classify language based on small input. 
I achieved 91% accuracy with mostly spoken 17 languages and 80% accuracy with all 56 languages.

The model is Tflite convertible, so you can perform offline language detection on mobile devices.

## Issues

[[Back to top]](https://github.com/wahabjawed/language-detection-mobile#index)

You can report the bugs at the [issue tracker](https://github.com/wahabjawed/language-detection-mobile/issues)

**OR**

You can [message me](https://www.linkedin.com/in/abdul-wahab-47745163/) if you can't get it to work. In fact, you should message me anyway.

## Contributing

[[Back to top]](https://github.com/wahabjawed/language-detection-mobile#index)

This program was developed to secure an SQLite database with multi-lingual data. These basic ciphers were selected to provide weak encryption without impacting performance.
There could be other ciphers that could provide stronger encryption without degrading performance. If you know one, don't be shy to make a Pull request :)

For making contribution:

1. Fork it
2. Clone it

```
    git clone https://github.com/wahabjawed/language-detection-mobile.git
    cd language-detection-mobile
```

**use IntelliJ IDEA to open the project**

### Contributers

[[Back to top]](https://github.com/wahabjawed/language-detection-mobile#index)

- [@wahabjawed](https://github.com/wahabjawed/)   [visit website](https://www.linkedin.com/in/abdul-wahab-47745163/)

## License

Copyright 2020 Abdul Wahab

Licensed under the MIT License, (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

       https://opensource.org/licenses/MIT

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

[[Back to top]](https://github.com/wahabjawed/language-detection-mobile#index)
