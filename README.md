**Tool Image Downloader**
### Dependencies needed  

1. Selenium  
Install as `pip install selenium`  
2. Geckodriver  
[Geckodriver is already provided in the repository]  

### Download any number of images from Google image search.

`python image_download_python3.py <query> <number of images>`  
where:  
`<query>`: is the the query to search for.  
`<number of images>`: min(`<number of images>`, total google results) will be downloaded.  

All the images are downloaded from Google image search. These should be used for educational  purposes only. Copyright is owned by the respective websites.

* To clear the downloads folder:

    `./clearDownloads.sh`