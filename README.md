    
/*Starting a Band*/

    bool musician = 0; //only added this cause in the ppt you said we needed a bool
	string musicianValue{};
	string typeOfIntrument{};

	cout << "Oh hey do you play any instruments? yes or no would be fine" << endl;
	cin >> musicianValue;

	if (musicianValue == "yes"){
		musician = true;
	}
		
	
	if (musician == 1) {
		cout << "Oh cool, what instrument do you play? " << endl;
		cin >> typeOfIntrument;

		if (typeOfIntrument == "guitar") {
			cout << "Oh nice, I really need a guitarist Please join me!!!" << endl;
		}
		else if(typeOfIntrument == ("drum") || typeOfIntrument == ("drums")) {
			cout << "Oh nice, I really need a drummer Please join me!!!" << endl;
		}
		else {
			cout << "Aww I only needed a guitarist or a drummer" << endl;
		}

	}
	else {
		cout << "aww i wanted to start a band" << endl;
		return 0;
	}
