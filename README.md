# homeworks

/*odd or even*/

	int number{};

	cout << "enter a number to check if its odd or even" << endl;
	cin >> number;

	if (number % 2 == 0) {
		cout << "number is even" << endl;
	}
	else {
		cout << "number is odd" << endl;
	}

/*number checker */

	int number{};

	cout << "enter a number to check if its positive, negative or zero" << endl;
	cin >> number;

	if (number == 0) {
		cout << "The number is a zero" << endl;
	}
	else if (number > 0) {
		cout << "The number is postive" << endl;
	}
	else {
		cout << "The number is negative " << endl;
	}


/*Profit or Loss*/

	int purchasePrice{};
	int salePrice{};

	cout << "What was the purchase price of the item" << endl;
	cin >> purchasePrice;
	cout << "What about the sale price of the item" << endl;
	cin >> salePrice;

	if ((salePrice - purchasePrice) > 0) {
		cout << "Profit!" << endl;
	}
	else {
		cout << "Loss!" << endl;
	}
		

	/*Name that Shape*/

	int shapeSides{};

	cout << "how many sides does your shape have?" << endl;
	cin >> shapeSides;

	if (shapeSides == 3) {
		cout << "This shape is a triangle" << endl;
	}else if (shapeSides == 4) {
		cout << "shape is a square" << endl;
	}
	else if (shapeSides == 5) {
		cout << "This shape is a pentagon" << endl;
	}
	else if (shapeSides == 6) {
		cout << "This shape is a hexagon" << endl;
	}
	else if (shapeSides == 7) {
		cout << "This shape is a heptagon or otherwise known as septagon" << endl;
	}
	else if (shapeSides == 8) {
		cout << "This shape is a octagon" << endl;
	}
	else if (shapeSides == 9) {
		cout << "This shape is a nonagon" << endl;
	}
	else if (shapeSides == 10) {
		cout << "This shape is a decagon" << endl;
	}
	else {
		cout << "This shape  cannot be identified with current limitations" << endl;
	}



