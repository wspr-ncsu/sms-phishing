# SMS Phishing Code and Data Releases

This repository will hold code and data from our 2024 Paper: 

> Aleksandr Nahapetyan, Sathvik Prasad, Kevin Childs, Adam Oest, Yeganeh Ladwig, Alexandros Kapravelos, Bradley Reaves. "On SMS Phishing Tactics and Infrastructure." in Proceedings of IEEE Symposium on Security and Privacy, 2024.

If you would like access to code or data that is not presented here, contact [Brad Reaves](mailto:bgreaves@ncsu.edu)

# Data format

`phishing_messages` contains the raw messages collected from the gateways that VirusTotal and APWG marked as phishing along with the destination number. `phishing_campaigns` contains the campaigns that we constructed, along with the URLs that they use, first and last seen timestamps (UNIX timestamps), and number of messages observed. 

# Bibtex


```
@inproceedings{smsphishing-sp24,
  title = {{On SMS Phishing Tactics and Infrastructure}},
  author = {Nahapetyan, Aleksandr and Prasad, Sathvik and Childs, Kevin and Oest, Adam and Ladwig, Yeganeh and Kapravelos, Alexandros and Reaves, Brad},
  booktitle = {{Proceedings of the IEEE Symposium on Security and Privacy}},
  month = may,
  year = {2024}
}
```