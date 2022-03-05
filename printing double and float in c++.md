[link](https://www.programiz.com/cpp-programming/float-double)
some notes :
since float has a precision of up to only 7 digits, it shows garbage values after its precision is exceeded.

Our double variable shows the correct number because it has a precision of 15 digits, while the number itself consists of 13 digits.

demo :
cout << fixed << setprecision(5) << (float)count_positive / float (n) << endl;
here fixed is being used to fix setprecisions value.
