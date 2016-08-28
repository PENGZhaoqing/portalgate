# UcasPortal (Doorkeeper)

## Introduciton

UcasPortal is a campus portals information system for Chinese Academy of Science, which is developed to provide as unified access entrance for the faculties, students and campus application developers.

UcasPortal ultizes [OAuth 2.0](https://oauth.net/2/) protocol to achieve the interactive communication within mulitple heterogeneous web apps, therefore, UcasPortal can act as the main login panel for campus users and web app developers who are going to conncet their apps with UcasPortal. 

### For campus users 

For the campus users, which means faculities and students, UcasPortal is a SSO (Single Sign-on) platform. Once campus users logined in UcasPortal, they could have access to all relative campus applications without providing other username and password.

### For campus applications developers

For campus applications developers, which means the developers owning the inner campus applications (Campus Libaray System...) and the third-part applications (those ultizes the campus users info to provide their service such as selling take-out food), UcasPortal is the OAuth provider and inforamtion holder.

Developers could login in UcasPortal and create new apps and configue the OAuth conncetion to owned app. Besides, in UcasPortal, Developers can also decide the target users who they are providing service to. 

This repertory is the main portal and we have a sample application just for [demo](https://github.com/PENGZhaoqing/UcasPortal_SampleApp) 

## Getting Started
 
### Prerequisities


### Installation

```
$ bundle install
$ rake db:migrate
$ rake db:seed
```




 
 

