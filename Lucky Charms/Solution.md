Title : Lucky Charms

Category : Cryptography

Description :Found this behind the box of a ceral. Can you help decode the message?

⭐🧲🌈⭐🦄⭐⭐🌈🍀⭐🦄❤️⭐🌈🎈⭐🌚⭐⭐❤️🍀⭐🧲🌚⭐❤️🌈⭐🎈🍀⭐🌈🦄⭐🌈🌈⭐🌈🌈⭐🌈🌈⭐🍀🎈⭐❤️🌚❤️🌈🍀⭐🦄🌚⭐🦄⭐⭐🌚🍀⭐🦄⭐❤️🌈❤️⭐🌈🦄❤️🌈🦄⭐🎈🦄

Hints : 50 points ->The question has nothing to do with advanced cryptography or anything. It's a basic question and do read the wikipedia page again!

Files : none

Points : 200

Solves : 1

Flags : VishwaCTF{ummm_D3lici0u5}

## Solution 

1. The first clue is giving in the name itself, "Lucky charms". When you google that and open the [wiki page](https://en.wikipedia.org/wiki/Lucky_Charms), and the second hint is given there.
2. In the taglines, the given 8 unique symbols are said and using the order that they are said in, the symbols represent numbeers 0 to 7 thus making the message in an octet.
3. If you count the emoji's, there are totaly 75 therfore 75/3 = 25. This could be another apporach to guess that 3 emojies are used to represent one letter of the flag.
4. Now just replace each emoji with its corresponding number and decrypt the octate to get the flag.
