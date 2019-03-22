# kotto
The file is best read "raw" to accomodate drawings
Kotto is a cloud hosting aplication.

The server is written in nodeJS.

A user uploads a file, and is given a link, simple as that.
Files uploaded will be deleted every midnight PST automatically.

# the database

The database will be redis.
the file structure will be a hash
URL_ID:[1], {filename in harddrive}
       [2], {file title}
       [3], {type}

# the server

The server will serve the front webpage as all file pages

front page
-------------------------------------------------------------------------------------------------------
|  Kotto                                                                                              |
|  File hosting                                                                                       |
|                                                                                                     |
|                                                                                                     |
|                                                                                                     |
|                                                                                                     |
|                                                                                                     |
|     |image|                                                                                         |
|     |title (optional)|                                                                              |
|     |select file| |upload|                                                                          |
|                                                                                                     |
|                                                                                                     |
|                                                                                                     |
|                                                                                                     |
|                                                                                                     |
|                                                                                                     |
|  please donate im very poor: {email}                                                                |
-------------------------------------------------------------------------------------------------------

file page
-------------------------------------------------------------------------------------------------------
|  Kotto                                                                                              |
|  File hosting       Title: {title} type: {file type}                                                |
|  |---------------------------------------------------------------------|                            |
|  |                                                                     |                            |
|  |                                                                     |                            |
|  |                                                                     |                            |
|  |                                                                     |                            |
|  |                                                                     |                            |
|  |                  file                                               |                            |
|  |                                                                     |                            |
|  |                                                                     |                            |
|  |                                                                     |                            |
|  |                                                                     |                            |
|  |                                                                     |                            |
|  |---------------------------------------------------------------------|                            |                            |                                                                                                     |
-------------------------------------------------------------------------------------------------------

and thats pretty much it.
