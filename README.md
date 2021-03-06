Viska: Android App for Secure VoIP over XMPP
============================================

Viska is an XMPP client on Android with lots of modern features while focusing
on security. Viska heavily relies on
[`libviska-java`](https://github.com/seamlik/libviska-java) so most features and
drawbacks can be found in its project page. Some highlights of Viska include:

* Strictly conforms to XMPP standards without inventing custom protocols that
  breaks the federation.
* Supports audio chats (only, other features coming soon).
* Force encrypted communications

## Rationale and Audience

"Viska" is Swedish for "whisper", which implies that this project puts secure
communications at the top priority. We hope the apps built by the Viska project
can help people in the world enjoy the freedom of speech without having too much
technical knowledge.

In addition to this, enterprise companies can also benefit from using the Viska
project and providing private XMPP services to employees, in which way they can
protect classified information while improving productivity with modern
communications. Since the Viska projects are open source softwares and private
XMPP servers are trusted by the company, employees can collaborate using instant
messaging and video conferencing without worrying about being eavesdropped.

## License

The Android app Viska is free software and is licensed under the GNU General
Public License v3.0. The license can be found in the `LICENSE` file.

## Contributing

Please refer to the same section in the `README.md` in `libviska-java`.

### Building the app

Simply run

```shell
gradle build
```

At the moment, `libviska-java` is not yet available in JCenter. In order to
build the app, you may need to build `libviska-java` first and install it to
your local Maven cache.

### TODOs

  * Supports Android Wear
  * Supports Android TV
  * Supports exchanging contents via close-range connections
  * Supports video conferencing
  * Supports text messaging with OMEMO
  * Supports sending audio, pictures and geographic locations
  * Supports file transferring

## History

The Viska project was orignally a capstone project of 3 undergraduate students
from National Taichung University of Education:

* [Kai-Chung Yan (殷啟聰)](https://github.com/seamlik): Core engineering
* [BrokenPen (龔學良)](https://github.com/BrokenPen): Test engineering

With Professor [Lin-Huang Chang (張林煌)](http://www.ntcu.edu.tw/lchang) as the
mentor.

The conception stage of the project started in late October 2016 and the coding
phase officially started in February 2017. Since a graduate project lasts only
2 semesters, the goal of the project was only to implement the audio chat while
skipping the very basic XMPP messagings.