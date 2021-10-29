# Test ngx-avatars

This repo is made to test the integration of `ngx-avatars`.

Unfortunatly, it failed.

Here the error:

```
$ ng serve

✔ Browser application bundle generation complete.

Initial Chunk Files | Names         |      Size
vendor.js           | vendor        |   2.20 MB
polyfills.js        | polyfills     | 128.49 kB
main.js             | main          |   8.76 kB
runtime.js          | runtime       |   6.61 kB
styles.css          | styles        |   1.18 kB

                    | Initial Total |   2.34 MB

Build at: 2021-10-29T21:52:44.414Z - Hash: 1f52841bf09f27269108 - Time: 4188ms

./src/app/app.module.ts:5:0-43 - Error: Module not found: Error: Can't resolve 'ngx-avatars' in '~/test-ngx-avatars/src/app'

Error: src/app/app.component.html:1:1 - error NG8001: 'ngx-avatars' is not a known element:
1. If 'ngx-avatars' is an Angular component, then verify that it is part of this module.
2. If 'ngx-avatars' is a Web Component then add 'CUSTOM_ELEMENTS_SCHEMA' to the '@NgModule.schemas' of this component to suppress this message.

1 <ngx-avatars facebookId="1508319875"></ngx-avatars>
  ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

  src/app/app.component.ts:5:16
    5   templateUrl: './app.component.html',
                     ~~~~~~~~~~~~~~~~~~~~~~
    Error occurs in the template of component AppComponent.


Error: src/app/app.component.html:2:1 - error NG8001: 'ngx-avatars' is not a known element:
1. If 'ngx-avatars' is an Angular component, then verify that it is part of this module.
2. If 'ngx-avatars' is a Web Component then add 'CUSTOM_ELEMENTS_SCHEMA' to the '@NgModule.schemas' of this component to suppress this message.

2 <ngx-avatars googleId="1508319875"></ngx-avatars>
  ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

  src/app/app.component.ts:5:16
    5   templateUrl: './app.component.html',
                     ~~~~~~~~~~~~~~~~~~~~~~
    Error occurs in the template of component AppComponent.


Error: src/app/app.component.html:3:1 - error NG8001: 'ngx-avatars' is not a known element:
1. If 'ngx-avatars' is an Angular component, then verify that it is part of this module.
2. If 'ngx-avatars' is a Web Component then add 'CUSTOM_ELEMENTS_SCHEMA' to the '@NgModule.schemas' of this component to suppress this message.

3 <ngx-avatars twitterId="1508319875"></ngx-avatars>
  ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

  src/app/app.component.ts:5:16
    5   templateUrl: './app.component.html',
                     ~~~~~~~~~~~~~~~~~~~~~~
    Error occurs in the template of component AppComponent.


Error: src/app/app.component.html:4:1 - error NG8001: 'ngx-avatars' is not a known element:
1. If 'ngx-avatars' is an Angular component, then verify that it is part of this module.
2. If 'ngx-avatars' is a Web Component then add 'CUSTOM_ELEMENTS_SCHEMA' to the '@NgModule.schemas' of this component to suppress this message.

4 <ngx-avatars instagramId="dccomics" size="70"></ngx-avatars>
  ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

  src/app/app.component.ts:5:16
    5   templateUrl: './app.component.html',
                     ~~~~~~~~~~~~~~~~~~~~~~
    Error occurs in the template of component AppComponent.


Error: src/app/app.component.html:5:1 - error NG8001: 'ngx-avatars' is not a known element:
1. If 'ngx-avatars' is an Angular component, then verify that it is part of this module.
2. If 'ngx-avatars' is a Web Component then add 'CUSTOM_ELEMENTS_SCHEMA' to the '@NgModule.schemas' of this component to suppress this message.

5 <ngx-avatars skypeId="1508319875"></ngx-avatars>
  ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

  src/app/app.component.ts:5:16
    5   templateUrl: './app.component.html',
                     ~~~~~~~~~~~~~~~~~~~~~~
    Error occurs in the template of component AppComponent.


Error: src/app/app.component.html:6:1 - error NG8001: 'ngx-avatars' is not a known element:
1. If 'ngx-avatars' is an Angular component, then verify that it is part of this module.
2. If 'ngx-avatars' is a Web Component then add 'CUSTOM_ELEMENTS_SCHEMA' to the '@NgModule.schemas' of this component to suppress this message.

6 <ngx-avatars gravatarId="adde9b2b981a8083cf084c63ad86f753"></ngx-avatars>
  ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

  src/app/app.component.ts:5:16
    5   templateUrl: './app.component.html',
                     ~~~~~~~~~~~~~~~~~~~~~~
    Error occurs in the template of component AppComponent.


Error: src/app/app.component.html:7:1 - error NG8001: 'ngx-avatars' is not a known element:
1. If 'ngx-avatars' is an Angular component, then verify that it is part of this module.
2. If 'ngx-avatars' is a Web Component then add 'CUSTOM_ELEMENTS_SCHEMA' to the '@NgModule.schemas' of this component to suppress this message.

7 <ngx-avatars gravatarId="user@gmail.com"></ngx-avatars>
  ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

  src/app/app.component.ts:5:16
    5   templateUrl: './app.component.html',
                     ~~~~~~~~~~~~~~~~~~~~~~
    Error occurs in the template of component AppComponent.


Error: src/app/app.component.html:8:1 - error NG8001: 'ngx-avatars' is not a known element:
1. If 'ngx-avatars' is an Angular component, then verify that it is part of this module.
2. If 'ngx-avatars' is a Web Component then add 'CUSTOM_ELEMENTS_SCHEMA' to the '@NgModule.schemas' of this component to suppress this message.

8 <ngx-avatars src="assets/avatar.jpg"></ngx-avatars>
  ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

  src/app/app.component.ts:5:16
    5   templateUrl: './app.component.html',
                     ~~~~~~~~~~~~~~~~~~~~~~
    Error occurs in the template of component AppComponent.


Error: src/app/app.component.html:9:1 - error NG8001: 'ngx-avatars' is not a known element:
1. If 'ngx-avatars' is an Angular component, then verify that it is part of this module.
2. If 'ngx-avatars' is a Web Component then add 'CUSTOM_ELEMENTS_SCHEMA' to the '@NgModule.schemas' of this component to suppress this message.

9 <ngx-avatars name="John Doe"></ngx-avatars>
  ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

  src/app/app.component.ts:5:16
    5   templateUrl: './app.component.html',
                     ~~~~~~~~~~~~~~~~~~~~~~
    Error occurs in the template of component AppComponent.


Error: src/app/app.component.html:10:1 - error NG8001: 'ngx-avatars' is not a known element:
1. If 'ngx-avatars' is an Angular component, then verify that it is part of this module.
2. If 'ngx-avatars' is a Web Component then add 'CUSTOM_ELEMENTS_SCHEMA' to the '@NgModule.schemas' of this component to suppress this message.

10 <ngx-avatars value="75%"></ngx-avatars>
   ~~~~~~~~~~~~~~~~~~~~~~~~~

  src/app/app.component.ts:5:16
    5   templateUrl: './app.component.html',
                     ~~~~~~~~~~~~~~~~~~~~~~
    Error occurs in the template of component AppComponent.


Error: src/app/app.component.html:12:1 - error NG8001: 'ngx-avatars' is not a known element:
1. If 'ngx-avatars' is an Angular component, then verify that it is part of this module.
2. If 'ngx-avatars' is a Web Component then add 'CUSTOM_ELEMENTS_SCHEMA' to the '@NgModule.schemas' of this component to suppress this message.

 12 <ngx-avatars
    ~~~~~~~~~~~~
 13   facebookId="userFacebookID"
    ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
...
 22   [round]="true"
    ~~~~~~~~~~~~~~~~
 23 >
    ~

  src/app/app.component.ts:5:16
    5   templateUrl: './app.component.html',
                     ~~~~~~~~~~~~~~~~~~~~~~
    Error occurs in the template of component AppComponent.


Error: src/app/app.component.html:22:3 - error NG8002: Can't bind to 'round' since it isn't a known property of 'ngx-avatars'.
1. If 'ngx-avatars' is an Angular component and it has 'round' input, then verify that it is part of this module.
2. If 'ngx-avatars' is a Web Component then add 'CUSTOM_ELEMENTS_SCHEMA' to the '@NgModule.schemas' of this component to suppress this message.
3. To allow any property add 'NO_ERRORS_SCHEMA' to the '@NgModule.schemas' of this component.

22   [round]="true"
     ~~~~~~~~~~~~~~

  src/app/app.component.ts:5:16
    5   templateUrl: './app.component.html',
                     ~~~~~~~~~~~~~~~~~~~~~~
    Error occurs in the template of component AppComponent.


Error: src/app/app.module.ts:4:30 - error TS2307: Cannot find module 'ngx-avatars' or its corresponding type declarations.

4 import { AvatarModule } from 'ngx-avatars';
                               ~~~~~~~~~~~~~


Error: src/app/app.module.ts:9:12 - error NG1010: Value at position 1 in the NgModule.imports of AppModule is not a reference
  Value could not be determined statically.

9   imports: [BrowserModule, AvatarModule, HttpClientModule],
             ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

  src/app/app.module.ts:9:28
    9   imports: [BrowserModule, AvatarModule, HttpClientModule],
                                 ~~~~~~~~~~~~
    Unknown reference.




** Angular Live Development Server is listening on localhost:4200, open your browser on http://localhost:4200/ **


✖ Failed to compile.

```
