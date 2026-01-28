Music Playlist Manager


Technology Used

* Language: C
* Data Structure: Singly Linked List



Concepts:



* Dynamic Memory Allocation
* Pointers
* Structures
* Menu-driven program



Project File

musicplaylistmanager.c



Description



This project implements a Music Playlist Manager using a singly linked list in C.

Each song is stored as a node containing the song title, artist name, and a pointer to the next song.

The program allows users to dynamically manage a playlist through a menu-driven interface.



Features



1.Add Song

* Add a new song (title and artist) to the playlist.
* Songs are inserted at the end of the list.



2.Delete Song

* Delete a song using its title.
* Displays a message if the song is not found.



3.Display Playlist

* Shows all songs in the playlist.
* Displays a message if the playlist is empty.



4.Shuffle Playlist

* Randomly rearranges the songs in the playlist.
* Works only if there are two or more songs.



5.Exit

* Frees all allocated memory before exiting the program.



How to Run the Program



Using GCC Compiler

gcc musicplaylistmanager.c -o playlist

./playlist

Using Turbo C / CodeBlocks

Create a new C project

Paste the code into musicplaylistmanager.c

Compile and run



Sample Menu

--- Music Playlist Manager ---

1\. Add Song

2\. Delete Song

3\. Display Playlist

4\. Shuffle Playlist

5\. Exit



Learning Outcomes



* Understanding linked list operations.
* Implementing dynamic data structures.
* Applying memory management using malloc() and free().
* Building menu-driven C programs.



Time Complexity



Operation	Complexity

Add Song	O(n)

Delete Song	O(n)

Display		O(n)

Shuffle		O(n²)



Conclusion



This project demonstrates how linked lists can be effectively used to manage dynamic data such as a music playlist, allowing flexible insertion, deletion, traversal, and shuffling of elements.


