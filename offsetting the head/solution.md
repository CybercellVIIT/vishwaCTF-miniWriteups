We are given a 7z file. It has a file inside called password.txt, extract it and open. It has the text give_me_the_flag in ascci art.

Its weird that original fila is 150KB and the extracted file is 486 bytes, so I run binwalk challenge.7z

So at offset 0xC2 there is another 7z file.

Open the original 7z file with notepad++ for example and search for 7z (or extract it with binwalk --dd='.*', it will create a folder named _challenge.7z.extracted and a file called C2 inside, thats the 7z file we need)

You can see selected the start of the other file. Delete all characters before that and save the file as challenge2.7z

Open it and it asks for a password. We can use give_me_the_flag and it extracts OK.

There is a flag.txt file and a part2 folder.

Open flag.txt and there is the flag.

Enter the stuff inside curly brackets in vishwaCTF{} format
