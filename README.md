## Welcome to MobiRuby for iOS (alpha)

Notice: It's for mruby and iOS hackers

Current build status: ![status](https://mobiruby-ci.s3.amazonaws.com/mobiruby-ios.png)


## Getting started

At first time, you might need to install the below gems:

```
sudo /usr/bin/gem install xcodeproj -v=0.3.5
sudo /usr/bin/gem install nokogiri
```

And then, type the commands in terminal:

```
git clone https://github.com/mobiruby/mobiruby-ios.git
cd mobiruby-ios
make setup
open mobiruby-ios.xcodeproj
```

If you use XCode beta version, you should modify ``bin/build-config.sh`` or set up xcode-select correctly.

It's tested only Mountain Lion and XCode 4.6.x

When you got 'ar' or something error, please check "command line tools" version in Xcode preference.


``app.rb`` is MobiRuby starting point. Let's change and hack it.



## Contributing

Feel free to open tickets or send pull requests with improvements.
Thanks in advance for your help!


## Authors

Original Authors "MobiRuby developers" are [https://github.com/mobiruby/mobiruby-ios/tree/master/AUTHORS](https://github.com/mobiruby/mobiruby-ios/tree/master/AUTHORS)


## License

 "MobiRuby for iOS" is released under the MIT license:

* http://www.opensource.org/licenses/mit-license.php
