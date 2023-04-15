# ITSA 題目
## 題目
哈哈是我啦

12345
## 程式碼 & 說明
`123`
```cpp
#include <iostream>
using namespace std;

int funtion(int num) {
	if ((num == 0) || (num == 1))
		return num + 1;
	else
		return funtion(num - 1) + funtion(num / 2);
}
int main() {
	int num;
	cin >> num;
	cout << funtion(num) << endl;
	return 0;
}
```
*斜體*

**粗體**

***粗體+斜體***

~~刪除線~~

1\*2\*3

![cat](https://media.tenor.com/GTcT7HODLRgAAAAC/smiling-cat-creepy-cat.gif)