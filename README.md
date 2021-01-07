# TODO
Linux console todo utility for recording tasks.

Features:  
- view the list of tasks  
- add new tasks  
- delete old tasks  
- mark a specific task completed or not  

## Installation
`wget https://raw.githubusercontent.com/trifonovkv/todo/main/todo`   
`chmod +x ./todo`

## Usage
For add task:  
`todo "task_description"`   
For show current tasks:  
`todo`  
Output example:  
```
  1.  (17:35 25/12) "task #1"
  2.  (20:02 25/12) "task #2"
  3.  (23:51 26/12) "task #3"
---
[c]omplete task <number>
[i]ncomplete task <number>
[d]elete task <number>
[q]uit
:
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)


