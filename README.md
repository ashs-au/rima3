# rima3
webpage text/slidedeck for Performance work 'Rima' by Squidsilo (Artshouse, Melbourne July 2016)

Another component of the show for which the code in the "sensors" repo was created. The animated text is posted at: http://squidsilo.net/rima3/ 

During the performance, text fragments were generated from the perfromer's activity and inserted into a Cloudant database. This page pulled updates to display the unfolding story ina an endless growing loop. After the show finished it was put into a simple looping mode to replay the texts in order.

Since Cloudant has now been retired - this version loads the text repository as a local JSON file and loops the entire sequence of 404 fragments.
