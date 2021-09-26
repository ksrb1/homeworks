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
		





