# System-Observer
This project is inspired By linux system monitor 'HTOP'.My goal is to Brush up system programming skills as well as build a deep understanding of linux architecture .

### Features :
 - View Running processes
 - View Memory Consumption of Processes
 - View Cpu state
 - kill process ( not implemented)

### UML Diagram:


### How to run:
ncurses is a library that facilitates text-based graphical output in the terminal. This project relies on ncurses for display output.

Install ncurses within your own Linux environment: 
```
sudo apt install libncurses5-dev libncursesw5-dev
```
Build and run the project:
```
$ mkdir build && cd build
$ cmake ..
$ make 
$ ./observer
```


### Demo:
 ![Alt Text](https://github.com/abidKiller/System-Observer/blob/master/doc/demo.gif)
