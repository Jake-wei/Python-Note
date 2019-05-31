#Pthon-Note
、Python2.x版本之前，raw_input()函数和input()函数都是用于创建输入框，并获取用户输入内容；Python3.x版本以后整合两个函数，只保留了input()函数。
raw_input()和input()函数之间的不同： raw_input()函数获取用户输入内容时，用户可以输入任何类型的数据，，即用户输入的可以是number，也可以是string,无论用户输入什么类型的数据，raw_iunput()函数的返回值类型就是字符串string; 而Python2.x版本之前的input()函数只能获取python表达式类型的输入内容，所谓的python表达式类型，即如果是number，就是数字，如果是string类型的内容，那么就应该输入“string”，一定要加引号，如果输入mok，没有加引号，这函数返回错误。
Python3.x版本中只剩下了input()函数，input()函数获取所有类型的输入，并返回字符串类型。

关于读取文件：可以理解为是三个步骤：一、开放获取文件权限；二、读取文件内容；三：关闭文件权限。
关于写入文件：和读取文件类似，三个步骤：一、开放获取文件的权限
python3.x之后都是用open(“path”)函数来打开问
