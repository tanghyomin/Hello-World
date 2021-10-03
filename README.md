# Hello-World







struct Student {
	int id;
	char name[20];
	char subject[20];
};

int main()
{
	Student a[5];
	Student* b;
	Student* c;

	b = &a[1];
	c = &a[3];

	a[0].id = 20193883;
	strcpy_s(a[0].name, "Tang Hongxia");
	strcpy_s(a[0].subject, "게임공학");

	cout << a[0].id << endl;
	cout << a[0].name << endl;
	cout << a[0].subject << endl;
	cout << endl;

	return 0;
}
