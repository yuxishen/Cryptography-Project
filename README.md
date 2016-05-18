# Cryptography-Project
CS5830 Cryptography Final Project

For Server establishment, we don't have a top level domain, so we generate our own cert and convince iPhone in the iOS code that this site is safe and the cert is acceptable. In downloading a file ,we have a certain directory and we are now building a UITableView to show all the files we have got in a table.

In the asymmetric encryption part, we generate the private key on the server and copy the corresponding public key to the RasPi to simulate the signature verification. The method is DSA_with_SHA256 and we modify HW5 structure a little bit to make it actually works between the server and RasPi.
