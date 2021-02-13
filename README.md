# colly-scraper-examples
Playing with the examples from the go webscraper colly: http://go-colly.org

# Install Colly
Type following command on Terminal and hit enter to install Colly.
```
go get -u github.com/gocolly/colly/...
```
# Create go.mod for this repo
```
go mod init github.com/hauk3wu1ff/colly-scraper-examples
```

# Create and run Basic example:
* vi basic.go
* Copy the code from http://go-colly.org/docs/examples/basic/ into the bfile basic.go in vim: Use i for insert and crtl-v to copy from system clipboard. 
* Delete the code automatically created by the vim go-plugin with the vi {count}{motion}{action}-command 7jd, which means move 7 lines down and delete. 
* Run it with go
```
go run basic.go
```
