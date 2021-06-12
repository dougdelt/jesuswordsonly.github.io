# jesuswordsonly.github.io 

Backup and restoration of the original jesuswordsonly.com 

Early in 2021 I noticed that the jesuswordsonly.com website was down. I found an archived copy from the Wayback Machine. The most recent archive from the Wayback Machine that has the page as it was for years is http://web.archive.org/web/20210122033624/https://jesuswordsonly.com/ 

Using a Ruby Gem (program), I retrieved this site in a restorative fashion (without Wayback Machine markings) using the following linux command:
```/home/a/.local/share/gem/ruby/2.7.0/bin/wayback_machine_downloader -t 20210122033624 https://jesuswordsonly.com/```
The "first commit" is exactly this retrieval, except with a README.md file. 

The Wayback Machine archive is missing, at the very least, some key things such as the JWO book chapters in pdf format. However, the HTML formatted chapters and appendices were retrieved. Yet the Bibliography and Index of Topics pages were only in PDF and were not archived. 

The only file from subsequent Wayback Machine archives that contains additional info is recommendedreading/33-sabbathcommand.html.
