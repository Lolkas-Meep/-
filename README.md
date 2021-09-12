# atomic experiment / "rat"

so as the dev that put the rat there, let me explain what this was:

the client itself was an actual solid client, no intent of ratting it down the line. As i made a rather big update, i remembered the botched attempt at making something like this a few months ago, and wanted to repeat it, so i just, without thinking too much, put a "rat" into the utils class, that just sent me basic account info + the access token to the account, so i could have something private that should never be accessed outside of the pc, to prove that it really is that simple.

the rat went live, everything went great, but then i told friends about it, that ultimately got me to stop the entire thing. the data was deleted, in the end there were about 44 users' accounts in there, after about 3 hours of runtime.

could i have executed this better? absolutely, i just didnt think about it, and that was really the main issue. I could've just hashed all the info and just went on with it, so no actual personal info is compromised, but i just went with it without thinking too much of it

again, this is just a botched remake of another botched attempt at making people aware of malware and how easy it is to put it in legit software, but this time we actually did raise some awareness and got people to realise, so i guess thats at least some form of win?

even if everything went bad, the info wouldn't have been abused to do something like the phobos incident, the tokens would invalidate after 2 days and we'd have a completely empty dataset.

i hope this isnt too much of an inconvenience, everything's laid off atm, the client's public version is gone

- 0x150
