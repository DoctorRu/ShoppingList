# Shopping List
## Ionic 3 / Firebase

## Screenshots

![alt tag](https://raw.githubusercontent.com/DoctorRu/shoppinglist/master/screenshots/01.jpg)
![alt tag](https://raw.githubusercontent.com/DoctorRu/shoppinglist/master/screenshots/02.jpg)
![alt tag](https://raw.githubusercontent.com/DoctorRu/shoppinglist/master/screenshots/03.jpg)
![alt tag](https://raw.githubusercontent.com/DoctorRu/shoppinglist/master/screenshots/04.jpg)



Notes: 
First of all go to Firebase site and create a Realtime Database and change the rules to

	{
	  "rules": {
	    ".read": "true",
	    ".write": "true"
	  }
	}

then create 

	src/keys/firebase/firebase.credentials.ts
	
with your firebase database details:

	export const FIREBASE_CONFIG =
	
		{
			apiKey: "<your apiKey>",
			authDomain: "<your authDomain>",
			databaseURL: "<your dtabaseURL>",
			projectId: "<your projectId>",
			storageBucket: "<your storageBucket>",
			messagingSenderId: "<your messagingSenderId>"
		};

### Run
	ionic lab