# SDK for Python Clients CHANGELOG

## 1.0.0-beta.2 build 20220809

_Compatible with Lightstreamer Server since 7.2._<br>
_Released on 9 August 2022_

Fixed the exception `TypeError: can only concatenate str (not "int") to str` that could have concealed a network error.


## 1.0.0-beta.1 build 20220624

_Compatible with Lightstreamer Server since 7.2._<br>
_Released on July 2022_

The new Python client library introduces full support for the Unified Client API model that we have been introducing in all client libraries for some years now. The big advantage in using the Unified API is that the same consistent interface and behavior are guaranteed across different client platforms. In other words, the same abstractions and internal mechanisms are provided for very different platforms (Web, Andorid, Java, iOS, ...), while respecting the conventions, styles, and best practice of each platform.