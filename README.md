## micromouse_python

#### Introduction

This is meant to program a Raspberry Pi to autonomously solve a square maze, which is described in more detail below. Originally written by Sam Roth during the Spring 2015 semester, for use by the 2015-2016 Micromouse team.

#### The Maze

The maze object must be instantiated with the size parameter, which will be used to
create the array that the algorithm will use to navigate to the center. For now, this
will only work with square mazes.


An example 8x8:
```
6 5 4 3 3 4 5 6
5 4 3 2 2 3 4 5
4 3 2 1 1 2 3 4
3 2 1 0 0 1 2 3
3 2 1 0 0 1 2 3
4 3 2 1 1 2 3 4
5 4 3 2 2 3 4 5
6 5 4 3 3 4 5 6
```

An example 16x16:
```
14  13  12  11  10  09  08  07  07  08  09  10  11  12  13  14

13  12  11  10  09  08  07  06  06  07  08  09  10  11  12  13

12  11  10  09  08  07  06  05  05  06  07  08  09  10  11  12

11  10  09  08  07  06  05  04  04  05  06  07  08  09  10  11

10  09  08  07  06  05  04  03  03  04  05  06  07  08  09  10

09  08  07  06  05  04  03  02  02  03  04  05  06  07  08  09

08  07  06  05  04  03  02  01  01  02  03  04  05  06  07  08

07  06  05  04  03  02  01  00  00  01  02  03  04  05  06  07

07  06  05  04  03  02  01  00  00  01  02  03  04  05  06  07

08  07  06  05  04  03  02  01  01  02  03  04  05  06  07  08

09  08  07  06  05  04  03  02  02  03  04  05  06  07  08  09

10  09  08  07  06  05  04  03  03  04  05  06  07  08  09  10

11  10  09  08  07  06  05  04  04  05  06  07  08  09  10  11

12  11  10  09  08  07  06  05  05  06  07  08  09  10  11  12

13  12  11  10  09  08  07  06  06  07  08  09  10  11  12  13

14  13  12  11  10  09  08  07  07  08  09  10  11  12  13  14
```
