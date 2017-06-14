# Lists

Lists are a more efficient way to have a range of values than an array. This is because lists can be added values to it whereas arrays are set once initialized in the script.

For example:

public List<string> myStrings;
myStrings = new List<string>();
myStrings.Add("Bob");

//outputs Bob/ adds bob to the list

public List<string> myStrings;
myStrings = new List<string>();
myStrings.Add("Bob","Grant","Bill");

//outputs Bob and Grant and Bill/ adds them to the list

public List<int> num;
num = new List<int>();
num.Add(1,2,3);

//outputs 1,2,3/ adds them to the list num

public List<float> myNums;
myNums = new List<float>();
myNums.Add(2.3,4.5);

//outputs 2.3,4.5 and adds them to the list

public List<string> letters;
letters = new List<string>();
letters.Add("l","h");

//outputs l,h and adds them to the list
