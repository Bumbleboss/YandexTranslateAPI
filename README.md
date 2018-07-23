<img align="right" src="https://translate.yandex.com/icons/favicon.png" height="100" width="100">

## Yandex Translate API
A Java API wrapper for [Yandex Translate](https://translate.yandex.com/)
* Check the Terms of Use of API Yandex.Translate service before using this. You can find it [here](https://yandex.com/legal/translate_api/)

## How to use
For setting the token
```Java
YandexAPI api = new YandexAPI("your-token");
```
Requesting translations
```Java
System.out.println(inf.getYandexResponse("Hello there!", YandexLanguage.French)
	.getText().get(0));
```
Getting Language
```Java
System.out.println(api.getTextLanguage("Hello there!").getLang());
```

## Download
**Latest version**: [GitHub releases](https://github.com/Bumbleboss/YandexTranslateAPI/releases) [![](https://jitpack.io/v/Bumbleboss/YandexTranslateAPI.svg)](https://jitpack.io/#Bumbleboss/YandexTranslateAPI)


## Dependencies
* [gson-2.8.5](https://github.com/google/gson)
* [okhttp-3.10.0](https://github.com/square/okhttp)
* [okio-1.14.1](https://github.com/square/okio/)
* [logback-classic](https://github.com/qos-ch/logback/tree/master/logback-classic)