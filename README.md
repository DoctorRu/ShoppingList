# Shopping List
## Ionic 3 / Firebase

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

