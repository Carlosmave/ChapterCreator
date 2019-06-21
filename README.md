# ChapterCreator

A tool to create chapter markers based on the information found in the scene index section of any movie in the Barnes & Noble website.

## Getting Started

You can clone the project if you want to do any modifications. If you want to use it right away, an executable jar file can be found inside the "target" folder.

## Instructions

In the "File Name" field, place the name you'd like for your file, for example "chaptertrack". Then copy the information from the index section of any movie found in Barnes and Noble website in the big text field.

Example of index section information:

1. Chapter 1 [8:33]
2. Chapter 2 [8:17]
3. Chapter 3 [10:27]
4. Chapter 4 [11:51]
5. Chapter 5 [9:34]
6. Chapter 6 [4:01]
7. Chapter 7 [7:34]
8. Chapter 8 [10:35]
9. Chapter 9 [8:13]
10. Chapter 10 [10:52]
11. Chapter 11 [10:16]
12. Chapter 12 [8:40]

Finally, press the "Generate" button. The text file with the chapter markers will be located in the same directory where you placed the executable jar file.

Example of final result:

CHAPTER01=00:00:00.000<br/>
CHAPTER01NAME=Chapter 1<br/>
CHAPTER02=00:08:33.000<br/>
CHAPTER02NAME=Chapter 2<br/>
CHAPTER03=00:16:50.000<br/>
CHAPTER03NAME=Chapter 3<br/>
CHAPTER04=00:27:17.000<br/>
CHAPTER04NAME=Chapter 4<br/>
CHAPTER05=00:39:08.000<br/>
CHAPTER05NAME=Chapter 5<br/>
CHAPTER06=00:48:42.000<br/>
CHAPTER06NAME=Chapter 6<br/>
CHAPTER07=00:52:43.000<br/>
CHAPTER07NAME=Chapter 7<br/>
CHAPTER08=01:00:17.000<br/>
CHAPTER08NAME=Chapter 8<br/>
CHAPTER09=01:10:52.000<br/>
CHAPTER09NAME=Chapter 9<br/>
CHAPTER10=01:19:05.000<br/>
CHAPTER10NAME=Chapter 10<br/>
CHAPTER11=01:29:57.000<br/>
CHAPTER11NAME=Chapter 11<br/>
CHAPTER12=01:40:13.000<br/>
CHAPTER12NAME=Chapter 12<br/>

The generated text file is ready to add to Subler or other similar programs.

## Built With

* Java

## Authors

Carlos Antonio Martinez Vélez

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.