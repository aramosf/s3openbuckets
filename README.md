# S3OpenBuckets

### Introduction
This repository collects information obtained after analyzing all
internet(tm) searching for open Buckets of S3.
To do this, I have downloaded the CommonCrawl WAT files and parsed the
links, I have checked and listed the contents of those that were open.
This analysis is similar to the one performed by Rapid7 in 2013.

For reference, some used files are published. If you want more and you
are not a security porn star wannabe, I can share with you, ask by
email with your gov email.

## Conclusions
* 5,738 open buckets were found from the 55,454 Buckets analyzed (10.3%).
* More than open 40 buckets are used for black SEO
* From the file list obtained (partial), more than 1,198PB are
publicly available
* File list have the name of 783M files inside.
* The file with (partial) file list (ls -l) of openbuckets is 60Gb.
* Not all files are private. There a tons of public files in open buckets.

### Files
* keywords.txt: post-exploitation file containing strings to search
for interesting information.
* s3AllBuckets.txt: list of all the buckets found in CommonCrawl files (55.454)
* myOwns3dict.txt: dictionary created with the top100 most used names.

### Tools
Updated list of the open buckets searching tools available:
* https://github.com/tomdev/teh_s3_bucketeers/
* https://github.com/eth0izzle/bucket-stream
* https://github.com/gwen001/s3-buckets-finder
* https://github.com/aaparmeggiani/s3find
* https://github.com/bbb31/slurp
* https://github.com/kromtech/s3-inspector
* https://github.com/petermbenjamin/s3-fuzzer
* https://github.com/jordanpotti/AWSBucketDump
* https://github.com/bear/s3scan
* https://github.com/sa7mon/S3Scanner
* https://github.com/magisterquis/s3finder
* https://github.com/abhn/S3Scan
* https://breachinsider.com/honey-buckets/
* https://www.buckhacker.com/

### Articles
Some articles listing major vulnerabilities and information about the problem:
* http://flaws.cloud/
* https://www.virtuesecurity.com/blog/aws-penetration-testing-s3-buckets/
* https://rhinosecuritylabs.com/penetration-testing/penetration-testing-aws-storage/
* https://pentestarmoury.com/2017/07/19/s3-buckets-for-good-and-evil/
* https://blog.rapid7.com/2013/03/27/open-s3-buckets/
* https://www.rapid7.com/resources/amazon-s3-bucket-misconfiguration/
* https://blog.detectify.com/2017/07/13/aws-s3-misconfiguration-explained-fix/
* https://www.upguard.com/breaches/cloud-leak-inscom
* https://mackeepersecurity.com/post/fedex-customer-records-exposed

### Bounties reports
Bug bounties report list including Amazon’s opened buckets:
* https://hackerone.com/reports/129381
* https://hackerone.com/reports/128088
* https://hackerone.com/reports/209223

