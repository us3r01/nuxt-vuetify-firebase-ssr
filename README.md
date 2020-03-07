# nuxt-vuetify-firebase-ssr
Nuxt on fire is a template to deploy Nuxt SSR Websites using Firebase hosting
# Install dependencies in functions dir
`$ cd functions`
`$ npm i install`
# Install dependencies in src dir
`$ cd src`
`$ npm i install`
# Change firebase project ID
> on the root folder 
`$ firebase login`
 > login into your firebase account, note that your project should be created first at the firebase web console 
 `$ firebase --use add`
 > select your project ID
 On the root dir 
 `$ firebase deploy`

> If you have an error because public_base dir does not exist, just create it using mkdir public_base at the root directory

# Demo 

https://nuxt-on-fire-a373f.firebaseapp.com/ 




