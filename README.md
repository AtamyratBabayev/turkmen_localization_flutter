# Localization for turkmen language
Unfortunately, I didn't find any support for turkmen language, so I decided to add my own support,
most of information you could find by going to: https://docs.flutter.dev/development/accessibility-and-localization/internationalization

## How to use it
```
return const MaterialApp(
  title: 'Localizations Sample App',
  localizationsDelegates: [
    TmMaterialLocalization.delegate, //add this one to add localization
    GlobalMaterialLocalizations.delegate,
    GlobalWidgetsLocalizations.delegate,
    GlobalCupertinoLocalizations.delegate,
  ],
  supportedLocales: [
     const Locale('tm', 'TM'), //Turkmenistan - turkmen language
     const Locale('ru', 'RU'), 
     const Locale('en', 'GB')  
  ],
  home: MyHomePage(),
);
```
## Requirements
> Flutter 2.0
 Means that works with nullsafety.

##LICENSE
 MIT
